# TryHackMe CTF & Room Writeups

This directory contains technical writeups, evidence artifacts, and attack chains for completed [TryHackMe](https://tryhackme.com/) rooms and Capture The Flag (CTF) challenges.

---

## 📂 Repository Structure

```text
CTF/
├── README.md
│
├── Hammer/
│   ├── README.md
│   └── screenshots/
│       ├── 01-nmap-port-scan.png
│       ├── 02-nmap-service-enumeration.png
│       ├── 03-ffuf-directory-enumeration.png
│       ├── 04-vendor-directory-listing.png
│       ├── 05-composer-jwt-version.png
│       ├── 06-phpmyadmin-error-disclosure.png
│       ├── 07-developer-note.png
│       ├── 08-hmr-directory-enumeration.png
│       ├── 09-exposed-error-log.png
│       ├── 10-recovery-timer-manipulation.png
│       ├── 11-recovery-code-found.png
│       ├── 12-password-reset.png
│       ├── 13-authenticated-dashboard.png
│       ├── 14-jwt-role-modification.png
│       ├── 15-admin-command-execution.png
│       └── 16-flag.png
│
└── sqlmap-challenge/
    ├── README.md
    └── screenshots/
        ├── 01-gobuster-directory-enumeration.png
        ├── 02-sql-injection-error.png
        ├── 03-database-enumeration.png
        ├── 04-table-enumeration.png
        ├── 05-current-database-user.png
        └── 06-flag-table-dump.png
```

---

## 🎯 Completed Rooms & Challenges

| Challenge / Room | Category | Core Vulnerability | Primary Tools | Writeup |
| :--- | :--- | :--- | :--- | :--- |
| **Hammer** | Web Application Security / Authentication | Rate-Limit Bypass (`X-Forwarded-For`), Password Reset Flaw, JWT Secret Exposure & Role Manipulation, RCE | Nmap, FFUF, Burp Suite, Python, JWT.io | [View Writeup](Hammer/README.md) |
| **SQLMap Challenge** | Web Security / CTF | SQL Injection (`view.php?id=1`) | Gobuster, Burp Suite, SQLMap | [View Writeup](sqlmap-challenge/README.md) |

---

## ⚠️ Disclaimer

All testing and activities documented in this repository were conducted in authorized, intentionally vulnerable lab environments provided by TryHackMe for educational and security training purposes.
