# Espresso Systems Security Policy

This policy applies to repositories under the Espresso Systems organization unless otherwise stated.

If you believe you have found a security vulnerability, please report it to us through the process described below. We ask that you do not publicly disclose the issue until we have had a reasonable opportunity to investigate and remediate it.

## Reporting a Vulnerability

Please report vulnerabilities by emailing: security@espressosys.com

Include as much of the following as possible:
- a clear description of the issue
- the affected repository, component, contract, service, or environment
- steps to reproduce
- proof of concept code, scripts, or tests if available
- impact assessment
- any suggested remediation ideas

For critical vulnerabilities requiring urgent attention, clearly mark the report as **Critical** in the subject line.

We aim to acknowledge reports promptly, typically within a few business days.

## What to Expect

Submissions are reviewed by the Espresso security team.

Our review process generally includes:
- validating the report
- determining whether the issue is in scope
- assessing severity and impact
- coordinating remediation with the relevant engineering team
- verifying the fix before closure

Remediation timelines vary depending on complexity, affected systems, release constraints, and any governance or deployment requirements.

## Responsible Disclosure

To help protect users and the protocol, we ask that you:
- do not publicly disclose the vulnerability before it is resolved
- do not exploit the issue beyond what is necessary to demonstrate impact
- do not access, modify, or exfiltrate user funds or user data
- do not degrade the availability or integrity of our systems
- do not use social engineering, phishing, spam, or physical attacks

We will work with you in good faith to understand and remediate valid reports.

## Safe Harbor

If you act in good faith and in accordance with this policy, Espresso Systems will not pursue legal action against you for your research.

This means, among other things, that you should:
- avoid privacy violations, destruction of data, or service disruption
- avoid exploiting a vulnerability beyond what is minimally necessary for demonstration
- stop testing and notify us as soon as you discover sensitive user data or a critical exploit path
- comply with applicable laws

Activities that involve extortion, ransom demands, social engineering, physical intrusion, or intentional harm are not covered by this safe harbor.

## Scope

This policy covers security research into Espresso Systems repositories and systems unless a repository states otherwise.

Specific repositories may provide additional scope details, exclusions, or bounty information in their own documentation.

Examples of systems that may be covered, depending on the repository:
- smart contracts
- protocol logic
- cryptographic verification logic
- node or infrastructure software
- APIs and backend services
- developer tooling maintained by Espresso Systems

Out-of-scope items may include, unless explicitly stated otherwise:
- third-party services or dependencies not maintained by Espresso
- social engineering and phishing
- denial of service without a concrete protocol or security impact
- test files, mocks, examples, or non-production code
- reports based solely on best-practice suggestions without a demonstrable security impact
- known issues already publicly documented or previously reported

## Bug Bounty

Certain repositories, especially those containing production smart contracts, may be covered by a repository-specific bug bounty program.

Where applicable, the repository README or other repo documentation will describe:
- bounty scope
- severity guidance
- reward ranges
- any repo-specific exclusions

If a repository does not explicitly offer a bug bounty, that does not guarantee a monetary reward.

Any reward decisions are made at Espresso Systems’ discretion and depend on factors such as severity, impact, exploitability, report quality, and whether the issue is otherwise known.

## Disclosure and Coordination

We ask researchers not to publish details of a vulnerability until:
- we confirm remediation is complete, or
- we mutually agree on a disclosure timeline

If coordinated disclosure is appropriate, we are happy to work with researchers on timing and wording.

## Additional Notes

- Researchers are responsible for any applicable taxes, fees, or reporting obligations related to any bounty payment.
- Final determinations regarding severity, eligibility, and rewards are made by Espresso Systems.
- This policy may be updated from time to time.

Thank you for helping keep Espresso Systems and its users safe.
