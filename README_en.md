# SecureNavigator

An offline security assessment tool that organizes security posture by attack scenarios and compliance guidelines, then converts findings into actionable reports.

[日本語版](README.md)

---

## What SecureNavigator Does

SecureNavigator analyzes an organization's security posture from the attacker's perspective using MITRE ATT&CK-based attack scenarios. It evaluates current defenses against six representative attack patterns, identifies defensive gaps, and maps findings to compliance guidelines including IPA SME Guidelines (Japan), METI Cybersecurity Management Guidelines (Japan), and NIST CSF 2.0. The tool generates prioritized improvement roadmaps and exportable reports for communication with management and stakeholders. All processing runs entirely offline — no data ever leaves the user's device.

## Who It's For

- **IT administrators** — Assess and document security posture for internal review
- **Security officers** — Identify defensive gaps and prioritize improvements
- **SME managers** — Understand organizational security status without specialized expertise
- **Anyone who needs to communicate security improvements** — Generate structured reports for management briefings and improvement planning

## Key Features

- **Fully Offline** — All assessment data stays on the local device. No external communication, no telemetry, no cloud dependency.
- **Attack Scenario Analysis** — Six attack scenarios based on MITRE ATT&CK techniques analyze how attacks progress through an organization's defenses step by step.
- **Multiple Compliance Frameworks** — IPA SME Guidelines available in Free. METI Cybersecurity Guidelines and NIST CSF 2.0 available in Pro.
- **Improvement Roadmap** — Prioritized recommendations across four time horizons: Immediate, Short-term, Mid-term, and Long-term.
- **Report Export** — Export assessment results as PDF, HTML, or Markdown reports. [Pro]
- **Advanced Analysis** — Detailed maturity breakdown, cause-and-action tables, and ATT&CK technique-level analysis. [Pro]
- **Japanese / English** — Full bilingual support for both assessment interface and generated reports.

## Free vs. Pro

| Feature | Free | Pro |
|---------|:----:|:---:|
| Full assessment (all questions) | ✓ | ✓ |
| Attack scenario simulation | ✓ | ✓ |
| Improvement roadmap (on-screen) | ✓ | ✓ |
| IPA SME Guidelines compliance | ✓ | ✓ |
| METI Cybersecurity Guidelines compliance | — | ✓ |
| NIST CSF 2.0 compliance | — | ✓ |
| Advanced analysis (maturity detail, cause & action) | — | ✓ |
| ATT&CK technique detail analysis | — | ✓ |
| PDF report export | — | ✓ |
| HTML / Markdown report export | — | ✓ |
| Hearing sheet export (Excel) | — | ✓ |
| Japanese / English | ✓ | ✓ |
| Saved sessions | 1 | 3 |

## Use Cases

- **Periodic security review** — Organize the current state of defenses and clarify priority improvements.
- **Management reporting** — Generate PDF reports that summarize security posture, defensive gaps, and recommended actions for executive briefings.
- **Improvement prioritization** — Use the roadmap to determine which security measures to implement first based on attack likelihood and gap severity.
- **Compliance evaluation** — Assess alignment with IPA, METI, and NIST CSF 2.0 guidelines to understand where the organization stands relative to established frameworks.

## Privacy & Offline Operation

SecureNavigator operates 100% offline. It does not connect to any external server, does not transmit assessment data, and does not include any telemetry or analytics. All data — including assessment responses, evaluation results, and application settings — is stored locally in SQLite databases under `%LocalAppData%\SecureNavigator\`. The only network activity occurs during installation and updates via the Microsoft Store, which is handled by the OS, not by the application itself.

## Screenshots

> Screenshots coming soon.

## Links

| | |
|---|---|
| Product Website | https://secure-navigator.sumikkolab.com/ |
| User Manual | https://secure-navigator.sumikkolab.com/manual/ |
| Privacy Policy | https://secure-navigator.sumikkolab.com/privacy-policy.html |
| Terms of Use | https://secure-navigator.sumikkolab.com/terms-of-use.html |
| Support | https://secure-navigator.sumikkolab.com/support.html |

## System Requirements

- Windows 10 Version 2004 or later / Windows 11
- WebView2 Runtime (required for PDF export; usually bundled with the OS)
- Disk space: approx. 50 MB
- Internet: Not required (fully offline operation)

## License

SecureNavigator is proprietary software. Free and Pro editions are available.

- **Free** — Personal or internal organizational self-assessment
- **Pro** — Internal evaluation, reporting, and improvement planning
- Commercial use for third parties requires a separate license appropriate for the intended use

See [Terms of Use](https://secure-navigator.sumikkolab.com/terms-of-use.html) for details.

---

© 2026 Sumikko Lab. All rights reserved.
