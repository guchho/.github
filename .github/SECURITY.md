# Security Policy

## Supported Versions

Security fixes are applied to the latest release on the default branch of each
repository owned by the [Guchho](https://github.com/guchho) organization. Older
versions may not receive security patches; please update when possible.

| Version       | Supported          |
| ------------- | ------------------ |
| latest (main) | :white_check_mark: |
| older releases| :x:                |

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, report them privately using one of the following channels:

- **GitHub Security Advisories**: Prefer [reporting a vulnerability](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/reporting-a-vulnerability-in-a-repository) directly on the affected repository (Security tab → Report a vulnerability).
- **Email**: hematagayan2000@gmail.com

Include as much of the following as you can:

- A description of the vulnerability and its potential impact
- Steps to reproduce the issue (PoC, test case, or affected commands/config)
- Affected version(s) and platform(s)
- Any known mitigations

## What to expect

- You will receive an acknowledgement as soon as possible, typically within **72 hours**.
- We will work with you to understand and validate the issue.
- A fix will be prepared and released, and public disclosure coordinated with you once a patch is available — unless you prefer otherwise.
- Credit will be given to reporters who wish to be acknowledged (unless you prefer to remain anonymous).

## Scope

This policy applies to security vulnerabilities in software maintained by the
Guchho organization, such as the bundler, compiler, and associated tooling.

Out of scope examples:

- Vulnerabilities in third-party dependencies that do not affect Guchho's usage (report these upstream instead).
- Denial-of-service or resource-exhaustion attacks requiring unrealistic input volume.
- Issues requiring physical access to a user's machine.
- Social engineering, phishing, or physical attacks.

## Preferred Languages

English is preferred for all communications.

## Safe Harbor

We consider security research conducted in good faith and in accordance with
this policy to be authorized. We will not pursue legal action against
researchers who:

- Make a good-faith effort to avoid privacy violations, data destruction, and
  service disruption.
- Report findings promptly and keep them confidential until a fix is available.
- Do not exploit the vulnerability beyond what is needed to demonstrate it.
