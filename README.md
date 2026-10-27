# Medical Store Point of Sale - Official Releases 💊📦

Welcome to the official public releases and distribution repository for **Medical Store Point of Sale (POS) System**.

This repository hosts official installer releases, release notes, and the centralized update metadata (`version.json`) used by the desktop application's auto-update system.

---

## 🚀 Latest Release: v1.0.3

- **Download Installer:** [MedicalStorePOS_Setup_v1.0.3.exe](https://github.com/Codewithhaider29/Medical-Store-POS-System-release/releases/download/v1.0.3/MedicalStorePOS_Setup_v1.0.3.exe)
- **Direct Update Metadata:** [version.json](https://raw.githubusercontent.com/Codewithhaider29/Medical-Store-POS-System-release/main/version.json)
- **Release Date:** October 2026

---

## 📋 System Requirements
- **OS:** Windows 10 / Windows 11 (64-bit)
- **RAM:** Minimum 2 GB (4 GB recommended)
- **Disk Space:** 300 MB free space
- **Runtime:** .NET Desktop Runtime 8.0 (included / prompted on installation)

---

## 🔄 Auto-Update Configuration
The desktop application automatically checks this repository for newer versions. You can also configure the update URL in the desktop app under:
`Settings -> System -> Software Updates & Releases`

Set the update URL to:
```text
https://raw.githubusercontent.com/Codewithhaider29/Medical-Store-POS-System-release/main/version.json
```

---

## 🔒 Security & Verification
All official installers are verified using SHA-256 checksums listed in `version.json` and on each release tag.

To verify your downloaded installer in PowerShell:
```powershell
Get-FileHash -Path .\MedicalStorePOS_Setup_v1.0.3.exe -Algorithm SHA256
```
