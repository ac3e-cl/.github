# Contributing to AC3E Projects

Thank you for your interest in contributing to AC3E software and research
artifacts. These guidelines apply to repositories that do not define their own
project-specific process.

## Before You Start

- Read the repository `README.md`, `LICENSE`, and open issues.
- Confirm that your proposed contribution is compatible with the repository
  license and any data-use restrictions.
- For research code, preserve reproducibility: document inputs, parameters,
  expected outputs, and environment assumptions.
- For substantial changes, open an issue first to discuss the scope with the
  maintainers.

## Development Workflow

1. Fork or create a branch from `main`.
2. Keep changes focused and small enough to review.
3. Add or update tests, examples, or documentation when behavior changes.
4. Run the repository's formatter, linter, and test suite before submitting.
5. Open a pull request using the provided template.

## Commit and Pull Request Standards

- Use clear commit messages that explain the purpose of the change.
- Link related issues, datasets, publications, or experiments when relevant.
- Avoid committing generated artifacts, credentials, raw private data, or large
  binary files unless the repository explicitly requires them.
- Document breaking changes clearly in the pull request.
- Keep discussions respectful and technical, following the Code of Conduct.

## Code Quality

Contributions should prioritize:

- Readability and maintainability.
- Reproducible results.
- Minimal, well-scoped dependencies.
- Explicit assumptions for hardware, datasets, or experimental setups.
- Tests or validation scripts for core behavior.

## Research Outputs

When a repository supports a publication, thesis, dataset, or technical report,
include enough context for others to understand and reproduce the work:

- Citation information.
- Data sources and licenses.
- Experiment configuration.
- Hardware or software requirements.
- Known limitations.

## Security and Sensitive Information

Do not open public issues or pull requests containing vulnerabilities, secrets,
private data, or restricted research material. Follow `SECURITY.md` for
responsible disclosure.

## License

By contributing, you agree that your contributions will be licensed under the
license of the repository unless another written agreement applies.
