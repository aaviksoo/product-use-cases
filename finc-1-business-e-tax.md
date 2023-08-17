# FINC-1 - Business E-Tax

## Product Use Case Summary

<table><thead><tr><th width="305.5">ID</th><th>FINC-1</th></tr></thead><tbody><tr><td>Name</td><td>Business E-Tax</td></tr><tr><td>Sector</td><td>Finance</td></tr><tr><td>Version</td><td>1.0</td></tr><tr><td>Status</td><td>Draft</td></tr></tbody></table>

This use case profiles the digital transformation of tax administration (e-taxataion) in the business sector. Tax administrations across the globe are examining the potential benefits of digitalization to broaden the tax base  and improve the quality of taxpayer services - tax reporting and collection. Digital tools are seen as potential means that can make tax systems more accessible, efficient and seamless for both taxpayers and tax administration.&#x20;

Moreover, digitalizaing the tax collection process is now seen as a way to combat tax evasion and promote compliance - broaden the tax base and reduce the room for non-compliance. Thus, more countries are focused on moving away from a paper-based tax administration to primarily computer-based interaction between taxpayer and administration. A digitized process driven by data that is automatically streamed from the taxpayer, captured, cleaned, filtered, matched, and warehoused for assessing risk, audit, dispute, and other processes. \*\*\*This process can also help tackle problems of businesses operating in the the hidden and informal economy.

## Stakeholders

* Ministry responsible for adminstering and enforcing all laws relating to tax revenue.
* Chamber of Commerce facilitating all business registration and/or certification in a country.
* Revenue Authority and/or taxation authorities/ agency in charge of the collection and receipt of all business related tax revenue in a country.&#x20;
* Taxpayers and potential tax payers - running business entities in the country - companies, branches of foreign companies and partnerships.
* Tax agents reviewing submitted tax related files.

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

Success of digitalizing the tax administration process requires a high level of commitment on the part of policymakers via a communication strategy that focuses on stakeholder management, and a fully articulated implementation plan (road map). In this step, the national body in charge of tax administration collaborates closely with the national Chamber of Commerce and trains/educates tax officials and chamber of commerce staff about the new and improved business tax reporting system.&#x20;

For communication with the target business entity taxpayers - the tax administration implements a  robust awareness raising campaign via telephone, email (i.e., Chambers of Commerce registered business entities contact database), SMS, newspapers, and social media, informing this group about the new and madatory digitized tax reporting process with clear guidelines and initial support on how to file taxes electronically using the platform in place. All information on the tax reporting platform should already be easily accessible and disseminated on all governement run websites including in the Chambers of Commerce website, - timeframe to register, tax submission steps and requirements, deadlines, pre-filled standard form to declare revenue, expenses etc., . \*\*\*Certain countries have a grace period of 1-3 years by which all businesses are required to transition to electronic invoicing (instead of cash based transactions) to streamline and automate tax filing and reporting process.

&#x20;**Workflows**

* **Client communication** to facilitate awareness of the tax platform for target audience and mandatory registration and enrollment process.&#x20;
* **Client education** for educating target users/audience on the objective(s), benefit(s), process, guideline etc.
* **Content management** for the staff  to generate relevant educational and promotional content&#x20;

**Building Blocks**

