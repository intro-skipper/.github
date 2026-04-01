# Privacy Policy

**intro-skipper · Last updated: April 1, 2026**

---

## Overview

This document describes how the intro-skipper project collects, handles, and processes data across its plugin and web services. Our approach is privacy-first: we minimise data collection, anonymise what we do log, and are transparent about every third party involved.

---

## Plugin Privacy Policy

### Data Collection

The plugin does not collect any personal information without explicit user consent.

### Data Storage

User preferences and settings are stored locally on your device only. No preference or settings data is transmitted to intro-skipper or any third party.

### Data Controller

intro-skipper is the data controller for all plugin data. Contact us at [info@intro-skipper.org](mailto:info@intro-skipper.org).

### Your Rights

Even though the plugin does not collect personal data, you retain all rights granted by applicable privacy law (including GDPR where applicable). To exercise any right, please contact us at the address above or open an issue in the project repository.

---

## Website Privacy Policy

Applies to: `https://intro-skipper.org/manifest.json` and `https://editor.intro-skipper.org/`

### Data Controller

intro-skipper is the data controller. Contact: [info@intro-skipper.org](mailto:info@intro-skipper.org)

### Personal Data We Collect

We do not collect personal data. Web server logs are anonymised before storage — IP addresses are stripped prior to any log data being transmitted or retained.

> **Note:** Anonymised log entries may still include technical metadata such as User-Agent strings (e.g. `Jellyfin-Server/10.10.6`), TLS details, and remote port numbers. While we do not treat these as personal data, we acknowledge that such metadata could theoretically be combined with external information to re-identify a user. We therefore minimise retention to 1 day and transmit logs only to our DPA-covered processor, Axiom.

### Purposes of Processing

Anonymised server logs are retained solely for technical diagnostics (e.g. detecting service outages, diagnosing redirect failures). No personal data is processed.

### Legal Basis

The collection of anonymised diagnostic logs is carried out on the basis of our legitimate interest (Article 6(1)(f) GDPR) in maintaining a reliable and secure service. No personal data is processed; accordingly no further legal basis is required for personal-data processing.

### Data Sharing

We do not share any data with third parties, except:

- Anonymised log data is transmitted to and stored by [Axiom](https://axiom.co), a third-party log management service, under a Data Processing Agreement (DPA). Axiom processes this data solely for log storage and diagnostics on our behalf.
- As required by applicable law.

### International Transfers

We do not collect personal data; GDPR international transfer rules therefore do not apply to personal data. Anonymised log data (containing no personal data) may be stored on servers outside the European Economic Area by Axiom under the terms of their DPA.

### Data Retention

Anonymised log data is retained for no more than 1 (one) day. As no personal data is collected, GDPR retention limits do not apply to these logs.

### Security Measures

- All connections are protected with SSL/TLS encryption.
- Log anonymisation (IP stripping) is applied before any data is stored or transmitted.

### Cookies

We do not use cookies on any intro-skipper web property.

### Your Rights

Where GDPR or other applicable law grants data subject rights (access, rectification, erasure, restriction, portability, objection), you may exercise them by contacting us at [info@intro-skipper.org](mailto:info@intro-skipper.org). Because we do not collect or retain personal data, we expect that most requests will result in confirmation that no personal data is held; however, we will respond to every request within the legally required timeframe.

---

## Third-Party Services

The following third-party infrastructure providers may receive limited technical data (such as IP addresses) when you access intro-skipper services, subject to their own privacy policies and DPAs.

### CDN — jsDelivr

jsDelivr may receive your IP address when serving static assets.
Privacy policy: <https://www.jsdelivr.com/terms/privacy-policy-jsdelivr-net/>

### Log Management — Axiom

Axiom receives anonymised log data (no personal data) as described above, under a signed DPA.
DPA: <https://axiom.co/docs/legal/data-processing>

### CDN / DDoS Protection — Cloudflare

Cloudflare may process your IP address and request metadata as part of DDoS protection and CDN services.
DPA: <https://www.cloudflare.com/cloudflare-customer-dpa/>

### Hosting — DigitalOcean

DigitalOcean hosts intro-skipper infrastructure and may process IP addresses at the network level.
DPA: <https://www.digitalocean.com/legal/data-processing-agreement/>

### Hosting — Hetzner

Hetzner hosts intro-skipper infrastructure and may process IP addresses at the network level.
DPA: <https://www.hetzner.com/AV/DPA_en.pdf>

---

## Changes to This Privacy Policy

- Users will be notified of any material privacy policy updates.
- All changes will be documented in the project changelog.
- Continued use of the plugin or web services after notification constitutes acceptance of the updated policy.

---

## Contact

For privacy concerns or questions:

- **Email:** [info@intro-skipper.org](mailto:info@intro-skipper.org)
- **GitHub:** Open an issue in the project repository
- **Discord:** <https://discord.gg/AYZ7RJ3BuA>
