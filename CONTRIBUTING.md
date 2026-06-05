# Contributing to OpenAN

Thank you for your interest in contributing to OpenAN! This document provides guidelines and information for contributors.

## How to Contribute

1. **Join the community.** Subscribe to the [OpenAN mailing lists](https://lists.openan.dev) and introduce yourself.
2. **Find an issue.** Browse [open issues](https://github.com/project-openan) across our repositories, or propose a new feature or improvement on the mailing list.
3. **Fork and branch.** Fork the repository you want to contribute to and create a feature branch from `main`.
4. **Make your changes.** Write clear, well-documented code. Include tests where appropriate.
5. **Sign off your commits.** All contributions must include a DCO sign-off (see below).
6. **Submit a pull request.** Open a PR against the `main` branch with a clear description of your changes.

## Developer Certificate of Origin (DCO)

All contributions to OpenAN must be signed off under the [Developer Certificate of Origin (DCO)](https://developercertificate.org/), Version 1.1. The DCO is a lightweight mechanism for contributors to certify that they have the right to submit their contribution under the project's license.

By signing off, you agree to the following:

```
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.

Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```

To sign off on a commit, add a `Signed-off-by` line to your commit message:

```
Signed-off-by: Your Name <your.email@example.com>
```

You can do this automatically with `git commit -s` or `git commit --signoff`.

The name and email in your sign-off must match your Git identity. The GitHub DCO App is installed on all OpenAN repositories and will check every PR for valid sign-offs.

## License

All contributions are accepted under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0). By submitting a contribution, you agree that your contribution will be licensed under that license.

### SPDX License Headers

All new source files should include the following SPDX license identifier near the top of the file:

```
# SPDX-FileCopyrightText: Copyright contributors to the OpenAN project
# SPDX-License-Identifier: Apache-2.0
```

Adjust the comment syntax for your file type (e.g., `//` for Go/Java/C, `/* */` for CSS, `<!-- -->` for HTML/XML).

## Code Review

All submissions require review before merging. Maintainers will review your PR for technical correctness, style, and alignment with project goals. Be responsive to feedback and willing to make adjustments.

## Reporting Issues

When reporting issues, please include:

- A clear, descriptive title
- Steps to reproduce the issue
- Expected versus actual behavior
- Your environment (OS, software versions, etc.)
- Any relevant logs or screenshots

## Code of Conduct

All participants must follow the [LF Projects Code of Conduct](https://lfprojects.org/policies/code-of-conduct/). Be respectful, inclusive, and constructive in all interactions.

## Questions?

If you have questions about contributing, reach out on the [OpenAN mailing lists](https://lists.openan.dev) or open a [GitHub Discussion](https://github.com/orgs/project-openan/discussions). For project operations or governance questions, contact the LFN staff at [support@lfnetworking.org](mailto:support@lfnetworking.org). For infrastructure issues (GitHub access, SSO/LFID accounts), visit [support.linuxfoundation.org](https://support.linuxfoundation.org).
