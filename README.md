# Selkirk Paddle Borrow Program

A lightweight system for Selkirk Advocates and retail partners to track demo paddle borrowing, send automatic confirmation emails, and manage return reminders — all using Google Forms, Google Sheets, and Apps Script.

---

## 🔧 Key Features

- 📋 **Simple Borrower Intake Form**
  - Collects name, contact info, paddle model, and a photo
- 📧 **Automatic Confirmation Emails**
  - Sent to the borrower with paddle info and due date
- ⏰ **Return Reminders**
  - Automatic follow-up emails when the paddle is due back
- 📊 **Live Shareable Database**
  - Google Sheet tracks borrow/return status for each paddle
- 🏷️ **Supports Selkirk Models**
  - Includes Amped, Vanguard, Halo, Luxx, and more

---

## 🔗 Live Demo Links

- **Google Form (Borrower Intake)**  
  [View Form](https://docs.google.com/forms/d/1PDFE01enWWjNBEoeODmIHI1TAGAX23UoupHElVktWbY/edit)

- **Google Sheet (Data Tracker)**  
  [View Sheet](https://docs.google.com/spreadsheets/d/1usoduC7jnMRhnzk_mCh6siAjFDxMXn5ZgqCMP7C2BJQ/edit)

---

## 🚀 How It Works

1. **Borrower fills out the form**
   - Submits contact info, photo, and paddle selection
2. **Script triggers on submission**
   - Sends a branded confirmation email with return details
3. **Admin views responses in Google Sheet**
   - Tracks borrowed paddles, return dates, and contacts
4. **Reminder emails auto-send**
   - If not returned on time, borrower gets a follow-up

---

## 📁 Files in This Repo

| File | Description |
|------|-------------|
| `paddleBorrow.gs` | Google Apps Script to handle email automation |
| `Paddle_Borrow_Form.pdf` | Snapshot of the Google Form |
| `sample-borrower-data.csv` | Example of form response sheet |
| `/screenshots/` | Visuals of form, sheet, and emails |
| `README.md` | This file |
| `LICENSE` | (Optional) MIT License for public use |

---

## 📬 Example Email Output

> _Thank you for borrowing a Selkirk paddle! Please return it by June 9th. Let us know if you have any questions._  
> _(Includes paddle image, Advocate contact, and return policy)_

---

## 🛠️ How to Set Up Your Own

1. **Make a copy** of the Form and Sheet
2. **Paste in the Apps Script** (`paddleBorrow.gs`)
3. **Set triggers** for form submission and time-based reminders
4. **Update your sender email** in the script
5. **Test with a mock borrower**

Need help setting this up? Contact [Tom Hincy](mailto:tshincy@gmail.com)

---

## 📜 License

This project is open-sourced under the MIT License. Use it freely, adapt it, and share improvements.

