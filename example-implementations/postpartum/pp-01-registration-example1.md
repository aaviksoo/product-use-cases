# PP-01-Registration-Example1

<table data-header-hidden><thead><tr><th width="209"></th><th></th></tr></thead><tbody><tr><td><strong>Use Case Step</strong></td><td>Use Case: PostPartum and Infant Care, Step: Registration (provide link to UC when complete)</td></tr><tr><td><p><strong>Preconditions</strong></p><p>(list of conditions that MUST be met in order to be able to successfully execute this process)</p></td><td><ul><li> The government-accredited health worker has successfully logged into the MCTS government portal(Registration BB) and has the necessary authorization to complete the registration process of the mother and child into the postpartum care program.</li><li>Data sharing agreement between Registration BB and respective registries where information is queried from has been signed (contract) and respective REST API services in Information Mediator has been opened to Registration BB.</li><li>The mother and newborn have already been registered in a national identification system (ID BB).</li><li>The mother has her identity proof (card, QR code, ID number, etc) available together with the required credentials for the MCC that can be verified and authenticated with the national ID system.</li></ul></td></tr><tr><td><strong>Data inputs</strong></td><td><ol><li>Name of the mother</li><li>National ID number of the mother</li><li>National ID number of the newborn</li><li>Name of the newborn baby</li><li>Place of birth (explain the rationale behind this field)</li><li>Time of birth</li><li>Location of birth</li></ol></td></tr><tr><td><p><strong>Actors</strong></p><p>(the people, organizations, computer systems - hardware and software, and building blocks that participate in the activity)</p></td><td><p><strong>Human:</strong> Government-accredited health worker, A woman who has delivered her first baby</p><p><strong>System:</strong></p><ul><li>MCTS/ MCC application (Registration BB)</li><li>Digital Registries BB</li><li>Identity BB</li><li>Consent BB</li><li>Messaging BB</li><li>Information Mediator BB</li><li>National Population Registry (Digital Registries BB or Identity BB)</li><li>MCC Membership Registry (Digital Registries BB)</li></ul></td></tr><tr><td><strong>Normal Course</strong> (what happens if the event is triggered and the preconditions have been met)</td><td><p>The registration form screen for the MCC application provides a list of initial details required to proceed with the registration (eligibility verification, required documents, required fees).</p><p><strong>Step 1:</strong> The health worker enters the required initial details, including, but not limited to the following:</p><ol><li>Mother’s and newborn baby’s National ID number</li><li>Name of the newborn child</li><li>Date of Birth</li><li>Place of Birth (such as home, clinic, etc.)</li><li>Time of Birth</li><li>Location of Birth</li><li>The health worker (<em>MCC Application</em>) suggests the Mother an option to retrieve additional data from the Population Registry and asks for a consent to do so.</li></ol><p><code>1Feature: Get Consent Agreement 2Scenario: MCC Application retrieves Consent Agreement for Mother 3 Given an Agreement for MCC user registration exists in Consent BB 4 And MCC Application has MCC application has Mother's &#x3C;ID> and authentication token for the registration session 5 When MCC application fetches a Consent Agreement for MCC user registration 6 Then MCC application gets a valid Draft Consent Agreement associated with Mother's ID 7</code>API Endpoints</p><p> </p><p><strong>Step 2:</strong> The health worker (via MCC Application) introduces to the Mother the Consent Agreement for fetching the relevant details from the Population registry for verification and appropriate use with the MCC and captures signature to the Consent Agreement from the Mother.</p><p><code>1Feature: Sign Consent Record 2 3Background: 4 Given MCC Application has the Draft Consent Agreement associated with Mother's ID 5 And MCC application has Mother's &#x3C;ID> and authentication token for the registration session 6 And Mother has read the Draft Consent Agreement 7 And Mother approves to sign the Draft Consent Agreement associated with Mother's ID 8 9Scenario: Sign Consent Record on Paper 10 Given MCC application has captured the consent in a digital form (for example: scan of a paper form) 11 When MCC sends digital Consent Record payload to Consent BB 12 Then Consent BB digitally signs Consent Record 13 And Consent BB confirms to MCC Application that Consent Record for Mother has been successfully signed 14 15Scenario: Sign Consent Record Digitally 16 Given Mother has capability to sign Consent Record digitally 17 When MCC sends the Draft Consent Agreement to Consent BB 18 Then Consent BB creates a paired ConsentRecord and Signature object 19 And Consent BB digitally signes Consent Record 20 And Consent BB confirms to MCC Application that Consent Record for Mother has been successfully signed 21</code>API Endpoints</p><p> </p><p><strong>Step 3:</strong> The MCC application form submits the verified national ID number to the Population registry hosted in the IDBB/Digital Registries BB seeking relevant details of the mother, by invoking the API “Data read value” on the Govstack Digital Registries BB.</p><p>This scenario uses a set of features:</p><ul><li>Verify Consent Record by Consent BB</li><li>Import data from a registry by Registry BB</li></ul><p><code>1Feature: Verify Consent Record 2MCC Application verifies if Mother has signed Consent Record to fetch the needed personal data from Population registry for MCC user registration 3 4Scenario: Retrieve valid Consent Record 5Given Mother has Signed Consent Record stored in Consent BB 6When MCC Application makes the request to population registry API to fetch Mother's personal data 7Then MCC Application makes prior request to Consent BB API to retrieve Mother's Signed Consent Record 8 And Consent BB sends the signed Consent Record to MCC Application 91Feature: Imports client personal data from a registry 2Import Mother's pesonal information from Population Registry to the e-service form 3 4Given Mother has entered &#x3C;ID> in the Registration e-service registration form, national ID number field 5 And MCC Application has received Signed Consent Record from Consent BB 6 When the MCC Application user pushes a button "Import Mothers's information" 7 Then the MCC Application makes a request to Population Registry API 8 And Population Registry returns requested data to MCC Application 9 And MCC Application fills the form on the screen with Mothers data &#x3C;ID>,&#x3C;first>, &#x3C;last>, &#x3C;birth> 10 Examples: 11 |ID|first|last|birth| 12 |53|Sowmya|Krishnamurti|2022-11-01| 13 14</code>API Endpoints</p><p> </p><p>In response, the Govstack IDBB/ Digital Registries BB is expected to return the following:</p><p> </p><p>Data returned from Registy</p><p><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br></p></td></tr><tr><td><p><strong>Alternative Course</strong></p><p>(links to other use cases in case there are different ways how to solve the same use case)</p></td><td><p>If the mother does not possess a national ID, the registration application needs to provide an alternate mechanism for the health worker to verify the details of the mother. GetIdentityProfile - elaborate</p><ol><li>If the consent record is previously created and available, the registration application should fetch the consent agreement by invoking the API: “serviceListIndividualRecord” on the Govstack Consent BB</li></ol><p>“GET /dataconsumer/consent/”</p></td></tr><tr><td><strong>Data output</strong></td><td><p>The successful completion of the postpartum and infant care registration process will result in confirmation and issuance of a program-specific ID that can be used by the mother for future interactions with the program.</p><p>Expected data from Registration BB</p><p><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br></p></td></tr><tr><td><strong>Post-Conditions</strong> (the success criteria)</td><td> The mother and child are registered in the mother and child care program registry.</td></tr><tr><td><p><strong>Exceptions</strong></p><p>(error situations)</p></td><td><ul><li><p>A child can be only registered once in MCC. The system must prevent multiple registrations.</p><ul><li>Provide details on exception code and message</li><li><em>Mitigation steps:</em> Describe steps to be taken by the actors</li></ul></li><li><p>If the mother is not registered in Population Registry, then it is not possible to register in MCC.</p><ul><li>Provide details on exception code and message</li><li><em>Mitigation steps:</em> Describe steps to be taken by the actors</li></ul></li><li><p>If Identity BB or Consent BB is not available (service outage), then …..</p><ul><li><em>Mitigation steps:</em> Describe steps to be taken by the actors</li></ul></li><li><p>If no internet, then the system is not available and information must be collected on paper forms or on offline data capturing devices.</p><ul><li><em>Mitigation steps:</em> Describe steps to be taken by the actors</li></ul></li><li><p>If the child is not registered in Population Registry, then the system must enable integrated government service and the child's information must be collected during the same process and forwarded to the correct registration process (Identity BB API to register a new child and issue an ID number for the child).</p><ul><li><em>Mitigation steps:</em> Describe steps to be taken by the actors</li></ul></li></ul></td></tr><tr><td><p><strong>Related BBs</strong></p><p>(working groups related to this example implementation)</p></td><td><p>Identity BB</p><p>Consent BB</p><p>Registration BB</p><p>Digital Registries BB</p></td></tr></tbody></table>

