# Privacy Policy

**On the Boards — QuickBooks Online Integrations**
**Last updated: July 24, 2026**

## 1. Overview

On the Boards is a 501(c)(3) nonprofit performing arts organization in Seattle, Washington.
This policy describes how data is handled by the internal integration applications On the
Boards operates against its own QuickBooks Online account.

## 2. Data Accessed

These applications access QuickBooks Online accounting data belonging to On the Boards,
including but not limited to accounts, classes, transactions, journal entries, vendors, and
customers. They access no other QuickBooks Online customer's data.

## 3. Data Use

All data accessed is used solely for On the Boards' internal accounting and financial
management purposes. Data is not sold, shared with third parties, or used for marketing.

## 4. Data Storage

OAuth credentials (access and refresh tokens) are stored in one of two places, depending on
the application:

- **Staff workstations** — in access-restricted local files readable only by the
  authorized staff member's account.
- **On the Boards' administrative portal** — in a PostgreSQL database on a private server
  operated for On the Boards by DigitalOcean, LLC (United States). Client secrets are held
  in the server's environment and are not written to the database.

A read-only mirror of accounting data used for budget reporting is held in that same
database. No On the Boards accounting data is stored anywhere else outside of QuickBooks
Online itself.

## 5. Data Sharing

On the Boards does not share QuickBooks data accessed through these applications with any
third party, except as required by law or as necessary for audit and tax compliance.
DigitalOcean, LLC acts solely as an infrastructure provider and does not access or process
the data for its own purposes.

## 6. Security

Access is restricted to authorized personnel. OAuth tokens are stored in secured local
files or in the portal's database, are transmitted only to Intuit's QuickBooks Online API
over TLS, and are not sent to any other external service. Tokens are rotated on each
refresh in accordance with Intuit's OAuth 2.0 requirements.

## 7. Retention

Accounting records are retained for as long as required by On the Boards' audit and tax
obligations. OAuth credentials are discarded when an application is retired or its access
is revoked.

## 8. Contact

For questions about this privacy policy, contact:

On the Boards
7153 Aurora Ave N
Seattle, WA 98103
edward@ontheboards.org
