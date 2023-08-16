# HLTC-4 - Pandemic Response

## Product Use Case Summary

| ID      | HLTC-4            |
| ------- | ----------------- |
| Name    | Pandemic Response |
| Sector  | Health            |
| Version | 1.0               |
| Status  | Draft             |

This use case profiles digitalizing pandemic response operations and management systems in a country to ensure effective control of the pandemic. Accurate and real-time data is central to any pandemic response. Having a digitized pandemic response system could entail utilizing robust data science, interactive dashboards, and analytics tools to better understand pandemic impact across the country - where cases are concentrated, coordinate and track treatments and implement preventative measures in communities. This can support emergency operation centers and other coordination response efforts to make quick and informed decisions during disease outbreaks or pandemics.&#x20;

Digitalizing pandemic response can facilitate rapid information sharing of accurate data (number of cases, deaths, geolocation, testing and vaccinations, among others) to assist with outbreak response and public health decision making. Governments are increasingly digitizing this process to inform their pandemic response action effectively and efficiently. This promotes a streamlined process for the coordination of disease control measures such as testing, vaccination and lockdown, as well as for the support to frontline health workers and public health responders in their pandemic response efforts.&#x20;

## Stakeholders

* Ministry or national government body in charge of disease surveillance and epidemic/pandemic response.
* Health professionals - general practitioners, public health responders, frontline health workers, health system managers, emergency operation officers, surveillance officers etc,.
* Population at exposed to epidemics and pandemics.

## SDG Targets

