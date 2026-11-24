# Hi, I'm Jebeen Lee.

I'm a fourth-year Computer Science student at Incheon National University.

I work mainly on **software security research** — finding and verifying vulnerabilities in open source projects and in production software.

My main interests are **authentication and authorization**, **trust boundaries**, **privilege validation**, **bug bounty**, and **AI-assisted vulnerability analysis**.

In the long run I'm aiming for a career in **security research**, **penetration testing**, or **red teaming**. I'd also like to build on what I'm doing in open source security now and widen that scope toward **supply chain security**.

## CVEs & GHSAs

### Visual Studio Code — Microsoft (MSRC)

| ID | Finding | Credit | Severity |
|---|---|---|---|
| [CVE-2026-81378](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-81378) | Content the agent processes steers it to a crafted URL that bypasses the configured network restrictions | **Sole credit** | Important · SFB |
| [CVE-2026-121660](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-121660) | Extensions install and run despite the administrator's extension allowlist policy | **Sole credit** | Important · SFB |
| [CVE-2026-78462](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-78462) | Workspace Trust bypass — a crafted workspace runs code without the user granting trust | Joint credit | Important · SFB |
| [CVE-2026-70094](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-70094) | Remote Code Execution | Joint credit | Important · RCE |
| [CVE-2026-121661](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-121661) | Security Feature Bypass | Joint credit | Important · SFB |
| [CVE-2026-81376](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2026-81376) | Security Feature Bypass | Joint credit | Important · SFB |

### Open Source

| ID | Project | Finding | Credit | Severity |
|---|---|---|---|---|
| [CVE-2026-59765](https://github.com/go-gitea/gitea/security/advisories/GHSA-2wm4-vwp6-v7xc) | Gitea | SSRF via migration asset downloads bypasses `hostmatcher` — reads internal files and cloud metadata | Reporter | High |
| [CVE-2026-56443](https://github.com/go-gitea/gitea/security/advisories/GHSA-7p4h-3gxq-x3h3) | Gitea | Token public-only scope bypassed on Limited-visibility owners | Reporter | Moderate |
| [GHSA-r3v3-v742-55j5](https://github.com/RocketChat/Rocket.Chat/security/advisories/GHSA-r3v3-v742-55j5) | Rocket.Chat | A caller-supplied event name is forwarded to other room members' notify-user streams — forced logout and UI phishing | **Sole reporter** | Moderate |
| [CVE-2026-94609](https://github.com/goauthentik/authentik/security/advisories/GHSA-h6c5-mpvq-j4jc) | authentik | Privilege escalation via delegated group and user management | Reporter | High |
| [CVE-2026-94612](https://github.com/goauthentik/authentik/security/advisories/GHSA-cqj8-fxxf-9pg7) | authentik | Authentication bypass in SAML sources via assertion confusion and replay | Reporter | High |
| [CVE-2026-115474](https://github.com/zulip/zulip/security/advisories/GHSA-vwqp-7j32-xfg5) | Zulip | Guests reach other users' profile information under restricted user visibility | **Sole reporter** | Moderate |
| [GHSA-wj5v-8mqg-gvqw](https://github.com/zulip/zulip/security/advisories/GHSA-wj5v-8mqg-gvqw) | Zulip | Missing access check in the typing endpoint exposes inaccessible users' IDs and emails | **Sole reporter** | Moderate |
| [CVE-2026-102893](https://github.com/zulip/zulip/security/advisories/GHSA-xw9h-9rcm-hx4m) | Zulip | OpenID Connect authentication ignores the `email_verified` claim | **Sole reporter** | Low |
| [CVE-2026-55216](https://github.com/logto-io/logto/security/advisories/GHSA-gc94-xqg8-v8r7) | Logto | Account takeover via `email_verified` bypass in social account linking | **Sole reporter** | High |
| [CVE-2026-5038](https://github.com/expressjs/multer/security/advisories/GHSA-3p4h-7m6x-2hcm) | Multer | Denial of service via incomplete cleanup of aborted uploads | Finder | Moderate |

## Penetration Testing

* Incheon National University
* Incheon City Public Institution

## Coordinated Disclosure

* **Microsoft (MSRC)** — ongoing coordinated disclosure on Visual Studio Code.
* **KISA — Government CVD/VDP pilot program** — participant.

Additional vulnerability reports are currently under coordinated disclosure and are not listed here.

## Bug Bounty & Special Mention

* **Microsoft (MSRC)** — bounties awarded for Visual Studio Code findings.
* **Microsoft (MSRC)** — listed on [Special Mention](https://msrc.microsoft.com/special-mention).
* **Automattic / WPScan** — bounty awarded for a valid vulnerability report.

## OSS Contributions

* **Fugit** — reported a cron parser bug causing uncaught `ZeroDivisionError` exceptions, and validated the upstream fix.

## Activities

* **Hacklipse** — Member of the Web Team at Incheon National University's cybersecurity club.
