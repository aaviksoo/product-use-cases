# FINC-1 - Business E-Tax

## Product Use Case Summary

<table><thead><tr><th width="305.5">ID</th><th>FINC-1</th></tr></thead><tbody><tr><td>Name</td><td>Business E-Tax</td></tr><tr><td>Sector</td><td>Finance</td></tr><tr><td>Version</td><td>1.0</td></tr><tr><td>Status</td><td>Draft</td></tr></tbody></table>

This use case profiles the digital transformation of tax administration (e-taxataion) in the business sector. Tax administrations across the globe are examining the potential benefits of digitalization to broaden the tax base  and improve the quality of taxpayer services - tax reporting and collection. Digital tools are seen as potential means that can make tax systems more accessible, efficient and seamless for both taxpayers and tax administrations.&#x20;

Moreover, digitalizaing the tax collection process is now seen as a way to combat tax evasion and promote compliance - broaden the tax base and reduce the room for non-compliance. Thus, more countries are focused on moving away from a paper-based tax administration, to a digitized process driven by data that is automatically streamed from the taxpayer, captured, cleaned, filtered, matched, and warehoused for assessing risk, audit, dispute, and other processes. \*\*\*This process can also help tackle problems of businesses operating in the the hidden and informal economy.

## Stakeholders

* Ministry responsible for adminstering and enforcing all laws relating to tax revenue.
* Revenue Authority and/or taxation authorities/ agency in charge of the collection and receipt of all business related tax revenue in a country.&#x20;
* Business entities wishing to conduct/ already conducting business in the country - companies, branches of foreign companies and partnerships.

## SDG Targets

