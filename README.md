# Comparator

**A powerful Windows application for comparing files and folders.**

Comparator is a Windows desktop application designed to make comparing files and directories easier and more efficient.

This repository provides official, pre-built Windows releases of Comparator.

> **This is the official public distribution repository. The application source code is maintained separately in a private repository.**

---

## Download

Get the latest version of Comparator from the releases page.

**[Download the Latest Release](https://github.com/dgtechofficial/comparator-release/releases/latest)**

Alternatively, browse the available versions:

[View All Releases](https://github.com/dgtechofficial/comparator-release/releases)

### Available Downloads

| File | Description |
|---|---|
| `.zip` | Downloadable Windows application package |
| `.sha256` | SHA-256 checksum for file integrity verification |

Always download the latest release unless you specifically need an older version.

---

## Installation

1. Download the latest Windows ZIP package from the Releases page.
2. Extract the downloaded ZIP file.
3. Open the extracted folder.
4. Run the Comparator executable.
5. Follow any application-specific setup instructions.

No Python installation is required if you are using the packaged Windows application.

---

## Verify Your Download

Release packages include SHA-256 checksum files.

You can verify a downloaded ZIP using PowerShell:

```powershell
Get-FileHash .\Comparator.zip -Algorithm SHA256
```

Compare the resulting hash with the corresponding `.sha256` file provided with the release.

---

## Automatic Builds

Comparator releases are built automatically using GitHub Actions.

The publishing workflow:

- Runs automated tests.
- Builds the Windows application using PyInstaller.
- Prepares application licenses.
- Packages the application.
- Generates release checksums.
- Publishes the resulting distribution.

Builds are generated from the private source repository.

---

## System Requirements

- Windows 10 or Windows 11 (64-bit).
- No separate Python installation required for packaged releases.

Actual minimum hardware and Windows requirements may vary by version.

---

## Version Information

The latest published build version is available in the [`dist/VERSION`](dist/VERSION) file.

For version history and release notes, visit the [Releases](https://github.com/dgtechofficial/comparator-release/releases) page.

---

## Support & Issues

For bug reports, feature requests, or technical assistance, please use the repository's [Issues](https://github.com/dgtechofficial/comparator-release/issues) page.

When reporting a problem, include:

- Comparator version.
- Windows version.
- Steps to reproduce the issue.
- Screenshots or error messages, when applicable.

---

## License

Please refer to the license and notices included with each official distribution package.

---

**Comparator**  
Official Windows Distribution

© DGTech Official. All rights reserved.
