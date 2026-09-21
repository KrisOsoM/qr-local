# Security Policy

## Supported release

The current supported release is **QR Local v2.6.1**.

## Security model

QR Local is a client-side, single-file application. It has no application server, user accounts, remote database or cloud backend.

QR contents and imported CSV/XLSX data are processed in the browser. Users should still treat downloaded/exported files according to their own security requirements.

## Reporting a vulnerability

After the public repository is created, security issues should be reported through the repository's issue/contact channel. For vulnerabilities that would expose sensitive information, avoid posting exploit details publicly before the maintainer has had a chance to review them.

## Scope

Useful reports include:

- unexpected outbound network access;
- unsafe parsing behavior for malformed CSV/XLSX files;
- unintended persistence of QR payload data;
- arbitrary script execution introduced by application logic;
- export corruption that could lead to misleading or unsafe output.