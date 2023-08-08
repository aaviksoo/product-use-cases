# INST-2 - Anticipatory Cash Transfers

## Product Use Case Summary

<table><thead><tr><th width="305.5">ID</th><th>INST-2</th></tr></thead><tbody><tr><td>Name</td><td>Anticipatory Cash Transfers </td></tr><tr><td>Sector</td><td>Institution</td></tr><tr><td>Version</td><td>1.0</td></tr><tr><td>Status</td><td>Draft</td></tr></tbody></table>

The primary agent aims to leverage digital technologies and data-driven approaches to implement anticipatory cash transfers, providing timely financial assistance to vulnerable populations in high-risk areas prone to natural disasters.

Anticipatory cash transfers (or forecast-based financing) are a social protection mechanism to protect people from climate and human-induced disasters. Anticipatory action in the form of a cash transfer provides support to people before a disaster has struck, as an investment in prevention and resiliency, rather than recovery. Early response is a more dignified way of supporting communities and is more cost-effective than rebuilding efforts, but they vary in scope and are highly time-sensitive and connected to forecasts. This use case considers leveraging digital to streamline ACTs in climate disaster scenarios..

## Stakeholders

* Aid dispensing agent in charge of the program. The agent can be government, NGOs, multilateral)
* Aid recipients or end beneficiaries of cash disbursement
* Government agencies required for data collection, coordination, and oversight. Specific ministries that need to be involved may vary from country to country and may include 1) civil defense, emergencies, and disaster relief, 2) earth sciences and observatory, 3) oceanic and atmospheric agencies, 4) ministry of finance in cases where governments are the agents, etc.
* Mobile network operators involved in the digital aspects of the use case
* Financial institutions for disbursement of funds.

## SDG Targets

