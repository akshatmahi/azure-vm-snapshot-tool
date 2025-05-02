# Azure VM Snapshot Tool 🛡️

Automates Azure VM OS/Data disk snapshots across **multiple subscriptions** using PowerShell — complete with robust reporting and smart, ticket-based naming.

---

## 🚀 Features

- 🔁 Processes multiple Azure subscriptions automatically
- 💽 Creates snapshots for both OS and data disks
- 📄 Generates detailed CSV reports (Success, Failure, Not Found)
- 🏷️ Appends custom ticket IDs to snapshot names for traceability
- ✂️ Smart name truncation to stay within Azure name limits
- 📦 Clean and modular PowerShell design
- 🧪 Includes safety checks and status reporting

---

## 📂 File Structure

```plaintext
azure-vm-snapshot-tool/
│
├── Take-VMSnapshot.ps1        # Main automation script
├── vmnames.sample.txt         # Sample input file for VM names
├── .gitignore                 # Ignore logs and reports
└── README.md                  # This documentation
