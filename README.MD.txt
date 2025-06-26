# 🔐 Feedback-friend

This project is a mock **User Management Web Application** enhanced with essential security practices as part of a cybersecurity internship. It focuses on identifying vulnerabilities and implementing standard defenses such as input validation, password hashing, secure authentication, and proper logging.

---

## 📌 Project Goals

- Detect common web application vulnerabilities (XSS, SQL Injection, weak password storage)
- Apply industry best practices for web security
- Perform basic penetration testing
- Enable logging for monitoring and incident tracking

---

## 🚧 Key Security Features

- ✅ **Input Validation** using `validator.js` to sanitize user input
- ✅ **Password Hashing** with `bcrypt` (salting + hashing)
- ✅ **Token-Based Authentication** using JWT (stateless, secure)
- ✅ **Security Headers** added (via Helmet): `Content-Security-Policy`, `X-Frame-Options`, etc.
- ✅ **HTTPS** enforced in final deployment
- ✅ **Logging** integrated using `winston` for error and authentication tracking
- ✅ **Penetration Testing** with Nmap: no vulnerable services or ports found

---

## ✅ Final Security Checklist

- [x] Input validation  
- [x] Secure password hashing  
- [x] HTTPS enabled  
- [x] Proper logging (Winston)  
- [x] Security headers configured  
- [x] Token-based authentication  

---

## 🧪 Test Results

- ❌ XSS: Blocked after sanitization  
- ❌ SQL Injection: Blocked after validation  
- ✅ All authentication and profile features remained functional  

---

## 📁 Files

- `checklist.txt` – summary of security features and test results  
- `server.js` / `auth.js` – main application files with implemented security measures  
- `README.md` – project documentation

---

## 📎 GitHub Repository

🔗 https://github.com/lakeshkumar026/Feedback-friend
---

## 🎓 Intern Experience

> “Through this internship, I gained practical skills in identifying and securing web application vulnerabilities, preparing me for real-world cybersecurity challenges.”

---

## 📅 Submitted by:
**Lakesh Kumar (DHC-1390)**  
**Date:** 26 June 2025
