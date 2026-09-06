# Security Policy

The BCA Upper Cafe project includes software and services that may handle information related to students, staff, study hall usage, authentication, and system administration. Security vulnerabilities should be reported responsibly so they can be investigated and resolved without unnecessarily exposing users or school systems.

## Reporting a Vulnerability

Please **do not disclose security vulnerabilities through public GitHub issues, pull requests, discussions, or other public channels**.

If you discover a potential security vulnerability affecting any repository, application, service, or infrastructure associated with the BCA Upper Cafe project, report it privately to the project maintainers using the contact method listed in the repository or GitHub organization profile.

When reporting a vulnerability, please provide enough information for the maintainers to reproduce and investigate the issue, including:

- A clear description of the vulnerability.
- The affected repository, application, service, or feature.
- Steps required to reproduce the issue.
- The potential security impact.
- Relevant logs, screenshots, or error messages that do not contain sensitive information.
- A suggested mitigation or fix, if applicable.

## Do Not Include Sensitive Information

Do not include the following in a vulnerability report:

- Student names, IDs, records, or other personally identifiable information.
- Staff or teacher information that is not publicly available.
- Passwords or authentication credentials.
- API keys, access tokens, session tokens, or cookies.
- Database credentials or connection strings.
- Private school or district information.
- Any other confidential or sensitive information.

If sensitive information is accidentally exposed during testing, do not copy, download, retain, or share more of it than is necessary to demonstrate the vulnerability. Notify the maintainers privately and stop testing that could expose additional information.

## Responsible Testing

Security testing should be limited to systems and accounts that you are authorized to test.

Researchers should not:

- Access, modify, or delete another user's data.
- Attempt to access administrative functionality without authorization.
- Perform denial-of-service or other disruptive testing.
- Attempt to bypass authentication against real user accounts.
- Use a vulnerability to obtain, retain, or disclose confidential information.
- Modify production data.
- Conduct automated or high-volume testing that could affect system availability.

Whenever possible, demonstrate a vulnerability using the minimum amount of access and data necessary to establish that the issue exists.

## Scope

This security policy applies to **all repositories, applications, services, APIs, websites, and related infrastructure associated with the BCA Upper Cafe project**.

Third-party services and infrastructure are subject to their respective providers' security policies and may have separate vulnerability reporting procedures.

## Vulnerability Handling

After receiving a report, project maintainers will:

1. Review the report and determine whether the issue is valid.
2. Assess its severity and potential impact.
3. Take appropriate steps to contain or mitigate the vulnerability.
4. Develop and deploy a fix when necessary.
5. Verify that the vulnerability has been resolved.
6. Communicate with the reporter when additional information is needed or when appropriate.

Response and remediation times may vary depending on the severity and complexity of the issue.

## Disclosure

Please allow the maintainers reasonable time to investigate and address a reported vulnerability before publicly disclosing technical details.

Public disclosure should not expose student information, credentials, confidential school information, or technical details that could enable exploitation of an unresolved vulnerability.

## Questions

For questions about this security policy or how to report a potential vulnerability, contact the project maintainers privately through the contact method listed in this repository or the BCA Upper Cafe GitHub organization profile.
