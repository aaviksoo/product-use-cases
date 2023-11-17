# AGR-1 - Market Linkage

## Product Use Case Summary

| ID      | AGR-1          |
| ------- | -------------- |
| Name    | Market Linkage |
| Sector  | Agriculture    |
| Version | 1.0            |
| Status  | Draft          |

This use case profiles a market linkage service that links buyers to sellers in the agriculture sector. In this context, market linkage pertains to connecting rural farmers to market information, products, and related services in order to boost productivity, and improve rural incomes and livelihoods. Due to the constraints of their remote location, farmers in remote areas - especially in developing countries, tend to have unequal market power, and poorer access to agricultural production inputs (seeds, fertilizer, and other goods) and services needed to grow and sell their crops.&#x20;

Governments in low- and middle-income countries are increasingly driven to identify sustainable strategies to link farmers with input and output market services, and stimulate agricultural productivity. One pathway is through the implementation of a digital Marketplace platform that connects farmers and other players within the agricultural value chain to: effectively trade goods and services, facilitate management and timely communication of market data (i.e, prices, harvest schedule), wider market access and help agro-dealers manage and streamline the farm input trade (i.e. fertilizers). Such a platform could improve operational efficiency, communication and viable linkages within the agricultural value chain thereby further unlocking the potential of the agriculture sector.

## Stakeholders

* Ministry of Agriculture and/or relevant governement run agriculture extension institution.
* Agricultural extension agents serving as experts and trainers of a Marketplace platform dedicated to supporting market linkage in the agriculture sector.
* Farmers seeking to buy affordable agricultural inputs and services, and sell their agricultural products.
* Agro suppliers/dealers/middlemen that provide agricultural inputs (fertilizers, pesticides), equipments, processing and/or wholesale services to farmers. &#x20;

## Sustainable Development Goals (SDGs)

