# 🚀 Microsoft Copilot Labs – Dynamics 365 Business Central

This repository contains hands-on lab exercises demonstrating how Microsoft Copilot enhances productivity, automation, and decision-making inside.

These labs walk through real-world business scenarios across Purchasing, Sales, Finance, Inventory, e-Documents, and Marketing Content Creation.

---

## 📌 Repository Overview

This lab collection is designed for:

- Functional Consultants  
- ERP Administrators  
- Finance Teams  
- Sales Teams  
- Business Users  
- Microsoft Certification Learners  

Each lab provides structured, step-by-step implementation guidance using Copilot features within Business Central.

---

# 📚 Lab Modules

---

## 🧾 Lab 1 – Accelerate Purchase Order Review with Copilot

### 🎯 Objective
Use Copilot to analyze, summarize, sort, group, and autofill purchase order data.

### 🔍 Key Topics Covered
- Activating Business Central Trial
- Creating Sandbox Environment
- Verifying Copilot & Agent Capabilities
- Analyze List using Copilot
- Grouping & Sorting Purchase Orders
- Autofill Purchase Order Fields
- Chat with Copilot

### ✅ Skills Gained
- AI-driven purchase analysis  
- Conversational ERP interaction  
- Faster purchase order review  
- Intelligent data grouping  

---

## 💰 Lab 2 – Vendor Invoice Automation for Finance Teams

### 🎯 Objective
Automate vendor invoice processing using the Payables Agent.

### 🔍 Key Topics Covered
- Activate Payables Agent
- Configure Mailbox Integration
- Process Invoice Emails
- Review AI-Generated Purchase Drafts
- Post Purchase Invoices
- Generate & Modify Number Series using Copilot

### ✅ Skills Gained
- End-to-end AP automation  
- Reduced manual invoice entry  
- Controlled AI-assisted posting  
- Smart number series management  

---

## 📦 Lab 3 – Improve Order Fulfillment with AI Suggestions

### 🎯 Objective
Improve inventory availability and customer satisfaction using substitute item suggestions and AI summaries.

### 🔍 Key Topics Covered
- Suggest Substitute Items
- Confidence Score Filtering
- Remove Low-Confidence Matches
- Insert Medium/High-Confidence Items
- Summarize Purchase Orders

### ✅ Skills Gained
- Inventory optimization  
- Faster purchasing review  
- AI-supported fulfillment decisions  
- Improved order accuracy  

---

## 📩 Lab 4 – Automating Sales Order Capture with Sales Agent

### 🎯 Objective
Automate customer inquiry handling and quotation generation.

### 🔍 Key Topics Covered
- Activate Sales Agent
- Configure Mailbox for Inquiries
- Process Customer Emails
- AI-Generated Quotation Draft
- Send Automated Responses

### ✅ Skills Gained
- Automated sales communication  
- Faster quotation turnaround  
- Reduced manual processing  
- Enhanced customer responsiveness  

---

## 📄 Lab 5 – Map E-Documents to Purchase Orders

### 🎯 Objective
Use Copilot to automatically match e-document lines with purchase order lines.

### 🔍 Key Topics Covered
- Generate Demo Data
- Review Linked Purchase Orders
- Auto-Match with Copilot
- Compare Manual vs Automatic Matching
- Save Final Mapping

### ✅ Skills Gained
- Automated document matching  
- Reduced procurement errors  
- Streamlined e-document workflows  
- Improved financial accuracy  

---

## ✍️ Lab 6 – AI-Powered Item Marketing Text Creation

### 🎯 Objective
Generate, refine, and finalize marketing text using Copilot.

### 🔍 Key Topics Covered
- Generate Draft Marketing Text
- Select Product Attributes
- Regenerate Suggestions
- Adjust Tone & Format
- Review & Finalize Content

### ✅ Skills Gained
- AI-assisted content creation  
- Brand-aligned messaging  
- Faster product documentation  
- Human-in-the-loop validation  

---

# 🛠️ Prerequisites

