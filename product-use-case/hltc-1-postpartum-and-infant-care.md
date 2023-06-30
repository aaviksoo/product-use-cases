# HLTC-1- Postpartum and Infant Care

## Product Use Case Summary

| ID      | HLTC-1                     |
| ------- | -------------------------- |
| Name    | Postpartum and Infant Care |
| Sector  | Health                     |
| Version | 1.0                        |
| Status  | Published                  |

This use case profiles the digital integration steps to provide high-quality and integrated Postpartum and Infant Care services for a mother and child spanning the mother's prenatal and postnatal periods - during the pregnancy, childbirth and after birth. Governments in low- and middle-income countries are increasingly implementing mother and child care programmes to provide primary healthcare services, prenatal care and educate new mothers about post-delivery care (e.g. breastfeeding, nutrition, immunization, personal hygiene).

Postpartum maternal and infant mortality is still high across multiple low and middle income countries. This use case will support and guide countries in their efforts to reduce maternal and perinatal mortality and morbidity, through digitizing the process of postpartum care and services.

## Stakeholders

* Ministry of Health and Welfare or national government body in charge of providing nationwide healthcare services and/or postpartum services and care.
* Community healthcare workers trained in essential newborn care, and providing postpartum care for both mother and their newborns.
* Expectant mothers and their new born babies as the key beneficiaries of this service.

## SDG Targets

