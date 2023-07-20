## How IAAS works

Infrastructure as a Service (IaaS) is a cloud computing model that provides virtualized computing resources over the internet. 

Let's explore how IaaS works by breaking down its key components:

+ `Compute Pool:` The compute pool in IaaS consists of a collection of virtual machines (VMs) or instances. These instances are created and managed by the cloud service provider (CSP) and are made available to users on-demand. Users can choose the desired specifications for their VMs, such as CPU, memory, and operating system. The compute pool allows for scalability and flexibility, as users can easily provision or release VM instances as needed.

+ `Storage Pool:` The storage pool refers to the centralized storage infrastructure provided by the CSP. It offers various types of storage options, including block storage, object storage, and file storage. Users can allocate and manage storage resources based on their requirements. The storage pool ensures data persistence and durability, enabling users to store and access their data reliably within the cloud environment.

+ `Compute Controller:` The compute controller, also known as the virtual machine manager or hypervisor, is responsible for managing and orchestrating the compute resources in the IaaS environment. It provisions and manages VM instances within the compute pool. The compute controller allocates physical server resources, monitors the health and performance of VMs, and handles tasks such as VM migration, scaling, and load balancing.

+ `Management Network (using APIs):` The management network in IaaS provides connectivity and communication between different components of the cloud infrastructure. APIs (Application Programming Interfaces) play a crucial role in enabling interaction and control over the IaaS resources. Users and administrators can utilize APIs to automate the provisioning and management of VMs, storage resources, network configurations, and other IaaS functionalities. APIs allow for programmatic access to IaaS services, facilitating integration with third-party tools, applications, and management systems.

+ `Storage/Volume Controller:` The storage/volume controller manages the storage resources within the storage pool. It handles tasks such as provisioning storage volumes, managing data replication and redundancy, and implementing data access controls. The storage controller ensures efficient allocation and utilization of storage resources, as well as data protection and backup mechanisms.

+ `Management Network Plane:` The management network plane in IaaS is a dedicated network infrastructure used for communication and management purposes within the cloud environment. It facilitates communication between different management components, such as the compute controller, storage controller, and management interfaces. The management network plane is isolated from the user-facing networks to ensure security and proper segregation of management traffic.

In summary, IaaS works by providing users with virtualized compute and storage resources from a compute pool and storage pool respectively. The compute controller manages the provisioning and management of VM instances, while the storage/volume controller handles storage resource allocation. The management network, including APIs, enables users and administrators to interact with and control the IaaS resources effectively. The management network plane ensures secure communication between different management components within the cloud infrastructure.


![image](https://github.com/adeleke123/I4GCybersecurity/assets/51156057/dcccd715-dd97-466f-8d0d-d726b94c7a6e)

