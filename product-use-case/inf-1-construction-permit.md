# INF-1 - Construction Permit

## Product Use Case Summary

| ID      | URB-1                      |
| ------- | -------------------------- |
| Name    | Construction Permit        |
| Sector  | Sustainable Infrastructure |
| Version | 1.0                        |
| Status  | Published                  |

This use case profiles the implementation process of a construction permit. A service that automates the entire construction permit approval process - from enabling online application submissions of building construction plans, to initiating verification and final approval by the local government authorities. This process is how local governments can decide whether to approve or decline construction permit applications by evaluating submitted building plans, and assessing their compliance with standard building codes and local regulations. A construction permit is an important requirement for countries to ensure buildings and structures are safe, with sound engineering, foundations and construction techniques.

Municipalities and counties/towns have traditionally managed construction permits "over the counter" and through paper or PDF applications. This time-consuming, complex and error-prone tasks has raised issues in some countries - around the accountability and transparency, as well as inefficiencies in achieving timely construction permitting processes, and sustainable urban planning development. As a result, a number of governments in low-and-middle income countries are implementing an online construction permit. A digital service with a hassle-free online procedure and user-friendly tools to achieve a more streamlined end to end approval process that ensures transparency, accountability, and time-bound services.

## Stakeholders

* Ministry or national government body in charge of urban development, housing, and/or town planning.
* Local building government authorities - building officials, inspectors and design auditors - across municipalities in charge of reviewing and/or issuing construction permits.
* Technical team responsible for the rollout of the construction permit portal/platform initiative in the state - system integrator, building architect, software engineer, QA engineer, help desk staff, DevOps engineer etc.
* Citizens and professionals (engineers, architects, construction supervisors) seeking permission to construct, renovate or alter a building.

## SDG Targets

