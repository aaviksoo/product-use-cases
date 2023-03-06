# URB - 1 - Online Building Plan Approval System

## Product Use Case Summary

| ID      | URB-1                                 |
| ------- | ------------------------------------- |
| Name    | Online Building Plan Approval System  |
| Sector  | Urban Planning/ Development           |
| Version | 1.0                                   |
| Status  | Draft                                 |

This use case profiles the implementation process of an online building plan approval system. A system that automates the entire construction permit approval process - from enabling online application submissions of building construction plans, to initiating verification and final approval by the local government agency. A construction permit is an important requirement for countries to ensure buildings and structures are safe, with sound engineering, foundations and construction techniques. This process is how local governments can evaluate construction, renovation or alteration plans and assess their compliance with standard building codes and local regulations.&#x20;

Municipalities and counties/towns have traditionally managed building permits "over the counter" and through paper or PDF applications. This time-consuming and error-prone tasks has raised issues in some countries, around the accountability and transparency, as well as inefficiencies in achieving timely construction permitting processes, and sustainable urban planning development. As a result, a number of governments in low and middle income countries are implementing an online building plan approval system. A system with a hassle-free online procedure and user friendly tools to achieve a more streamlined end to end approval process that ensures transparency, accountability, and time-bound services.

## Stakeholders

* Ministry or national government body in charge of urban development, housing, and/or town planning.
* Local building government authorities - building officials and inspectors, across municipalities in charge of reviewing and issuing construction permits.
* Technical team responsible for the rollout of the building plan portal/platform initiative in the state - system integrator, building architect, software engineer, QA engineer, help desk staff, DevOps engineer etc.&#x20;
* Citizens and professionals (engineers, architects, construction supervisors) seeking permission to construct a building. &#x20;

## SDG Targets

