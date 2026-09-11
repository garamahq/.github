# Security Policy

We take the security of our applications, open-source frameworks, and infrastructure tools seriously. We appreciate the security community's assistance in identifying vulnerabilities and disclosing them in a responsible, coordinated manner.

## Supported Versions

We provide security updates for the latest major versions of all active Garama HQ repositories.

| Project | Supported Version | Status |
| :--- | :--- | :--- |
| **bedrock-forge** | `>= 1.0.x` | :white_check_mark: Active |
| **cloudmesh** | `>= 1.0.x` | :white_check_mark: Active |
| **server-foundation** | `>= 1.0.x` | :white_check_mark: Active |
| **wp-secure-guard** | `>= 1.0.x` | :white_check_mark: Active |
| **gemeni-key-rotator** | `>= 1.0.x` | :white_check_mark: Active |
| All other utilities/templates | Latest release only | :warning: Best-effort |

## Reporting a Vulnerability

**Please do not open public issues for security vulnerabilities.**

If you discover a potential vulnerability, please report it through one of the following channels:

1. **GitHub Private Vulnerability Reporting:** Navigate to the "Security" tab of the specific repository and click **Report a vulnerability** to open a private advisory draft. This is our preferred channel as it enables secure encrypted coordination.
2. **Email:** Contact our security team directly at [security@garama.ly](mailto:security@garama.ly) (or [hello@garama.ly](mailto:hello@garama.ly)).

### What to Include in a Report

To help us triage, reproduce, and resolve the vulnerability effectively, please provide:
* A clear description of the vulnerability and its potential security impact.
* Step-by-step reproduction instructions (including proof-of-concept scripts or payload examples where applicable).
* Environment details (operating system, runtime versions, configuration flags).

### Our Response Process

* **Acknowledgment:** We will acknowledge receipt of your vulnerability report within 48 hours.
* **Assessment:** We will investigate and verify the vulnerability, requesting additional context if needed.
* **Fix & Disclosure:** Once a fix is verified, we will coordinate release deployment and publish an advisory. We aim to remediate critical vulnerabilities within 30 days of report verification.
* **Attribution:** With your consent, we will credit your responsible disclosure in release notes and security bulletins.
