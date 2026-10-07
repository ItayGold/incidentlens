# Privacy and trust

## Current public scaffold

The landing page has no scripts, forms, analytics, cookies, external fonts, or
application network requests. It does not ingest incident data. Opening it locally
does not send example data to a service.

When files are served by a hosting provider, that provider may receive ordinary
request metadata such as IP addresses and access logs under its own policies.
Following a GitHub link takes you to GitHub, whose policies apply there. This is
not a promise of anonymous browsing.

All example evidence is fictional. Do not put real logs, secrets, personal data,
customer identifiers, or production artifacts into issues or pull requests.

## Requirements for a future product

Before handling real evidence, a future implementation needs explicit decisions
and documented controls for:

- Authorized source access and collection limited to the investigation's needs.
- Authentication, least-privilege access, and tenant isolation.
- Encryption, secret management, and auditable access.
- Retention, deletion, export, and incident response procedures.
- Data residency, subprocessors, and any external model-provider processing.
- Clear separation between observed evidence and generated interpretation.

These are requirements, **not implemented capabilities or compliance claims**.
No external AI provider, data residency commitment, or retention period has been
selected in this public scaffold.

## Human responsibility

Proposed explanations must remain reviewable. An explanation should not be treated
as a verified cause merely because it is coherent. Operational and security actions
remain the responsibility of authorized responders.
