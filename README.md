# FUTURE_CS_01  
**Task 1 — Web Application Security Testing**  
Cyber Security Internship @ Future Interns  

---

##  About this Task
This is the first task of my Cyber Security Internship with **Future Interns**.  
I worked on a deliberately vulnerable web application (OWASP Juice Shop) to practice ethical hacking.  
The main goal was to identify common security flaws (SQL Injection, XSS, CSRF, etc.) and document them following **OWASP Top 10 standards**.  

---

##  Tools Used
- **Burp Suite (Community Edition)** → manual testing & intercepting requests  
- **OWASP ZAP** → automated scanning for vulnerabilities  
- **SQLMap** → SQL injection testing  
- **OWASP Juice Shop** → target environment  

---

##  Deliverables
- **[Security Report (PDF)](./Security_Report_Task1.pdf)** → findings + remediation steps  
- **Screenshots** → proof of vulnerabilities tested (`/screenshots/`)  
- **Logs** → outputs from ZAP scan (`/logs/`)  

---

##  Key Learnings
- Performed **web app penetration testing** in a controlled environment  
- Strengthened understanding of **OWASP Top 10 threats**  
- Gained experience in writing **professional-style security reports** with risk ratings  
- Learned how to **organize work in a GitHub portfolio**  

---

##  Repository Layout
FUTURE_CS_01/
│
├── README.md
├── Security_Report_Task1.pdf
│
├── screenshots/
│   ├── 01_app_home.png
│   ├── 02_zap_findings.png
│   ├── 03_burp_request.png
│   ├── 04_sql_injection.png
│   ├── 05_auth_success.png
│   ├── 06_auth_request.png
│   ├── 07_insecure_cookie.png
│   ├── 08_missing_headers.png
│   └── 12_report_cover.png
│
├── logs/
│   └── zap_report.pdf

---

 *This repo documents my work for **Task 1 — Web Application Security Testing** as part of my Cyber Security Internship at Future Interns.*




