# B2G-UC1-MoJDataReporting-04-Add-Framework-Gov-Admin

<table data-header-hidden><thead><tr><th width="172"></th><th></th></tr></thead><tbody><tr><td>Use Case Step</td><td>Use Case: Ministry of Justice - HMPPS Data &#x26; Reporting platform, Step: Add Framework (Public Sector procurement owner)</td></tr><tr><td><p>Preconditions</p><p>(list of conditions that MUST be met in order to be able to successfully execute this process)</p></td><td><p>·         The government owner must be employed by, or represent, a public sector organisation responsible for procurement.</p><p>·         The government owner has a work email address to create an account </p><p>·         The government owner has successfully logged into their government SSO (Registration BB) and has the necessary authorization to carry out administrative activities.</p><p>·         Multiple authorised government owners can work on this concurrently.</p><p>·         Data sharing agreement between Registration BB and respective registries where information is queried from has been signed (contract) and respective REST API services in Information Mediator has been opened to Registration BB.</p></td></tr><tr><td>Data inputs</td><td><p>1.      </p><p><br></p></td></tr><tr><td><p>Actors</p><p>(the people, organizations, computer systems - hardware and software, and building blocks that participate in the activity)</p></td><td><p>Human: Government owner, Sellers</p><p>System:</p><p>·         Digital Registries BB</p><p>·         Identity BB</p><p>·         Consent BB</p><p>·         Messaging BB</p><p>·         Information Mediator BB</p></td></tr><tr><td>Normal Course (what happens if the event is triggered and the preconditions have been met)</td><td><p>Add a new framework: The framework is set up and opened. Suppliers can then apply to be on the framework. </p><p>Step 1: The government owner creates a new framework ‘Create framework’</p><p>Step 2: The government owner adds framework information:</p><ol><li>Framework name</li><li>Common Procurement Vocabulary (CPV) code  (e.g. 72000000 - IT services: consulting, software development, Internet and support)</li><li>Reference number</li><li>Type of contract (e.g. services)</li><li>Divided into Lots (yes / no)</li><li>Total value of procurement</li><li>Description</li><li>Date applications open</li><li>Date applications close</li><li>Go live date</li><li>Clarification questions (yes / no)</li><li>Contact details of contracting authority </li><li>Type of contracting authority (e.g. ministry or any other national or federal authority)</li><li>Main activity (e.g. general public services)</li><li>Type of procedure (e.g. open)</li></ol><p>Step 3: The government owner uploads documentation (e.g. framework contract, call-off contract, terms and conditions):</p><ol><li>Government owner selects all files for upload</li><li>Files uploaded</li><li>Government owner edits the document titles for user-friendly display</li><li>Confirm changes</li></ol><p>Step 4:   The government owner selects the framework type (buyer posts an opportunity vs supplier catalogue of services)</p><ol><li>Government owner selects Buyer Opportunities framework type</li><li>Government owner edits the Supplier Declaration Form</li><li>Government owner selects how many Lots are on the framework</li><li>Government owner creates the first Lot</li><li><p></p><ol><li>Lot name (e.g. Specialists)</li><li>Description </li><li>Place of performance (e.g. UK)</li><li>Award criteria (e.g. Name: Quality / Weighting: 100 Price - Weighting: 0)</li><li>Description of service listing (e.g. “Digital specialists suppliers must provide at least one of the following roles”)</li><li>Add list of services e.g. </li><li><p></p><ol><li>— agile coach,</li><li>— business analyst,</li><li>— communications manager,</li><li>— content designer,</li><li>— cyber security consultant,</li><li>— delivery manager or project manager,</li><li>— designer,</li><li>— developer,</li><li>— performance analyst,</li><li>— portfolio manager,</li><li>— product manager,</li><li>— programme delivery manager,</li><li>— quality assurance analyst,</li><li>— service manager,</li><li>— technical architect,</li><li>— user researcher— visual designer,</li><li>— web operations engineer,</li><li>— data engineer,</li><li>— data scientist,</li><li>— data architect</li></ol></li><li>Add additional information sections, for example:</li><li><p></p><ol><li>Information about options (yes / no)</li><li>Information about European Union Funds (e.g. The procurement is related to a project and/or programme financed by European Union funds: Yes / No)</li><li>Duration: e.g. Initial 12 months with an optional 12 month extension</li></ol></li></ol></li><li>Government owner creates new Lot</li><li><p></p><ol><li>Lot name (e.g. Outcomes)</li><li>Description </li><li>Place of performance (e.g. UK)</li><li>Award criteria (e.g. Name: Quality / Weighting: 100 Price - Weighting: 0)</li><li>Description of service listing (e.g. “Digital outcomes suppliers will provide at least one of the following”)</li><li>Add list of services e.g. </li><li><p></p><ol><li>performance analysis and data</li><li>security</li><li>service delivery</li><li>software development</li><li>support and operations</li><li>testing and auditing</li><li>user experience and design</li><li>user research</li></ol></li><li>Add additional information sections, for example:</li><li><p></p><ol><li>Information about options (yes / no)</li><li>Information about European Union Funds (e.g. The procurement is related to a project and/or programme financed by European Union funds: Yes / No)</li><li>Duration: e.g. Initial 12 months with an optional 12 month extension</li></ol></li></ol></li><li>Government owner sets up the Buyer Opportunity listing for the Lot. e.g. for Outcomes, refer to <a href="https://docs.google.com/document/d/1WxpnBnT7pMBlb5P37VV7UaKkBg0EhX4LsGK7IKdg-nQ/edit">Steps 1-3 in MP-03</a>.</li><li>Government owner creates a new lot until the total set in framework details is reached.</li><li>Government owner reviews draft (auto-saved).</li><li>Government owner produces <a href="https://www.gov.uk/guidance/g-cloud-suppliers-guide">supplier </a>and <a href="https://www.gov.uk/guidance/g-cloud-buyers-guide">buyer </a>guidance.</li><li>Government owner publishes the framework.</li><li>Framework opens to supplier submissions on the date and time set in step 2.8.</li></ol></td></tr><tr><td><p>Alternative Course</p><p>(links to other use cases in case there are different ways how to solve the same use case)</p></td><td><p>Step 2a) The government owner changes the date of opening or closing the application period. <br></p><p>Step 4a) The government owner selects a supplier catalogue framework type</p><ol><li>Government owner selects Supplier catalogue framework type</li><li>Government owner edits the Supplier Declaration Form</li><li>Government owner selects how many Lots are on the framework</li><li>Government owner creates the first Lot</li><li><p></p><ol><li>Lot name (e.g. Cloud hosting)</li><li>Description </li><li>Place of performance (e.g. UK)</li><li>Award criteria (e.g. Direct award only. No further competition is permissible.)</li><li>Description of service listing (e.g. “Cloud hosting services sold here are cloud platform or infrastructure Services that can help buyers do at least one of the following:<br>Deploy, manage and run software, provision and use processing, storage or networking resources.<br>Buyers only need to pay for what they use. The cloud hosting lot is equivalent to the National Institute of Standards and Technology (NIST) definitions of ‘Platform as a Service’ and ‘Infrastructure as a Service’:<a href="http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf"> http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf<br></a>Cloud hosting suppliers will provide services in at least one of these categories”</li><li>Add list of services e.g. </li><li><p></p><ol><li>Archiving, backup and disaster recovery</li><li>Compute and application hosting</li><li>Container service</li><li>Content delivery network</li><li>Cyber security</li><li>Database</li><li>Data warehousing</li><li>NoSQL database</li><li>Relational database</li><li>Load balancing</li><li>Logging and analysis</li><li>Message queuing and processing</li><li>Networking (including Network as a Service)</li><li>Platform as a Service (PaaS)</li><li>Infrastructure and platform security</li><li>Distributed denial of service attack (DDOS) protection</li><li>Firewall</li><li>Service intrusion detection</li><li>Protective monitoring</li><li>Search</li><li>Storage</li><li>Block storage</li><li>Object storage.</li></ol></li><li>Add additional information sections, for example:</li><li><p></p><ol><li>Information about options (yes / no)</li><li>Information about European Union Funds (e.g. The procurement is related to a project and/or programme financed by European Union funds: Yes / No)</li><li>Duration: e.g. Initial 12 months with an optional 12 month extension</li></ol></li></ol></li><li>Government owner creates new Lot</li><li><p></p><ol><li>Lot name (e.g. Cloud Software)</li><li>Description </li><li>Place of performance (e.g. UK)</li><li>Award criteria (e.g. Direct award only)</li><li>Description of service listing (e.g. “Cloud Software Services sold here are applications that are accessed over the internet and hosted in the cloud. Buyers only need to pay for what they use.<br>The cloud software lot is equivalent to the National Institute of Standards and Technology (NIST) definition of Software as a Service: <a href="http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf">http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf</a><br>Cloud software suppliers will provide cloud software services in at least one of these categories”)</li><li>Add list of services e.g. </li><li><p></p><ol><li>Accounting and finance</li><li>Analytics and business intelligence</li><li>Application security</li><li>Collaborative working</li><li>Creative, design and publishing</li><li>Customer relationship management (CRM)</li><li>Cyber security</li><li>Electronic document and records management (EDRM)</li><li>Healthcare</li><li>Human resources and employee management</li><li>Information and communication technology (ICT)</li><li>Legal and enforcement</li><li>Marketing</li><li>Operations management</li><li>Project management and planning</li><li>Sales</li><li>Schools, education and libraries</li><li>Software development tools</li><li>Transport and logistics</li></ol></li><li>Add additional information sections, for example:</li><li><p></p><ol><li>Information about options (yes / no)</li><li>Information about European Union Funds (e.g. The procurement is related to a project and/or programme financed by European Union funds: Yes / No)</li><li>Duration: e.g. Initial 12 months with an optional 12 month extension</li></ol></li></ol></li><li>Government owner creates new lot until total set in framework details is reached</li><li>Government owner sets up supplier submissions for each product/service offering.The supplier will provide this high-level information for each of their catalogue products/services on this specific Lot, as part of their application to the framework:</li><li><p></p><ol><li>Product name</li><li>Product description</li><li>Product features (Government owner can set the maximum number of features, and max word length per feature)</li><li>Product benefits (Government owner can set the maximum number of benefits, and max word length per benefit)</li><li>Product price  (Yes / No)</li><li>Service documents (Government owner can specify the title of each service document and if they are mandatory or optional, e.g. Pricing document, Rate card, Service definition document, Terms and Conditions) Set the accepted document format: PDF, ODF etc.</li></ol></li><li>Government owner sets up product feature listings for each product/service offering on this specific Lot.The supplier will provide this detailed information for each of their catalogue products/services, as part of their application to the framework. It will allow buyers to browse and filter, to find what they need. </li><li><p></p><ol><li>Government owner creates a Feature Type heading (e.g. User Support)</li><li>Government owner creates a list of features under the Feature Type (e.g. Email or online ticketing support, Support response times, User can manage status and priority of support tickets, Online ticketing support accessibility, Phone support, Phone support availability, Web chat support, Onsite support, Support levels). Each feature in the list consists of:</li><li><p></p><ol><li>Feature title (e.g. Email or online ticketing support)</li><li>Response type:</li><li><p></p><ol><li>Free text</li><li>Yes / No</li><li>Supplier can choose one or more options from the selection provided by the Government owner here (e.g. Real-time dashboards, Regular reports, Reports on request)</li><li>Supplier can choose only one option from the selection provided by the Government owner here (e.g. 2-factor authentication, Public key authentication, Username-Password)</li></ol></li></ol></li></ol></li><li>Government owner finishes the full set of product feature listings for each Lot, and reviews the draft. (auto-saved)</li></ol></td></tr><tr><td>Data output</td><td> </td></tr><tr><td>Post-Conditions (the success criteria)</td><td>.</td></tr><tr><td><p>Exceptions</p><p>(error situations)</p></td><td><p>·         A buyer can be only registered once. The system must prevent multiple registrations.</p><p>o    Provide details on exception code and message</p><p>o    Mitigation steps: Describe steps to be taken by the actors</p><p>·         If the buyer does not have an email address with a domain registered in the Registry, then it is not possible to create an account (no personal emails).</p><p>o    Provide details on exception code and message</p><p>o    Mitigation steps: Describe steps to be taken by the actors</p><p>·         If Identity BB or Consent BB is not available (service outage), then …..</p><p>o    Mitigation steps: Describe steps to be taken by the actors</p><p>·         If no internet, then the system is not available.</p><p>o    Mitigation steps: Display error page</p></td></tr><tr><td><p>Related BBs</p><p>(working groups related to this example implementation)</p></td><td><p>Identity BB</p><p>Approval BB</p><p>Registration BB</p><p>Digital Registries BB</p></td></tr><tr><td>Sequence Diagram</td><td> </td></tr></tbody></table>