- Business Central Trial Environment  
- Admin Tenant Access  
- Sandbox Environment (Recommended: cronus_sandbox)  
- Contoso Demo Tool Data  
- Email Account (for Payables & Sales Agent testing)  

---

# 📋 Microsoft License Requirements

The following Microsoft licenses are required to complete the labs in this repository:

| License | Purpose | Required For |
|---------|---------|-------------|
| **Microsoft Dynamics 365 Business Central Essentials** or **Premium** | Core ERP platform with Copilot capabilities built-in | All Labs (1–6) |
| **Microsoft 365 (Business Standard or higher)** | Email integration for agent-based automation using Outlook | Lab 2 (Payables Agent), Lab 4 (Sales Agent) |

### 🔑 Key Licensing Notes

- **Business Central Trial**: A free 30-day trial is available at [microsoft.com/dynamics-365/products/business-central](https://www.microsoft.com/en-us/dynamics-365/products/business-central). No paid license is required to start.
- **Copilot Features**: Microsoft Copilot capabilities (AI analysis, Payables Agent, Sales Agent, e-document mapping, marketing text generation) are **built into Business Central** and are included with a standard Business Central Essentials or Premium license — **no separate Copilot license is required**.
- **Email Account**: A personal or organizational email account (e.g., Outlook) is needed to simulate vendor invoices (Lab 2) and customer inquiries (Lab 4). Any working email account is sufficient.
- **Admin Tenant**: A Microsoft Entra ID (formerly Azure Active Directory) tenant with admin privileges is needed to activate Business Central and manage environments.

---

# 🌐 Azure Portal Access

**Yes — users need access to the Azure Portal** as part of the initial lab environment setup.

### Why Azure Portal Access Is Needed

| Reason | Details |
|--------|---------|
| **Microsoft Entra ID Authentication** | Users sign in to Business Central using their Microsoft Entra ID (formerly Azure Active Directory) credentials, which are managed through the Azure Portal. |
| **Initial Environment Setup** | The getting-started guide directs users to sign into the Azure Portal to verify credentials and access the lab environment. |
| **Admin Center Access** | The Business Central Admin Center (used to create sandbox environments) is accessed via Microsoft Entra ID-authenticated accounts. |

### What Azure Portal Is NOT Required For

The core lab exercises (Labs 1–6) are performed entirely within:

- **Microsoft Dynamics 365 Business Central** portal
- **Business Central Admin Center** (accessible from within Business Central)
- **Microsoft Outlook** (for email testing in Labs 2 and 4)

> **Note:** Direct configuration of Azure resources (e.g., Azure VMs, Azure services) is **not** required for any lab exercise. Azure Portal access is only needed for initial sign-in and identity verification.

---

# 🧠 Copilot Capabilities Demonstrated

- Analyze List  
- Group & Aggregate Data  
- Chat-Based Queries  
- Autofill Suggestions  
- Confidence Scoring  
- Email-to-Document Automation  
- Number Series Generation  
- AI Content Drafting  
- Document Summarization  

---

# 🏗️ Environment Setup Overview

| Component | Purpose |
|------------|----------|
| Production Environment | Core functional scenarios |
| Sandbox Environment | Demo data testing |
| Payables Agent | Invoice automation |
| Sales Agent | Inquiry automation |
| Copilot Engine | AI-powered assistance |

---

# 📈 Business Value

By completing these labs, users will understand how Copilot:

- Accelerates purchasing workflows  
- Automates accounts payable processes  
- Enhances sales responsiveness  
- Improves inventory decision-making  
- Simplifies e-document processing  
- Speeds up marketing content creation  

---

# 🎓 Learning Outcome

After completing all labs, participants will be able to confidently:

- Configure Copilot-powered agents  
- Automate purchasing and sales workflows  
- Use AI prompts effectively inside Business Central  
- Review and validate AI-generated business documents  
- Implement AI features in real-world ERP scenarios  

---

## 📌 License

This repository is intended for educational and demonstration purposes.

---

**Author:** Vishwjeet Singh Chauhan  
**Platform:** Microsoft Dynamics 365 Business Central  
**Focus Area:** Copilot for ERP Automation