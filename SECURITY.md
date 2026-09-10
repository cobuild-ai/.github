# Security Policy

## 🔒 cobuild-ai Security Commitment

All cobuild-ai projects are architected with a **privacy-first, on-device** philosophy. We take security seriously across all our repositories.

---

## 🛡️ Supported Versions

| Project | Version | Supported |
| ------- | ------- | --------- |
| deartalk-ai | 1.0.x | ✅ |
| skybrain | 0.1.x | ✅ |
| continuum | 0.1.x | ✅ |

---

## 🚨 Reporting a Vulnerability

If you discover a potential security vulnerability in any cobuild-ai project, please report it responsibly:

1. **Email:** Send details to `security@deartalk.ai` (or via [GitHub Security Advisory](https://docs.github.com/en/code-security/security-advisories)).
2. **Details to Include:**
   - The affected project and version.
   - Description of the vulnerability.
   - Steps to reproduce or proof-of-concept.
   - Any log captures or network packet inspection traces.
3. **Response Timeline:**
   - **Acknowledgment:** Within 48 hours.
   - **Patch Timeline:** Within 7 days.

---

## 🔐 Key Privacy Invariants

- **Zero External Network Traffic:** User data (keystrokes, text, audio) never leaves the local device.
- **Local Model Execution:** All AI inference runs strictly on-device (CPU/GPU/NPU/Metal).
- **No Telemetry:** We do not collect usage analytics or telemetry data.

---

## ⚠️ Out of Scope

- Issues in third-party dependencies (report to the upstream project).
- Social engineering attacks.
- Denial of service attacks.

Thank you for helping keep cobuild-ai safe! 🙏
