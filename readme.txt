SecureAuthApp – Secure Registration & Login System
===================================================

 Project Description:
-----------------------
This project is a secure user authentication system built with HTML, inline JavaScript, and Firebase. 
It includes the following core features:

- User registration with password strength checker and reCAPTCHA
- Email verification before login
- Secure login with audit logging and brute-force protection
- Forgot password functionality using OTP email verification with expiry
- Dashboard with name, email display, password update, and logout
- Link expiry handling (for email and password reset)
- All JS and CSS are embedded directly in each HTML file for simplicity.

Folder Structure:
---------------------
/SecureAuthApp
  ├── login.html                # Login with audit logging + brute-force protection
  ├── register.html             # Registration with password strength + CAPTCHA
  ├── forgotpassword.html       # Secure password recovery using OTP and expiry
  ├── dashboard.html            # Logged-in user panel (edit name/email/pass)
  ├── readme.txt                # Project documentation
  └──  screenshots              # Screenshots for submission or demo

  Setup Instructions:
---------------------
1. Download or clone the entire project folder to your local machine.
2. Firebase is already configured in all HTML files. If using your own Firebase project, replace the `firebaseConfig` object in each HTML/JS file.
3. Google reCAPTCHA v2 is integrated in register.html. Ensure your site key is active in Google reCAPTCHA settings.
4. No backend is required  all logic is implemented using Firebase Authentication and Firestore.
5. You can deploy the project using Firebase Hosting or test locally by opening the HTML files in a browser (or using Live Server in VS Code).

Features Implemented:
-------------------
✔ Email verification on registration  
✔ CAPTCHA validation before account creation  
✔ Audit logging for login and password actions  
✔ Strong password enforcement via real-time strength meter  
✔ Brute-force protection (locks after 5 failed logins)  
✔ OTP-based password reset with expiration  
✔ Password history checks to prevent reuse  
✔ Dashboard for updating profile details  
✔ Clean and modern dark-themed UI

Authors:
---------
- Developed by Sabanam Poudel
- University of Sunderland, CET324 - Advanced Cybersecurity Assignment 2 (2024–25)

References:
--------------
- Saputra et al. (2025) – Password Strength via Zxcvbn
- Dinh & Hoang (2023) – CAPTCHA Security Review
- Kim et al. (2024) – Password Reuse Risk Study
- USENIX (2023) – Bcrypt Retrospective
- Almeida et al. (2024) – OTP Reset Flow Review
- Dayanand et al. (2024) – Audit Logging Justification

License:
---------
This project is for academic purposes only. Unauthorized use or distribution is prohibited.