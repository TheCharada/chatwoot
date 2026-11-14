# Upstream Information

## Overview

This project is an independently maintained fork of the **Chatwoot Community Edition**.

The goal is to extend and customize the open-source Chatwoot platform while preserving compatibility with upstream improvements whenever possible.

This repository is not affiliated with, endorsed by, or officially supported by Chatwoot Inc.

## Original Project

| Property | Value |
|---|---|
| Project | Chatwoot |
| Upstream repository | `chatwoot/chatwoot` |
| Initial upstream version | `v4.19.1` |
| Initial upstream commit | `caab07a8f00032d5205b5a5d7e2eb0ba2f3d2d82` |
| Edition | Community Edition |
| Primary license | MIT |
| Enterprise components | Excluded |
| Git history | Independently initialized |

The original project is developed and maintained by Chatwoot Inc. and its contributors.

All applicable original copyright notices and license terms are preserved.

## Community Edition Only

This repository is based exclusively on the open-source Community Edition.

The following directories were excluded during the initial import:

- `enterprise/`
- `spec/enterprise/`

The proprietary Enterprise Edition code is not intended to be included in this repository.

References to Enterprise functionality may still exist in shared Community Edition code where required for compatibility with the upstream architecture.

Such references do not imply that the corresponding proprietary implementations are included.

## Repository History

This repository was initialized with a new Git history rather than preserving the complete upstream history.

This was done to establish an independent repository containing the selected Community Edition source code without incorporating the historical contents of excluded Enterprise directories.

The original upstream version and commit are documented above for traceability.

## Initial Modifications

The initial import includes the following changes to the upstream Community Edition:

### Enterprise Removal

The proprietary Enterprise Edition directories and their corresponding tests were removed.

### Docker Configuration

Docker configuration was adjusted to explicitly identify the application as Community Edition.

The following environment variables are used:

`CW_EDITION=ce`

`DISABLE_ENTERPRISE=true`

### Deployment Configuration

Docker Compose configuration may be customized for independent builds, self-hosted deployments, and container image distribution.

### Continuous Integration

Upstream GitHub Actions workflows may be removed or adapted to support this repository's independent testing, security checks, and Docker image publishing.

### Security Policy

The original security reporting policy was replaced with a fork-specific policy.

See `SECURITY.md` for details.

## Upstream Update Strategy

This project aims to incorporate relevant upstream Community Edition improvements, bug fixes, and security patches.

Because this repository has an independent Git history, upstream changes should be imported through a controlled process rather than merging the complete upstream Git history.

### Update Procedure

1. Identify the target upstream Chatwoot release.
2. Obtain a clean copy of the upstream source code at the selected tag.
3. Remove proprietary Enterprise Edition directories and tests.
4. Review new or relocated files for applicable licensing restrictions.
5. Compare the sanitized Community Edition source against the previously imported upstream version.
6. Review and integrate changes while preserving fork-specific modifications.
7. Run automated tests, security checks, and Docker builds.
8. Verify database migrations and deployment compatibility.
9. Update the upstream version information in this document.
10. Submit the changes through a Pull Request for review.

Upstream updates must not reintroduce proprietary Enterprise Edition components.

Security-related upstream updates should be prioritized.

## Current Upstream Base

| Property | Value |
|---|---|
| Version | `v4.19.1` |
| Commit | `caab07a8f00032d5205b5a5d7e2eb0ba2f3d2d82` |

This section should be updated whenever a new upstream version is incorporated.

## Versioning

Fork releases may use a version identifier that preserves the original upstream version while distinguishing local modifications.

For example:

- `v4.19.1-fork.1`
- `v4.19.1-fork.2`
- `v4.20.0-fork.1`

This convention is optional but recommended for traceability.

## Licensing

The original Chatwoot Community Edition source code is distributed under the MIT license, except for third-party components governed by their respective licenses.

Original copyright notices must be preserved.

New contributions and modifications are subject to the applicable repository and third-party license terms.

This project does not grant rights to use Chatwoot Inc. trademarks beyond those otherwise permitted by applicable law or separate authorization.

See `LICENSE` for additional information.

## Contributions

Contributions are welcome, particularly improvements involving:

- Customer support workflows.
- Conversation routing and assignment.
- Customer portals and ticket management.
- Service-level agreements.
- Reporting and analytics.
- Customer satisfaction management.
- Security and performance improvements.

Contributions should not introduce proprietary Chatwoot Enterprise Edition code.

Where possible, changes should remain compatible with the upstream Community Edition.

## Acknowledgments

This project builds upon the work of Chatwoot Inc. and the open-source contributors who developed the original Chatwoot platform.

Their contributions are acknowledged and appreciated.
