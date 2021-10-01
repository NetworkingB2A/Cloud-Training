what is cloud computing?
The ability to rent compute and storage from someone else's datacenter.
compute power
- CPU
- Ram
- Backups
- up to date
storage
- Amount of Data
- Grow as you need


Why can Cloud computing be cheaper?
- Pay as you go/Only pay for what you use
- Run services only as you need (shutdown at nighttime)
- Grow as you need and reduce as you need

Why might I move to the cloud?
- teams deliver new features to their users at record speeds
- Users expect an increasing rich and immersive experience with their devices and their software

What is Azure?
Here are just some of the services/offerings by azure
- IaaS
- PaaS
- SaaS
- Pay-as-you-go
- Cloud-based storage
- Azure app services
- Azure Functions
- Azure containers
- Azure kubernetes 
- Databases
- azure cosmos DC
- AI and Machine learnings
- Regional data centers
- Azure portals

High level - How does Azure work?
- Virtualization
    - hypervisor
each data center has many servers
each server includes hypervisor
Network switch provides connections to all the servers
1 server in each rack runs a piece of software called the "Fabric controller"
Each "Fabric controller" is connected to a piece of software called the "orchestrator"
The "orchestrator" is responsible for everything that happens in Azure, including responding to users
Users make request to the "orchestrator" via the web api
the Web api can be called by many tools, including the web interface of the azure portal
When a user wants a VM, the request is sent to the orchestrator, the orchestrator picks the best server rack, the fabric controller creates the VM

What is the Azure Marketplace?
Azure marketplace helps connect users with Microsoft partners, independent software vendors ans startups that are offering their solution ans services, which are optimized to run on Azure. 

Azure services broken down by Main catagories
- Compute
  - VM
  - ECT
- Networking
  - Allows you to connect on Prem
  - VPN
  - Load balancing
- Storage
  - File 
  - disk
  - blob
  - Archival
- Mobile
  - management
  - app control?
- Databases
  - proprietary
  - open source
- Web
- Internet of things
- Big data
- AI
- DevOps
  - CI/CD

Different types of cloud
  - Public
    - No Capital expenditures to scale up.
    - Applications can be quickly provisioned and deprovisioned.
    - Organizations pay only for what they use.
  - Private
    - Hardware must be purchased for start-up and maintenance.
    - Organizations have complete control over resources and security.
    - Organizations are responsible for hardware maintenance and updates.
  - Hybrid
    - Provides the most flexibility.
    - Organizations determine where to run their applications.
    - Organizations control security, compliance, or legal requirements.

What are some cloud computing advantages?
- High availability
- Scalability
  - Vertically - increase compute capacity by adding RAM or CPU.
  - Horizontally - adding VMs.  
- Elasticity
- Agility
- Geo-distribution
- Disaster recovery

Capital expenses vs operating expenses
- Capital expenditures (CapEx)
  - This is more project based
  - or this is where you are given the cash up front or the availability of the cash.
- Operational expenditures (OpEx)
  - this is the concept of you are bill for a service and you pay that service once you are billed.
  - Employees are more operational expense, where contractors are more capital expense.
  - This is where cloud computing fits in.

Cloud service modules
- IaaS
- PaaS
- SaaS  
Here is a good break down of the services  
![Picture of service breakdown](../images/Cloud%20services.png)

Azure organization structure
- Management groups
  - These groups help you mange access, policy, and compliance for multiple subscriptions
- Subscription
  - Groups together user accounts and the resources that have been created by those users.
  - used to manage cost and access to resource group and resources
- Resource group
  - Resources are combinded into resource groups, which act like a logical container into which azure resources like web apps, databases and storage accounts are deployed and managed.
- Resources
  - instances of services that you create, like virtual machines, storage, or sql databases.  
  Here is a good breakdown of the organization structure.

![Picture of Azure org structure](../images/Azure%20org%20structure.png)