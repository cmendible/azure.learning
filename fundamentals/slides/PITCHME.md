---?image=fundamentals/slides/img/cover.png
@title[Cover]

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Overview)

- Principles of cloud computing
- Introduction to Azure
- Manage services with the Azure portal
- Azure compute options
- Azure data storage options
- Azure networking options
- Control and organize Azure resources with Azure Resource Manager

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Overview)

- Security, responsibility and trust in Azure
- Apply and monitor infrastructure standards with Azure Policy
- Predict costs and optimize spending for Azure)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](What is cloud computing?)

- Cloud computing is renting resources, like storage space or CPU cycles, on another company's computers.
- You only pay for what you use.
- The cloud provider is responsible for the physical hardware required to execute your work.

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Benefits of cloud computing)

- Cost-effective
- Scalable
- Elastic
- Current
- Reliable
- Global
- Secure

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](CapEx vs OpEx)

- **Capital Expenditure (CapEx)**: CapEx is an upfront cost, which has a value that reduces over time.

- **Operational Expenditure (OpEx)**: There's no upfront cost. You pay for a service or product as you use it.

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Cloud deployment models)

- Public
- Private
- Hybrid

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Types of cloud services)

![Iaas, PaaS, SaaS](fundamentals/slides/img/5-layer-diagram.png)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Pizza as a Service)

![Pizza as a Service](fundamentals/slides/img/pizza-as-service.jpeg)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Regions)

![Azure Regions](fundamentals/slides/img/regions-map-large.svg)

Note:

- 54 regions worldwide
- available in 140 countries

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Availability Zones)

![Azure Availability Zones](fundamentals/slides/img/4-availability-zones.png)

Note:

Each Availability Zone is made up of one or more datacenters equipped with independent power, cooling, and networking. It is set up to be an isolation boundary.

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Region Pairs)

![Azure Availability Zones](fundamentals/slides/img/5-region-pairs.png)

Note:

Each Azure region is always paired with another region within the same geography

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Services)

![Type of Cloud Services](fundamentals/slides/img/3-azure-services.png)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Subscriptions)

![Azure Accounts & Subscriptions](fundamentals/slides/img/3-accounts-and-subscriptions.png)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Billing)

![Billing](fundamentals/slides/img/3-understand-your-bill.png)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Tenant)

![Billing](fundamentals/slides/img/4-azure-ad-tenant.png)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Management Options)

- Azure Portal
- Azure PowerShell
- Azure Command-Line Interface (CLI)
- Azure Cloud Shell
- Azure Mobile app

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Cloud Shell Dev Tools)

- Languages: .NET Core, Python, Java, Node.js, Go
- Editors: code (Cloud Shell Editor), vim, nano, emacs
- Tools: git, maven, make, npm, ...

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Portal)

- Layout & Blades
- Resource Panel
- Marketplace
- Settings

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Compute Options)

- Virtual Machines
- Containers
- Azure App Services
- Serverless Computing

---?image=fundamentals/slides/img/slide.png
### @color[rgb(0, 127, 255)](Scaling VMs in Azure)

- Availability sets
- Scale Sets
- Azure Batch

Note:

- An availability set is a logical grouping of two or more VMs that help keep your application available during planned or unplanned maintenance.
- Scale Sets let you create and manage a group of identical, load balanced VMs
- Azure Batch enables large-scale job scheduling and compute management with the ability to scale to tens, hundreds, or thousands of VMs

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Containers in Azure)

- Azure Container Instances (ACI)
- Azure Kubernetes Service (AKS)
- Managed OpenShift on Azure (OSA)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure App Services)

- Web Apps
- API Apps
- WebJobs
- Mobile Apps

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Serverless Computing)

- **Azure Functions** which can execute code in almost any modern language.
- **Azure Logic Apps** which are designed in a web-based designer and can execute logic triggered by Azure services without writing any code.

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Storage Benefits)

- Automated backup and recovery
- Replication across the globe
- Support for data analytics
- Encryption capabilities
- Multiple data types disks
- Data storage in virtual disks
- Storage tiers

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Storage Options)

- Azure SQL Database
- Azure Cosmos DB
- Azure Blob Storage
- Azure Data Lake Storage Gen2
- Azure Files
- Azure Queue
- Disk Storage

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Storage Comparison)

![Storage Comparison](fundamentals/slides/img/4-storage-comparison.png)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Networking)

- Virtual Networks
- Network Secuirty Groups
- Load Balancers
- Traffic Manager
- Azure Application Gateway
- CDN
- IPs
- DNS Zones

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Virtual Network)

![VNET](fundamentals/slides/img/vnet.png)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Traffic Manager)

![Traffic Manager](fundamentals/slides/img/traffic-maanager.png)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Application Gateway)

![Application Gateway](fundamentals/slides/img/3-appgateway.png)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Site to Site VPN)

![Site to Site VPN](fundamentals/slides/img/site-to-site-diagram.png)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Express Route)

![Express Route](fundamentals/slides/img/expressroute.png)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Organizing Resources)

- Resource Groups
  - Logical grouping
  - Life cycle
  - Authorization (RBAC)
- Tags (max 15)
- Policies
- RBAC
- Resource Locks

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure ARM Templates)

- Declarative solution for Deployment and Configuration
- Power of Repeatability
- Ensure Idempotency
- Simplify Orchestration
- Simplify Roll-back
- Provide Cross-Resource Configuration and Update Support
- [Templates](https://azure.microsoft.com/en-us/resources/templates/)

---?image=fundamentals/slides/img/slide.png

### @color[rgb(0, 127, 255)](Azure Tips)

- Start using the portal to deploy services.
- Explore the services using resources.azure.com
- Practice with CLI & ARM
- Understand what services can cover your use case
- [Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/)

---?image=fundamentals/slides/img/bsod.png
@title[Joke]

---?image=fundamentals/slides/img/end.png
@title[Thanks]