* [11.3](https://solutions.dial.community/sdgs/sustainable\_cities\_and\_communiti): By 2030, enhance inclusive and sustainable urbanization and capacity for participatory, integrated and sustainable human settlement planning and management in all countries.
* [11.6](https://solutions.dial.community/sdgs/sustainable\_cities\_and\_communiti): Reduce the adverse per capita environmental impact of cities, including by paying special attention to air quality and municipal and other waste management.

## Building Blocks

* [**Consent**](https://govstack.gitbook.io/bb-consent/)
* [**Digital Registry**](https://govstack.gitbook.io/specification/v/version-0.9.0/building-blocks/digital-registries)
* [**Identification and Verification**](https://govstack.gitbook.io/bb-identity/)
* [**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)
* [**Messaging**](https://govstack.gitbook.io/bb-messaging/)
* [**Payments**](https://govstack.gitbook.io/bb-payments)
* [**Registration**](https://govstack.gitbook.io/bb-registration)
* [**Scheduler**](https://govstack.gitbook.io/specification/building-blocks/scheduler)
* [**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)

## Source Documents

* [Methodology for the Implementation of Building Permits](https://urban.digit.org/products/modules/online-building-plan-approval-system-obpas/obpas-implementation-guide)
* [Djibouti Construction Permit - To Be User Journey - Digital Service Proposal](https://gizonline.sharepoint.com/:p:/r/sites/ICTBuildingBlocks-CommondigitalSDGplatformwithguests/Freigegebene%20Dokumente/General/Country%20Engagement/HoAI/Djibouti%20info%20pack/Construction%20Permit%20To-Be%20User%20Journey%20-%20Service%20Design%20Proposal/Construction%20Permit%20Digital%20Service%20Design%20\(Validated%20in%20March%202023\)%20FRENCH.pptx?d=w621c0c6a6f51435b9672840a4d6b83d7\&csf=1\&web=1\&e=S5SToa)

## Steps

### 1 - Outreach Communication

Staff from the Ministry of Urban Planning or another leading agency / organization in charge of regulating all aspects of a country's construction permit issuance processes (building codes and laws), leads the campaign to disseminate information about the construction permit. Roll out of this service can be disseminated on the Ministry's and all the municipalities' websites and social media platforms. Marketing and promotional communication materials (i.e., brochures, pamphlets, flyers etc) can also be made available at the local municipalities/urban planning centers.

To achieve clarity, consistency and transparency on the new online process and requirements for obtaining a construction permit, target communication to the key stakeholders involved (issuing government authorities, citizens, architects, engineers) should be prioritized. The state team can lead rollout plans and ensure the necessary infrastructure for local municipalities staff training and deployment are made available at each building plan department in the country. Moreover, to ensure that implementation of the construction permit approval method is uniform throughout the country and that the rules are not interpreted differently, a user manual on the new construction permit should be provided to each local government building plan staff.

Awareness campaigns can be organized across municipalities informing citizens about the new construction permit application procedure with information on how they can upload their application (building plans and construction documents), pay fees and track their application online, schedule an inspection (if required), and download and print their permit order once issued.

**Workflows**

* **Client communication** to facilitate information dissemination on the new digitized construction permit via government and municipalities' building construction permit websites, social media, and national media channel(s).
* **e-Marketplace** as a web-based application to promote and disseminate information of all government services offered to citizens, and guidance on how to access them.
* **Content management** for the development of a user manual and training guide on the digitized service for building plan officials and/or users wishing to submit a construction permit application.
* **Staff communication and education** for informing construction permit issuing staff authorities about the construction permit. Organize training sessions for staff on how to review applications, check fee payment status, and process and issue permits - all online.
* **Identification and Registration** for providing an administration account for all qualified government building plan staff with authority to issue construction permits.
* **Data Collection and Reporting** for capturing the new construction permit and regulation changes, and to report this data to all relevant stakeholders.

**Building Blocks**

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Scheduler**](https://govstack.gitbook.io/specification/building-blocks/scheduler)

### 2 - Registration

Registration is the process of collecting information of users wishing to access a digital service. Depending on specific country context and the platform being utilized to host the construction permit, registration process could defer. This service can be hosted using a single window approach to facilitate the end-to-end construction permit application procedure and clearances from multiple agencies or departments.

In certain countries, there is a statewide online construction permit platform in place, and the target users - citizens, architects, engineers etc., are required to register (provide full name, email, phone number, occupation etc.) on the platform in order to generate personalized login credentials. Then subsequently with these login credentials, the user can then create, save and/or submit a construction permit application on the online portal. \*\*If a country already has a national digital registry system in place with a unique identification number for every citizen, then the registration step that allocates a unique username and password to access the permitting platform might not be necessary. In some countries, a citizen can use their national electronic identification data to access all online public services. This system will pull in all applicants' data to facilitate their registration process.

**Workflows**

* **Data Collection and Reporting** for capturing, managing and evaluating registration application data submitted, and in some cases - allocating personalized login credentials per user.
* **Identification** to easily be able to identify and track registered users.
* **Client Case Management** to help automate and manage the registration process, and respond to any inquiries or issues around registering on the platform.

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

### 3 - Application Process

A permit application is the process of applying for the issuance of a legal document to conduct a specific activity that requires the approval from a governmental authority. In this use case, a construction permit is an official approval issued by a local government agency that reviews construction permit applications to ensure the building plan complies with local standards for land use, zoning, and construction. Once approval has been received, the applicant can start the construction project.

Depending on the country context, the application process can require applicants to first login to the permitting platform using their unique identification data from the registration step (i.e., username and password or national identification data). Then fill out a standardized online application form, upload the documents required to process the application and asses the building design (i.e., building plan - drawings, specifications, photographs of existing situation, photomontage of proposal, land title, ownership certificate, etc) and pay the application fee that must be submitted with the application. Once their application is submitted, applicants should be able to view and track their application, schedule any follow-up appointments required for document scrutiny and/or site inspection visits by a public official. Emails and SMS notifications can be sent to the applicants to request follow-up action items and provide updates during the application process. \*\* An application cancellation request could be made available for applicants to cancel their permit request at any stage.

**Workflows**

* **Client Case Management** to help automate and manage the permit application submission process. Support in vetting applications - ensuring the applicants meet the eligibility requirements and have submitted all required documentations. Also schedule any necessary follow-up site visits by the building plan inspection authority.
* **Data Collection and Reporting** for capturing and evaluating permit application data submitted by the user applicant.
* **Identification** to easily be able to identify and track registered applicant applying for a construction permit.
* **Financial Services** for processing the permit application fee and generating payment confirmation receipt.

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Payments**](https://govstack.gitbook.io/bb-payments/)

### 4 - Data Verification and Validation

Data within the online construction permit is generally checked\* by the Central Level Ministry in charge of urban planning and the local permit issuing municipality departments, against other government databases (e.g., ID, tax, land titles, utilities, etc.) in order to fill in any missing gaps, verify and validate collected information, including authentication of all records. \*Data checking approaches also vary: sometimes batch-sharing via CD, sometimes full interoperability. This step may be done for both the registration (step 2), and application process (step 3) - whereby before any application is reviewed, each applicant's submitted data will be scrutinized and vetted. \*\*To address data privacy issues, in some countries, data sharing permission should have already been requested and granted from the applicant, to conduct the data checking process against other government databases.

**Workflows**

* **Client Case Management** for storing and reviewing registration, and construction permit application records.
* **Data Analysis and Business Intelligence** for cross-referencing and verifying records across multiple registry sources and reconciling gaps / overlaps.

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)

### 5 - Eligibility Determination

The construction permit can have APIs in place that can scrutinize submitted construction permit applications to support in the decision-making process. This entails the detailed review of application form data and all uploaded documentations (i.e., building plan design, land ownership, deed etc). Applicants should receive general updates on the status of their application such as a notification when their application is being processed with a tentative decision date, or additional information and documents required.

NOTE: Depending on the country, construction permit approval takes different forms e.g. some countries have a document submission checklist embedded and if one of the required documents is not submitted or the submitted documents are unclear or structural design images blurry, then the application is left as pending and a local building plan officer receives a notification for a more manual review and followup. The applicant will receive a notification (via email, SMS, on the permitting platform) stating what is missing or required. The building plan officer can request the hard copy permit application submissions, when appropriate. The application can then be revised and resubmitted.

In most countries that have implemented the construction permit, a building authority still scrutinizes all applications received and consults with other authorities: i.e., a design auditor may conduct an audit to provide feedback regarding the extent to which the design conforms to planning demands and technical requirements. If opinions from other authorities and design auditors are favorable, and the building authority is satisfied that the building design meets the compliance and technical building plan requirements (fire safety, accessibility, space standards etc), then a construction permit is granted. If the building design and construction documents do not meet the compliance and technical building plan requirements, the applicant will be issued a notice stating why their construction project does not comply. These applicants could be asked to submit further information or a revised application meeting the compliance requirements, in order for their application to be reconsidered. \*\*All submitted applications should be archived to ensure a secure longterm storage of this data.

**Workflows**

* **Client Case Management** for reviewing submitted applications and communicating any application status updates or additional information needed to the applicant.
* **Data Analysis and Business Intelligence / Decision Support** for approving or rejecting applications - based on compliance with building regulations, submission of required documents, and existing criteria (e.g. via checklist, or category-based).

**Building Blocks**

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Messaging**](http://127.0.0.1:5000/s/mNnAAqNpNoSI6WELhO9t/1-description)

### 6 - Payment

Multiple fee types can be required in the construction permit approval process (e.g., filing fee, permit fee, surcharge fee, fixed fee per building use etc). A document can be made available summarizing the construction permit fees and calculation method.

If an electronic payment process is enabled, then applicants can pay these fees via a digital financial service embedded in the platform. In certain countries, these fees are calculated based on the size, type and valuation of construction. Following the submission of their online permit application, the applicant can be taken to a payment portal with information on the calculation of their permit fee which is payable online i.e., via a third-party integration (NOC, Payment gateway, Digital signature) or local government online payment system. The applicant must pay all outstanding fees for their permit to be issued. Once the payment is processed, a payment confirmation screen is displayed. Applicants should also receive (i.e., via email, mobile etc) a standard payment receipt.

**Workflows**

* **Financial Services** for processing all fees associated with the construction permit approval process and generating payment confirmation receipts.
* **Client Case Management** for calculating fees, and monitoring/verifying that all required payment transactions, per applicant, has been fully processed and received. Also ensuring that applicants receive payment confirmation and receipt.
* **Content Management** for the development of documentation summarizing construction permit fees and calculation method.

**Building Blocks**

[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)

[**Messaging**](http://127.0.0.1:5000/s/mNnAAqNpNoSI6WELhO9t/1-description)

[**Payments**](https://govstack.gitbook.io/bb-payments/)

[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)

### **7 - Permit Issuing**

Permit issuing generally takes place once the submitted construction permit application has been reviewed and approved, and in some country cases - an extra step includes conducting an in-person building site inspection prior to permit issuance. Examples of construction permit standards that must be met could include structural safety, fire safety, the control of toxic substances, ventilation, sanitation, fall-protection and general safety measures that will be implemented during the design, installation and inspection of building construction works.

Once the building authority also ensures that all outstanding fees have been paid by the applicant, a notification is sent to the applicant informing them that their construction permit has been granted and issued. The permit can be allocated in different forms – a digital format that is downloadable via the permitting platform and/or issuance of a physical permit document with an official stamp. Permit issuance is communicated to different parties - informing relevant individuals/stakeholders of the issuance. A digital security label could be embedded in all government issues construction permits and an online system utilized to validate the authenticity of all permits during any building construction processes.

\*\*\* In certain countries, following permit issuance, construction work can start right away. However, a construction permit can expire if construction work is not started within a certain period or is not completed within a certain time from the date the permit was granted. An application to extend the period to start or to complete the construction work can be submitted to the building authority. Beyond a certain limit, a new construction permit must be applied for.

**Workflows**

* **Data Collection and Reporting** for capturing and tracking all approved permit issuances and permit holders and informing all relevant authorities of approval decision.
* **Client Case Management** to check that the applicant has paid all outstanding fees. To communicate approval decision to the applicant and coordinate permit pickup should allocation of a physical copy be a requirement.

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)

[**Messaging**](http://127.0.0.1:5000/s/oEAfhW9JLP3tJ6mPyxtF/2-description)

[**Scheduler**](https://govstack.gitbook.io/specification/building-blocks/scheduler)

[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)

### **8 - Ongoing Case Management**

This step involves ensuring that there is a virtual help desk and/or physical support centers in place to address any queries pertaining to registration on the platform and the construction permit approval decision. Incorporating a complaint management software will efficiently and transparently ensure that all grievances, complaints and appeals raised by the applicants, are tracked and addressed. In certain countries, this process is led by the construction permit help desk support unit at the state level, to address problem diagnosis needs pertaining to the platform. The local building officials can also be trained to address any queries that cannot be addressed through an automated process.

**Workflows**

* **Data Collection and Reporting** for capturing reoccurring complaints, queries and feedback received from the construction permit service users and permit holders. And integration of other databases and systems for automated data update on client cases overtime.
* **Client Case Management** for identifying and capturing reported cases on grievances / appeals etc., and for determining decisions/actions to proceed with by reviewing individual applicant's client case.

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Messaging**](http://127.0.0.1:5000/s/oEAfhW9JLP3tJ6mPyxtF/2-description)

[**Scheduler**](https://govstack.gitbook.io/specification/building-blocks/scheduler)

[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)

### **9 - Ongoing M\&E**

Monitoring and evaluation is crucial to ensure transparency, accountability and quality public service delivery. To facilitate this process, the government authority leading the implementation of the construction permit can allocate a coordination team (i.e., inspection unit) in charge of ensuring construction work is carried out in compliance with the approved building plans, the construction permit and building regulations. This team could have in place a system with key stages to inspect all construction works or carry out random site inspections to supervise construction works. The inspector authority can provide a report for each examination - available in a digital format and accessible via the permitting platform. If construction works take place without a construction permit or do not comply with the approved design, they can be suspended until the relevant local authority takes a decision regarding demolition or continuation. A fine may also be charged.

In certain countries, once the construction work has been completed, the building authorities are to be notified. Several documents may be required to demonstrate completion, such as, the building design with the actual works carried out, reports of site inspections etc. In addition, submission of an attestation stating that the construction work has been carried out in accordance with the approved design and if any changes were made, that they comply with the building regulatory requirements. In other country cases, a final site inspection is required - the purpose is to verify whether construction works actually carried out comply with the building regulations and the approved building design.

**Workflows**

* **Financial Services** for processing fine payments of construction works not complying with the approved building design.
* **Client Case Management** for monitoring building construction compliance by all permit holders. Also scheduling all site inspection visits, tracking site inspection reports, and communicating with permit holders.

**Building Blocks**

[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)

[**Identification and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Messaging**](http://127.0.0.1:5000/s/oEAfhW9JLP3tJ6mPyxtF/2-description)

[**Payments**](https://govstack.gitbook.io/bb-payments/)

[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)

## Contributors

* Dominika Bieńkowska, IT Project Manager, SolDevelo
* Wesley Brown, GovStack Product Owner, Digital Impact Alliance
* Steve Conrad, Associate Director of Technology, Digital Impact Alliance
* Hani Eskandar, Head of Digital Service Division, International Telecommunication Union (ITU)
* Sarah Farooqi, The Exchange Product Owner, Digital Impact Alliance
* Ibrahim Habib, Director, Djibouti Ministry of Housing, Urbanism and Environment
* Abdallah Ibrahim, Secretary General, Djibouti Ministry of digital economy & Innovation
* Sainabou Jallow, Business Analyst, Digital Impact Alliance
* Concorde Kananura, GovStack Regional Coordinator, Africa, International Telecommunication Union (ITU)
* Mohamad Kaourah, Deputy Director, Djibouti Ministry of Housing, Urbanism and Environment
* Arnold Kibuuka, Project Officer, International Telecommunication Union (ITU)
* Nico Lück, GovStack Advisor, GIZ
* Margus Mägi, GovStack Project Lead for Estonia, Government of Estonia
* Yolanda Martínez, Overall Lead for GovStack, International Telecommunication Union (ITU)
* Stephen Oyala Odhiambo, Digital Government Advisor, GIZ
* Farina Carolina Owusu, Junior Advisor Global Program Digital Transformation with GovStack, GIZ
* Hossam Ragheb, GovStack Regional Coordinator, International Telecommunication Union (ITU)
* Dr. P. S. Ramkumar, GovStack, International Telecommunication Union (ITU)
* Christin Schulz, Governance Advisor and Component Leader, GIZ
* Pia Seiffarth, Junior Advisor Global Program Digital Transformation, GIZ
* Ayush Shukla, Technical Officer, International Telecommunication Union (ITU)
* Siri Nanz Snow, Country Engagement Lead for the GovStack Initiative, GIZ
* Valeria Tafoya, Technology Consultant, International Telecommunication Union (ITU)
* Meelis Zujev, Project Manager, Govstack Sandbox, Gofore
* Raul Kaidro, GovStack
