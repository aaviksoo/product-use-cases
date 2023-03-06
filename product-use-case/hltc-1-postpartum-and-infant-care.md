# HLTC-1-Postpartum and Infant Care

### Product Use Case Summary

| ID      | HLTC-1                     |
| ------- | -------------------------- |
| Name    | Postpartum and Infant Care |
| Sector  | Healthcare                 |
| Version | 1.0                        |
| Status  | Draft                      |

This use case profiles the digital integration steps to provide high-quality and integrated Postpartum and Infant Care services for a mother and child spanning the mother's prenatal and postnatal periods - during the pregnancy, childbirth and after birth. Governments in low- and middle-income countries are increasingly implementing mother and child care programmes to provide primary healthcare services, prenatal care and educate new mothers about post-delivery care (e.g. breastfeeding, nutrition, immunization, personal hygiene). This use case will support and guide countries in their efforts to reduce maternal and perinatal mortality and morbidity, and reach every woman and child to ensure that pregnancy, birth and the first postnatal weeks are a safe experience.

### SDG Targets

* [3.1](https://solutions.dial.community/sdgs/good\_health\_and\_wellbeing): By 2030, reduce the global maternal mortality ratio to less than 70 per 100,000 live births.
* [3.2](https://solutions.dial.community/sdgs/good\_health\_and\_wellbeing): By 2030, end preventable deaths of newborns and children under 5 years of age, with all countries aiming to reduce neonatal mortality to at least as low as 12 per 1,000 live births and under‑5 mortality to at least as low as 25 per 1,000 live births.

### Building Blocks

* [Consent](https://govstack.gitbook.io/bb-consent)
* [Identification and Verification](https://govstack.gitbook.io/bb-identity)
* [Messaging](https://govstack.gitbook.io/bb-messaging/)
* [Payments](https://govstack.gitbook.io/bb-payments)
* [Registration](https://govstack.gitbook.io/bb-registration)
* [Scheduling](https://govstack.gitbook.io/bb-scheduler/)
* [Workflow and Algorithm](https://govstack.gitbook.io/bb-workflow)

Future building block inclusion

* **Artificial Intelligence**
* **Client Case Management**
* **Collaboration Management**
* **Data Collection**
* **eLearning**
* **eMarketplace**
* **Geographic Information Services (GIS)**
* **Mobility Management**
* **Shared Data Repositories**
* **Terminology**

### Steps

#### 1 - Outreach Communications

Staff from the Ministry of Health, Social Health Activist Unit or another leading agency / organization collaborates with Community Health Workers (CHW), and organizes an information campaign to spread awareness and encourage enrollment in the mother and childcare community health programme. The campaign is conveyed via mobile messaging and/or aired on national radio/television as well as through field visit campaigns to local villages, hospitals/clinics - performed by well trained Community Health Workers. Outreach communication is intensive during the kick-off phase of the new programme, but also requires targeted communications to encourage expectant mothers' enrollment in the mother and child care community programme.&#x20;

A comprehensive information and education campaign is developed around prenatal and postnatal healthcare services available through the programme. Ongoing touchpoints and educational materials/content is available offline in local languages, and available for distribution at all health clinics, facilitates and hospitals. The materials should include information on programme enrollment process and incentives, primary care recommendations/guidelines, pre-and post delivery healthcare support services being offered, participating facilities/clinics, beneficiaries rights and responsibilities, etc.

**Workflows**

* **Client communication** to facilitate the spreading of programme awareness for target audience and encouraging enrollment via mobile / media channel(s)
* **Client education** for educating potential target beneficiaries around the approach and objective(s), benefit(s), incentives, role of Community Health Workers, partner(s), etc. of the programme
* **Content management** for the backend Community Health Workers staff to populate relevant educational and promotional content that local clinics, hospitals, facilities etc, can disseminate and use during on-the-ground outreach campaigns
* **Identification and Registration** (with aid of geographic information services tool \*\*\*\* for potential use) in mapping and locating households with infants/ expectant mothers for outreach target

**Example Implementation**

To do

**Building Blocks**

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Scheduling**](https://govstack.gitbook.io/bb-scheduler/)

**Mobility Management**

**eLearning**

#### 2 - Registration

Registration is the process of collecting information of target beneficiaries for identification purpose, assessment of their needs and conditions, and to enroll them in a programme. Registration will support the creation of an electronic medical record (EHR) for each enrolled beneficiary to ensure the effective monitoring/supervision of complete, accurate, and timely flow of healthcare data. Depending on specific country context, registration can work in very different ways. However the general data and information required for this use case is in order to register the target beneficiaries in to a Mother and Child Tracking System (MCTS) that the government has in place. MCTS is a centralized information technology - based application for improving the delivery of maternal and child health care services through name-based tracking.&#x20;

Registration of the target beneficiaries into the MCTS should include the following: the mother's name, phone number and ID, as well as the information of their child's name, address and birth certificate. The data (the birth certificate and mother’s ID) provided is then automatically validated in the government’s citizen records system. Once their information is validated, it results in the following: 1. an online account per beneficiary - created for records associated with the mother and child care community programme; 2. a barcode unique to each beneficiary; 3. a Community Health Worker assigned to their case to support the beneficiary in accessing all health services under this programme. The registered phone number of the mother/main child caretaker can also be used to coommunicate, book appointments and coordinate various services being provided within this programme.

\*\*\*Submission of the required enrollment details, leads to the issuance of a unique ID to the central mother and child care system, which authenticates the ID with the national ID system and creates a new record for the mother and child.

**Workflows**

* **Data Collection and Reporting** for capturing responses or general observation during registration process
* **Identification and Registration** for registering and enrolling the mother and child in the system and enabling permissions for interaction with the MCTS
* **Client Case Management** for the target beneficiary (mother/child's main caregiver) to give permission to a Healthcare Worker to access and use their electronic healthcare record to coordinate the mother and child's healthcare services being provided under the programme

**Example Implementation**

To do

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Registration**](https://govstack.gitbook.io/bb-registration/)

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

#### 3 - Data Verification and Validation

Data within the Mother and Child Tracking System (MCTS) is generally checked\* by the Ministry of Health managers, against other government databases (eg. ID, citizen's records, civil registry municipality etc.) in order to fill in any missing gaps, verify and validate collected information, including authentication of all records. \*Data checking approaches also vary: sometimes batch-sharing via CD, sometimes full interoperability.

**Workflows**

* **Client Case Management** for storing and reviewing identification records and authentication information of target beneficiaries
* **Data Analysis and Business Intelligence** for cross-referencing and verifying records across multiple registry sources, and reconciling gaps / overlaps

**Example Implementation**

To do

**Building Block Workflows**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

**Client Case Management**

**Analytics and Business Intelligence**

#### 4 - Eligibility Determination&#x20;

In most countries, the maternal and child health programme is part of the general health services provided by the government, however the eligibility structure can vary across countries. All expecting mothers and core caregiver of infant children are generally considered to be eligible beneficiaries. The targets for this programme are all women in their reproductive age groups, i.e., 15 - 49 years of age, and infants/ new born population. \*\*\*Certain government's give eligibility priorities to low-income pregnant individuals to help them get the health and social services they may need and covers a variety of services for pregnant individuals and their infants.

**Workflows**

* **Client Case Management** for effectively managing all eligible and enrolled beneficiaries in the programme and monitoring the healthcare services being provided to them&#x20;
* **Data Analysis and Business Intelligence** potentially for mapping and analyzing the different beneficiaries - socioeconomic / demographic information

**Example Implementation**

To do

**Building Blocks**

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

**Client Case Management**

**Analytics and Business Intelligence**

**Artificial Intelligence**

#### 5 - Enrollment

Through identification by Community Health Workers or target beneficiaries' vist to local clinics, hospitals etc, the eligible beneficiaries will be informed about the benefits and incentives of the mother and child community health programme and asked to enroll in the programme. During the enrollment, further data can be collected (depending on programme design) e.g. pregnancy and general health details, phone number, bank account details, biometrics, etc. Moreover, depending on the system setup by country, each beneficiary is then issued an online account and/or unique barcode to keep track/record of each beneficiary participating in the programme and utilizing the primary healthcare services being provided.&#x20;

All programme specific data is often stored in the Mother and Child Tracking System (MCTS). In practice, this is a tailored software application that supports beneficiary management functions (e.g. enrollment, payments, case management, M\&E etc.).

**Workflows**

* **Data Collection and Reporting** for capturing additional programmatic information on the beneficiaries during enrolment
* **Financial Services** for staging beneficiary account details for enrollment  incentive payment processing
* **Identification and Registration** for identifying beneficiaries and confirming enrolment
* **Client Case Management** for storing program specific data for tracking

**Example of Implementation**

To do

**Building Blocks**

[**Payments**](https://govstack.gitbook.io/bb-payments/)

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Registration**](https://govstack.gitbook.io/bb-registration/)

**Client Case Management**

**Artificial Intelligence**

#### 6 - Payment

Certain mother and child community health programs have a financial incentive in place in order to incentivize eligible beneficiaries to enroll and fully participate in the programme and the pre and post natal health services being provided. Furthermore in some cases, Community Health Workers also receive an incentive distribution for convincing/facilitating the process for expectant mothers to enroll in the programme. In most cases, incentive distributions are paid through mobile G2C or B2C incentive payments. Payments are subsequently paid according to the programme schedule e.g. one time incentive payment.&#x20;

**Workflows**

* **Financial Services** for processing incentive payments that are G2C or B2C mobile payments, for withdrawal by beneficiary from designated mobile money/ pay-point(s) thereafter
* **Client Case Management** for identifying and authenticating individual that is making a withdrawal, or to recall / verify deposit account information prior to payment transaction

**Example Implementation**

To do

**Building Blocks**

[**Payments**](https://govstack.gitbook.io/bb-payments/)

**Client Case Management**

#### 7 - Ongoing Case Management

As part of this programme, Community Health Workers or healthcare professionals, play a very active and hands-on role in the programme. They are generally the professionals on the ground, reaching out to target beneficiaries and convincing them to enroll in the programme.&#x20;

This step involves ongoing interaction with beneficiaries via Community Health Workers and local hospitals/clinics/facilities to: ensure information on beneficiaries stays up to date, monitor usage of the primary healthcare services, and address grievances, and general primary care needs. Note that this step also requires clarity, clear decisions, and protocols regarding up-to-date data management and sharing between different health clinics and hospitals that provide pre-and post natal healthcare services.

**Workflows**

* **Data Collection and Reporting** for capturing changes in beneficiary information
* **Client Case Management** for identifying and recording beneficiary interaction with Community Health Workers, local hospitals/clinics and capturing reported cases on grievances etc., and for determining risks / conditionality by reviewing individual beneficiary client case
* **Work Planning and Coordination** to potentially suggest and connect with other hospitals, clinics and relevant healthcare services to target beneficiaries

**Example Implementation**

To do

**Building Blocks**

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Consent**](https://govstack.gitbook.io/bb-consent/)

**Data Collection**

**Geographic Information Services (GIS)**

**Scheduling**

**Workflow**

#### 8 - Ongoing M\&E

National healthcare managers and officers make decisions and management choices (e.g. where to conduct add-on training on pre-natal and post-natal care, enrollment facilities in clincs/hospitals, or communities, where to prioritize budget, etc.) on up-to-date data on the programme/s (e.g. what primary healthcare services are being provided and by whom, where and when, what areas are performing better, etc). Note that countries that do this effectively ensure programme data is connected / integrated/ uptodate on MCTS and other relevant databases.

**Workflows**

* **Client Case Management** for ongoing monitoring and tracking of both mother and child's health wellbeing and performance, ensure easy assessment of holistic view and reporting
* **Identification and Registration** (with aid of geographic information services tool for potential use) in tracking / locating clinics and hospitals being used through the programme
* **Data Analysis and Business Intelligence** / **Decision Support** / **Data Collection and Reporting** to analyze, update, and report programme output / performance information

**Building Block Workflows**

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Consent**](https://govstack.gitbook.io/bb-consent/)

**Data Collection**

**Geographic Information Services (GIS)**

**Scheduling**

**Workflow**

#### 9 - Updating

Ensuring data is up to date to trigger: Programme exit for those who are no longer eligible e.g. when a beneficiary dies, migrates, child exceeds eligible infant age or no longer qualifies for other reasons. This is achieved via a combination of re-enrollement campaigns anytime a mother is expecting, automated data updates, and data-sharing with other government databases e.g. civil registration for brith and death. Programme entry for newly eligible beneficiaries, via new data collection or analysis etc. Other changes to entitlements (e.g.child no longer considered an infant). Note that this step also requires clarity, clear decisions, and protocols regarding whose data (or subset of such) is to be updated by which programme personnel or role and at what time.

**Workflows**

* **Data Collection and Reporting** for routine update of information on the beneficiary client base, and integration of other databases and systems for automated data update on client cases overtime
* **Client Case Management** for ongoing review of beneficiary case information
* **Data Analysis and Business Intelligence** / **Decision Support** to support identification of individuals for exit or entry based on analyzing change in programme-specific / socioeconomic data

**Example Implementation**

To do

**Building Block Workflows**

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Consent**](https://govstack.gitbook.io/bb-consent/)

**Data Collection**

**Geographic Information Services (GIS)**

**Scheduling**

**Workflow**

### Outputs

1. To Do

### Failure Points

1. To Do
