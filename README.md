# Application Modernization Project


Parts Unlimited is an online auto parts store. Founded in Spokane, WA, in 2008, they are providing both genuine OEM and aftermarket parts for cars, sport utility vehicles, vans, and trucks, including new and remanufactured complex parts, maintenance items, and accessories. Their mission is to make buying vehicle replacement parts easy for consumers and professionals. Parts Unlimited has 185 stores in the US, with plans to scale to Mexico and Brazil.

Parts Unlimited has a hosted web application on its internal infrastructure and using a Windows Server, Internet Information Services (IIS), and Microsoft SQL Server to host the solution. Beyond the initial effort and costs, these applications incur ongoing maintenance costs in hardware, operating system updates, and licensing fees. These maintenance costs make Microsoft Azure App Service an attractive alternative. Their team is looking to migrate Microsoft ASP.NET/ Core applications and any SQL Server databases to Azure App Service and Azure SQL Database. However, they are worried that their application might not be supported. They want to know ahead of time the amount of work required to migrate to Azure. They have a project they want to start with to understand the migration process. They wonder if they can move to the cloud now and migrate their application later. What are the options?

Additionally, Parts Unlimited has plans to increase its marketing investment, currently on hold because of scaling issues. The company is stuck and can't grow without increasing its infrastructure footprint. Their CEO wants to finalize their cloud vs. on-premises decision based on the current migration effort's success. The engineering team is worried about their order processing subsystem. Currently, they have a strongly coupled order processing system that runs synchronously during checkout. When moved to the cloud, they don't want to be worried about their order processing system's scalability. They are looking for a modern approach with the least migration effort possible.

Finally, Parts Unlimited is looking to invest in DevOps practices to decrease human error in deployments. They are looking for options to have a staging environment to test functionality before shipping to production. However, their team does not have any experience in building CI/CD pipelines. They are not sure if this goal is achievable in the short term, and they do not want it to hold up their migration to the cloud.


### Project

In this Project, you gain a better understanding of the steps involved in modernizing legacy on-premises applications and infrastructure by leveraging cloud services. You see how applications can be assessed and migrate to Azure thanks to Azure Migrate and complimented with modern concepts such as Serverless.

At the end of this project, your ability to design and implement a modernization plan for organizations looking to move services from on-premises to the cloud will be improved.

### Hands-on lab

In this hands-on Project, you implement the steps to move a legacy on-premises application to Azure, including upgrading and migrating the database to Azure and updating the application to take advantage of serverless and cloud services.

At the end of this hands-on Project, your ability to build solutions for modernizing legacy on-premises applications and infrastructure using cloud services will be improved.

## Azure services and related products

- App Services
- Azure Database Migration Service
- Azure Functions
- Azure Key Vault
- Azure Migrate
- Azure Redis
- Azure SQL Database
- Azure Storage
- Azure Virtual Machines
- Visual Studio Code

## Related references

- [Reference architecture for Managed Web Applications](https://docs.microsoft.com/azure/architecture/reference-architectures/app-service-web-app/basic-web-app)
- [Azure application architecture guide](https://docs.microsoft.com/azure/architecture/guide/)
