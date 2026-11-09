# Document Converter for Windows: releases

Installers for **Document Converter** by [Pumpkin Business Services](https://pumpkin.cloud). It turns bank and credit card statement PDFs into Excel and CSV, and checks every statement against its own printed balances and totals.

This repository holds releases only (installers and release notes). The program's source code is not here.

## Download

Get the latest `DocumentConverter-Setup-<version>.exe` from **[Releases](https://github.com/Pumpkin-Apps/document-converter-releases/releases/latest)** and run it. It installs for the current user without an admin prompt, on Windows 10 or 11 (64-bit).

Installed copies check here for updates (at most once a day, and with "Check for updates" on the Help tab) and offer to install new versions. An update is installed only if it matches its published SHA-256 checksum.

To check a download yourself, compare its checksum with the `.sha256` file published next to it:

```powershell
Get-FileHash .\DocumentConverter-Setup-<version>.exe
```

## Questions

aaron@pumpkin.cloud · [pumpkin.cloud](https://pumpkin.cloud)
