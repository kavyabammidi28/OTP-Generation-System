# 🔐 OTP Verification System

A web-based application that securely generates and verifies **One-Time Passwords (OTP)** using email. Ideal for integrating authentication in login or registration flows.

## 🌟 Features
- 📩 Email-based OTP generation
- ⏳ OTP expiry logic (e.g., 5 minutes)
- 🔁 Retry/Resend OTP option
- 🧑 User registration with SQLite
- 📬 Email sending using `smtplib`
- 🧪 OTP validation on frontend
- 🔐 Basic security measures

## ⚙️ Tech Stack
- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite
- **Email**: smtplib (Gmail SMTP server)

## 🧪 Demo Workflow
1. User registers with email
2. System generates a 6-digit OTP
3. OTP sent to user's email
4. User enters OTP to verify
5. Verified users stored in the database

## 📁 Folder Structure
