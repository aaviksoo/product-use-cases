# EDU-1 - Remote Learning

| ID      | EDU-1           |
| ------- | --------------- |
| Name    | Remote Learning |
| Sector  | Education       |
| Version | 1.0             |
| Status  | Draft           |

The primary objective of the remote learning platform is to deliver engaging and effective educational content to students, facilitate seamless communication between educators and learners, enable interactive assessments, and support continuous learning in a virtual environment.

Remote learning systems can be used to enhance traditional schooling, for vocational training, or for continuous learning and it reduces the need for physical infrastructure, travel, and resource duplication. Learners can access educational content and participate in classes from anywhere, breaking down geographical barriers, and promoting learners of all abilities to participate effectively.&#x20;

## Stakeholders

* **Administrator** that manages the remote learning system and can be available for technical difficulties.
* **Educator** that is in charge of course creation, course delivery, and student evaluation.
* **Learner** that is accessing platform for educational content.&#x20;

## SDG Targets

* [4.1](https://exchange.dial.global/sdgs/quality\_education): By 2030, ensure that all girls and boys complete free, equitable and quality primary and secondary education leading to relevant and effective learning outcomes
* [4.3](https://exchange.dial.global/sdgs/quality\_education): By 2030, ensure equal access for all women and men to affordable and quality technical, vocational and tertiary education, including university
* [4.4](https://exchange.dial.global/sdgs/quality\_education): By 2030, substantially increase the number of youth and adults who have relevant skills, including technical and vocational skills, for employment, decent jobs and entrepreneurship
* [4.5](https://exchange.dial.global/sdgs/quality\_education): By 2030, eliminate gender disparities in education and ensure equal access to all levels of education and vocational training for the vulnerable, including persons with disabilities, indigenous peoples and children in vulnerable situations

## Building Blocks

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Identity** ](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Registration**](https://govstack.gitbook.io/bb-registration/)

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Scheduler**](https://govstack.gitbook.io/bb-scheduler/)

[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)

## Source Documents

[_SDG Digital Investment Framework - A whole-of-Government Approach to Investing in Digital Technologies to Achieve the SDGs_](http://handle.itu.int/11.1002/pub/812df924-en)

## Steps

### 1 - Registration&#x20;

Educators register on the platform by providing their credentials, teaching experience, and expertise. Their accounts are verified and approved by administrators. Learners register on the platform by providing basic personal information. User accounts are created, allowing access to course offerings and other platform features.

**Workflows**

* **Data Collection and Reporting** for capturing details of educators and learners.
* **Identification and Registration** for educators and students.&#x20;
* **Client Case Management** for creating user records

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Identity** ](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Registration**](https://govstack.gitbook.io/bb-registration/)

### 2 - Data Verification and Validation&#x20;

Accounts are verified and approved by administrators, including setting permissions based on the user profile. For example, educators will have access to course creation features and will have grade visibility of all students (if applicable). Learners will have a view that supports their personal learning. Advanced identity verification mechanisms, such as email confirmation or multi-factor authentication can ensure the accuracy of user-provided information and prevent unauthorized access. In some cases verification will also involve checking with learning institution (such as student/faculty ID numbers).&#x20;

**Workflows**

* **Client Case Management** for storing and reviewing identification records&#x20;
* **Data Analysis and Business Intelligence** for cross-referencing and verifying records with email, two-factor authentication, student/faculty records

**Building Blocks**&#x20;

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

### 3 - Payment&#x20;

In some cases, payment will be required as part of the course, and students and/or educators will have to make the payment after registration. In other cases, payment may be collected as part of a school student and will be external to the learning management system. If payment is required, the platform can facilitate secure online payment options for course enrollment, or the student may be be requested to travel to the nearest designated pay-point and pay in person.

**Workflows**

* **Financial Services** for processing educator and/or learner payments for accessing the course
* **Client Case Management** for identifying and authenticating individual that is making the payment&#x20;

**Building Blocks**

[**Payments**](https://govstack.gitbook.io/bb-payments/)

### 4 - Educator functions

Educators can create courses, upload course materials, including lecture notes, presentations, assignments, and reading materials. These resources are made available to enrolled students. They can also conduct real-time virtual classes using video conferencing tools integrated into the platform.&#x20;

**Workflows**

* **Client Education** for tutorials or guides aimed educators that are creating course content
* **Knowledge Management** to manage course materials, lectures, assets, etc.
* **Work planning and Coordination** to manage release of learning modules, grades, quizzes, etc.&#x20;

**Building Blocks**

[**Scheduler**](https://govstack.gitbook.io/bb-scheduler/)

[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)

### 5 - Student functions

Learners can access course content when released by instructors, submit assignments, access quizzes, access grades, and use discussion boards interact with peers and educators. Students can also receive notifications when new modules, messages, or grades are received.

**Workflows**

* **Client Education** for tutorials or guides aimed learners to be able to use platform with ease
* **Knowledge Management** to manage submissions, interactions with educators and peers, etc.&#x20;

**Building Blocks**

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Scheduler**](https://govstack.gitbook.io/bb-scheduler/)

[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)

### 6 - Provide evidence of learning

At the end of the course, the learner will receive proof of evidence of learning, for example: a digital badge, final grade, and/or certificate that shows the course was completed by the student.

**Workflows**

* **Identification and registration** to link student account with credential/digital badge

**Building Blocks**

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Scheduler**](https://govstack.gitbook.io/bb-scheduler/)

### 7 - Ongoing monitoring and evaluation

The platform tracks student performance, engagement, and progress throughout the course. Educators and administrators access real-time analytics and reports to monitor learning outcomes. Administrators can also track bug and issues create system updates accordingly.&#x20;

**Workflows**

* **Client Case Management** for ongoing monitoring and tracking of how educators and learners are using the platform
* **Data Analysis and Business Intelligence** / **Decision Support** / **Data Collection and Reporting** to analyze, update, and report course performance and evaluation

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Scheduler**](https://govstack.gitbook.io/specification/building-blocks/scheduler)

[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)

### 7 - Archiving/Sunsetting

The system should cater to the archiving/sunsetting of student data, cohort data, and course data, while considering the security of personally identifiable information. In some cases, data should be archived at the end of the course or at the end of student enrollment. In other cases, the system will have a delay function where data will be archived after a pre-determined amount of time. While most data should be archived, analytics and other anonymized data can be retained. Reminder messages may be sent to stakeholders to remind them that their data will be archived/deleted.

**Workflows**

* **Content management** for student/educator records.
* **Data analysis and business intelligence** to retain necessary analysis on courses, student progress, educator profiles, etc.&#x20;
* **Knowledge management** for archiving course content and any libraries associated with courses.

**Building Blocks**

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Scheduler**](https://govstack.gitbook.io/specification/building-blocks/scheduler)

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)

## **Contributors**

Rachel Lawson

Meelis Zujev

Ayush Shukla

Sarah Farooqi
