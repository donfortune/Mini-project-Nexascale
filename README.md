# 🛡️ DevSecOps Mini Project: CI Pipeline for OWASP Juice Shop (Using Jenkins)

## 📌 Project Overview

This project guides you to build a **Jenkins-based CI pipeline** to analyze the [OWASP Juice Shop](https://github.com/juice-shop/juice-shop) for security vulnerabilities using industry-standard SAST tools and export the results to **DefectDojo**.

---

## 🎯 Objectives

1. **Clone** the OWASP Juice Shop application.
2. **Set up a CI/CD pipeline in Jenkins** to run on code changes.
3. **Run SAST scans** with:
   - 🔐 [Gitleaks](https://github.com/gitleaks/gitleaks) – secret detection
   - 🧠 [Semgrep](https://semgrep.dev/) – static code analysis
   - 🔎 [NJSSCAN](https://github.com/ajinabraham/njsscan) – scan Node.js dependencies
4. **Generate reports** from each tool (preferably in JSON or SARIF format).
5. **Programmatically upload scan results to DefectDojo** via its REST API.


---

## 🧠 Skills You’ll Gain

- Jenkins Pipeline (Scripted/Declarative)
- Static Application Security Testing (SAST)
- Git and CI/CD automation
- Parsing and handling security scan outputs
- Secure API interaction with DefectDojo
- Managing Jenkins credentials securely

---

## 📦 Deliverables

- ✅ GitHub repo or project zip file
- ✅ Jenkinsfile with all scan stages
- ✅ Sample JSON/SARIF reports from each tool
- ✅ Script to upload to DefectDojo 
- ✅ Screenshots of Jenkins pipeline stages


---

.

---

## 🧰 Tools and Resources

| Tool       | Description                         | Link |
|------------|-------------------------------------|------|
| Juice Shop | Vulnerable app for testing          | https://github.com/juice-shop/juice-shop |
| Jenkins    | CI/CD tool                          | https://www.jenkins.io/ |
| Gitleaks   | Secrets scanner                     | https://github.com/gitleaks/gitleaks |
| Semgrep    | Static code analysis                | https://semgrep.dev/ |
| NJSSCAN    | Node.js SAST scanner                | https://github.com/ajinabraham/njsscan |
| DefectDojo | Security orchestration and reporting | https://demo.defectdojo.org/api/v2/doc/ |

---

## 🕒 Deadline

📅 **Submit by:** _[24/05/2025]_

---
