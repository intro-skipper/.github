# Security Policy

**intro-skipper · Last updated: September 9, 2026**

---

## Reporting a Vulnerability

Please report security issues privately through GitHub: **[Report a vulnerability](https://github.com/intro-skipper/intro-skipper/security/advisories/new)**, or the **Security** tab of whichever intro-skipper repository is affected. Private reporting is enabled across the organisation, so a report stays between you and the maintainers until a fix is published.

If GitHub is not an option, email [info@intro-skipper.org](mailto:info@intro-skipper.org).

Please do **not** use a public issue, pull request, discussion, or Discord message for a suspected vulnerability.

### What to include

- Plugin version and Jellyfin server version
- Operating system and install method (Docker, native package, …)
- What an attacker gains, and what access they need to start
- Steps to reproduce, or a proof of concept
- Relevant log output, with paths and tokens redacted

### What to expect

intro-skipper is a volunteer-maintained project, so handling is best effort. We aim to acknowledge a report within 7 days. Once a report is confirmed we will fix it on the supported branch, publish a GitHub Security Advisory, and credit you unless you would rather stay anonymous. We would appreciate you holding off on public disclosure until that advisory goes out.

---

## Supported Versions

The plugin tracks Jellyfin's release cadence. **Only the plugin line targeting the current stable Jellyfin release receives security fixes.** There is no long-term support line and no fixed support window measured in months or years — when Jellyfin promotes a new stable release, the plugin branch for the previous one stops receiving fixes.

| Plugin branch | Targets          | Security fixes                             |
| ------------- | ---------------- | ------------------------------------------ |
| `12.0`        | Jellyfin 12.0.x  | Yes — current stable release               |
| `10.11`       | Jellyfin 10.11.x | No — superseded by Jellyfin 12.0           |
| `10.10`       | Jellyfin 10.10.x | No                                         |

If you run an older Jellyfin server, **upgrading Jellyfin is the remediation path** — fixes are not backported. The manifest at `https://intro-skipper.org/manifest.json` serves builds matched to the Jellyfin version that requests it, so an outdated server keeps being offered the last build made for it. That build is frozen, not maintained.

---

## Scope

In scope:

- The plugin, including its bundled configuration page assets
- The build and release workflows, and the artifacts they publish
- The manifest and web properties operated by intro-skipper

Out of scope — please report these upstream instead:

- The Jellyfin server, its API, or its web client → [jellyfin/jellyfin](https://github.com/jellyfin/jellyfin/security/policy)
- `jellyfin-ffmpeg` → [jellyfin/jellyfin-ffmpeg](https://github.com/jellyfin/jellyfin-ffmpeg)
- Forks, third-party builds, or manifests not published by this organisation

Plugin settings are administrator-only by design, so a finding that requires an existing administrator session or an already-compromised server is generally not treated as a vulnerability. If you are unsure, report it anyway and we will route it.

---

## Verifying a Release

Release binaries are signed through [SignPath](https://signpath.io/). If GitHub attestations (for example, SLSA provenance and SBOM) are published for a release, you can verify them with `gh attestation verify PATH_TO_DOWNLOADED_FILE --repo intro-skipper/intro-skipper`.

---

## Contact

- **Security reports:** [GitHub Security Advisories](https://github.com/intro-skipper/intro-skipper/security/advisories/new)
- **Email:** [info@intro-skipper.org](mailto:info@intro-skipper.org)
- **Discord:** <https://discord.gg/AYZ7RJ3BuA> (general questions only — never vulnerability details)
