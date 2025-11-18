# 📧 Email Sender CLI Tool  
### My First JavaScript Project

This is my first JavaScript project — a **Command Line Email Sender** that allows you to send emails directly from the terminal using Node.js.  
The project uses **Nodemailer**, **Readline-Sync**, and **Chalk** to create a simple yet colorful and interactive CLI experience.

---

## 🚀 Features

- ✔ Send emails directly from your terminal  
- ✔ Supports up to **50 receivers at once**  
- ✔ Hidden password input for security  
- ✔ Colorful CLI interface using Chalk  
- ✔ Uses secure Gmail App Password  
- ✔ Beginner-friendly and easy to understand  

---

## 🛠 Technologies Used

- **Node.js**
- **Nodemailer**
- **Readline-Sync**
- **Chalk**

---

## 📦 Installation

### 1️⃣ Install Node.js  
Download from: https://nodejs.org/

---

### 2️⃣ Install required packages

```bash
npm install nodemailer readline-sync chalk

---

# 🔐 Create Gmail App Password (IMPORTANT)

Google does **not** allow you to use your normal Gmail password for apps.  
You MUST generate an **App Password**.

Follow these steps:

1. Go to **Google Account → Security**
2. Enable **2-Step Verification**
3. Open **App Passwords**
4. Select **Mail**
5. Select your device
6. Click **Generate**
7. Copy the 16-character password, example:


Use this password in the CLI tool when asked.

---

## ▶️ How to Run the Tool

Install dependencies:

```bash
npm install

node app.js
