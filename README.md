# securify
WordPress Security Plugin

## Folder Structure
wp-security-plugin/ <br/>
├── wp-security-plugin.php       # Main Plugin File <br/>
├── includes/ <br/>
│   ├── class-security-enforcer.php    # Core Security Functions <br/>
│   ├── class-login-security.php       # Login and Password Features <br/>
│   ├── class-spam-protection.php      # Spam and URL Filtering <br/>
│   ├── class-file-integrity.php       # File Integrity Checks <br/>
│   ├── class-security-audit.php       # Security Audits <br/>
│   └── class-security-headers.php     # Security Headers <br/>
├── assets/ <br/>
│   ├── css/ <br/>
│   │   └── admin-style.css            # Admin Panel Styles <br/>
│   └── js/ <br/>
│       └── admin-scripts.js           # Admin Panel Scripts <br/>
└── views/ <br/>
    └── settings-page.php              # Settings Page Template <br/>
