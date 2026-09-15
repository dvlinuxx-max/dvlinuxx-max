# Mohammed Abd Alrahman

Security researcher and developer from Iraq.

I look for vulnerabilities in widely deployed WordPress plugins and in open-source
security tooling, report them through the vendor's own channel, and follow them
until they're fixed. Between those, I build the tools I needed and couldn't find:
small, dependency-light, and Arabic-first where it matters.

[mohmadev.com](https://mohmadev.com) · <dvlinuxx@gmail.com>

## Security research

Fifteen issues found and reported so far. Write-ups for each are at
[mohmadev.com/cves](https://mohmadev.com/cves).

| ID | Product | Issue | Sev |
| --- | --- | --- | --- |
| CWE-436 | [GuardDog](https://github.com/DataDog/guarddog) | ZIP parser differential — scans clean, installs code | 7.4 |
| CVE-2026-19723 | UltimatelySocial | Reflected XSS in share handler | 7.1 |
| — | Automatic YouTube Gallery | Multiple issues, one unauthenticated | 7.4 |
| [CVE-2026-74992](https://nvd.nist.gov/vuln/detail/CVE-2026-74992) | Kirki | Stored XSS via font-archive upload | 6.8 |
| CVE-2026-19719 | UltimatelySocial | Contributor+ stored XSS via post title | 6.8 |
| [CVE-2026-19615](https://nvd.nist.gov/vuln/detail/CVE-2026-19615) | Admin and Site Enhancements | Stored XSS via SVG upload | 6.8 |
| CVE-2026-84222 | Kirki | Unauth. post-content disclosure | 5.3 |
| [CVE-2026-19075](https://nvd.nist.gov/vuln/detail/CVE-2026-19075) | All-in-One Video Gallery | Server-side request forgery | 5.0 |
| CVE-2026-77786 | Rank Math SEO | Broken access control | 4.9 |
| CWE-295 | AI Engine (Meow Apps) | TLS verification skipped, 100k+ installs | Med |
| CVE-2026-84745 | The Events Calendar | Contributor+ content disclosure via REST | 2.7 |
| CVE-2026-77787 | Rank Math SEO | Author+ metadata overwrite | 2.7 |
| CVE-2026-77785 | Rank Math SEO | Author+ post disclosure via Abilities API | 2.7 |
| CWE-778 | [CrowdSec](https://github.com/crowdsecurity/hub) | Exim parser missed every auth failure | Low |

One more, in Content Egg, is still under coordinated disclosure and isn't detailed yet.

## Contributing to

- [DataDog/guarddog](https://github.com/DataDog/guarddog) — malware scanner for PyPI and npm
- [crowdsecurity/hub](https://github.com/crowdsecurity/hub) — detection scenarios and log parsers
- [abdulrahman-103/kitab](https://github.com/abdulrahman-103/kitab) — an Arabic word processor written in Qt

## Things I've built

| Project | What it does | Built with |
| --- | --- | --- |
| [AFIN](https://github.com/dvlinuxx-max/AFIN) | Offline-first field data collection: form builder, XLSForm import/export, a PWA collector with an offline queue, RBAC, end-to-end encrypted submissions, analytics and maps. Bilingual AR/EN | Next.js, Prisma |
| [Cleanix](https://github.com/dvlinuxx-max/Cleanix) | Finds what is eating your disk on Windows and tells you what is safe to delete — duplicate detection, per-file safety rating, temp and recycle-bin cleanup, Arabic interface. On the [Microsoft Store](https://apps.microsoft.com/detail/9NV81Z29GK9R) | Python |
