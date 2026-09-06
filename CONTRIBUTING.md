# Contributing

Thanks for your interest in contributing to **BCA Upper Cafe**.

BCA Upper Cafe is a multi-repository project, and contributions are welcome from members of the Bergen County Academies community and other authorized contributors. Contributions may include code, documentation, bug reports, testing, design improvements, and other work that helps improve the project.

Please read the project's **Code of Conduct** and **Security Policy** before contributing.

## Before Contributing

Before making a contribution:

- Do not commit student, teacher, staff, or other personally identifiable information.
- Do not commit passwords, credentials, API keys, access tokens, session tokens, or other secrets.
- Do not use real production data for development, testing, screenshots, demonstrations, or examples.
- Use fictional, synthetic, or properly anonymized data instead.
- Do not test against production systems unless you have explicit authorization to do so.
- Follow the setup and contribution instructions provided in the repository you are working on.
- Keep changes focused on a specific feature, bug, improvement, or other clearly defined objective.
- Follow the existing conventions and architecture of the repository.
- Document significant architectural, security, or behavioral changes.

## Issues and Feature Proposals

For bugs, improvements, and questions, use the appropriate GitHub issue or discussion channel when available.

For **substantial changes**, please open an issue before beginning implementation. This gives maintainers and contributors an opportunity to discuss:

- The problem being addressed.
- The proposed approach.
- Potential alternatives.
- Architectural implications.
- Privacy and security considerations.
- Potential effects on other parts of the project.

Smaller fixes and straightforward improvements may not require an issue beforehand.

**Do not use public GitHub issues or discussions to report security vulnerabilities.** Follow the project's Security Policy instead.

## Development

Each repository may have its own development environment, dependencies, scripts, and setup requirements. Follow the repository-specific documentation before making changes.

When developing:

- Keep dependencies up to date where practical.
- Avoid introducing unnecessary dependencies.
- Do not hard-code secrets or environment-specific credentials.
- Use environment variables or the project's established secret-management approach for sensitive configuration.
- Keep development and production environments appropriately separated.
- Test changes before submitting them.
- Consider privacy and security implications when working with authentication, APIs, databases, or school-related functionality.

## Pull Requests

Pull requests should clearly explain what was changed and why.

Where applicable, include:

- A concise description of the change.
- The issue or feature the change addresses.
- Relevant implementation details.
- Testing performed.
- Any configuration or migration requirements.
- Any known limitations or follow-up work.

Keep pull requests reasonably focused. Large changes that combine unrelated features, refactors, or fixes may be harder to review and may be asked to be split into multiple pull requests.

Maintainers may request changes before a pull request is merged.

## Commits

Write clear and descriptive commit messages.

Do not include sensitive information in commit messages, source code, configuration files, logs, screenshots, or other repository content.

If a secret is accidentally committed, **do not simply delete it from the latest commit and assume it is resolved**. Notify the project maintainers privately so the appropriate credentials or tokens can be revoked and the exposure can be assessed.

## Code Review

Contributors should participate constructively in code review.

Review feedback should focus on improving the implementation and should be communicated respectfully. Contributors are encouraged to explain the reasoning behind significant implementation decisions and to address legitimate review concerns before merging.

Maintainers may request additional testing, documentation, changes to implementation, or other improvements before approving a contribution.

## Privacy and Security

BCA Upper Cafe may interact with school-related information, making privacy and security a particularly important part of the contribution process.

Contributors must follow the project's **Code of Conduct** and **Security Policy** when working with project systems or reporting issues.

When demonstrating a bug or feature, use the minimum amount of information necessary and avoid exposing real user data.

If you discover a potential security vulnerability, **do not create a public issue or pull request**. Report it privately using the process described in the Security Policy.

## Repository-Specific Requirements

This document provides general contribution guidelines for the BCA Upper Cafe project.

Individual repositories may have additional requirements, including repository-specific:

- Setup instructions
- Development commands
- Testing requirements
- Coding conventions
- Branching conventions
- Environment configuration
- Deployment procedures
- Review requirements

Always follow the more specific instructions provided by the repository you are contributing to.

## Questions

If you are unsure whether a proposed contribution, testing method, or change is appropriate, contact a project maintainer before proceeding.

Thank you for helping improve BCA Upper Cafe.
