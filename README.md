# 📧 Personalized Email Automation

> An automated email communication workflow built with **n8n, Google Sheets, and Gmail**.

This project automates the process of sending personalized welcome emails to users whose information is stored in Google Sheets.

The workflow reads user records, processes them one by one, sends a customized HTML email, and updates the corresponding Google Sheets record after the email process.

---

## 📌 Project Overview

When a user submits a form, their information is often stored in a spreadsheet.

Normally, someone would have to:

1. Open the spreadsheet
2. Check the user information
3. Write a welcome email
4. Send the email
5. Update the record manually

This workflow automates these steps using **n8n**.

### Automated Process

```text
Google Sheets
      ↓
Read User Data
      ↓
Process Each User
      ↓
Personalized Email
      ↓
Gmail
      ↓
Update Google Sheets
