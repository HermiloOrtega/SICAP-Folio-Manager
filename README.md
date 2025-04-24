# 📦 SICAP Folio Manager

## 🧭 Overview
**SICAP Folio Manager** is a Windows application developed using C# and SQL Server. It is designed for project coordinators, project managers, and project administrators to generate and manage unique serial numbers (folios) for contracts. Access to the tool is secured via a login system with encrypted credentials and communications, ensuring that only authorized users can use the application.

### Home screen
![Screenshot](./assets/1.png) <!-- Replace with your image path -->

## 💡 Idea & Concept
The primary objective of SICAP Folio Manager is to streamline the process of generating serial numbers for various contracts within the organization.

It supports two types of contracts:
- **Administrative Contracts:** Prompts for a contract number and auto-fills key contract information (description, user, financial plan, provider).
- **Standard Contracts:** Allows generation of a serial number without auto-populated data.

After contract verification, users can register new folios and use built-in search to retrieve records by serial number or contract details.

## ✨ Features & Functionality
- **Secure Login:** Encrypted login credentials and communication.
- **Dual Serial Number Creation:**
  - Admin contracts with auto-populated fields.
  - Standard contracts with direct serial number generation.
- **Registration:** Register new folios after confirmation.
- **Search:** Locate records using serial number or contract information.
- **Compact UI:** All core features accessible from a single screen.

## ⚙️ Tech Stack
- **Platform:** Windows Application
- **Programming Language:** C#
- **Database:** SQL Server

## 🏗 Architecture & Design
- Built with C# and SQL Server for secure contract data handling.
- Login and communication are fully encrypted.
- One-screen design for streamlined usage.
- Internal deployment, ensuring security and control.

## 🚀 Installation & Setup
- **Prerequisites:** Windows OS, .NET Framework, SQL Server
- **Deployment:** Installed internally on company network machines
- **Access:** Login required, encrypted and restricted to authorized users

> **Note:** Setup and maintenance are handled by internal IT.

## 🧑‍💻 Usage
1. Login securely.
2. Generate folio:
   - For admin contracts, enter contract number to auto-fill fields.
   - For standard contracts, proceed with direct generation.
3. Confirm and register the serial number.
4. Use search to locate and manage previous entries.

## 🔍 My Role & Contributions
- 💼 Full development using C# and SQL Server
- 🧱 Designed secure login and encryption
- 🐞 Built dual-path serial generation workflows
- 🤝 Created a unified, user-friendly interface

## 🧗 Challenges & Learnings
- Implemented robust encryption for access control.
- Developed auto-populating logic for admin contracts.
- Designed an intuitive, all-in-one interface.
- Strengthened skills in contract management workflows and secure application development.

## 📈 Future Enhancements
- Support more contract types.
- Add search filters and export/reporting features.
- Integrate with internal project systems for end-to-end contract lifecycle management.

## 🤝 Contributing
Internal tool — changes are made and maintained internally. Feedback can be directed to the project lead.

## 🪪 License
⚠️ License Notice  
This repository was originally published under the MIT License.  
As of April 22, 2025, the license has been changed to **CC BY-NC-ND 4.0**.  
See the LICENSE file for details.

## 🔗 Additional Resources
- **Related Systems:** Connects with internal project management tools.
- **Microsoft Relevance:** Strong alignment with Microsoft technologies (C#, SQL Server, secure WinForms development).