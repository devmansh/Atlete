# Security Policy

We take security seriously and strive to ensure that **Atlete** remains free from vulnerabilities or malicious injections.
---

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

Only the most recent stable versions are maintained with security updates.

---

## 🛡️ Security Best Practices

To protect this repository and its users, we follow these principles:

- 🔐 No hardcoded secrets (API keys, passwords, etc.)
- 🔍 Regular dependency updates and vulnerability scans
- ✅ Strict code reviews for all PRs, especially those affecting core logic or dependencies
- 🔒 Branch protection enabled on `main` and `release` branches
- ✨ GitHub Dependabot enabled for automatic security alerts
- 🛑 No use of unverified third-party scripts or binaries

---

## 🚨 Reporting a Vulnerability

If you discover a security issue, **please report it responsibly** instead of opening a public issue.


### 🔐 How to report:
- Send an email to: **[manojsharma.officialid@gmail.com]**
- Or file a private report via GitHub's [Security Advisories](https://docs.github.com/en/code-security/security-advisories/repository-security-advisories/creating-a-repository-security-advisory)

### 📬 What to expect:
- A response within **72 hours**
- Coordinated investigation and patching (if valid)
- Disclosure and credit (if applicable) only **after** the issue is resolved

---

## 🧪 Developers & Contributors: Secure Coding Guidelines

- Use latest python, django with security patches
- Avoid unsafe code (`unsafe { }`) unless absolutely necessary
- Sanitize all user inputs (avoid SQL injection, XSS)
- Do not disable security middleware (e.g., HTTPS redirection, CORS)
- Review `.gitignore` to ensure no secrets are committed
- Sign commits if possible (GPG)

---

## 📄 License

This repository is covered by the [MIT License](LICENSE), but security reports and communications are confidential.

---

> 🛡️ We are committed to keeping this project secure and clean. Thank you for your help in achieving that goal.