* [3.b](https://exchange.dial.global/sdgs/good\_health\_and\_wellbeing): Support the research and development of vaccines and medicines for the communicable and non‑communicable diseases that primarily affect developing countries, provide access to affordable essential medicines and vaccines, in accordance with the Doha Declaration on the TRIPS Agreement and Public Health, which affirms the right of developing countries to use to the full the provisions in the Agreement on Trade-Related Aspects of Intellectual Property Rights regarding flexibilities to protect public health, and, in particular, provide access to medicines for all.
* [3.d](https://exchange.dial.global/sdgs/good\_health\_and\_wellbeing): Strengthen the capacity of all countries, in particular developing countries, for early warning, risk reduction and management of national and global health risks.

## Building Blocks

* [**Consent**](https://govstack.gitbook.io/bb-consent/)
* [**Digital Registry**](https://govstack.gitbook.io/specification/v/version-0.9.0/building-blocks/digital-registries)&#x20;
* [**GIS**](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/Z9tuRxtxAgEaZ9v9oHvl)
* [**E-Signature**](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/EiApewuu4GrhgGCBTps0)
* [**Identification and Verification**](https://govstack.gitbook.io/bb-identity/)
* [**Information Mediator** ](https://govstack.gitbook.io/bb-information-mediation)
* [**Messaging**](https://govstack.gitbook.io/bb-messaging/)
* [**Payments**](https://govstack.gitbook.io/bb-payments)
* [**Registration**](https://govstack.gitbook.io/bb-registration)
* [**Scheduler**](https://govstack.gitbook.io/specification/building-blocks/scheduler)
* [**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)

## Source Documents

* [Digital Impact Exchange ](https://exchange.dial.global/use\_cases/pandemic\_response)
* [Digital Applications and Tools Across an Epidemiological Curve (DATEC)](https://static1.squarespace.com/static/59bc3457ccc5c5890fe7cacd/t/603d549f3e5f2c2800651483/1614632096462/DATEC-FINAL.pdf)&#x20;

## Steps

### 1 - Coordination and Operation

The government body in charge of Public Health and emergency operation response efforts, should agree on streamlined decision making and coordination processes pertaining to pandemic preparedness and response. Governments should assess and evaluate gaps in the health system, ensure they have up to date map of regions and districts - for mapping locations of clusters in a country to guide emergency response efforts, and decide where to prioritize monitoring and other systems that are essential during a disease outbreak. As a next step, they can identify the most strategic opportunities to adapt digital tools at different phases of a pandemic to monitor, detect and manage spread of disease as well as screen and track suspected infected persons.&#x20;

Once a disease outbreak has been declared in a country, i.e., the emergency operation centers can then rapidly leverage the digital tools to acquire real time data on situation on the ground, put in place adequate disease control measures and share accurate information/messaging with the population.

**Workflows**&#x20;

* **Data Collection and Reporting** for collecting data on epidemics and pandemics, and to report this data to all relevant stakeholders.&#x20;
* **Data Analysis and Business Intelligence** for analyzing data to make informed decisions on how to respond to pandemic and aid population. Data from screening tools can also be assessed and used to inform national decisions that may restrict travel from certain countries or regions.

**Building Blocks**

[**GIS**](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/Z9tuRxtxAgEaZ9v9oHvl)

### 2 - Outreach Communications

Staff from the Ministry of Health and/or public health agencies responsible for surveillance and epidemic/pandemic management organizes outreach communications and trainings for frontline healthcare workers and emergency operations response teams - about a new digitized and streamlined process of responding to epidemics and pandemics. The staff are then trained on digital tools and standards to gather/input real-time data during pandemic responses.&#x20;

Communication outreach should be facilitated often to improve public awareness of facts and best practices for disease prevention and encourage treatment-seeking behaviors. Subsequently, once a disease outbreak occurs, staff from the Ministry of Public Health and the frontline healthcare workers can launch an information campaign to: inform population about the outbreak, counter/address misinformation, advise on disease control measures to control the outbreak, explain what to do in case symptoms appear, and locations of testing and treatment facilities. The campaign is conveyed using all available communication outlets - via television/radio, official government websites, mobile messaging and in person at local healthcare facilities and hospitals.&#x20;

**Workflows**

* **Client communication** to facilitate real-time and accurate information on epidemic/pandemic, preventative measures, self-reporting mechanisms and treatments. SMS and other digital tools can be used to share information with the community about a potential outbreak of a new disease or renewed outbreak of a disease already well known to a community.
* **Client education** for educating population about the epidemic/pandemic, safety measures and available support.
* **Identification and Registration** (along with GIS) in mapping and locating households and individuals in affected region/area.

**Building Blocks**

[**GIS**](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/Z9tuRxtxAgEaZ9v9oHvl)

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Scheduling**](https://govstack.gitbook.io/bb-scheduler/)

### 3 - Registration

In this use case, registration is the process of collecting and documenting data of infected and exposed persons during a disease outbreak. Citizens can be provided with means to electronically self-report exposure to the disease. Data can then be collected to facilitate testing, track/map exposure location, designate treatment and to easily be able to follow-up and track infected/exposed persons in the health system. Exposed and infected pesons' can register by contacting their local emergency operation center or via representative frontline health workers that can register affected individuals and schedule testing. \*\*\* These individuals can also opt to receive automated contact notification and follow-ups.

**Workflows**

* **Data Collecting and Reporting** for capturing infected persons health related data, collect information on others they could have passed the disease to, monitor all testing and clinical interactions across facilities.&#x20;
* **Identification and Verification** for enrolled person and enabling permissions.
* **Client Case Management** for creating user records - managing clients who are suspected and/or infected. Also, to appropriately document health visits, follow-up needs, and treatment protocols.

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**E-Signature**](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/EiApewuu4GrhgGCBTps0)

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator** ](https://govstack.gitbook.io/bb-information-mediation)

[**Registration**](https://govstack.gitbook.io/bb-registration/)

### 4 - Data Verification and Validation

In this step, registration data needs to be verified and validated. The person's data can be verified with local digital identification or census database. \*\*Permission should be granted from each person to anonymously use this data for sharing and comparing data between the states and territories, to track real-time data - infection rates and facilitate treatment/vaccine rollouts. And to help national government body in making informed decisions to improve pandemic operations on an on-going basis.

**Workflows**

* **Client case management** - used for verifying and validating patient data.
* **Data analysis and Business Intelligence / Data Collection and Reporting** - for administrators and front line healthcare workers to monitor and track infections and exposures.

**Building Blocks**

[**Consent**](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/YDTiUt5Ch8a6EBI6Vc6H)

[**Identity**](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/0usSj5SjaAsqoOEju90C)

[**Information Mediator**](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/qgqbtL2D985Y6M8wG1ds)

### 5 - Supply Chain

In a pandemic situation, an effective supply chain and logistics management system can support allocation of resources to aid in response - ensure that testing kits, therapeutics, and other treatment commodities, as well as essential supplies like gloves, cleaning agents, etc., are ordered, tracked, and delivered on time at health facilities. I.e., governments can use forecasting tools and built-in data visualizations and analytics at the point of an outbreak, and report any delays in supply through supply chain systems. This can also help ensure accuracy of ordering and timeliness of shipments, and should there be a delay, provide visibility into data insights around the supply chain. Robust analytics, artificial intelligence (AI)/machine learning (ML), and other data science tools can support countries to ensure their supply chains are working effectively.

**Workflows**

* **Identification** to easily be able to track pandemic aid supplies and testing.
* **Client Case Management** to provide support and track supplies are being utilized effectively to aid infected/exposed persons.
* **Supply Chain Management**: for capturing, managing and evaluating supplies during a pandemic.

**Building Blocks**

[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)

[**Identity and Verification**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator** ](https://govstack.gitbook.io/bb-information-mediation)

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Scheduler**](https://govstack.gitbook.io/specification/building-blocks/scheduler)

[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)

### 6 - Ongoing Case Management

Depending on the type of pandemic there will be a need to track infected individuals to manage and reduce spread of disease. Ongoing case management entails coordination of patient data throughout a country, allowing health providers to appropriately document health visits, follow-up needs, and treatment protocols.&#x20;

It is also essential to deploy some type of contact tracing tools to track the cases and anyone who has been exposed to the disease by that case. Digital contact tracing tools deployed at this stage can enable authorities to track and slow the spread of the disease by imposing isolation measures on infected and exposed persons and to understand geographically where clusters of cases are located. Contact tracing tools can also send alerts to exposed persons.&#x20;

**Workflows**

* **Data Collection and Reporting** for capturing data on cases and contacts, testing outcomes and treatments received.&#x20;
* **Client Case Management** - for identifying and recording cases with health care providers/worker and capturing reported cases on grievances.

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Messaging**](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/izJ8qoBNDEfETK9xzjLp)

[**Workflow**](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/gHnBHs9nQwhEP9Cf2In0)

### 7 - Ongoing Monitoring and Evaluation

Administrators at the Ministry of Health and/or public health agency in charge of surveillance and epidemic/pandemic management conduct ongoing M\&E to incorporate feedback on better ways to develop e-learning solutions in pandemic responses, and more effective ways to help the population. In addition, they can use data analytics to identify better techniques that can help preempt outbreaks through real time surveillance to identify early onset of cases, and more effective ways to deploy preventive measures early.

**Workflows**

* **Client Case Management** - for ongoing monitoring and tracking of frontline healthcare workers feedback as well as population feedback.&#x20;
* **Data Analysis and Business Intelligence/ Decision Support / Data Collection and Reporting** - to analyze, update, and report  output/ information

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**GIS**](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/c/Z9tuRxtxAgEaZ9v9oHvl)

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Scheduler**](https://govstack.gitbook.io/specification/building-blocks/scheduler)

[**Workflow**](https://govstack.gitbook.io/specification/building-blocks/workflow)

## Contributors

Wes Brown, Digital Impact Alliance

Sarah Farooqi, Digital Impact Alliance&#x20;

Pilar Hernandez, SORMAS (Surveillance Outbreak Response Management & Analysis System) Foundation

Sainabou Jallow, Digital Impact Alliance

Julia Niklewski, GIZ





