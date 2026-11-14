# Security Policy

## About This Project

This repository is an independently maintained fork of the Chatwoot Community Edition, initially based on version `v4.19.1`.

It is not affiliated with, endorsed by, or officially supported by Chatwoot Inc.

Security fixes from the upstream Chatwoot project may be incorporated into this fork, alongside fixes and improvements specific to this repository.

## Supported Versions

Security updates are provided on a best-effort basis.

| Version | Supported |
|---|---|
| Latest published release of this fork | ✅ Best effort |
| Older releases | ❌ |
| `main` (development) | ⚠️ Not guaranteed stable |

Until the first release of this fork is published, no version is designated as production-supported.

Users running this project in production are encouraged to keep their installations updated and follow upstream Chatwoot security advisories.

## Reporting a Vulnerability

If you discover a security vulnerability, please report it privately.

**Preferred reporting method:**

1. Navigate to the **Security** tab of this repository.
2. Open **Advisories**.
3. Select **Report a vulnerability**.
4. Provide the relevant technical details.

This reporting method requires GitHub Private Vulnerability Reporting to be enabled.

If private reporting is unavailable, please open a GitHub issue requesting a private contact method, without disclosing vulnerability details.

**Do not publicly disclose vulnerabilities through GitHub Issues, Discussions, Pull Requests, or social media before coordinated disclosure.**

### What to Include

When submitting a report, please provide:

- A description of the vulnerability.
- The affected version or commit.
- Steps to reproduce the issue.
- The potential security impact.
- A proof of concept, if available.
- Any recommended mitigations.

Please avoid including production credentials, real customer information, or other sensitive data.

## Security Scope

We are particularly interested in vulnerabilities involving:

- Authentication and authorization bypasses.
- Privilege escalation.
- Cross-account data exposure.
- SQL injection.
- Cross-site scripting (XSS).
- Server-side request forgery (SSRF).
- Remote code execution.
- Unauthorized access to conversations, contacts, or attachments.
- Insecure API endpoints.
- Sensitive information disclosure.
- Security vulnerabilities introduced by modifications to the upstream Community Edition.

Security testing must be performed only against environments you own or are explicitly authorized to test.

Please do not test vulnerabilities against third-party or production installations without authorization.

## Vulnerability Handling

Security reports will be reviewed on a best-effort basis.

When a vulnerability is confirmed, maintainers may:

1. Investigate the issue and determine its impact.
2. Develop and test a fix.
3. Coordinate disclosure with the reporter.
4. Publish a security advisory when appropriate.
5. Release a patched version.

No specific response or resolution time is guaranteed.

This project does not currently operate a bug bounty program.

## Upstream Security Issues

This fork is based on the Chatwoot Community Edition.

If a vulnerability also affects the original Chatwoot project, reporters are encouraged to notify the upstream maintainers through their official private security reporting process.

Security issues introduced specifically by this fork should be reported here.

Reporting an issue to the upstream project does not automatically notify the maintainers of this fork.

## Disclaimer

This software is provided under the terms of its applicable licenses, without warranties or guarantees of security.

Users are responsible for securing their own deployments, infrastructure, credentials, and integrations.

Thank you for helping keep this project and its users safe.
