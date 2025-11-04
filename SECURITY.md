# 🔐 Security Policy — CustomDLL NextGoPos

## Supported Versions

The following versions are actively maintained and receive security updates and patches.  
Versions marked ❌ have reached end-of-support (EoS).

| Version | Supported          | Notes |
| -------- | ------------------ | ------ |
| 5.1.x    | ✅ Active Support  | Current stable build — security-patched monthly |
| 5.0.x    | ❌ End of Support  | Upgrade required — unpatched vulnerabilities possible |
| 4.0.x    | ✅ LTS Support     | Critical fixes only until Q4 2025 |
| < 4.0    | ❌ Deprecated      | No maintenance; insecure for production use |

---

## Reporting a Vulnerability

If you discover a security issue, **do not open a public GitHub issue**.

Please report it responsibly to the Monarck Security Team:

📧 **security@monarck.net**  
🔗 [Wiki – Custom DLL NextGo](https://github.com/michael-lindor/Custom-DLL-NexgoPost/wiki/Wiki-Custom-DLL-NextGo)

Include:
- Detailed description of the vulnerability  
- Affected version(s)  
- Steps to reproduce  
- Potential impact and suggested mitigation

### Response Timeline
| Action | Timeframe |
| ------- | ---------- |
| Acknowledgement | Within 48 hours |
| Initial Assessment | Within 3 business days |
| Patch or Advisory | Within 5–10 business days (critical), or scheduled for next release cycle |

---

## Security Commitments

- **No Secrets in Code:** All credentials are managed via secure environment variables.  
- **Integrity Verification:** DLL builds are signed and SHA-512 hashed before release.  
- **TLS 1.2+ Required:** All outbound and remote connections must use secure transport.  
- **Audit Logging:** Transactions and errors are logged with timestamps and checksums.  
- **Secure Supply Chain:** Only verified Monarck repositories are used for build dependencies.  

---

## Responsible Disclosure

We highly appreciate coordinated disclosures.  
Researchers who follow this policy and report vulnerabilities responsibly may be publicly credited in release notes.

© 2025 Monarck / Prozs — All rights reserved.  
Part of the **NextGo POS Security and Compliance Program**.
