# Security Policy

This policy covers all Romulus repositories and services.

## Reporting a vulnerability

Do not open a public issue, pull request or discussion for a security problem.

Send the report by email to **compliance@romulus.io** with the subject `SECURITY: <short summary>`. Include:

- The affected product, URL, endpoint or package
- The steps to reproduce, or a proof of concept
- The impact that you expect (for example, data exposure or privilege escalation)
- Your name and contact details, if you want us to credit you

Do not put credentials, customer data or secrets in the report. If you must share sensitive material, ask us for a secure channel first.

## What happens next

We will get back to you once we review your report.

## Supported versions

We support only the current production version of our services. We do not fix older versions.

## In scope

- The Romulus web app
- The Romulus integration API
- `romulus.io` and its subdomains

## Out of scope

- Denial of service (DoS) or load testing
- Social engineering, phishing or physical attacks
- Spam
- Reports from automated scanners with no proven impact
- Missing security headers or best-practice settings with no proven impact
- Third-party services (for example Google Cloud and Firebase). Report these to the vendor.

## Rules for testing

- Use only your own test accounts.
- Do not access, change or keep the data of other users. If you see such data by accident, stop and tell us.
- Do not degrade or interrupt our services.
- Give us a reasonable time to fix the issue before you disclose it.

## Dependencies

Dependabot and Snyk check our repositories for vulnerable dependencies.
