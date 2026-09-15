# Mohammed Abd Alrahman

Security researcher and developer from Iraq.

I look for vulnerabilities in widely deployed WordPress plugins and in open-source
security tooling, report them through the vendor's own channel, and follow them
until they're fixed. Between those, I build the tools I needed and couldn't find:
small, dependency-light, and Arabic-first where it matters.

[mohmadev.com](https://mohmadev.com) · <dvlinuxx@gmail.com>

## Security research

Nine issues found and disclosed so far. Write-ups for each one are at
[mohmadev.com/cves](https://mohmadev.com/cves).

| ID | Product | Issue | Severity |
| --- | --- | --- | --- |
| CWE-436 | [GuardDog](https://github.com/DataDog/guarddog) (DataDog) | ZIP parser differential — a crafted wheel reads as empty to the scanner but still unpacks on install | High |
| [CVE-2026-74992](https://nvd.nist.gov/vuln/detail/CVE-2026-74992) | Kirki (Themeum) | Stored XSS through unvalidated files inside an uploaded font archive | 6.8 |
| [CVE-2026-19615](https://nvd.nist.gov/vuln/detail/CVE-2026-19615) | Admin and Site Enhancements (WPease) | Stored XSS through unsanitised SVG upload | 6.8 |
| [CVE-2026-19075](https://nvd.nist.gov/vuln/detail/CVE-2026-19075) | All-in-One Video Gallery (PluginsWare) | Server-side request forgery | 5.0 |
| CVE-2026-77786 | Rank Math SEO | Broken access control (CWE-863) | 4.9 |
| CWE-295 | AI Engine (Meow Apps) | TLS certificate verification skipped on outbound requests — 100k+ installs | Medium |
| — | Automatic YouTube Gallery (Plugins360 Labs) | Several issues, including an unauthenticated one | Medium |
| CWE-778 | [CrowdSec](https://github.com/crowdsecurity/hub) | Exim parser dropped every authentication failure, so brute force produced no events | Low |

One more is with a vendor under coordinated disclosure and isn't listed yet.

## Contributing to

- [DataDog/guarddog](https://github.com/DataDog/guarddog) — malware scanner for PyPI and npm
- [crowdsecurity/hub](https://github.com/crowdsecurity/hub) — detection scenarios and log parsers
- [abdulrahman-103/kitab](https://github.com/abdulrahman-103/kitab) — an Arabic word processor written in Qt

## Things I've built

| Project | What it does | Built with |
| --- | --- | --- |
| [AFIN](https://github.com/dvlinuxx-max/AFIN) | Offline-first field data collection: form builder, XLSForm import/export, a PWA collector with an offline queue, RBAC, end-to-end encrypted submissions, analytics and maps. Bilingual AR/EN | Next.js, Prisma |
| [Cleanix](https://github.com/dvlinuxx-max/Cleanix) | Finds what is eating your disk on Windows and tells you what is safe to delete — duplicate detection, per-file safety rating, temp and recycle-bin cleanup, Arabic interface. On the [Microsoft Store](https://apps.microsoft.com/detail/9NV81Z29GK9R) | Python |
