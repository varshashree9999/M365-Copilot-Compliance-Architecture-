# M365 Copilot Compliance Architecture.

An enterprise-grade Microsoft 365 solution integrating secure 
AI grounding, automated document routing, and data governance 
controls using Copilot Studio, Power Apps, Power Automate, and 
Microsoft Purview.

## 🚀 Project Overview
This project demonstrates the implementation of a secure enterprise
AI environment.It combines custom AI assistant grounding with strict 
compliance policies and automatedworkflow routing to ensure secure 
handling of internal company documents.

## 🛠️ Key Technologies Used
* **Microsoft Copilot Studio**: Built and deployed the custom
  *HR Policy Guide* AI agent grounded with verified organizational
  knowledge sources.
* **Power Apps (Canvas App)**: Designed an interactive interface for
* employees and managers to manage document submissions and requests.
* **Power Automate**: Configured automated cloud flows for real-time
* document routing, notifications, and approval logic.
* **SharePoint Online (`Company-Hub`)**: Served as the centralized
* backend repository and data source for organizational files and metadata.
* **Microsoft Purview**: Implemented sensitivity labels
*  (`Restricted - Executive Only`) and Data Loss Prevention (DLP) policies to
*  secure confidential data and prevent unauthorized AI access.

## 📂 Key Features & Architecture
1. **Secure AI Grounding**: The **HR Policy Guide** agent answers
2.  employee queries exclusively based on authorized company policies,
3.   minimizing hallucinations.
4. **Automated Document Workflows**: Seamless integration between
5.  Power Apps and SharePoint via Power Automate ensures streamlined
6.  document tracking and status updates.
7. **Data Governance & Compliance**: Enforced strict security barriers and
8.  Purview sensitivity labels to protect sensitive executive-level content.

---