* [**SDG 2**](https://exchange.dial.global/sdgs/zero\_hunger): Zero Hunger
* [**SDG 8**](https://exchange.dial.global/sdgs/decent\_work\_and\_economic\_growth): Decent Work and Economic Growth

## Building Blocks

* [**Consent**](https://govstack.gitbook.io/bb-consent)
* [**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)
* [**eMarketplace**](https://govstack.gitbook.io/bb-emarketplace)
* [**Identity**](https://govstack.gitbook.io/bb-identity/)
* [**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)
* [**Messaging**](https://govstack.gitbook.io/bb-messaging/)
* [**Payments**](https://govstack.gitbook.io/bb-payments)
* [**Registration**](https://govstack.gitbook.io/bb-registration)
* [**Scheduler**](https://govstack.gitbook.io/bb-scheduler/)
* [**Workflow**](https://govstack.gitbook.io/bb-workflow)

## Source Documents

* [Digital Impact Exchange - Market Linkage](https://exchange.dial.global/use\_cases/market\_linkage)

## Steps

### 1 - Outreach Communication

Staff from the Ministry of Agriculture/ Agriculture extension institution, organizes an awareness campaign about a newly launched digital Marketplace platform. A platform that connects core actors in the agricultural value chain (farmers, input suppliers, processors, wholesalers etc.,) to be able to connect with each other in order to buy and/or sell agricultural goods - products or services.&#x20;

The campaign is spread using promotional services - mobile messaging and/or aired on national radio/television to inform buyers and sellers across the of agriculture value chain, about the benefits of the Marketplace platform and process to register, download the app and create an account. To address literacy issues and reach more scope, the government extension institution staff will put a team in place to coordinate in-person community outreach to rural farming communities. Awareness drives will be implemented to educate and explain to farmers on how to use the Marketplace application - use the audio feature if they cannot read.

**Workflows**

* **Client communication** to raise awareness to target users about the Marketplace and encourage registration and account creation via mobile messaging / media channel(s)/ in-person
* **Client education** for educating potential target users about the digital Marketplace platform's approach, objective(s), benefit(s), constraint(s), guideline on the Marketplace app/platform usage etc
* **Content management** for the government staff and/ extension agents working on the Marketplace platform, to develop and manage training content for farmers on how to use the Marketplace and access all its feautures and functionality
* **Identification and Registration** (with aid of geographic information services tool for potential use) in mapping and locating the target users&#x20;
* **Marketplace** as an application workflow (mobile or web) to connect buyers and sellers, and to enable them to transact digitally&#x20;

**Building Blocks**

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Scheduler**](https://govstack.gitbook.io/bb-scheduler/)

[**Workflow**](https://govstack.gitbook.io/bb-workflow)

### 2 - Registration

Registration is the process of collecting standard information of a target group. For this use case, buyers and sellers working across the agricultural value chain, will be required to complete a registration process in order to fully access the Digital Marketplace (via app download and/or web browser). The user needs to complete a registration form with their identifiable information - this could include the person's citizen ID information, phone umber, age, gender, occupation etc.,). The purpose is to collect and authenticate the data identity and information of the intended Marketplace user. Once the intended user's identity data has been verified, they will then receive notification (via sms, e-mail and/or messaging system) confirming their registration with a first-time user ID and password to create a personalized profile on the Marketplace platform. Users can browse Marketplace with or without being logged in. If they want to sell and/or buy goods on the platform, then they must login with a valid account.

**Workflows**

* **Data Collection and Reporting** for capturing responses provided during the registration process
* **Identification and Registration** allows users to register themselves in the Marketplace in order to access the platform and its services. A built-in GPS in the users' main device i.e. mobile phone, automatically captures the user's location data so as to provide location based services

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Digital Registries**](https://govstack.gitbook.io/bb-digital-registries)

[**eMarketplace**](https://govstack.gitbook.io/bb-emarketplace)

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Registration**](https://govstack.gitbook.io/bb-registration/)

### 3 - Data Verification and Validation

As the purpose of the Marketplace is to easily facilitate the buying and selling of products and services in the agriculture value chain, a process is needed to verify and validate the submitted identity registration data. The data is automatically checked against other government databases (eg. ID, tax, land cadastre, business registration, etc.) in order to fill in any missing gaps, verify and validate collected information, including authentication of all records. Data checking approaches also vary: sometimes it has full interoperability.

**Workflows**

* **Client Case Management** for storing and reviewing identification records&#x20;
* **Data Analysis and Business Intelligence** for cross-referencing and verifying records across multiple registry sources, and reconciling gaps / overlaps

**Building Blocks**

[**Consent**](https://govstack.gitbook.io/bb-consent/)

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

### 4 - User Profile Account&#x20;

Every user on the Marketplace that registers will be provided with a personalized username and password to create their own detailed account on the platform. However if a country has a national identity scheme/nation ID registry in place, then this information can used for users to log in/access their personalized account on the Marketplace.\
Once a user has an account, they must be able to log in, change their details, and  create profile with their name or business name, upload images, and other relevant information.&#x20;

Users should be able to select what kind of services they are seeking to access on the Marketplace platform - i.e., the type of products or services they wish to buy and/or sell on the platform and whether they wish to receive agriculture advisory notifications via audio and text messages (on weather forecasts, crop calendars, pest and disease prevention/control, new seeds, inputs and technology, and market pricing alerts). For any users wishing to supply any products or services, they should be able to personalize their profile page to make their business stand out, and input information on products or services for sale, and their set preferred delivery method (pick up and/or delivery). All of this needs to be done in a way that both keeps user data secure and is compliant with a country's legal requirements.

**Workflows**

* **Data Collection and Reporting** for capturing the personalized profile information of all registerd users on the platform
* **Financial Services** for staging users' account details for payment transfer processing
* **Identification and Registration** for identifying users and linking them to a personalized profile on the Marketplace&#x20;
* **Client communication** sends users automated notification of harvest schedule, market prices for subscribed products, and weather/natural disaster updates, transaction-based and promotional information from the Marketplace through digital messaging (e.g. SMS, notification, etc.)&#x20;

**Building Blocks**

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Registration**](https://govstack.gitbook.io/bb-registration/)

### 5 - Listing Pages

The Marketplace needs listing pages - pages on the platform where sellers can display their products for sale and buyers to browse the different options available. Listing information can be sourced from sellers profiles where they can list attributes of goods and services they have for sale - with pictures, descriptions, prices, delivery options etc. Search and discovery tools should be incorporated features on the listing pages to help buyers find what they’re looking for on the Marketplace - buyers should have the ability to search and filter through based on the attributes above as well as use key words, audio function, image search etc, to filter through the Marketplace. A government run Marketplace admin system could be put in place to monitor, change, approve, close, and delete listings if necessary.&#x20;

**Workflows**

* **Data Analysis and Business Intelligence** / **Decision Support** / **Data Collection and Reporting** to capture, analyze and update all products and services listed on the platform, and ensuring the listing pages are automatically kept up-to-date with any new changes
* **Client Case Management** for tracking products and services listed by Marketplace users on the platform and addressing any customer/ Marketplace users' related issues
* **Client Case Management** for tracking all business transactions

**Building Blocks**

[**eMarketplace**](https://govstack.gitbook.io/bb-emarketplace)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

### 6 - On-platform Communication

On-platform communication is typically achieved through a messaging tool; a common marketplace feature that allows buyers and sellers to communicate quickly and easily. Buyers might have questions about items before placing an order. Sellers need a way to share updates with buyers after their purchase. Further, once a buyer is interested in buying a specific product, they can search for the product in the Marketplace and find different sellers who are selling the product in different markets, the pricing they are offering and delivery options. Once the buyer finds a seller that meets their pricing and need, they can directly contact the seller, negotiate pricing and share the delivery location with the seller. If the seller agrees to deliver the product at the buyer's location and the pricing is agreed by both parties, then the payment process can be facilitated.&#x20;

**Workflows**

* **Communication** to facilitate communication between buyers and sellers via app, web browser, mobile etc
* **Client case management** to address any communication needs between users and schedueling support to coordinate on product or service delivery&#x20;

**Building Blocks**

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Scheduler**](https://govstack.gitbook.io/bb-scheduler/)

### 7 - Seller Transaction&#x20;

A digital Marketplace should incorporate a process to facilitate the payment of goods and services to the seller. To facilitate transactions/payments between buyers and sellers, the platform can have an in-built payment function in the application. Step 7 above tracks the farm products and/or related services listed on the Marketplace and the preferred delivery method by location (pick up and/or delivery). Once the seller agrees to sell to a buyer, and the buyer makes the payment, an SMS or anther direct messaging system is sent to the seller informing them of the remittance being processed. The money could be deposited in to an Escrow Account possibly managed by a financial service provider, which only releases the final remittance to the seller once the physical deliver of a good or service is received b the buyer successfully. Once the physical delivery process has succeeded, the seller then receives the payment in their account.

When filing out their profile with their necessary information and phone number, a process should be put in place for all users to verify their preferred method to receive payment (i.e.via  bank account or mobile money), mobil, which will be used to facilitate payment transactions on the platform. Should mobile banking be an agreed transation method, a verification process will be put in place to ensure the mobile number is associated with the user's banking details, and payment transfer can be facilitated via a financial service broker or intermediary embedded as part of the Marketplace platform.

**Workflows**

* **Client Case Management** for tracking transactions - identifying and authenticating payment transaction between buyers and sellers
* **Financial Services** to facilitate financial transactions between buyers and sellers in order to conclude the buy-sale process
* **Identification and Registration** to identify, register and verify a registered seller's bank and/or mobile banking details is associated to their account
* **Procurement:** buyers and sellers in the Marketplace procure via a Procurement workflow of goods and services by negotiating transactional terms and conditions (e.g. price, delivery time etc.)

**Building Blocks**

[**eMarketplace**](https://govstack.gitbook.io/bb-emarketplace)

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Payments**](https://govstack.gitbook.io/bb-payments/)

[**Scheduler**](https://govstack.gitbook.io/bb-scheduler/)

### 8 - Buyer Transaction

A digital Marketplace should also provide some kind of process to facilitate payment of the listed goods and services by thee registered buyer. After a user wishing to buy agricultural products or services completes their detailed profile on Marketplace, then based on this data, products and services can be suggested for the user. Once a buyer finds a product or service they wish to proceed with, they can get in touch with the seller to discuss pricing and delivery options. Once an agreement is reached, the buyer selects the payment service - it could be the in-built payment function in the Marketplace application connected to the seller's bank or mobile banking. After the payment successfully processed, the buyer receives an SMS or any direct digital messaging system - transaction confirmation authentication code, which has to be shared with the delivery service provider once they receive the goods.

When filing out their profile with their necessary information and phone number, a process should be put in place for all users to verify their preferred method to receive payment (i.e.via  bank account or mobile money), mobil, which will be used to facilitate payment transactions on the platform. Should mobile banking be an agreed transation method, a verification process will be put in place to ensure the mobile number is associated with the user's banking details, and payment transfer can be facilitated via a financial service broker or intermediary embedded as part of the Marketplace platform.

**Workflows**

* **Client Case Management** for tracking transactions - identifying and authenticating payment transaction between buyers and sellers
* **Financial Services** to facilitate financial transactions between buyers and sellers in order to conclude the buy-sale process
* **Identification and Registration** to identify, register and verify a registered buyer's bank and/or mobile banking details is associated to their account
* **Procurement:** buyers and sellers in the Marketplace procure via a Procurement workflow of goods and services by negotiating transactional terms and conditions (e.g. price, delivery time etc.)

**Building Blocks**

[**eMarketplace**](https://govstack.gitbook.io/bb-emarketplace)

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Payments**](https://govstack.gitbook.io/bb-payments/)

[**Scheduler**](https://govstack.gitbook.io/bb-scheduler/)

### 9 - Physcial Delivery of Goods

Physical delivery is the act of sending out and the receiving of goods or services at an arranged place. In this use case, once the seller receives confirmation of payment for their good or service, an invoice is generated with the buyer's name and address. The next step is to coordinate the delivery process of the physical good(s) to the agree location/address of the buyer. The delivery could be done independently by the seller themself or through a logistics service provider (courier company, transporter) etc. I.e. the seller pays the courier company for on-site pick up and the courier company picks up the good and delivers to the buyer. On receipt of purchased good, the buyer provides the authentication code (see step 8) to the delivery service. The code gets authenticated and the seller receives payment in their bank account.

**Workflows**

* **Client Case Management** for identifying and authenticating the buyer's authentication code&#x20;
* **Financial Services** to deposit payment into the seller's account once buyer confirms receipt of purchased goods or services&#x20;
* **Supply-chain Management**: ensuring the physical delivery of the goods and services being transacted in digital Marketplace and monitoring when the actual supply of goods or service happens physically&#x20;

**Building Blocks**

[**Messaging**](https://govstack.gitbook.io/bb-messaging/)

[**Payments**](https://govstack.gitbook.io/bb-payments/)

[**Workflow**](https://govstack.gitbook.io/bb-workflow)

### 10 - Ongoing Case Management

The government entity running the Marketplace platform has a team of case mangers and administers in place to operate the platform and ensure quality assurance. The case managers can address any queries and support needs of of users. This body also supports in monitoring and addressing complaints and grievances submitted by registered users.

**Workflows**

* **Client Case Management** for tracking all business transactions, and addressing complaints/grievances raised by Marketplace users
* **Data Collection and Reporting** for capturing the personalized profile information of all registered users on the platform

**Building Blocks**

[**Identity**](https://govstack.gitbook.io/bb-identity/)

[**Information Mediator**](https://govstack.gitbook.io/bb-information-mediation)

## Contributors

* Wesley Brown, GovStack Product Owner, Digital Impact Alliance
* Steve Conrad, Associate Director of Technology, Digital Impact Alliance
* Taylor Downs, CEO of OpenFunction
* Sarah Farooqi, The Exchange Product Owner, Digital Impact Alliance
* Sainabou Jallow, Business Analyst, Digital Impact Alliance
* Dr. P. S. Ramkumar, GovStack, International Telecommunication Union (ITU)
* Margus Mägi, GovStack Project Lead for Estonia
* Farina Owusu, Junior Advisor, Global Programme Digital Transformation at GIZ
* Meelis Zujev, GovStack, Estonia