### Sequence Diagram

```mermaid
sequenceDiagram
title Registration - Postpartum and Infant Care

HCWorker-->Security(API Gateway): Request access to Registration(Screenflow)
Security(API Gateway)->HCWorker: User is not authenticated, redirect to OAuth
HCWorker-->Security(OAuth): UI-Authenticate user

Security(OAuth)-->HCWorker: UI-Redirect to Registration(Screenflow)

HCWorker-->Registration(Screenflow): UI-HC worker is logged in with a healthcare worker policy
note right of Registration(Screenflow): Authorize user(Internal)

note right of Registration(Screenflow): Select MCTS registration process

note left of Registration(Screenflow): Capture basic details

opt get mother and child information
  Registration(Screenflow)->Social Protection Registry (Existing): Get information 
  Social Protection Registry (Existing)->Registration(Screenflow): Populate screen
end

note right of Registration(Screenflow): Enter the Surname, DoB and ID number of the Mother

Registration(Screenflow)->Workflow: Validate if mother is eligible
Workflow->Registration(Screenflow): Confirm eligibility

note right of Registration(Screenflow): Upload proof of identity and photo
opt Additional validation from Civil registry to avoid double registration
note right of Registration(Screenflow): check if similar records exist 
    Registration(Screenflow)->ID(Civil Registry): check if exist
    ID(Civil Registry) ->Registration(Screenflow): response
end


Registration(Screenflow)->Registry: Validate with MCTS- if exist
Registry->Registration(Screenflow): Validation response
note right of Registration(Screenflow): Store validation response for backoffice
note right of Registration(Screenflow): Capture Registration Details

opt Calculate registration fee
    Registration(Screenflow)->Rules engine: Calculate fees
    Rules engine->Registration(Screenflow): Fees
    Registration(Screenflow)->Payments: Request payment advice
    Payments->Registration(Screenflow): Returns payment advice
    note right of Registration(Screenflow): Display QR code
    note right of Registration(Screenflow): Mother pays in external system
    note right of Registration(Screenflow): HCWorker confirms payment
end
opt where legally required
    note right of Registration(Screenflow): Get Citizen Confirmation
end
note right of Registration(Screenflow): Submit application for registration

opt Registration in Civil registry (mother and/or child)
Registration(Screenflow)->Social Protection Registry (Existing) : Registration in Civil registry (if possible directly)
Registration(Screenflow)->Workflow : Who wants to have registration in Civil registry
Social Protection Registry (Existing)->Workflow : Any registrations for Civil registry?
Workflow->Social Protection Registry (Existing) : yes, registration in Civil registry
Social Protection Registry (Existing)->Social Protection Registry (Existing): Internal process
Social Protection Registry (Existing)->Workflow : Registration complete

Registration(Screenflow) -> Workflow: Is Mother/child Civil registration done?  number

note left of Registration(Screenflow): Wait until answer is received. 
Workflow ->Registration(Screenflow): Receive Mother/child ID number
   
end

Registration(Screenflow)->Registry: Registration in MCTS registry
Registry->Registration(Screenflow): Receive membership registration confirmation and reg.number. 
note left of Registration(Screenflow): New e-service starts from here!
note left of Registration(Screenflow): Issue program membership ID card
note right of Registration(Screenflow): Capture card details
note right of Registration(Screenflow): Assign Card to Parent
note right of Registration(Screenflow): Update MCTS registry
Registration(Screenflow)->Registry: Update MCTS registry information
Registry->Registration(Screenflow): Update successful
```