* [3.1](https://solutions.dial.community/sdgs/good\_health\_and\_wellbeing): By 2030, reduce the global maternal mortality ratio to less than 70 per 100,000 live births.
* [3.2](https://solutions.dial.community/sdgs/good\_health\_and\_wellbeing): By 2030, end preventable deaths of newborns and children under 5 years of age, with all countries aiming to reduce neonatal mortality to at least as low as 12 per 1,000 live births and under‑5 mortality to at least as low as 25 per 1,000 live births.

## Building Blocks

* [**Consent**](https://govstack.gitbook.io/bb-consent)
* [**Identification and Verification**](https://govstack.gitbook.io/bb-identity)
* [**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)
* [**Messaging**](https://govstack.gitbook.io/bb-messaging/)
* [**Payments**](https://govstack.gitbook.io/bb-payments)
* [**Registration**](https://govstack.gitbook.io/bb-registration)
* [**Scheduling**](https://govstack.gitbook.io/bb-scheduler/)
* [**Workflow and Algorithm**](https://govstack.gitbook.io/bb-workflow)

## Source Documents

* [Digital Impact Exchange - Postpartum and Infant Care](https://exchange.dial.global/use\_cases/postpartum\_and\_infant\_care)

## Steps

### 1 - Outreach Communications

Staff from the Ministry of Health or the relevant government agency leads a campaign to spread awareness about a new mother and childcare community health programme with the purpose of facilitating postpartum healthcare services. A comprehensive information and education campaign is developed around prenatal and postnatal healthcare services available through the programme. These educational materials/content can be made available in local languages online. The materials could include information on programme enrollment process and incentives, primary care recommendations/guidelines, pre-and post delivery healthcare support services being offered, participating facilities/clinics, beneficiaries rights and responsibilities, etc.

Outreach communication should be intensive during the kick-off phase of the new programme, but also requires targeted communications to encourage expectant mothers' enrollment in the mother and child care community programme. The campaign can be conveyed via mobile messaging and/or aired on national radio/television as well as through field visit campaigns to local villages, hospitals/clinics - performed by well trained community healthcare workers.

**Workflows**

* **Client Communication** to facilitate the spreading of programme awareness for target audience and encouraging enrollment via mobile / media channel(s)
* **Client Education** for educating potential target beneficiaries around the approach and objective(s), benefit(s), incentives, role of Community Healthcare Workers, partner(s), etc. of the programme
* **Content Management** for the backend Community Healthcare Workers staff to populate relevant educational and promotional content that local clinics, hospitals, facilities etc, can disseminate and use during on-the-ground outreach campaigns

**Building Blocks**

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Scheduling**](https://govstack.gitbook.io/bb-scheduler/)

### 2 - Registration

Registration is the process of collecting information of target beneficiaries for identification purpose, assessment of their needs and conditions, and to enroll them in a programme. Depending on specific country context, registration can work in very different ways. Registration should support the creation of an electronic medical record and tracking capabilities for each enrolled beneficiary. This can ensure timely and effective monitoring of healthcare data.

For example, some countries use a centralized information technology based application to deliver maternal and child health care services through name-based tracking. During registration, the following information is collected: the mother's name, phone number and ID, as well as the information of their child's name, address and birth certificate. The data (the birth certificate and mother’s ID) provided is then automatically validated in the government’s citizen records system. Once their information is validated, it results in the following: 1. an online account per beneficiary - created for records associated with the mother and child care community programme; 2. a barcode unique to each beneficiary; 3. a Community Healthcare Worker assigned to their case to support the beneficiary in accessing all health services under this programme.

**Workflows**

* **Data Collection and Reporting** for capturing responses or general observation during registration process
* **Identification and Registration** for registering the mother and child in the system
* **Client Case Management** for the target beneficiary (mother/child's main caregiver) to give permission to a Healthcare Worker to access and use their electronic healthcare record to coordinate the mother and child's healthcare services being provided under the programme

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Registration**](https://govstack.gitbook.io/bb-registration/)

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

### 3 - Data Verification and Validation

Data within the Mother and Child Tracking System (MCTS) is generally checked by the Ministry of Health managers, against other government databases (eg. ID, citizen's records, civil registry municipality etc.) in order to fill in any missing gaps, verify and validate collected information, including authentication of all records. \*Data checking approaches also vary: sometimes batch-sharing via CD, sometimes full interoperability.

**Workflows**

* **Client Case Management** for storing and reviewing identification records and authentication information of target beneficiaries
* **Data Analysis and Business Intelligence** for cross-referencing and verifying records across multiple registry sources, and reconciling gaps / overlaps

**Building Block Workflows**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

### 4 - Eligibility Determination

Eligibility determination is the process of assessing whether an eligibility criteria is met inorder to benefit from certain services. In most countries, the maternal and child health programme is part of the general health services provided by the government, however the eligibility structure can vary across countries. All expecting mothers and caregivers of infant children are generally considered to be eligible beneficiaries. The targets for this programme depends on a country by country basis. In certain countries, the target beneficiaries all women in their reproductive age groups, i.e., 15 - 49 years of age, and infants/ new born population. \*\*\*Certain government's give eligibility priorities to low-income pregnant individuals to help them get the health and social services they may need and covers a variety of services for pregnant individuals and their infants.

Community Healthcare workers determine eligibility by reviewing all submitted registration details. Once eligibility has been determined, a notification (via sms, email etc) is sent to the beneficiary.

**Workflows**

* **Client Case Management** for effectively managing all eligible and enrolled beneficiaries in the programme and monitoring the healthcare services being provided to them
* **Communication** to inform target beneficiaries that they meet the eligibility criteria and can start the enrollment process
* **Data Analysis and Business Intelligence** potentially for mapping and analyzing the different beneficiaries - socioeconomic / demographic information

**Building Blocks**

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

### 5 - Enrollment

Enrollment is the action of being enrolled and accepted as a beneficiary to receive certain benefits and/or access to a service provision. In certain countries, once eligibility is confirmed, the target beneficiary is considered as enrolled in the programme. During the enrollment, further data can be collected (depending on programme design) e.g. pregnancy and general health details, phone number, bank account details, biometrics, etc. Moreover, depending on the system setup by country, each beneficiary is then issued an online account and/or unique barcode to keep track/record of each beneficiary participating in the programme and utilizing the primary healthcare services being provided. \*\*All programme specific data is often stored in a tailored software application that supports beneficiary management functions (e.g. enrollment, payments, case management, M\&E etc.).

**Workflows**

* **Data Collection and Reporting** for capturing additional programmatic information on the beneficiaries during enrolment
* **Financial Services** for staging beneficiary account details for enrollment incentive payment processing
* **Identification and Registration** for identifying beneficiaries and confirming enrolment
* **Client Case Management** for storing program specific data for tracking

**Building Blocks**

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Payments**](https://govstack.gitbook.io/bb-payments/)

[**Registration**](https://govstack.gitbook.io/bb-registration/)

### 6 - Payment

Certain mother and child community health programs have a financial incentive in place in order to incentivize eligible beneficiaries to enroll and fully participate in the programme and the pre and post natal health services being provided. Furthermore in some cases, Community Health Workers also receive an incentive distribution for convincing/facilitating the process for expectant mothers to enroll in the programme. In most cases, incentive distributions are paid through mobile G2C or B2C incentive payments. Payments are subsequently paid according to the programme schedule e.g. one time incentive payment.

**Workflows**

* **Financial Services** for processing incentive payments that are G2C or B2C mobile payments, for withdrawal by beneficiary from designated mobile money/ pay-point(s) thereafter
* **Client Case Management** for identifying and authenticating individual that is making a withdrawal, or to recall / verify deposit account information prior to payment transaction

**Building Blocks**

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Payments**](https://govstack.gitbook.io/bb-payments/)

### 7 - Ongoing Case Management

As part of this programme, Community Healthcare Workers or healthcare professionals, play a very active and hands-on role in the programme. They are generally the professionals on the ground, reaching out to target beneficiaries and convincing them to enroll in the programme.

This step involves ongoing interaction with beneficiaries via Community Health Workers and local hospitals/clinics/facilities to: ensure information on beneficiaries stays up to date, monitor usage of the primary healthcare services, and address grievances, and general primary care needs. Note that this step also requires clarity, clear decisions, and protocols regarding up-to-date data management and sharing between different health clinics and hospitals that provide pre-and post natal healthcare services.

**Workflows**

* **Data Collection and Reporting** for capturing changes in beneficiary information
* **Client Case Management** for identifying and recording beneficiary interaction with Community Health Workers, local hospitals/clinics and capturing reported cases on grievances etc., and for determining risks / conditionality by reviewing individual beneficiary client case
* **Work Planning and Coordination** to potentially suggest and connect with other hospitals, clinics and relevant healthcare services to target beneficiaries

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Payments**](https://govstack.gitbook.io/bb-payments/)

### 8 - Ongoing M\&E

National healthcare managers and officers make decisions and management choices (e.g. where to conduct add-on training on pre-natal and post-natal care, enrollment facilities in clincs/hospitals, or communities, where to prioritize budget, etc.) on up-to-date data on the programme/s (e.g. what primary healthcare services are being provided and by whom, where and when, what areas are performing better, etc). Note that countries that do this effectively ensure programme data is connected / integrated/ uptodate on MCTS and other relevant databases.

**Workflows**

* **Client Case Management** for ongoing monitoring and tracking of both mother and child's health wellbeing and performance, ensure easy assessment of holistic view and reporting
* **Identification and Registration** (with aid of geographic information services tool for potential use) in tracking / locating clinics and hospitals being used through the programme
* **Data Analysis and Business Intelligence** / **Decision Support** / **Data Collection and Reporting** to analyze, update, and report programme output / performance information

**Building Block Workflows**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

### 9 - Updating

Ensuring data is up to date to trigger: Programme exit for those who are no longer eligible e.g. when a beneficiary dies, migrates, child exceeds eligible infant age or no longer qualifies for other reasons. This is achieved via a combination of re-enrollement campaigns anytime a mother is expecting, automated data updates, and data-sharing with other government databases e.g. civil registration for brith and death. Programme entry for newly eligible beneficiaries, via new data collection or analysis etc. Other changes to entitlements (e.g.child no longer considered an infant). Note that this step also requires clarity, clear decisions, and protocols regarding whose data (or subset of such) is to be updated by which programme personnel or role and at what time.

**Workflows**

* **Data Collection and Reporting** for routine update of information on the beneficiary client base, and integration of other databases and systems for automated data update on client cases overtime
* **Client Case Management** for ongoing review of beneficiary case information
* **Data Analysis and Business Intelligence** / **Decision Support** to support identification of individuals for exit or entry based on analyzing change in programme-specific / socioeconomic data

**Building Block Workflows**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

## Contributors

* Wesley Brown, GovStack Product Owner, Digital Impact Alliance
* Steve Conrad, Associate Director of Technology, Digital Impact Alliance
* Sarah Farooqi, The Exchange Product Owner, Digital Impact Alliance
* Sainabou Jallow, Business Analyst, Digital Impact Alliance
* Dr. P. S. Ramkumar, GovStack, International Telecommunication Union (ITU)
* Max Carlson, GovStack
* Raul Kaidro, GovStack
