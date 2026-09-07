# Contributing

Thank you for your interest in contributing to BCA Upper Cafe. We welcome contributions from students, staff, and community members. This guide explains how to open issues, propose changes, write code, and collaborate safely and respectfully.

## Before you begin

- Read CODE_OF_CONDUCT.md and follow it.
- Check existing issues and PRs to avoid duplicates.
- If your change affects student data or privacy, contact the maintainers before implementing and never use real student data.

## Reporting bugs and requesting features

- To report a bug or request a feature, open a new GitHub Issue in this repository with a clear title and steps to reproduce (for bugs). Avoid including personal or sensitive data in public issues.
- For security vulnerabilities or sensitive data leaks, email kabsek30@bergen.org instead of opening a public issue.

## Development workflow

- Branch from the default branch (usually `main`). Name your branch using a short prefix and description, e.g., `feature/ui-refresh` or `fix/login-bug`.
- Make small, focused commits with clear messages. Follow conventional commit prefixes where practical (e.g., `feat: …`, `fix: …`, `docs: …`).
- Run tests locally and ensure your changes pass CI.
- Open a Pull Request to `main` with a clear description of the change, references to related issues, and testing notes.

Recommended Git workflow (example)
- git checkout -b feature/short-description
- make changes, run tests
- git add <files>
- git commit -m "feat: short description"
- git push -u origin feature/short-description
- Open a PR on GitHub targeting `main`

## Code review and merging

- PRs will be reviewed by maintainers or other contributors. Be responsive to review feedback and update your PR as requested.
- Maintainers may request changes or ask for additional tests/documentation.
- Do not merge your own PR unless you are a designated maintainer with permission.
- Maintain a clean commit history; maintainers may ask you to rebase or squash commits before merging.

## Coding standards

- Follow existing project style and patterns. Keep code readable and well-documented.
- Write unit and integration tests for new features or bug fixes when applicable.
- Keep dependencies up to date and avoid introducing unnecessary or unvetted third-party libraries.
- Document non-obvious design decisions in code comments or PR descriptions.

## Tests

- Add tests for new functionality and run the test suite locally before opening a PR.
- If adding or changing behavioral features, include tests that cover the new behavior.
- If CI is configured, ensure your PR passes all required checks.

## Documentation

- Update README, module docs, or other documentation when your changes affect usage or developer workflows.
- Add examples and usage notes for new public APIs.

## Commit messages

- Use clear, imperative-style commit messages.
- Prefer a concise prefix indicating the type (e.g., `feat:`, `fix:`, `docs:`, `chore:`) followed by a short summary.
- Include additional details in the commit body if necessary.

## Attribution and licensing

- Ensure third-party code you add is compatible with the project's license and include attribution when required.
- When copying examples or code, retain original license notices where applicable.

## Getting help

- If you need help, open an issue or contact the maintainers at kabsek30@bergen.org. Be patient — maintainers may take time to respond.
- For security questions or to report sensitive data exposure, use kabsek30@bergen.org (do not post sensitive details in public issues).

Thank you for contributing!
