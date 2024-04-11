# Registration

## Service Block Summary

| Name    | Registration					   |
| ------- | ---------------------------------- |
| Version | 1.0                                |
| Status  | Draft                              |

This service block describes the steps and processes to register a beneficiary for a service. More description here.

## Building Blocks

* [**Consent**](https://govstack.gitbook.io/bb-consent)
* [**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)
* [**Identity**](https://govstack.gitbook.io/bb-identity)
* [**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)
* [**Messaging**](https://govstack.gitbook.io/bb-messaging/)
* [**Registration**](https://govstack.gitbook.io/bb-registration)
* [**Workflow**](https://govstack.gitbook.io/bb-workflow)

## Referenced Service Blocks

* [**User Consent**](https://govstack.gitbook.io/bb-consent/)

## UI/UX Patterns

* [**4.2.1 Register**](https://govstack.gitbook.io/specification/govstack-ui-ux-guidelines/4-design-patterns/5-user-flows/6.1-register)

## Steps

### 1 - Data Entry

To start the registration process the beneficiary information must be obtained, either via entry by or on behalf of the beneficiary or by finding the required information in a relevant digital registry. In some cases both data entry and data import will be required, depending on the specific data requirements for the use case in question. If data is obtained through a digital registry the beneficiary may also be required to confirm their consent to accessing the data and, if possible, any consent required for other steps within this service block should also be confirmed, to reduce the number of requests to the beneficiary.

**Referenced Service Blocks**

[**User Consent**](https://govstack.gitbook.io/bb-consent/)

[**User Consent: Step 1 - Initiate Request**](https://govstack.gitbook.io/bb-consent/)

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Registration**](https://govstack.gitbook.io/bb-registration/)

**Example Processes**

1. High-Level Process

```Mermaid
sequenceDiagram

actor Individual
Individual->>+Application: Invoke registration workflow
Application->>+Workflow BB: Trigger registration workflow

note over Workflow BB: Identifies the need for consent

Workflow BB->>+Consent BB: Fetch consent agreement (Registration)
Consent BB-->>-Workflow BB: Returns consent agreement
Workflow BB-->>-Application: Returns consent agreement
Application-->>-Individual: Show consent agreement to fetch data 

note over Individual: The individual agrees<br />to the consent agreement 

Individual->>+Application: Accept consent agreement
Application->>+Foundational ID: Redirect to Foundational ID UI

Foundational ID-->>-Individual: Return Foundational ID authentication UI
Individual->>+Foundational ID: Provide credentials to perform authentication
Foundational ID-->>-Application: Return Foundational ID token (e.g. JWT token) 

note over Application: Foundational ID token recieved<br />is the proof of consent

Application->>+Workflow BB: Fetch data workflow
note right of Workflow BB: Fetch data, <br />For e.g. a population regsitry.

Workflow BB-->>-Application: Confirms the workflow
Application-->>+Workflow BB: Record consent against consent agreement (Foundation ID token, Appl user ID)
Workflow BB-->>+Consent BB: Record consent against the consent agreement
Consent BB-->>-Workflow BB: Return consent ID
Workflow BB-->>-Application: Return consent ID
Application-->>-Individual: Confirm registration

note over Foundational ID: Individual is registered

2. New Registration

[Sequence Diagram]

3. Existing Data Import

[Sequence Diagram]

4. Error Handling

[Sequence Diagram]

### 2 - Data Verification

Once the required data has been obtained it must be verified using the appropiate trusted systems for the data in question. Some examples include verifying identification details, tax or financal data, and property ownership data. This verification will likely involve one or more digital registries and may require additional consent to perform.

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

**Example Processes**

1. Data Validation

[Sequence Diagram]

2. Error Handling

[Sequence Diagram]

### 3 - Eligibility Determination

Note - This step may or may not be required, depending on the use case.

The beneficiary data has now been obtained and verified and now the some type of workflow logic is utilized to determine if the beneficiary is eligibible for the service. Examples could include things validating income status, checking for existing enrollments, or confirming age requirements. The key difference between this step and the previous verification step is that this step is confirming service-specific requirements rather than verifying the registration data itself.

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Workflow**](https://govstack.gitbook.io/bb-workflow)

**Example Processes**

1. Confirming Eligibility

[Sequence Diagram]

2. Error Handling

[Sequence Diagram]

### 4 - Enrollment

Now that all the required data entry, data validation, and beneficiary eligibility steps have been performed, the beneficiary can be enrolled into the service. Depending on the use case, this may invovle some additional data gathering (like in step one, this could be manual or via a digital registry) as well as communcation to inform the beneficiary of the enrollment.

**Building Blocks**

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Payments**](https://govstack.gitbook.io/bb-payments/)

[**Registration**](https://govstack.gitbook.io/bb-registration/)

**Example Processes**

1. Enrollment

[Sequence Diagram]

## Contributors

* Wes!
