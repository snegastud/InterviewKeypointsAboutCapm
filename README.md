# InterviewKeypointsAboutCapm
**What is capm?**
>Framework provided by sap and it used to build enterpise grade applicaion on sap btp.
> capm provied  the strandard(build in) curd operations .(CREATE, READ,UPDATE,DELETE).
> we have implemented the custom logic when we need.
>its separate the floder structure like db level, srv , app.(its separate easy to main the applcaiton).
>its help develop the build the application very fast. its reduce boliercodes.

**why did your team use capm for your project?**
>we use capm its reduce the backend services and provide build 
>It provides built-in CRUD operations, so we mainly focus on the business logic we need. It also works well with SAP BTP services like HANA and XSUAA, and the project structure is clean, so it's easy to maintain and extend.

**How many ways create the project?**
>i know that we can generate the project template in two ways
>first one is cds init from the terminal
>second one is SAP Business Application Studio to generate the CAP project structure.
>But in my project, most of the time I cloned our existing repository and extended that.

**What is cds(Core data services)?**
>"CDS stands for Core Data Services. We use it to define our business data model in a structured way. For example, we create entities like employee or onboarding request inside the CDS file. Then, CAP uses that model to generate the database tables and expose them through OData services."
>"An entity represents a business object like employee or department."

**"Why did your team choose SAP CAP instead of other backend frameworks like Express.js? What are the advantages of CAP?"**
>Built-in CRUD operations.
>Focus on business logic.
>Automatic OData service generation.
>Built-in validations using CDS annotations.
>Less boilerplate code, so development is faster and the application is easier to maintain.
