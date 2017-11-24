---
layout: post
title: "Architecting Microsoft Azure Solutions"
categories: Cloud MS
author: J3551c9 Perez
---
# 70-535 exam guide

As you probably already know the Architecting Microsoft Azure Solutions 70-534 exam will be updated on December 31,2017, and in case you don't check the [Microsoft Training and Certification Community's announcement](https://borntolearn.mslearn.net/b/weblog/posts/microsoft-exam-70_2d00_535-to-replace-70_2d00_534_3a00_-architecting-microsoft-azure-solutions-on-november-30-_1320_-here_1920_s-what-you-should-know-). Most of the domains has changed, but here you can check the new [skills measured](https://www.microsoft.com/en-us/learning/exam-70-535.aspx).

When I prepared my self to take the now old exam one of my problems was found the resources to study, so that's why I write this as an intent of study guide where you can find resources to help you prepare your self for the new exam, of course there is more than just read, I extremely recommend hands on practice hope it helps.

This is working progress and I will constantly update this guide.

Now time to study!!!

## 1. Design Compute Infrastructure (20-25%)

### 1.1 Design solutions using virtual machines 
#### 1.1.1 [Design VM deployments by leveraging availability sets, fault domains, and update domains in Azure](https://docs.microsoft.com/en-gb/azure/virtual-machines/windows/manage-availability)

#### 1.1.2 Use web app for containers
* [Run a custom Docker Hub image in Azure Web App for Containers](https://docs.microsoft.com/en-us/azure/app-service/containers/)
* [Overview on Web App for Containers and Azure App Service on Linux](https://azure.microsoft.com/en-us/blog/webapp-for-containers-overview/)

#### 1.1.3 Design VM Scale Set
* [What are virtual machine scale sets in Azure?](https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-overview)
* [Design considerations for Scale Sets](https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-design-overview)

#### 1.1.4 [Design for compute-intensive tasks using Azure Batch](https://docs.microsoft.com/en-gb/azure/batch/batch-technical-overview)

#### 1.1.5 Define a migration strategy from cloud services
* [Migrate an Azure Cloud Services application to Azure Service Fabric](https://docs.microsoft.com/en-us/azure/architecture/service-fabric/migrate-from-cloud-services)
* [Differences between Cloud Services and Service Fabric before migrating applications](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-cloud-services-migration-differences)

#### 1.1.6 Recommend use of Azure Backup and Azure Site Recovery
* [Features in Azure Backup & Why use Azure Backup?](https://docs.microsoft.com/en-gb/azure/backup/backup-introduction-to-azure-backup)
* [What is Site Recovery?](https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-overview)
* [What workloads can you proctect with Azure Site Recovery](https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-workload)

### 1.2 Design solutions for serverless computing  
#### 1.2.1 [Use Azure Functions to implement event-driven actions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview)
#### 1.2.2 [Design for serverless computing using Azure Container Instances](https://opbuildstorageprod.blob.core.windows.net/output-pdf-files/en-us/Azure.azure-documents/live/container-instances.pdf)
#### 1.2.3 [Design application solutions by using Azure Logic Apps, Azure Functions, or both](https://docs.microsoft.com/en-us/azure/azure-functions/functions-compare-logic-apps-ms-flow-webjobs)
#### 1.2.4 [Determine when to use API management service](https://docs.microsoft.com/en-gb/azure/api-management/api-management-key-concepts)

### 1.3 Design microservices-based solutions  
#### 1.3.1 [Determine when a container-based solution is appropriate](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/microservices)
* [Deploying Microservices and Containers with Azure Container Service and DC/OS](https://azure.microsoft.com/mediahandler/files/resourcefiles/249aaf61-9b90-40f9-a217-41b6d23643f7/Deploying-Microservices-and-Containers-with-Azure-Container-Service-and-DC-OS.pdf)

#### 1.3.2 [Determine when container-orchestration is appropriate](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-orchestrator-relationship)

#### 1.3.3 [Determine when Azure Service Fabric (ASF) is appropriate](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-application-scenarios)
* [Service Fabric patterns and scenarios](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-patterns-and-scenarios)

#### 1.3.4 [Determine when Azure Functions is appropriate](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview)

#### 1.3.5  [Determine when to use API management service](https://docs.microsoft.com/en-gb/azure/api-management/api-management-key-concepts)

#### 1.3.6 [Determine when Web API is appropriate](https://www.quora.com/What-is-difference-between-Azure-API-App-and-Web-App)

#### 1.3.7 [Determine which platform is appropriate for container orchestration](https://docs.microsoft.com/en-us/azure/aks/intro-kubernetes)

#### 1.3.8 [Consider migrating existing assets versus cloud native deployment](https://docs.microsoft.com/en-us/dotnet/standard/modernize-with-azure-and-containers/lift-and-shift-existing-apps-devops/what-about-cloud-optimized-applications)

#### 1.3.9 [Design lifecycle management strategies](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=5&cad=rja&uact=8&ved=0ahUKEwiRk8q0mrTXAhWR56QKHXcrAn8QFgg8MAQ&url=https%3A%2F%2Fdownload.microsoft.com%2Fdownload%2F7%2F6%2F8%2F768E8E11-1C4B-4C5C-9211-96918C324722%2FContainerized%2520Docker%2520Application%2520Lifecycle%2520with%2520Microsoft%2520Platform%2520and%2520Tools%2520(eBook).pdf&usg=AOvVaw127kkoVYZ1FdhclHO80PXd)

### 1.4 Design web applications  
#### 1.4.1 Design Azure App Service Web Apps
* [Web Apps overview](https://docs.microsoft.com/en-gb/azure/app-service/app-service-web-overview)
* [Azure Web App Sandbox](https://github.com/projectkudu/kudu/wiki/Azure-Web-App-sandbox)

#### 1.4.2 [Design custom web API](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-create-api-app)
* [What is difference between Azure API App and Web App?](https://www.quora.com/What-is-difference-between-Azure-API-App-and-Web-App)

#### 1.4.3 Secure Web API
* [Secure calls to your custom APIs](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-custom-api-authentication)
* [How to protect a Web API backend with Azure Active Directory and API Management](https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-protect-backend-with-aad)

#### 1.4.4 Design Web Apps for scalability and performance
* [Scale up an app in Azure](https://docs.microsoft.com/en-gb/azure/app-service/web-sites-scale)
* [Monitor Azure web app performance](https://docs.microsoft.com/en-us/azure/application-insights/app-insights-azure-web-apps)
* [Application performance FAQs for Web Apps in Azure](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-availability-performance-application-issues-faq)

#### 1.4.5 [Design for high availability using Azure Web Apps in multiple regions](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/app-service-web-app/multi-region)

#### 1.4.6 Determine which App service plan to use
* [What is an App service plan?](https://docs.microsoft.com/en-us/azure/app-service/azure-web-sites-web-hosting-plans-in-depth-overview)
* [App service plan pricing](https://azure.microsoft.com/en-gb/pricing/details/app-service/)

#### 1.4.7 Design Web Apps for business continuity
* [Business continuity and disaster recovery (BCDR): Azure Paired Regions](https://docs.microsoft.com/en-us/azure/best-practices-availability-paired-regions)
* [Designing resilient applications for Azure](https://docs.microsoft.com/en-us/azure/architecture/resiliency/)
* [Designing Globally Resilient Apps with Azure App Service](https://www.opsgility.com/blog/2017/06/28/designing-globally-resilient-apps-with-azure-app-service/)

#### 1.4.8 [Determine when to use Azure App Service Environment (ASE)](https://docs.microsoft.com/en-gb/azure/app-service/environment/intro?toc=%2Fazure%2Fapp-service-web%2Ftoc.json)

#### 1.4.9 [Design for API apps](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

#### 1.4.10 [Determine when to use API management service](https://docs.microsoft.com/en-us/azure/api-management/api-management-key-concepts)

#### 1.4.11 Determine when to use Web Apps on Linux 
* [Introduction to Azure App Service on Linux](https://docs.microsoft.com/en-us/azure/app-service/containers/app-service-linux-intro)
* [Azure App Service on Linux FAQ](https://docs.microsoft.com/en-us/azure/app-service/containers/app-service-linux-faq)
* [Things You Should Know: Web Apps and Linux](https://blogs.msdn.microsoft.com/waws/2017/09/08/things-you-should-know-web-apps-and-linux/)

#### 1.4.12 [Determine when to use a CDN](https://docs.microsoft.com/en-us/azure/architecture/best-practices/cdn)
#### 1.4.13 [Determine when to use a cache, including Azure Redis cache](https://docs.microsoft.com/en-us/azure/architecture/best-practices/caching)

### 1.5 Create compute-intensive applications 
#### 1.5.1 [Design high-performance computing (HPC) and other compute-intensive applications using Azure Services](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/high-performance-computing)
#### 1.5.2 Determine when to use Azure Batch
* [Develop large-scale parallel compute solutions with Batch](https://docs.microsoft.com/en-us/azure/batch/batch-api-basics)
* [Use cases for Batch](https://docs.microsoft.com/en-gb/azure/batch/batch-technical-overview)

#### 1.5.3 Design stateless components to accommodate scale
* [Scalability checklist](https://docs.microsoft.com/en-us/azure/architecture/checklist/scalability)
* [Criteria for choosing an Azure compute option(check state managemet)](https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-comparison)

#### 1.5.4 Design lifecycle strategy for Azure Batch  

## 2. Design Data Implementation (15-20%) 
 
### 2.1 Design for Azure Storage solutions  
#### 2.1.1 Determine when to use Azure Blob Storage, blob tiers, Azure Files, disks, and StorSimple 
* [Introduction to Microsoft Azure Storage](https://docs.microsoft.com/en-gb/azure/storage/common/storage-introduction)
* [Deciding when to use Azure Blobs, Azure Files, or Azure Disks](https://docs.microsoft.com/en-gb/azure/storage/common/storage-decide-blobs-files-disks)
* [Azure Blob Storage: Hot, cool, and archive storage tiers](https://docs.microsoft.com/en-gb/azure/storage/blobs/storage-blob-storage-tiers)
* [StorSimple Virtual Array](https://docs.microsoft.com/en-us/azure/storsimple/storsimple-ova-overview)
* [StorSimple 8000 series](https://docs.microsoft.com/en-us/azure/storsimple/storsimple-overview)

### 2.2 Design for Azure Data Services  
#### 2.2.1 Determine when to use Data Catalog, Azure Data Factory, SQL Data Warehouse, Azure Data Lake Analytics, Azure Analysis Services, and Azure HDInsight  
* [What is Azure Data Catalog?](https://docs.microsoft.com/en-us/azure/data-catalog/data-catalog-what-is-data-catalog)
* [Azure Data Catalog common scenarios](https://docs.microsoft.com/en-us/azure/data-catalog/data-catalog-common-scenarios)
* [Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/introduction)
* [SQL Data Warehouse](https://docs.microsoft.com/en-us/azure/sql-data-warehouse/sql-data-warehouse-overview-what-is)
* [Best practices for Azure SQL Data Warehouse](https://docs.microsoft.com/en-us/azure/sql-data-warehouse/sql-data-warehouse-best-practices)
* [Microsoft Azure Data Lake Analytics](https://docs.microsoft.com/en-us/azure/data-lake-analytics/data-lake-analytics-overview)
* [What is Azure Analysis Services?](https://docs.microsoft.com/en-us/azure/analysis-services/analysis-services-overview)
* [Azure HDInsight](https://docs.microsoft.com/en-gb/azure/hdinsight/hadoop/apache-hadoop-introduction)
 
### 2.3 Design for relational database storage 
#### 2.3.1 [Determine when to use Azure SQL Database and SQL Server Stretch Database](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-paas-vs-sql-server-iaas)
#### 2.3.2 Design for scalability and features
* [SQL Server and SQL Database feature support](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-features)
* [Scaling out with Azure SQL Database](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-scale-introduction)
* [What are Azure SQL Database service tiers](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-service-tiers)

#### 2.3.3 Determine when to use Azure Database for MySQL and Azure Database for PostgreSQL
* [Azure Database for PostgreSQL Servers](https://docs.microsoft.com/en-gb/azure/postgresql/concepts-servers)
* [Azure Database for PostgreSQL Overview](https://docs.microsoft.com/en-gb/azure/postgresql/overview)
* [Azure Database for MySQL server](https://docs.microsoft.com/en-gb/azure/mysql/concepts-servers)
* [Azure Database for MySQL Overwiew](https://docs.microsoft.com/en-gb/azure/mysql/overview)

#### 2.3.4 [Design for HA/DR, geo-replication](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-high-availability-dr)
* [Designing highly available services using Azure SQL Database](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-designing-cloud-solutions-for-disaster-recovery)
*[Failover groups and active geo-replication](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-geo-replication-overview)

#### 2.3.5 Design a backup and recovery strategy  
* [Automatic SQL Database backups](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-automated-backups) 
* [Recover an Azure SQL database using automated database backups](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-recovery-using-backups)
* [Recover from outage](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-disaster-recovery)
 
### 2.4 Design for NoSQL storage 
#### 2.4.1 [Determine when to use Azure Redis Cache, Azure Table Storage, Azure Data Lake, Azure Search, Time Series Insights](https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/data-store-overview)
* [Criteria for choosing a data store](https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/data-store-comparison)
 
### 2.5 Design for CosmosDB storage 
* [Common Azure Cosmos DB use cases](https://docs.microsoft.com/en-gb/azure/cosmos-db/use-cases)
* [Azure Cosmos DB FAQ](https://docs.microsoft.com/en-gb/azure/cosmos-db/faq)

#### 2.5.1 Determine when to use MongoDB API, DocumentDB API, Graph API, Azure Tables API
* [Azure Cosmos DB: DocumentDB API](https://docs.microsoft.com/en-us/azure/cosmos-db/documentdb-introduction)
* [Azure Cosmos DB: API for MongoDB](https://docs.microsoft.com/en-us/azure/cosmos-db/mongodb-introduction)
* [Azure Cosmos DB: Table API](https://docs.microsoft.com/en-us/azure/cosmos-db/table-introduction)
* [Azure Cosmos DB: Graph API](https://docs.microsoft.com/en-us/azure/cosmos-db/graph-introduction)

#### 2.5.2 Design for cost, performance, data consistency, availability, and business continuity 
* [Azure Cosmos DB as a key value store – Cost overview](https://docs.microsoft.com/en-gb/azure/cosmos-db/key-value-store-cost)
* [Performance tips for Azure Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/performance-tips)
* [Tunable data consistency levels in Azure Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/consistency-levels)
* [How to distribute data globally with Azure Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/distribute-data-globally)
* [SLA for Azure Cosmos DB](https://azure.microsoft.com/en-us/support/legal/sla/cosmos-db/v1_0/)
* [Automatic regional failover for business continuity in Azure Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/regional-failover)
* [Automatic online backup and restore with Azure Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/online-backup-and-restore)

## 3. Design Networking Implementation (15-20%)  
 
### 3.1 Design Azure virtual networks 
#### 3.1.1 Design solutions that use Azure networking services: design for load balancing using [Azure Load Balancer](https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-overview) and [Azure Traffic Manager](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-overview)
#### 3.1.2 Define [DNS](https://docs.microsoft.com/en-us/azure/dns/dns-overview), DHCP, and [IP](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-ip-addresses-overview-arm) strategies 
#### 3.1.3 [Determine when to use Azure Application Gateway](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-load-balancing-azure)
#### 3.1.4 [Determine when to use multi-node application gateways, Traffic Manager and load balancers](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-load-balancing-azure)
 
### 3.2 Design external connectivity for Azure Virtual Networks
#### 3.2.1 Determine when to use Azure VPN, ExpressRoute and Virtual Network Peering architecture and design
* [Plan and design Azure Virtual Networks](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-vnet-plan-design-arm)
* [Planning and design for VPN Gateway](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-plan-design)
* [ExpressRoute](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-introduction)
* [Virtual network peering](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-peering-overview)

#### 3.2.2 [Determine when to use User Defined Routes (UDRs)](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-udr-overview)
#### 3.2.3 [Determine when to use VPN gateway site-to-site failover for ExpressRoute](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-howto-coexist-resource-manager)
 
### 3.3 Design security strategies 
#### 3.3.1 Determine when to use network virtual appliances
* [VPN Gateway FAQ](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-vpn-faq#V2VMulti)
* [About VPN devices and IPsec/IKE parameters for Site-to-Site VPN Gateway connections](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpn-devices)

#### 3.3.2 [Design a perimeter network (DMZ)](https://docs.microsoft.com/en-gb/azure/architecture/reference-architectures/dmz/secure-vnet-dmz?toc=%2Fazure%2Fvirtual-network%2Ftoc.json)

#### 3.3.3 Determine when to use a Web Application Firewall (WAF), Network Security Group (NSG), and virtual network service tunneling 
* [Overview of Application Gateway](https://docs.microsoft.com/en-us/azure/application-gateway/application-gateway-introduction)
* [Application Gateway FAQ](https://docs.microsoft.com/en-us/azure/application-gateway/application-gateway-faq)
* [Filter network traffic with network security groups](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-nsg)
* [Configure forced tunneling](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-forced-tunneling-rm)

### 3.4 Design connectivity for hybrid applications 
#### 3.4.1 Design connectivity to on-premises data from Azure applications using Azure Relay Service, Azure Data Management Gateway for Data Factory, Azure On-Premises Data Gateway, Hybrid Connections, or Azure Web App’s virtual private network (VPN) capability
#### 3.4.2 Identify constraints for connectivity with VPN
#### 3.4.3 identify options for joining VMs to domains 

## 4. Design Security and Identity Solutions (20-25%) 
 
### 4.1 Design an identity solution 
#### 4.1.1 Design AD Connect synchronization
* [What is Azure AD Connect?](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect) 
* [Azure AD Connect sync: Understanding the architecture](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsync-understanding-architecture) 
* [Azure AD Connect: Design concepts](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-design-concepts) 
* [Topologies for Azure AD Connect](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-topologies) 

#### 4.1.2 [Design federated identities using Active Directory Federation Services (AD FS)](https://docs.microsoft.com/en-gb/windows-server/identity/ad-fs/design/ad-fs-design-guide)
#### 4.1.3 [Design solutions for Multi-Factor Authentication (MFA)](https://docs.microsoft.com/en-us/azure/multi-factor-authentication/multi-factor-authentication-get-started)
#### 4.1.4 [Design an architecture using Active Directory on-premises and Azure Active Directory (AAD)](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/identity/considerations)
#### 4.1.5 [Determine when to use Azure AD Domain Services](https://docs.microsoft.com/en-us/azure/active-directory-domain-services/active-directory-ds-comparison)
#### 4.1.6 [Design security for Mobile Apps using AAD](https://docs.microsoft.com/en-gb/azure/active-directory/develop/active-directory-authentication-scenarios#native-application-to-web-api)

### 4.2 Secure resources by using identity providers  
#### 4.2.1 Design solutions that use external or consumer identity providers such as Microsoft account, Facebook, Google, and Yahoo
* [How to configure your App Service application to use Microsoft Account login](https://docs.microsoft.com/en-us/azure/app-service/app-service-mobile-how-to-configure-microsoft-authentication)
* [How to configure your App Service application to use Facebook login](https://docs.microsoft.com/en-us/azure/app-service/app-service-mobile-how-to-configure-facebook-authentication)
* [How to configure your App Service application to use Google login](https://docs.microsoft.com/en-us/azure/app-service/app-service-mobile-how-to-configure-google-authentication)
* [How to configure your App Service application to use Twitter login](https://docs.microsoft.com/en-us/azure/app-service/app-service-mobile-how-to-configure-twitter-authentication)

#### 4.2.2 [Determine when to use Azure AD B2C and Azure AD B2B](https://docs.microsoft.com/en-gb/azure/active-directory/active-directory-b2b-compare-b2c)

#### 4.2.3 Design mobile apps using AAD B2C or AAD B2B 

### 4.3 [Design a data security solution](https://docs.microsoft.com/en-us/azure/security/azure-security-data-encryption-best-practices)
#### 4.3.1 [Design data security solutions for Azure services](https://docs.microsoft.com/en-gb/azure/active-directory/active-directory-hybrid-identity-design-considerations-data-protection-strategy)

#### 4.3.2 Determine when to use Azure Storage encryption, Azure Disk Encryption, Azure SQL Database security capabilities, and Azure Key Vault
* [Azure Storage encryption](https://docs.microsoft.com/en-gb/azure/storage/common/storage-security-guide?toc=%2fazure%2fsecurity%2ftoc.json)
* [Azure Disk Encryption](https://docs.microsoft.com/en-gb/azure/security/azure-security-disk-encryption)
* [Azure SQL Database security capabilities](https://docs.microsoft.com/en-gb/azure/security/azure-database-security-best-practices)
* [Azure Key Vault](https://docs.microsoft.com/en-gb/azure/key-vault/key-vault-whatis)

#### 4.3.3 [Design for protecting secrets in ARM templates using Azure Key Vault](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-keyvault-parameter)

#### 4.3.4 [Design for protecting application secrets using Azure Key Vault](https://docs.microsoft.com/en-us/azure/architecture/multitenant-identity/key-vault)

#### 4.3.5 [Design a solution for managing certificates using Azure Key Vault](https://docs.microsoft.com/en-gb/rest/api/keyvault/certificate-scenarios)

#### 4.3.6 [Design solutions that use Azure AD Managed Service Identity](https://docs.microsoft.com/en-us/azure/app-service/app-service-managed-service-identity) 

### 4.4 Design a mechanism of governance and policies for administering Azure resources  
#### 4.4.1 [Determine when to use Azure RBAC standard roles and custom roles](https://docs.microsoft.com/en-gb/azure/active-directory/role-based-access-control-what-is)
* [Built-in roles](https://docs.microsoft.com/en-gb/azure/active-directory/role-based-access-built-in-roles)
* [Custom roles](https://docs.microsoft.com/en-gb/azure/active-directory/role-based-access-control-custom-roles)

#### 4.4.2 Define an Azure RBAC strategy
#### 4.4.3 [Determine when to use Azure resource policies](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-policy)

#### 4.4.4 [Determine when to use Azure AD Privileged Identity Management](https://docs.microsoft.com/en-us/azure/active-directory/active-directory-privileged-identity-management-configure)

#### 4.4.5 [Design solutions that use Azure AD Managed Service Identity](https://docs.microsoft.com/en-us/azure/active-directory/msi-overview)

#### 4.4.6 [Determine when to use HSM-backed keys](https://docs.microsoft.com/en-us/azure/key-vault/key-vault-hsm-protected-keys)

### 4.5 Manage security risks by using an appropriate security solution 
#### 4.5.1 [Identify, assess, and mitigate security risks by using Azure Security Center, Operations Management Suite Security and Audit solutions, and other services](https://docs.microsoft.com/en-us/azure/security/azure-security-technical-capabilities)
* [Azure Security Center](https://docs.microsoft.com/en-gb/azure/security-center/security-center-intro)
* [Operations Management Suite](https://docs.microsoft.com/en-gb/azure/operations-management-suite/operations-management-suite-overview)

#### 4.5.2 [Determine when to use Azure AD Identity Protection](https://docs.microsoft.com/en-us/azure/active-directory/active-directory-identityprotection)

#### 4.5.3 [Determine when to use Advanced Threat Detection](https://docs.microsoft.com/en-us/azure/security/azure-threat-detection)

#### 4.5.4 [Determine an appropriate endpoint protection strategy](https://docs.microsoft.com/en-us/azure/security-center/security-center-install-endpoint-protection)
 
## 5. Design Solutions by using Platform Services (10-15%)  
 
### 5.1 Design for Artificial Intelligence Services 
#### 5.1.1 Determine when to use the appropriate [Cognitive Services](https://docs.microsoft.com/en-gb/azure/#pivot=products&panel=cognitive), [Azure Bot Service](https://docs.microsoft.com/en-us/bot-framework/azure-bot-service-overview), [Azure Machine Learning](https://docs.microsoft.com/en-in/azure/machine-learning/preview/overview-what-is-azure-ml), and other categories that fall under cognitive AI  

### 5.2 Design for IoT 
#### 5.2.1 Determine when to use [Stream Analytics](https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-introduction), [IoT Hubs](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-what-is-iot-hub), [Event Hubs](https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-what-is-event-hubs), real-time analytics, [Time Series Insights](https://docs.microsoft.com/en-us/azure/time-series-insights/time-series-insights-overview), [IoT Edge](https://docs.microsoft.com/en-us/azure/iot-edge/how-iot-edge-works), [Notification Hubs](https://docs.microsoft.com/en-us/azure/notification-hubs/notification-hubs-push-notification-overview), [Event Grid](https://docs.microsoft.com/en-us/azure/event-grid/overview), and other categories that fall under IoT 
* [Comparison of Azure IoT Hub and Azure Event Hubs](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-compare-event-hubs)
* [Comparing Apache Storm and Azure Stream Analytics](https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-comparison-storm)
* [Azure IoT Edge Github repository](https://github.com/Azure/iot-edge)
* [Enterprise push architectural guidance](https://docs.microsoft.com/en-us/azure/notification-hubs/notification-hubs-enterprise-push-notification-architecture)


### 5.3 Design messaging solution architectures 
#### 5.3.1 Design a messaging architecture 
#### 5.3.2 Determine when to use [Azure Storage Queues](https://docs.microsoft.com/en-gb/azure/storage/queues/storage-queues-introduction), [Azure Service Bus](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-fundamentals-hybrid-solutions), Azure Event Hubs, Event Grid, [Azure Relay](https://docs.microsoft.com/en-us/azure/service-bus-relay/relay-what-is-it), [Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview), and Azure [Logic Apps](https://docs.microsoft.com/en-gb/azure/logic-apps/logic-apps-what-are-logic-apps)
* [Storage queues and Service Bus queues - compared and contrasted](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-azure-and-service-bus-queues-compared-contrasted)
* [Choose between Azure services that deliver messages](https://docs.microsoft.com/en-us/azure/event-grid/compare-messaging-services)
* [Service Bus messaging](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview)
* [Choose between Flow, Logic Apps, Functions, and WebJobs](https://docs.microsoft.com/en-us/azure/azure-functions/functions-compare-logic-apps-ms-flow-webjobs)

#### 5.3.3 [Design a push notification strategy for Mobile Apps](https://docs.microsoft.com/en-us/azure/notification-hubs/notification-hubs-enterprise-push-notification-architecture)

#### 5.3.4 Design for performance and scale 
* [Service Bus Premium and Standard messaging tiers](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-premium-messaging)
* [Best Practices for performance improvements using Service Bus Messaging](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-performance-improvements)
 
### 5.4 Design for media service solutions 
#### 5.4.1 Define solutions using [Azure Media Services](https://docs.microsoft.com/en-us/azure/media-services/scenarios-and-availability), [video indexer](https://docs.microsoft.com/en-gb/azure/cognitive-services/video-indexer/video-indexer-overview), [video API](https://docs.microsoft.com/en-us/azure/cognitive-services/video-indexer/video-indexer-use-apis), [computer vision API](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/home), preview, and other media related services  

## 6. Design for Operations (10-15%)  
 
### 6.1 Design an application monitoring and alerting strategy
### 6.1.1 Determine the appropriate Microsoft products and services for monitoring applications on Azure
### 6.1.2 Define solutions for analyzing logs and enabling alerts using Azure Log Analytics
### 6.1.3 Define solutions for analyzing performance metrics and enabling alerts using Azure Monitor
### 6.1.4 Define a solution for monitoring applications and enabling alerts using Application Insights 

### 6.2 Design a platform monitoring and alerting strategy
#### 6.2.1 Determine the appropriate Microsoft products and services for monitoring Azure platform solutions
#### 6.2.2 Define a monitoring solution using Azure Health, Azure Advisor, and Activity Log
#### 6.2.3 Define a monitoring solution for Azure Networks using Log Analytics and Network Watcher service
#### 6.2.4 Monitor security with Azure Security Center 

### 6.3 Design an operations automation strategy 
#### 6.3.1 Determine when to use Azure Automation, Chef, Puppet, PowerShell, Desired State Configuration (DSC), Event Grid, and Azure Logic Apps
#### 6.3.2 Define a strategy for auto-scaling
#### 6.3.3 Define a strategy for enabling periodic processes and tasks 
 
 
