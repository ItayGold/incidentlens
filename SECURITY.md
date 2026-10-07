# Security policy

## Scope

This repository is a concept-stage public scaffold, not a deployed incident
analysis service. Security feedback is relevant to the published static page,
examples, documentation, and any future public code.

No supported product versions or response-time commitments have been established.

## Reporting a concern

Do not include secrets, customer data, real incident evidence, or exploit details
in a public issue.

Check the repository's
[security advisory page](https://github.com/ItayGold/incidentlens/security/advisories)
for a **Report a vulnerability** option. If GitHub private vulnerability reporting
is enabled, use that channel. This document does not claim it is enabled.

If no private reporting option is available, open a minimal public issue asking
the maintainer for a private contact channel, without disclosing the vulnerability
or sensitive evidence. Wait for a verified private channel before sharing details.

Include affected files, reproduction steps, impact, and a suggested fix in the
private report, using synthetic data where possible.

## Sensitive-data exposure

If a credential is exposed, its owner should revoke or rotate it through the
appropriate provider. Removing a file from the current tree does not remove it
from Git history or copies.
