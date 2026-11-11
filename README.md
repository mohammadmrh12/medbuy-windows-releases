# MedBuy Windows Releases

Public distribution channel for the Windows desktop application used by نظام مشتريات مستشفى الحبوبي (MedBuy).

This repository contains **binary installers and update metadata only**. The application source code, database schema, staff identities, PINs, and production data remain in the private source repository.

## Downloads

- Windows 64-bit (x64): [Latest installer](https://github.com/mohammadmrh12/medbuy-windows-releases/releases/latest/download/MedBuy-Windows-x64-Setup.exe)
- Windows 32-bit (x86): [Latest installer](https://github.com/mohammadmrh12/medbuy-windows-releases/releases/latest/download/MedBuy-Windows-x86-Setup.exe)
- Update manifest: [latest.json](https://github.com/mohammadmrh12/medbuy-windows-releases/releases/latest/download/latest.json)

The desktop updater checks the latest release, selects the matching architecture, verifies the installer SHA-256 digest, and asks the user before launching the installer.

Releases are generated from the private source repository's Windows build workflow.
