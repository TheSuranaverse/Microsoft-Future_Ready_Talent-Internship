# Introduction to Azure Fundamentals

➤ If you find this **REPOSITORY** helpful, then do give it a `🌟` by pressing the topmost-right button 🤗

➤ To save a copy of this **REPOSITORY** to your own GitHub, then click on <a href="https://github.com/Neklaustares-tPtwP/Microsoft-Future_Ready_Talent-Internship/edit/master/README.md"><kbd><b>Fork</b></kbd></a> on the top right of your screen 🤗

## 1. What is Cloud Computing?

Cloud Computing is the delivery of computing services over the internet, which is otherwise known as the cloud. These services include servers, storage, databases, networking, software, analytics, and intelligence. Cloud computing offers faster innovation, flexible resources, and economies of scale.

### Why is cloud computing typically cheaper to use?
Cloud computing is the delivery of computing services over the internet by using a **pay-as-you-go** pricing model. It helps you:
- Lower your operating costs.
- Run your infrastructure more efficiently.
- Scale as your business needs change.
It is a way to rent compute power and storage from someone else's datacenter & you're billed only for what you use.

### Why should I move to the cloud?
The cloud helps you move faster and innovate in ways that were once nearly impossible. To power your services and deliver innovative and novel user experiences more quickly, the cloud provides on-demand access to:
- A nearly limitless pool of raw compute, storage, and networking components.
- Speech recognition and other cognitive services that help make your application stand out from the crowd.
- Analytics services that deliver telemetry data from your software and devices.
<hr>

## 2. What is Azure?

Azure is a continually expanding set of cloud services that help your organization meet your current and future business challenges. Azure gives you the freedom to build, manage, and deploy applications on a massive global network using your favorite tools and frameworks.

### What does Azure offer?
<details><summary>The following table lists several of the benefits that Azure provides:</summary>
  <ul>
        <li><b>Be ready for the future:</b> Continuous innovation from Microsoft supports your development today and your product visions for tomorrow.</li>
        <li><b>Build on your terms:</b> With a commitment to open source, and support for all languages and frameworks, you can build how you want and deploy where you want to.</li>
        <li><b>Operate hybrid seamlessly:</b> Integrate and manage your environments with tools and services designed for a hybrid cloud solution.</li>
        <li><b>Trust your cloud:</b> Get security from the ground up, backed by a team of experts, and proactive compliance trusted by enterprises, governments, and startups.</li>
    </ul>
</details>

### What can I do with Azure?
Azure provides more than 100 services that enable you to do everything from running your existing applications on virtual machines, to exploring new software paradigms, such as intelligent bots and mixed reality.

### How does Azure work?
It is a private & public cloud platform that help developers & IT administartors to build, deploy, and manage their applications. It uses a technology known as **Virtualization**. 
- **VIRTUALIZATION:** It helps seperate the tight coupling between a computer's hardware and its operating system using an abstraction layer called a **Hypervisor**.
- **HYPERVISOR:** It emulates all the functions of a real computer & its CPU in a virtual machine, optimizing the capacity of the obstructed hardware. It can run multiple Virtual Machines (VMs) at the same time & each VM can run any compatible OS such as Linux or Windows. MS takes this Vurtualization technology & repeats it on a massive scale in MS data centers throughout the world.
- **DATA CENTERS:** Each data centers has many racks filled with server and each server includes a hypervisor to run multiple VMs.
- **NETWORK SWITCH:** A network switch provides connectivity to all those servers. One server in each rack runs a special piece of software called a **Fabric Controller**.
- **FABRIC CONTROLLER:** Each fabric controller is connected to another piece of software known as the **Orchestrator**.
- **ORCHESTRATOR:** It is responsible for managing everything that happens in azure, including responding to user requests. Users make requests using the Orchestartor's web API. 
- **WEB API:** It can be called by many tools, using the user interface of the Azure portal. So when a user makes a request to create a VM, the Orchestrator packages everything that's needed , picks the best server rack, and then sneds the package and request to the Fabric Controller. Once the Fabric Controller has created the VM, the user can connect to it.  
It gives you the freedom to build, manage, and deploy applications on a massive global netowrk using your favourite tools and frameworks.


### What is the Azure portal?
The Azure portal is a web-based, unified console that provides an alternative to command-line tools. It is a one-stop, graphical management solution for creating, configuring, and controlling all your Azure services. With the Azure portal, you can manage your Azure subscription by using a graphical user interface.<details><summary>You can:</summary>
  <ul>
        <li>Build, manage, and monitor everything from simple web apps to complex cloud deployments.</li>
        <li>Create custom dashboards for an organized view of resources.</li>
        <li>Scale services by adding or removing resources from your subscription.</li>
        <li>Monitor the health of applications, track costs & billing status, analyze the performance of your applications in real-time or create reports for in-depth analysis.</li>
        <li>Configure accessibility options for an optimal experience.</li>
    </ul>
    <img src="https://github.com/Neklaustares-tPtwP/Microsoft-Future_Ready_Talent-Internship/blob/master/Azure%20Fundamentals%20(AZ-900)/Describe%20Core%20Azure%20Concepts/img/azure-portal-dd184579.png" width="360px">
</details>