* [17.1](https://exchange.dial.global/sdgs/partnerships\_for\_the\_goals): Strengthen domestic resource mobilization, including through international support to developing countries, to improve domestic capacity for tax and other revenue collection.

## Building Blocks

* [Information Mediator](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/qgqbtL2D985Y6M8wG1ds)
* [Workflow](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/s/zdXe8NbIMZIv5sydPBf6/)
* [Payments](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/s/uJEXiAICNFsZ8S17X5KP/)
* [Consent](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/YDTiUt5Ch8a6EBI6Vc6H)
* [Identity](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/0usSj5SjaAsqoOEju90C)
* [Registration](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/34nLw76x9QyukJXQ4A27)
* [Scheduler](https://govstack.gitbook.io/specification/building-blocks/scheduler)
* [Messaging](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/izJ8qoBNDEfETK9xzjLp)

## Source Documents

*

## Steps

### 1 - Outreach Communications

Success of digitalizing the tax administration process requires a high level of commitment on the part of policymakers via a communication strategy that focuses on stakeholder management, and a fully articulated implementation plan (road map). In this step, the national body in charge of tax administration - trains and educates tax officials on the new and improved tax reporting system.&#x20;

For communication with target group - business entity taxpayers, the tax administration proactively contacts the target group via the country's formal business registry system informing them on the new digitized tax reporting process with clear guidelines and initial support on how to file taxes electronically. All information on the tax reporting platform being utilized - submission process, timeline, pre-filled standard form to declare revenue, expenses etc., should be easily accessible and disseminated on all relevant governement and private sector sites. An awareness raising campaign should be launched - communication on this new process can also be disseminated via email, SMS, and social media to reach an even larger range of taxpayers. \*\*\*Certain countries have a grace period of 1-3 years by which all businesses are required to transition to electronic invoicing (instead of cash based transactions) to streamline and automate tax filing and reporting process.

&#x20;**Workflows**

* **Client communication** to facilitate awareness of the digitized process for target audience and ensure enrollment in tax adminstration platform.
* **Client education** for educating target users/audience around the approach and objective(s), benefit(s), etc.
* **Content management** for the staff of the primary agent to generate relevant educational and promotional content&#x20;

**Building Blocks**

* [Scheduler](https://govstack.gitbook.io/specification/building-blocks/scheduler)
* [Messaging](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/izJ8qoBNDEfETK9xzjLp)

### 2 - Registration&#x20;

Taxpayer registry and identity, providing a secure gateway and foundation for a digital tax administration.



**Workflows**

* **Data Collection and Reporting** for capturing interview responses or observation during registration process
* **Identification and Registration** for enrolled identified beneficiaries in the system and enabling possible permissions for interaction with the SRIS, and (with aid of geographic information services tool) to potentially locate and track households during the interview process
* **Client Case Management** for creating beneficiary user records

#### Building Blocks&#x20;

* [Consent](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/YDTiUt5Ch8a6EBI6Vc6H)
* [Identity](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/0usSj5SjaAsqoOEju90C)&#x20;
* [Information Mediator](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/qgqbtL2D985Y6M8wG1ds)
* [Registration](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/34nLw76x9QyukJXQ4A27)

### 3 - E-file

Use of standardized electronic form for filing tax returns required or optional; other income data (e.g., payroll and financial) filed electronically and matched annually.

&#x20;**Workflows**

* **Client Case Management**&#x20;
* **Data Analysis and Business Intelligence**&#x20;

**Building Blocks**

* [Consent](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/YDTiUt5Ch8a6EBI6Vc6H)
* [Identity](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/0usSj5SjaAsqoOEju90C)
* [Information mediator](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/qgqbtL2D985Y6M8wG1ds)

### 4 - E-accounting&#x20;

Submit accounting or other source data to support filings (e.g., invoices and trial balances) in a defined electronic format to a defined timetable; frequent additions and changes at this level.

&#x20;**Workflows**

* **Data analysis and business intelligence** to implement the trigger which responds to incoming data from government's early warning system.
* **Decision support** to automate the trigger mechanism based on the agreed-upon impact level.
* **Remote monitoring** by the government of weather patterns and other climate emergencies

**Building Blocks**

* [GIS](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/Z9tuRxtxAgEaZ9v9oHvl)
* [Information Mediator](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/qgqbtL2D985Y6M8wG1ds)
* [Workflow ](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/gHnBHs9nQwhEP9Cf2In0)

### 5 - E-match &#x20;

Submit additional accounting and source data; government accesses additional data (bank statements) and begins to match data across tax types, and potentially across taxpayers and jurisdictions, in real time.

**Workflows**

* **Data Collection and Reporting** for capturing additional programmatic information on the beneficiaries during enrolment
* **Financial Services** for staging beneficiary account details for cash transfer processing
* **Identification and Registration** for identifying beneficiaries and confirming enrolment
* **Client Case Management** for storing program specific data for tracking

**Building Blocks**

* [Identity and Verification](https://govstack.gitbook.io/bb-identity/)
* [Information Mediator](https://govstack.gitbook.io/bb-information-mediation)
* [Registration](https://govstack.gitbook.io/bb-registration/)

### 6 - Payment

Depending on specific country contexts, payments can be highly automated (such as through mobile banking) or highly manual (i.e., local staff as cash distributors. In the case of an automated system, service providers (such as digital payment services or mobile network operators) should have been formally contracted in step 1 to facilitate cash disbursements.&#x20;

&#x20;**Workflows**

* **Financial Services** for processing beneficiary payment directly to their account, or for generating payroll to deposit payment amounts for withdrawal by beneficiary from designated banking institution(s) / pay-point(s) thereafter
* **Client Case Management** for identifying and authenticating individual that is making a withdrawal, or to recall / verify deposit account information prior to payment transaction

**Building Blocks**

* [Payments](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/s/uJEXiAICNFsZ8S17X5KP/)

### 7 - E-audit

Level-2 data analyzed by government entities and cross-checked to filings in real time to map the geographic economic ecosystem; taxpayers receiving electronic audit assessments with limited time to respond.

&#x20;**Workflows**

* **Financial Services** for processing beneficiary payment directly to their account, or for generating payroll to deposit payment amounts for withdrawal by beneficiary from designated banking institution(s) / pay-point(s) thereafter
* **Client Case Management** for identifying and authenticating individual that is making a withdrawal, or to recall / verify deposit account information prior to payment transaction

**Building Blocks**

* [Payments](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/s/uJEXiAICNFsZ8S17X5KP/)

### 8 - E-assess

Government entities using submitted data to assess tax without the need for tax forms; taxpayers allowed a limited time to audit government- calculated tax.

**Workflows**

* **Financial Services** for processing beneficiary payment directly to their account, or for generating payroll to deposit payment amounts for withdrawal by beneficiary from designated banking institution(s) / pay-point(s) thereafter
* **Client Case Management** for identifying and authenticating individual that is making a withdrawal, or to recall / verify deposit account information prior to payment transaction

**Building Blocks**

* [Payments](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/s/uJEXiAICNFsZ8S17X5KP/)

### 9 - Ongoing Case Management

During non-emergency times, this step involves ongoing interaction with beneficiaries to ensure information on beneficiaries stays up to date. During emergency times, there may be an added responsibility to address complaints, grievances, and appeals. &#x20;

**Workflows**

* **Data Collection and Reporting** for capturing changes in beneficiary information
* **Client Case Management** for identifying and recording beneficiary interaction with local officers and capturing reported cases on grievances / appeals etc., and for determining risks / conditionality by reviewing individual beneficiary client case
* **Work Planning and Coordination** to potentially suggest and connect with departments / agencies offering other social benefits and services to eligible beneficiaries

**Building Blocks**

* [Consent](https://govstack.gitbook.io/bb-consent/)
* [Identity ](https://govstack.gitbook.io/bb-identity/)
* [Scheduler](https://govstack.gitbook.io/specification/building-blocks/scheduler)
* [Workflow](https://govstack.gitbook.io/specification/building-blocks/workflow)

### 10 - Ongoing M\&E&#x20;

The primary agent should conduct M\&E exercises to make management choices such as where to conduct training, registration campaigns, where to prioritize budget, etc.  Monitoring and evaluation for anticipatory cash requires involvement of stakeholders for different parts of the project. Periodic evaluation should consider whether the thresholds, data inputs, and triggers are appropriate or need to be re-evaluated. In addition, assessments should consider impact of the of the program rollout on the intended beneficiaries.

**Workflows**

* **Client Case Management** for ongoing monitoring and tracking of client performance, and integration to other registries for holistic view and reporting
* **Identification and Registration** (with aid of geographic information services tool for potential use) in tracking / locating areas in relation to level of activities and adherence, or client household location
* **Data Analysis and Business Intelligence** / **Decision Support** / **Data Collection and Reporting** to analyze, update, and report program output / performance information

**Building Blocks**

* [Consent](https://govstack.gitbook.io/bb-consent/)
* [Identity ](https://govstack.gitbook.io/bb-identity/)
* [Scheduler](https://govstack.gitbook.io/specification/building-blocks/scheduler)
* [Workflow](https://govstack.gitbook.io/specification/building-blocks/workflow)

## Contributors

*
