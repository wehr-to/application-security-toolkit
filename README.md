# 🧩 Application Security Toolkit

## 🎯 Purpose
This repo simulates and fixes real-world web vulnerabilities across Python (Flask, FastAPI) and Node.js applications. It also includes code scanning and review logic aligned with the OWASP Top 10.

## 🔐 What's Covered

### 🔥 Vulnerabilities (Simulated in Code)
- **XSS**: Reflected, stored, DOM-based
- **SQL Injection**: Parameter tampering in search/login
- **SSRF**: Proxy fetch endpoint abuse
- **RCE**: Template injection in Node
- **Broken Access Control**: IDOR, role misassignment

### 🛡️ Secure Patterns
- Escaping, input validation
- CSRF protection tokens
- Secure headers, method scoping
- Flask, FastAPI, and Node.js-specific hardening

### 🔎 Static + Manual Review
- Bandit, Semgrep, ESLint scanning demos
- Manual checklist with logic flaw examples
- Scanning vulnerable apps for training

## 📂 Ideal Use Cases
- Red + blue team AppSec training
- Secure coding workshops
- Manual + automated review demos

## ✅ To Do
- [ ] Add SSRF + DNS rebind lab
- [ ] Add GraphQL input fuzzing lab
- [ ] Build GitHub Actions pipeline to run Bandit & Semgrep

## 📄 License
MIT