* [Scheduler](https://govstack.gitbook.io/specification/building-blocks/scheduler)
* [Messaging](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/izJ8qoBNDEfETK9xzjLp)

### 2 - Registration&#x20;

Registration is the process of collecting information of all eligible tax paying busineses that have formally registered their business entity in a country. Registration on the tax administration platform can take place via computer, mobile device etc. Information required could include business name, address, legal structure, identification details of the company representative, bank account details, business identification number or certificate received from the Chamber of Commerce etc. Personalized log in credentials can then be provided for each entity to be able to login to tax administration platform. Depending on specific country context/processes, registration credentials used to log into the platform may be the same credentials provided when the business entity first registered their business via the Chamber of Commerce.

**Workflows**

* **Data Collection and Reporting** for capturing data of business entities.&#x20;
* **Identification and Registration** for each registered business to have personalized login details to the tax administration platform to submit all required forms and tax related documents.&#x20;
* **Client Case Management** for creating business entity user records.

#### Building Blocks&#x20;

* [Consent](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/YDTiUt5Ch8a6EBI6Vc6H)
* [Identity](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/0usSj5SjaAsqoOEju90C)&#x20;
* [Information Mediator](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/qgqbtL2D985Y6M8wG1ds)
* [Registration](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/34nLw76x9QyukJXQ4A27)

### 3 - Data Verification and Validation

Data verification and validation should be coordinated with all relevant governement authorities and regulatory bodies. For the e-tax system, in certain countries, the registration data that is submitted for tax purposes, is checked against other government databases (eg. chamber of commerce business registry, etc.) in order to fill in any missing gaps, verify and validate collected information, including authentication of all records. \*Data checking approaches also vary: sometimes batch-sharing via _CD, sometimes full interoperability._

**Workflows**

* **Client Case Management** for storing and reviewing identification, registration, and business registration records.
* **Data Analysis and Business Intelligence** for cross-referencing and verifying records across multiple registry sources, and reconciling gaps / overlaps.

#### Building Blocks&#x20;

* [Consent](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/YDTiUt5Ch8a6EBI6Vc6H)
* [Identity](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/0usSj5SjaAsqoOEju90C)&#x20;
* [Information Mediator](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/qgqbtL2D985Y6M8wG1ds)
* [Registration](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/34nLw76x9QyukJXQ4A27)

### &#x20;4 - E-file/Tax Submission

Use of standardized electronic form for filing tax returns required or optional; other income data (e.g., payroll and financial) filed electronically and matched annually. Submit accounting or other source data to support filings (e.g., invoices and trial balances) in a defined electronic format to a defined timetable; frequent additions and changes at this level.

&#x20;**Workflows**

* **Client Case Management**&#x20;
* **Data Analysis and Business Intelligence**&#x20;

**Building Blocks**

* [Consent](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/YDTiUt5Ch8a6EBI6Vc6H)
* [Identity](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/0usSj5SjaAsqoOEju90C)
* [Information mediator](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/qgqbtL2D985Y6M8wG1ds)
* [Workflow ](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/gHnBHs9nQwhEP9Cf2In0)

### 5 - Payment

Allowing taxpayers to switch from tax payment by cash to mobile banking, partially leapfrogging the traditional banking system stage_._ Depending on specific country contexts, payments is automated (such as through mobile banking).

&#x20;**Workflows**

* **Financial Services** for processing tax payments from designated banking institution(s)
* **Client Case Management** for identifying and authenticating business entities making the  payment transaction and ensuring it matches taxes owed to be paid.

**Building Blocks**

* [Payments](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/s/uJEXiAICNFsZ8S17X5KP/)

### 6 - E-match/checking process &#x20;

Submit additional accounting and source data; government accesses additional data (bank statements) and begins to match data across tax types, and potentially across taxpayers and jurisdictions, in real time. Level-2 data analyzed by government entities and cross-checked to filings in real time to map the geographic economic ecosystem; taxpayers receiving electronic audit assessments with limited time to respond.

**Workflows**

* **Data Collection and Reporting**&#x20;
* **Financial Services**&#x20;
* **Identification and Registration**
* **Client Case Management**&#x20;

**Building Blocks**

* [Identity and Verification](https://govstack.gitbook.io/bb-identity/)
* [Information Mediator](https://govstack.gitbook.io/bb-information-mediation)
* [Registration](https://govstack.gitbook.io/bb-registration/)

### 7 - Ongoing Case Management

This step involves ensuring information of businesses are kept up to date - specifically relating to tax payments. Also ensuring that there is a process in place to address any complaints, grievances and appeals raised. This process should be led by the government authority's compliance officers/team.

**Workflows**

* **Data Collection and Reporting** for capturing changes in business entity information
* **Client Case Management** for identifying and recording business entity interaction with local officers and capturing reported cases on grievances / appeals etc., and for determining risks / conditionality by reviewing individual client case
* **Work Planning and Coordination** to potentially suggest and connect with Chambers of Commerce

**Building Blocks**

* [Consent](https://govstack.gitbook.io/bb-consent/)
* [Identity ](https://govstack.gitbook.io/bb-identity/)
* [Messaging](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/izJ8qoBNDEfETK9xzjLp)
* [Scheduler](https://govstack.gitbook.io/specification/building-blocks/scheduler)
* [Workflow](https://govstack.gitbook.io/specification/building-blocks/workflow)

### 8 - Ongoing M\&E&#x20;

The primary agent should conduct M\&E exercises to acquire feedback from all relevant stakeholders on ways to improve the platform and ensure tax submission - calculation, payments etc. are as streamlined, effective and efficient as possible. This should incorporate periodic evaluation and impact assesment.&#x20;

**Workflows**

* **Client Case Management** for ongoing monitoring and tracking of performance, and integration to other registries for holistic view and reporting
* **Data Analysis and Business Intelligence** / **Decision Support** / **Data Collection and Reporting** to analyze, update, and report program output / performance information

**Building Blocks**

* [Consent](https://govstack.gitbook.io/bb-consent/)
* [Identity ](https://govstack.gitbook.io/bb-identity/)
* [Scheduler](https://govstack.gitbook.io/specification/building-blocks/scheduler)
* [Workflow](https://govstack.gitbook.io/specification/building-blocks/workflow)

## Contributors

*
