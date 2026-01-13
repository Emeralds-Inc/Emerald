# 🛡️ Security Policy

We take the security of the Lax programming language and its ecosystem seriously. Thank you for helping us keep Lax safe for students, developers, and industrial users.

## Supported Versions

Currently, we provide security updates for the following versions:

| Version | Supported          | Notes |
| ------- | ------------------ | ----- |
| **6.x.x** | :white_check_mark: | Current stable release (Lax Core) |
| < 6.0.0 | :x:                | Pre-release versions - Please upgrade |

> [!NOTE]
> As Lax is designed to be ultra-lightweight and run on legacy hardware, we prioritize fixes that prevent memory overflows and sandbox escapes.

## Reporting a Vulnerability

If you find a security vulnerability, please **do not open a public issue.** Use the following process instead:

### 1. How to report
Send an email to **[markd.voznyuk@gmail.com]** (or use the GitHub "Report a vulnerability" button if enabled). 
Include as much information as possible:
* A description of the vulnerability.
* Steps to reproduce (a small `.lx` script is ideal).
* The potential impact (e.g., system crash, unauthorized access).

### 2. What to expect
* **Acknowledgement:** We will respond to your report within **48–72 hours**.
* **Progress Updates:** We will keep you informed as we work on a fix.
* **Verification:** We may ask you to test the fix to ensure it fully resolves the issue.

### 3. Public Disclosure
Once a fix is ready and tested, we will release a new version and publicly credit you for the discovery (unless you prefer to remain anonymous). We ask that you wait for us to release the fix before sharing details publicly.

## Security Best Practices
When writing Lax scripts, remember:
* Lax is designed for simplicity. When integrating with C via interoperability, always validate inputs to prevent buffer overflows in the host environment.
* Always download Lax binaries or source code from our official repository.

---
*Thank you for supporting the security and stability of the Lax project!*
