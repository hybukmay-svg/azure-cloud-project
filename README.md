# azure-cloud-project
Azure Governance and Resource Organization in Microsoft Azure
Introduction
Cloud governance refers to the processes, policies, and controls used to manage cloud resources effectively. Microsoft Azure provides governance tools that help organizations control costs, manage access, enforce standards, and organize resources efficiently.
This project demonstrates the implementation of Azure governance principles through the use of subscriptions, resource groups, role-based access control (RBAC), Azure Policy, tagging, naming conventions, and cost management.
Project Objectives
The objectives of this project are to:
Understand the role of Azure Subscriptions.
Organize resources using Resource Groups.
Implement Role-Based Access Control (RBAC).
Apply Azure Policy for governance.
Implement resource tagging strategies.
Apply naming conventions for resources.
Monitor and control cloud costs using budgets and alerts.
Azure Hierarchy
Azure resources are organized in a hierarchical structure as shown below:
Azure Subscription
├── RG-Networking-Dev
├── RG-WebApp-Dev
└── RG-Database-Dev
The subscription serves as the billing and management boundary, while Resource Groups are used to organize related resources for easier administration.
Governance Strategy
Role-Based Access Control (RBAC)
RBAC was used to manage access to Azure resources. The following built-in roles were studied:
Owner
Contributor
Reader
Azure Policy
Azure Policy was used to enforce organizational standards by ensuring resources comply with predefined rules.
Naming Convention
The following naming convention was adopted:
ResourceType-Project-Environment-Number
Examples:
RG-WebApp-Dev
VNET-SchoolApp-Dev
NSG-SchoolApp-Dev
HybukDB
Tagging Strategy
The following tags were applied to resources:
Tag Name
Value
Environment
Development
Department
ICT
Owner
Ibukun

Tags improve resource tracking, governance, and cost management.

Architecture Diagram
└── HybukDBAzure Subscription
│
├── RG-Networking-Dev
│ ├── VNET-SchoolApp-Dev
│ └── NSG-SchoolApp-Dev
│
├── RG-WebApp-Dev
│ ├── hybukapp-web-001
│ └── hybukstorageappdev001
│
└── RG-Database-Dev

Screenshots
Attached is the screenshots of the followings with a brief caption:
Azure Subscription Overview
Resource Groups Page
RBAC (IAM) Configuration
Azure Policy Assignment
Resource Tags
Cost Analysis Dashboard
Budget Creation Page
Budget Alert Configuration
App Service Deployment
SQL Database Deployment

Challenges Encountered
1.Some Azure services were not available in the selected region.
Solution: Alternative services and supported regions were selected.
2.Certain resources required globally unique names.
Solution: Unique identifiers were added to resource names.
3.Understanding Azure governance concepts.
Solution: Microsoft Learn documentation and practical exercises were used to improve understanding.
Conclusion
This project provided practical experience in Azure governance and resource organization. Azure Subscriptions, Resource Groups, RBAC, Azure Policy, tagging, naming conventions, and cost management tools were successfully explored and implemented. The project demonstrated how governance practices help improve security, cost control, operational efficiency, and scalability within a cloud environment.