### What is Azure Marketplace?
[Azure Marketplace](https://azuremarketplace.microsoft.com/en-US/) helps connect users with Microsoft partners, independent software vendors, and startups that are offering their solutions and services, which are optimized to run on Azure.
<hr>

## 3. Tour of Azure Services

<details><summary>List of top 10 services:</summary>
<ul>
  <li><b>COMPUTE:</b> These cloud services let you `scale` your computing capability on demand while only paying for what you use. Add VMs as needed or scale your company's app services for web and mobile apps. </li>
  <li><b>NETWORKING:</b> These featurs help you connect your cloud & on-premise infrastructure in order to bring the best possible experience to your customers. `VPNs` & `Load-balancing` are two examples of this feature. </li>
  <li><b>STORAGE:</b> Disk, file, blob or archival storage, these services let you scale your data & app storage needs in a secure fashion.</li>
  <li><b>MOBILE:</b> Build & deploy cross-platform & native apps for any mobile device, use `Xamarin` to build cloud-powered apps, & take advantage of cognitive services.</li>
  <li><b>DATABASES:</b> Use tools to manage your SQL, Cosmos DB, MySQL, & other data services.</li>
  <li><b>WEB:</b> Help you build, deploy, manage & scale your web applications. Create web apps, publish APIs to your services, or use `Azure Maps` to provide geospatial context to your data.</li>
  <li><b>IoT:</b> Connect, monitor & manage all your IoT assets. Analyze the data as it arrives from the sensors & then take meaningful action with it.</li>
  <li><b>Big Data:</b> When you have large volumes of data, these open source cluster services will help you run analytics at a massive scale & make decisions based off of complex queries.</li>
  <li><b>AI:</b> Use your existing data to forecast future behaviours. Use ML to build, train & deploy models to the cloud.</li>
  <li><b>DevOps:</b> DevOps brings together people, processes, and technology by automating software delivery to provide continuous value to your users. Create, build & release pipelines that provide continuous integration, delivery, & deployment for your applications.</li>
</ul>


<h3> Compute </h3>
Compute services are often one of the primary reasons why companies move to the Azure platform. Azure provides a range of options for hosting applications and services. Here are some examples of compute services in Azure.

|Service name | Service function|
|:--:|:--:|
|Azure Virtual Machines | Windows or Linux virtual machines (VMs) hosted in Azure.|
|Azure Virtual Machine Scale Sets | Scaling for Windows or Linux VMs hosted in Azure.|
|Azure Kubernetes Service | Cluster management for VMs that run containerized services.|
|Azure Service Fabric | Distributed systems platform that runs in Azure or on-premises.|
|Azure Batch | Managed service for parallel and high-performance computing applications.|
|Azure Container Instances | Containerized apps run on Azure without provisioning servers or VMs.|
|Azure Functions | An event-driven, serverless compute service.|

<h3>Networking</h3>
Linking compute resources and providing access to applications is the key function of Azure networking. Networking functionality in Azure includes a range of options to connect the outside world to services and features in the global Azure datacenters.

|Service name|Service function|
|:--:|:--:|
|Azure Virtual Network|Connects VMs to incoming VPN connections.|
|Azure Load Balancer|Balances inbound and outbound connections to applications or service endpoints.|
|Azure Application Gateway|Optimizes app server farm delivery while increasing application security.|
|Azure VPN Gateway|Accesses Azure Virtual Networks through high-performance VPN gateways.|
|Azure DNS|Provides ultra-fast DNS responses and ultra-high domain availability.|
|Azure Content Delivery Network|Delivers high-bandwidth content to customers globally.|
|Azure DDoS Protection|Protects Azure-hosted applications from distributed denial of service (DDOS) attacks.|
|Azure Traffic Manager|Distributes network traffic across Azure regions worldwide.|
|Azure ExpressRoute|Connects to Azure over high-bandwidth dedicated secure connections.|
|Azure Network Watcher|Monitors and diagnoses network issues by using scenario-based analysis.|
|Azure Firewall|Implements high-security, high-availability firewall with unlimited scalability.|
|Azure Virtual WAN|Creates a unified wide area network (WAN) that connects local and remote sites.|

<h3>Storage</h3>

|Service name|Service function|
|:--:|:--:|
|Azure Blob storage|Storage service for very large objects, such as video files or bitmaps.|
|Azure File storage|File shares that can be accessed and managed like a file server.|
|Azure Queue storage|A data store for queuing and reliably delivering messages between applications.|
|Azure Table storage|Table storage is a service that stores non-relational structured data (also known as structured NoSQL data) in the cloud, providing a key/attribute store with a schemaless design.|

<h3>These services all share several common characteristics:</h3>
<ul>
<li>Durable and highly available with redundancy and replication.</li>
<li>Secure through automatic encryption and role-based access control.</li>
<li>Scalable with virtually unlimited storage.</li>
<li>Managed, handling maintenance and any critical problems for you.</li>
<li>Accessible from anywhere in the world over HTTP or HTTPS.</li>
</ul>

</details>

### What is the Learn sandbox?
Many of the Learn exercises use a technology called the `sandbox`, which creates a temporary subscription that's added to your Azure account. This temporary subscription allows you to create Azure resources for the duration of a Learn module. Learn automatically cleans up the temporary resources for you after you've completed the module.


# THANK YOU!

➤ If you find this **REPOSITORY** helpful, then do give it a `🌟` by pressing the topmost-right button 🤗

➤ To save a copy of this **REPOSITORY** to your own GitHub, then click on <a href="https://github.com/Neklaustares-tPtwP/Microsoft-Future_Ready_Talent-Internship/edit/master/README.md"><kbd><b>Fork</b></kbd></a> on the top right of your screen 🤗