# n8n Gmail Notification & Google Sheet Workflow

This repository contains an **n8n automation workflow** designed to streamline email notifications and data management using Gmail and Google Sheets.  
It ensures that both the client and the admin are instantly notified whenever a new form submission occurs, while also organizing data in a structured way.

---

## 🌟 Key Features

- **Automatic Form Submission Handling:**  
  Captures new form submissions and appends them to a Google Sheet for record keeping.

- **Conditional Filtering & Switching:**  
  Uses n8n's Filter and Switch nodes to handle different types of submissions automatically.

- **Dual Gmail Notifications:**  
  Sends Gmail notifications to both the client and the admin based on the submission type.

- **Merge Logic:**  
  Combines multiple paths to ensure all notifications are sent without duplication.

- **Structured & Scalable:**  
  Workflow is organized for easy modifications and future expansions.

---

## 🛠 Tools & Services Used

- **n8n** — Workflow automation platform  
- **Gmail API** — For sending notification emails  
- **Google Sheets** — For storing and organizing form data  

---

## 📂 Workflow Overview

1. **Form Submission Trigger:** Detects new entries from the form.  
2. **Append Row in Sheet:** Adds submission data to Google Sheets.  
3. **Filter Node:** Filters data based on custom conditions.  
4. **Switch Node:** Routes the flow depending on the submission type.  
5. **Gmail Notifications:** Sends emails to the client and admin.  
6. **Merge Node:** Combines paths to maintain a smooth flow.  
7. **Final Gmail Notification:** Sends a confirmation email or summary as needed.

*(Screenshot of the workflow is included in the `images` folder for reference.)*

---

## ⚡ How to Use

1. Import the workflow JSON file into your **n8n** instance.  
2. Connect your **Gmail** and **Google Sheets** accounts.  
3. Configure the email recipients (client & admin) and sheet ID.  
4. Activate the workflow.  
5. Test by submitting a sample form entry.

---

## 🔒 Notes

- API keys and personal data are **not included** for security reasons.  
- Ensure that the Google Sheet has appropriate permissions for writing rows.  
- This workflow is easily expandable for additional notification rules or other email recipients.

---

## ✅ Why This Workflow Is Useful

- Saves time by automating notifications and data entry.  
- Reduces human errors in tracking form submissions.  
- Professional setup suitable for client-facing automation projects.  

---

*This workflow demonstrates practical n8n automation skills and is a great addition to an AI/automation GitHub portfolio.*
