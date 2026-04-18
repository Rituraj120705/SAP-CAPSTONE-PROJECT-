# SAP-CAPSTONE-PROJECT-
Implementation of Procure-to-Pay (P2P) cycle in SAP MM, demonstrating end-to-end procurement process with integration of inventory and financial accounting.

🚀 Procure-to-Pay (P2P) Cycle in SAP MM
📌 Project Overview

This project explains the end-to-end Procure-to-Pay (P2P) process in SAP Materials Management (MM). The P2P cycle is a core business process in supply chain management that covers purchasing goods from vendors and making payments.

The project demonstrates how procurement activities are integrated with inventory management and financial accounting in SAP.


🎯 Problem Statement

Organizations need an efficient system to manage procurement, vendor transactions, and payments. Manual processes can lead to errors, delays, and lack of transparency.

This project addresses how SAP MM automates the Procure-to-Pay cycle, ensuring:

Accurate procurement tracking
Proper inventory management
Seamless financial integration

🏢 Business Scenario

ABC Pvt Ltd is a manufacturing company that procures raw materials from vendors to produce finished goods. The company uses SAP MM to manage procurement efficiently and ensure timely availability of materials.

🔄 Process Flow
Purchase Requisition → Purchase Order → Goods Receipt → Invoice Verification → Payment

🧩 Project Modules Used
SAP MM (Materials Management)
SAP FI (Financial Accounting)

📸 Process Steps
1️⃣ Purchase Requisition (ME51N)
Internal request to procure goods
2️⃣ Purchase Order (ME21N)
Formal order sent to vendor
3️⃣ Goods Receipt (MIGO)
Inventory updated after receiving goods
4️⃣ Invoice Verification (MIRO)
Vendor invoice is verified
5️⃣ Payment (F-53 / F110)
Vendor payment processed

💰 Accounting Entries
Goods Receipt:
Inventory A/c        Dr  
   To GR/IR A/c
Invoice Verification:
GR/IR A/c        Dr  
   To Vendor A/c
Payment:
Vendor A/c        Dr  
   To Bank A/c


📊 Advantages
Automation of procurement process
Improved accuracy
Transparency in transactions
Better vendor management
Integration with financial accounting

📂 Project Structure
/project-report
    ├── SAP_P2P_Project.docx
    ├── screenshots/
    ├── flowchart.png
    └── README.md

🛠️ Tools Used
SAP GUI (for process understanding)
Microsoft Word (documentation)
GitHub (version control & submission)

📌 Conclusion
The Procure-to-Pay (P2P) cycle in SAP MM provides an efficient and structured approach to procurement. It ensures seamless integration between purchasing, inventory, and finance, improving overall business efficiency.

👨‍💻 Author
Name: RITURAJ KUMAR
Course: B.Tech IT 6th Semester
College: KALINGA INSTITUTE OF INDUSTRIAL TECHNOLOGY(KIIT)