* [11.3](https://solutions.dial.community/sdgs/sustainable\_cities\_and\_communiti): By 2030, enhance inclusive and sustainable urbanization and capacity for participatory, integrated and sustainable human settlement planning and management in all countries.
* [11.6](https://solutions.dial.community/sdgs/sustainable\_cities\_and\_communiti): Reduce the adverse per capita environmental impact of cities, including by paying special attention to air quality and municipal and other waste management.

## Building Blocks

* ****[**Consent**](https://govstack.gitbook.io/bb-consent/)****
* ****[**Digital Registry**](https://govstack.gitbook.io/specification/v/version-0.9.0/building-blocks/digital-registries) ****&#x20;
* ****[**Identification and Verification**](https://govstack.gitbook.io/bb-identity/)****
* [**Messaging**](https://govstack.gitbook.io/bb-messaging/)
* ****[**Payments**](https://govstack.gitbook.io/bb-payments)****
* ****[**Registration**](https://govstack.gitbook.io/bb-registration)****
* ****[**Scheduler**](https://govstack.gitbook.io/specification/building-blocks/scheduler)****
* ****[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)****

Future building block inclusion

* Analytics and Business Intelligence
* Client Case Management
* Data Collection
* Reporting and Dashboards
* Shared Data Repositories
* Terminology

## Source Documents

* [Methodology for the Implementation of Building Permits](https://urban.digit.org/products/modules/online-building-plan-approval-system-obpas/obpas-implementation-guide)&#x20;
* [Djibouti Construction Permit - To Be User Journey - Digital Service Proposal ](https://gizonline.sharepoint.com/:p:/r/sites/ICTBuildingBlocks-CommondigitalSDGplatformwithguests/\_layouts/15/Doc.aspx?sourcedoc=%7B984CC24E-F629-46C4-AD83-AEC911A635D6%7D\&file=Construction%20Permit%20Digital%20Service%20Proposal.pptx\&action=edit\&mobileredirect=true)

## Steps

### 1 - Outreach Communication

Staff from the Ministry of Urban Planning or another leading agency / organization in charge of regulating all aspects of a country's construction issuance processes (building codes and laws), leads the campaign to disseminate information about the online building plan system. Roll out of the online building plan system can be disseminated on the Ministry's and all the building plan municipalities' websites and social media platforms. Marketing and promotional communication materials (i.e. brochures, pamplets, flyers etc) can also be made available at the building plan municipalities/urban centers.&#x20;

To achieve clarity, consistency and transparency on the new online process and requirements for obtaining a construction permit, target communication to the key stakeholders involved (issuing government authorities, citizens, architects engineers) should be prioritized. The state team can lead rollout plans and ensure the necessary infrastructure for local municipalities staff training and deployment are made available at each building plan department in the country. Moreover, to ensure that implementation of the online building plan approval process is uniform throughout the country and that the rules are not interpreted differently, a user manual on the new building plan approval system should be provided for each local government building plan staff.&#x20;

Awareness campaigns can be organized across municipalities informing citizens about the new online building plan application procedure with information on how they can upload their application (building plans and documents), pay fees and track their application online, schedule an inspection (if required), and download and print their permit order once approved.&#x20;

**Workflows**

* **Client communication** to facilitate information dissemination on the new digitized online building plan approval system via government and construction permit websites, social media, and national media channel(s).&#x20;
* **Content management** for the development of a user manual and training guide on the digital solution for building plan officials and/or users wishing to submit a construction permit application.&#x20;
* **Staff communication and education** for informing construction permit issuing staff authorities about the online building plan approval system, and organizing training sessions for staff on how to use the system to review applications, fee payment status, as well as process and issue permits online. &#x20;
* **Identification and Registration** for providing an administration account for all qualified government building plan staff with authority to issue construction permits.&#x20;

**Example Implementation**

To do

**Building Blocks**

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

****[**Scheduler**](https://govstack.gitbook.io/specification/building-blocks/scheduler) ****&#x20;

### 2 - Registration

Registration is the process of collecting information of users wishing to access a digital service. Depending on specific country context and the platform being utilized to host the online building plan approval system, registration process could defer. The online building plan approval system can be hosted using a single window approach to facilitate the end to end construction permit application procedure and clearances from multiple agencies or departments. In certain countries, there is a state wide online building plan platform in place, and the target users - citizens, architects, engineers etc, are required to register (provide full name, email, phone number, occupation etc) on the platform in order to generate personalized login credentials. Then subsequently with these login credentials, the user can then create, save and/or submit a construction permit application on the online portal.&#x20;

**Workflows**

* **Data Collection and Reporting** for capturing and evaluating registration application data submitted, and allocating personalized login cridentials per user.
* **Identification** to easily be able to identify and track registered users.
* **Client Case Management** to help automate and manage the registration process, and respond to any inquiries or issues around registering on the platform.&#x20;

**Example of Implementation**

To do

**Building Blocks**

****[**Consent**](https://govstack.gitbook.io/bb-consent/)****

****[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)****

****[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)****

**Client Case Management**&#x20;

### 3 - Application Process

A permit application is the process of applying for the issuance of a legal document to conduct a specific activity that requires the approval from a governmental authority. In this use case, a construction/building permit is an official approval issued by a local government agency that reviews construction permit applications to ensure the building plan complies with local standards for land use, zoning, and construction. Once approval has been received, the applicant can start the construction project.

Depending on the country context, the application process can require applicants to fill out a standardized online application form, upload specific documentation (i.,e. building plan, land title, ownership certificate, etc) and pay the required application fee online - all in a streamlined manner. Once their application is submitted, applicants should be able to view and track their application, scheduele any follow-up appointments required for document scrutiny and/or site inspection visits by a public official. Emails and SMS notifications can be sent to the applicants to request follow-up action items and/or provide updates during the application process.

**Workflows**

* **Data Collection and Reporting** for capturing and evaluating permit application data submitted by the user applicant.
* **Identification** to easily be able to identify and track registered applicant applying for a construction permit.  &#x20;
* **Client Case Management** to help automate and manage the permit application and approval process. Support in vetting/ensuring the applicants meet the eligibility requirements, and have submitted all required documentations. Also scheduele any necessary followup site visits by the building plan inspection authority.
* **Financial Services** for processing the permit application fee and generating payment confirmation receipt.&#x20;

**Example of Implementation**

To do

**Building Blocks**

****[**Consent**](https://govstack.gitbook.io/bb-consent/)****

****[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)****

****[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)****

****[**Messaging**](https://govstack.gitbook.io/bb-messaging/)****

****[**Payments**](https://govstack.gitbook.io/bb-payments/)****

**Client Case Management**&#x20;

### 4 - Data Verification and Validation

Data within the online building plan approval system is generally checked\* by the Central Level Ministry in charge of urban planning, housing and building and the local building plan management municipality departments, against other government databases (eg. ID, tax, land titles, utilities, etc.) in order to fill in any missing gaps, verify and validate collected information, including authentication of all records. \*Data checking approaches also vary: sometimes batch-sharing via CD, sometimes full interoperability.

**Workflows**

* **Client Case Management** for storing and reviewing registration, and construction permit application records.&#x20;
* **Data Analysis and Business Intelligence** for cross-referencing and verifying records across multiple registry sources, and reconciling gaps / overlaps.

**Example Implementation**

To do

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

****[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)****

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

****[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)****

**Client Case Management**

**Analytics and Business Intelligence**

### 5 - Review

Online building plan approval system can have APIs in place that can scrutinize submitted construction permit applications to decide whether to reject or approve the building plan. This entails the detailed review of application form data and all uploaded documentations (i.e. building plan, land ownership deed etc). NOTE: Depending on the country, construction permit approval takes different forms e.g. some countries have a document submission checklist embedded and if one of the required documents is not submitted, then the application is automatically rejected. If not approved, the applicant will receive an email stating what is missing or required. If the submitted documents are unclear or structural design images blurry, then the application is left as pending and a local building plan officer receives a notification for a more manual review. The building plan officer can then request the hard copy permit application submissions, when appropriate.&#x20;

Applicants should receive notification updates on the status of their application. Permits that are approved and issued should be downloadable on the applicant's personalized user account/ portal.

**Workflows**

* **Client Case Management** for reviewing submitted applications, and communicating any application status updates or additional information needed to the applicant.
* **Data Analysis and Business Intelligence / Decision Support** for approving or rejecting applications, based on required documentation submissions, and existing criteria (e.g. via checklist, or category-based).

**Example Implementation**

To do

**Building Blocks**

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

****[**Messaging**](https://app.gitbook.com/s/mNnAAqNpNoSI6WELhO9t/1-description)****

**Client Case Management**

**Analytics and Business Intelligence**

**Artificial Intelligence**

### 6 - Payment

Multiple fee types can be required in the construction permit approval process (e.g. filing fee, permit fee, surcharge fee, etc). A document can be made available summarizing the building permit fees and calculation method.

If an electronic payment process is enabled, then applicants can pay these fees via a digital financial service system embedded in the platform. In certain countries, these fees are calculated based on the construction location, project size and type. Following the submission of their online permit application, the applicant can be taken to a payment portal with information on the calculation of their permit fee which is payable online i.e, via a third-party integrations (NOC, Payment gateway, Digital signature) or local government online payment system. The applicant must pay all outstanding fees for their permit application to be issued. Once the payment is processed, a payment confirmation screen is displayed. Applicants should also receive (i.e. via email, mobile etc) a standard payment receipt.&#x20;

**Workflows**

* **Financial Services** for processing all fees associated with the building plan approval process and generating payment confirmation receipts.&#x20;
* **Client Case Management** for calculating fees, and monitoring/verifying that all required payment transactions, per applicant, has been fully processed and received. Also ensuring that applicants receive payment confirmation and recipt.&#x20;
* **Content management** for the development of documentation summarizing building permit fees and calculation method.

**Example Implementation**

To do

**Building Blocks**

****[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries) ****&#x20;

****[**Messaging**](https://app.gitbook.com/s/mNnAAqNpNoSI6WELhO9t/1-description)****

[**Payments**](https://govstack.gitbook.io/bb-payments/)

****[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)****

**Client Case Management**

### **7 - Ongoing Case Management**

This step involves ensuring that there is a virtual help desk and/or physical support centers in place to address any quiries pertaining to registration on the platform and the construction permit approval decision. Incorporating a complaint management software will efficiently and transparently ensure that all grievances, complaints and appeals raised by the applicants, are tracked and addressed. In certain countries, this process is led by the online building plan help desk support unit at the state level. The local building officials can also be trained to address any queries that cannot be addressed through an automated process.

**Workflows**

* **Data Collection and Reporting** for capturing reoccurring complaints, quieries and feedback received from the building plan approval system platform users and building permit holders. And integration of other databases and systems for automated data update on client cases overtime.
* **Client Case Management** for identifying and capturing reported cases on grievances / appeals etc., and for determining decisions/actions to proceed with by reviewing individual applicants client case.

**Example Implementation**

To do

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

****[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries) ****&#x20;

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

****[**Messaging**](https://app.gitbook.com/s/oEAfhW9JLP3tJ6mPyxtF/2-description) ****&#x20;

****[**Scheduler**](https://govstack.gitbook.io/specification/building-blocks/scheduler)****

****[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)****

**Data Collection**

## Contributors

* \<List of contributors, optionally including organization and email address>
