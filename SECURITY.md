# Security Policy

The OpenAN community takes security seriously. We appreciate your efforts to responsibly disclose any security vulnerabilities you find.

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

If you discover a security vulnerability in any OpenAN repository, please report it privately by emailing:

**security@lists.openan.dev**

Please include the following information in your report:

- A description of the vulnerability
- Steps to reproduce the issue
- The potential impact of the vulnerability
- Any suggested fixes or mitigations (if applicable)

## Response Process

After you submit a report, the OpenAN security team will:

1. Acknowledge receipt of your report within 3 business days.
2. Investigate and validate the vulnerability.
3. Work with you on a coordinated disclosure timeline.
4. Release a fix and publish a security advisory as appropriate.

We ask that you give us a reasonable amount of time to address the issue before making any public disclosure.

## Supported Versions

Security updates are provided for the latest release of each actively maintained OpenAN component. If you are running an older version, please upgrade to the latest release.

## Security Best Practices for Contributors

When contributing code, please follow these practices:

- Do not commit secrets, credentials, or API keys
- Use parameterized queries to prevent injection attacks
- Validate and sanitize all inputs
- Follow the principle of least privilege
- Keep dependencies up to date

## Contact

For general security questions or concerns, email **security@lists.openan.dev**.

For non-security issues, please use the standard [issue reporting process](CONTRIBUTING.md#reporting-issues).
