# AC3E GitHub Community Health

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/ac3e-logo-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/ac3e-logo-light.png">
    <img alt="AC3E - Advanced Center for Electrical and Electronic Engineering" src="assets/ac3e-logo-light.png" width="560">
  </picture>
</p>

> Default community health files and organization profile for AC3E, Chile's
> Advanced Center for Electrical and Electronic Engineering.

[![Standard Readme](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg)](https://github.com/RichardLitt/standard-readme)
[![License: Proprietary](https://img.shields.io/badge/license-proprietary-lightgrey.svg)](LICENSE)

## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Repository Standards](#repository-standards)
- [Branch Protection](#branch-protection)
- [Maintainers](#maintainers)
- [Contributing](#contributing)
- [Security](#security)
- [License](#license)

## Background

AC3E is the Advanced Center for Electrical and Electronic Engineering
(Centro Avanzado de Ingenieria Electrica y Electronica), headquartered at
Universidad Tecnica Federico Santa Maria (UTFSM) in Valparaiso, Chile.

This repository is the special GitHub `.github` repository for the AC3E
organization. GitHub uses it to provide default community health files,
issue templates, pull request templates, and the public organization profile.

## Install

This repository does not provide an installable package. To use it as AC3E's
organization defaults, publish it as:

```sh
git@github.com:ac3e-cl/.github.git
```

## Usage

The organization profile is defined in `profile/README.md`. GitHub displays it
on the organization page when this repository is public.

Default community files apply to repositories that do not define their own:

- `CODE_OF_CONDUCT.md`
- `CONTRIBUTING.md`
- `SECURITY.md`
- `SUPPORT.md`
- `.github/ISSUE_TEMPLATE/*`
- `.github/pull_request_template.md`

Repository-specific files override these defaults.

## Repository Standards

AC3E repositories should include:

- A clear `README.md` following the Standard Readme structure where practical.
- A license file approved by the project owner.
- Reproducible setup and usage instructions.
- Focused tests for research or production code.
- Security contact instructions when the repository is public.
- Citation metadata for research outputs, when applicable.

## Branch Protection

The intended default policy for `main` is:

- Require pull requests before merging.
- Require at least one approval.
- Dismiss stale approvals after new commits.
- Require conversation resolution.
- Require status checks to pass when checks are configured.
- Block force pushes and branch deletion.

A ruleset definition is provided at `.github/rulesets/main-branch-protection.json`
for import or manual configuration in GitHub repository settings.

## Maintainers

AC3E maintainers and repository administrators are responsible for keeping
these defaults current.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Security

See [SECURITY.md](SECURITY.md). Please do not report security vulnerabilities
through public GitHub issues.

## License

Copyright (c) 2026 AC3E. All rights reserved.

This repository is distributed under the terms of the
[AC3E Proprietary, Non-Commercial License](LICENSE).
