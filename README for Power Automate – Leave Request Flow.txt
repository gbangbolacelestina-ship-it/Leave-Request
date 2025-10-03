# Leave Request Flow (Power Automate)

This project contains a **Power Automate flow** that automates leave request submissions and approvals.  
The flow integrates with Outlook, SharePoint, and Office 365 for full automation.

## 📌 Features
- Triggered when an employee submits a leave request
- Saves leave request details to **SharePoint**
- Sends email notifications via **Office 365 Outlook**
- Uses **Office 365 Users** to enrich employee data
- Can notify HR/Managers for approval

## ⚡ Connectors Used
- **Office 365 Outlook** → Sends and receives email notifications
- **SharePoint** → Stores leave requests
- **Office 365 Users** → Employee directory data

## 📂 Files in this Repository
- `LeaveRequestFlow.json` → Exported Power Automate flow definition
- `README.md` → Documentation

## 🚀 Future Enhancements
- Add multi-level approval (Manager → HR → Director)
- Automatic leave balance tracking
- Teams notifications for approvals/rejections