* The specific SDG targets this use case contributes towards
* [1.3](https://exchange.dial.global/sdgs/no\_poverty): Implement nationally appropriate social protection systems and measures for all, including floors, and by 2030 achieve substantial coverage of the poor and the vulnerable
* [11.b:](https://exchange.dial.global/sdgs/sustainable\_cities\_and\_communiti) By 2020, substantially increase the number of cities and human settlements adopting and implementing integrated policies and plans towards inclusion, resource efficiency, mitigation and adaptation to climate change, resilience to disasters, and develop and implement, in line with the Sendai Framework for Disaster Risk Reduction 2015–2030, holistic disaster risk management at all levels
* [13.1](https://exchange.dial.global/sdgs/climate\_action): Strengthen resilience and adaptive capacity to climate-related hazards and natural disasters in all countries

## Building Blocks

* [GIS](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/Z9tuRxtxAgEaZ9v9oHvl)
* [Information Mediator](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/qgqbtL2D985Y6M8wG1ds)
* [Workflow](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/s/zdXe8NbIMZIv5sydPBf6/)
* [Payments](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/s/uJEXiAICNFsZ8S17X5KP/)
* [Consent](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/YDTiUt5Ch8a6EBI6Vc6H)
* [Identity](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/0usSj5SjaAsqoOEju90C)
* [Registration](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/34nLw76x9QyukJXQ4A27)
* [Scheduler](https://govstack.gitbook.io/specification/building-blocks/scheduler)
* [Messaging](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/izJ8qoBNDEfETK9xzjLp)

## Source Documents

* [FbF Practitioners Manual](https://manual.forecast-based-financing.org/en/)

## Steps

### 1 - Program Scoping and Design

The aid dispensing agent conducts scoping exercises in disaster-prone areas within a target region. As part of the scoping strategy, the agent should engage relevant stakeholders, including local communities, government agencies, financial service providers, and technology providers. In this step, the agent will also define the program's objectives, scope, and eligibility criteria. Importantly, the agent will determine the trigger mechanisms for initiating cash transfers based on early warning indicators and establish the frequency and duration of assistance. The trigger mechanisms need to be based on 1) available data and forecasts of emergency climate scenarios and 2) an agreed definition of impact level. The agent needs to coordinate with and leverage the government's existing early warning system.

&#x20;**Workflows**

* **Data collection and reporting** for primary data collection and assessment of the existing landscape and need and to to ensure that all involved stakeholders are appropriately mapped and included for program implementation
* **Work planning and coordination** to ensure roles and responsibilities are defined and that all stakeholders are involved in the process
* **Data analysis and business intelligence** to implement the trigger which responds to incoming data from government's early warning system.
* **Decision support** to automate the trigger mechanism based on the agreed-upon impact level.
* **Remote monitoring** by the government of weather patterns and other climate emergencies

**Building Blocks**

* [GIS](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/Z9tuRxtxAgEaZ9v9oHvl)
* [Information Mediator](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/qgqbtL2D985Y6M8wG1ds)
* [Workflow](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/s/zdXe8NbIMZIv5sydPBf6/)

### 2 - Outreach Communications

The aid dispensing agent organizes an information campaign to inform about the anticipatory cash transfer program aimed at the target beneficiary population that is eligible for emergency cash assistance. The campaign can leverage multiple channels such as mobile messaging, radio/television, and/or a village to village campaign is performed by district / local social welfare officers. Outreach communication is intensive during the kick-off phase of the new programme, but also requires ongoing touchpoints and additional information sharing, e.g. on grievance procedures, rights and responsibilities, behavioural change communication, etc.

&#x20;**Workflows**

* **Client communication** to facilitate program awareness for target audience and encouraging enrollment&#x20;
* **Client education** for educating potential target beneficiaries around the approach and objective(s), benefit(s), constraint(s), partner(s), etc. of the program
* **Content management** for the staff of the primary agent to generate relevant educational and promotional content&#x20;

**Building Blocks**

* [Scheduler](https://govstack.gitbook.io/specification/building-blocks/scheduler)
* [Messaging](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/izJ8qoBNDEfETK9xzjLp)

### 3 - Registration&#x20;

Registration is the process of collecting information on potential beneficiaries for assessment of their needs and conditions. Depending on specific country context, registration may occur by leveraging an existing social protection registration process or through on-demand registration, which would require the primary agent to collect registration data at local levels of implementation.  During this process, the beneficiary's demographic information is also collected, since the eligibility criteria may be very different based on the severity and extent of the anticipated emergency event. During registration, further data can be collected (depending on program design) e.g. bank account details, biometrics, etc.

**Workflows**

* **Data Collection and Reporting** for capturing interview responses or observation during registration process
* **Identification and Registration** for enrolled identified beneficiaries in the system and enabling possible permissions for interaction with the SRIS, and (with aid of geographic information services tool) to potentially locate and track households during the interview process
* **Client Case Management** for creating beneficiary user records

#### Building Blocks&#x20;

* [Consent](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/YDTiUt5Ch8a6EBI6Vc6H)
* [Identity](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/0usSj5SjaAsqoOEju90C)&#x20;
* [Information Mediator](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/qgqbtL2D985Y6M8wG1ds)
* [Registration](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/34nLw76x9QyukJXQ4A27)

### 4 - Data Verification and Validation

Data in the system should be checked and validated against other government databases (such as national IDs, tax, land, mobile, etc.) to fill in any missing gaps, verify and validate missing information, and authenticate records. This process should employ secure systems for identity verification to prevent fraud and duplication and the system should be ready-to-deploy in case of an emergency scenario

&#x20;**Workflows**

* **Client Case Management** for storing and using beneficiary records and eligibility information.
* **Data Analysis and Business Intelligence** for cross-referencing and verifying records across multiple registry sources, and reconciling gaps / overlaps

**Building Blocks**

* [Consent](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/YDTiUt5Ch8a6EBI6Vc6H)
* [Identity](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/0usSj5SjaAsqoOEju90C)
* [Information mediator](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/qgqbtL2D985Y6M8wG1ds)

### 5 - Program Trigger&#x20;

Based on national/regional early warning systems, the anticipatory cash program is triggered if the requirements have been met. The EWS leverages relevant data sources from the government such as technologies such as meteorological data, climate models, and risk indicators. The program will begin if the algorithms or models meet predetermined thresholds. Cash disbursements cannot begin until the threshold for severity, geographical extent, and risk of the climate event has been met.&#x20;

&#x20;**Workflows**

* **Data analysis and business intelligence** to implement the trigger which responds to incoming data from government's early warning system.
* **Decision support** to automate the trigger mechanism based on the agreed-upon impact level.
* **Remote monitoring** by the government of weather patterns and other climate emergencies

**Building Blocks**

* [GIS](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/Z9tuRxtxAgEaZ9v9oHvl)
* [Information Mediator](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/qgqbtL2D985Y6M8wG1ds)
* [Workflow ](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/gHnBHs9nQwhEP9Cf2In0)

### 6 - Real-time Eligibility Determination &#x20;

Once the program has been triggered after an emergency event, there will be a real-time eligibility process for beneficiaries to receive cash. Depending on regional/national context, this process could range from highly automated (using mobile technology) to highly manual (with on ground staff) to determine eligibility on a case-by-case basis. Eligibility criteria will be made clear (such as which geographic regions the rollout is specific to) so that non-eligible registrants understand the conditions under which eligibility has been determined.&#x20;

**Workflows**

* **Data Collection and Reporting** for capturing additional programmatic information on the beneficiaries during enrolment
* **Financial Services** for staging beneficiary account details for cash transfer processing
* **Identification and Registration** for identifying beneficiaries and confirming enrolment
* **Client Case Management** for storing program specific data for tracking

**Building Blocks**

* [Identity and Verification](https://govstack.gitbook.io/bb-identity/)
* [Information Mediator](https://govstack.gitbook.io/bb-information-mediation)
* [Registration](https://govstack.gitbook.io/bb-registration/)

### 7 - Payment

Depending on specific country contexts, payments can be highly automated (such as through mobile banking) or highly manual (i.e., local staff as cash distributors. In the case of an automated system, service providers (such as digital payment services or mobile network operators) should have been formally contracted in step 1 to facilitate cash disbursements. If the electronic payment system has been enabled, the payment can be processed for eligible beneficiaries. In the context where a digital financial service system is not employed, each beneficiary would be requested to travel to the nearest designated paypoint and collect money by program-specific authentication. In either case, the money is transferred to the selected payment provider as per generated payroll and is subsequently verified against the individual’s identification of program enrollment. Other possible add-on intervention activities at this step: behavior change communication; triggering of add-on benefits (or widening of beneficiary pool) if emergency worsens.&#x20;

&#x20;**Workflows**

* **Financial Services** for processing beneficiary payment directly to their account, or for generating payroll to deposit payment amounts for withdrawal by beneficiary from designated banking institution(s) / pay-point(s) thereafter
* **Client Case Management** for identifying and authenticating individual that is making a withdrawal, or to recall / verify deposit account information prior to payment transaction

**Building Blocks**

* [Payments](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/s/uJEXiAICNFsZ8S17X5KP/)

### 8 - Ongoing Case Management

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

### 9 - Ongoing M\&E and Program Update

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

* Ayush Shukla, ITU
* Sainabou Jallow, DIAL, sjallow@dial.global&#x20;
* Sarah Farooqi, DIAL, sfarooqi@dial.global&#x20;
