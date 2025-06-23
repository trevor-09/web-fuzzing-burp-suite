# Web Fuzzing with Burp Suite 🔍

This project demonstrates how to analyze and manipulate HTTP requests using Burp Suite and test a vulnerable web application (DVWA) using fuzzing techniques.

---

## 📌 Project Overview

- Analyzed GET and POST requests in a test environment
- Used **Burp Suite** to intercept and modify login requests
- Performed input fuzzing using **Intruder tool**
- Observed server responses to malicious payloads
- Wrote a detailed report including screenshots and observations

---

## 🛠 Tools Used

- [Burp Suite](https://portswigger.net/burp)
- [DVWA - Damn Vulnerable Web Application](https://github.com/digininja/DVWA)
- Firefox / Burp Embedded Browser
- XAMPP (for local hosting)

---

## 📄 Final Report

📥 [Download PDF Report](./Web_Fuzzing_Report_AbhayRaj.pdf)

---

## 💡 What I Learned

- How HTTP requests work under the hood
- How ethical hackers intercept and analyze web traffic
- Basics of fuzzing and automated input testing
- Importance of tools like Burp Suite in cybersecurity

---

## 📷 Screenshots

### 📸 Screenshot 1: DVWA Login Page with Burp Intercepting POST Request
Shows the DVWA login form with Burp Suite capturing the login request to `/login.php`.  
![Screenshot 1](screenshots/Screenshot%202025-06-20%20195405.png)

---

### 📸 Screenshot 2: Burp Suite – Intercepted POST Request to Login
Displays the raw intercepted request with `username=test` and request body parameters.  
![Screenshot 2](screenshots/Screenshot%202025-06-20%20195546.png)

---

### 📸 Screenshot 3: Burp Suite Intruder – Payload Position and Payload List
Shows the configured position on the `username` field and the list of fuzzing inputs.  
![Screenshot 3](screenshots/Screenshot%202025-06-20%20200903.png)

---

### 📸 Screenshot 4: Intruder Attack Results
Displays the results of each payload sent via Intruder, showing status and length differences.  
![Screenshot 4](screenshots/Screenshot%202025-06-20%20200845.png)


## 📚 Status

✅ Completed – as part of the **Web Security Bootcamp by Devtown**  
📅 Submitted on **20 June 2025**  
🎓 Hands-on practical project focusing on HTTP requests, Burp Suite, and input fuzzing  
🛡️ All testing was done ethically in a controlled local environment using DVWA
