<div align="center">

# 🐞 Bug Bounty — All Platforms

**The most complete, community-powered index of every bug bounty, vulnerability disclosure (VDP), and crowdsourced security platform on the Internet — plus the guidance to actually use them.**

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#-contributing)
[![Awesome](https://img.shields.io/badge/style-awesome-ff69b4.svg)](#)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)](./LICENSE)
[![Maintained](https://img.shields.io/badge/maintained-yes-success.svg)](#)

</div>

---

> **What makes this list different?**
> Most lists just dump platform names. This one adds the columns hunters actually care about — **reward type (cash / crypto / swag), program access, region** — and pairs the directory with a full **getting‑started playbook**: how to choose a platform, a beginner roadmap, recon tooling, report‑writing tips, and the legal ground rules. Everything here is for **authorized, in‑scope testing only.**

## 📑 Table of Contents

- [How to read the tables](#-how-to-read-the-tables)
- [Platforms](#-platforms)
  - [General crowdsourced platforms](#1-general-crowdsourced-platforms)
  - [Government & public-interest programs](#2-government--public-interest-programs)
  - [Web3 & smart-contract platforms](#3-web3--smart-contract-platforms)
  - [AI & LLM security platforms](#4-ai--llm-security-platforms)
  - [Vulnerability acquisition & brokered disclosure](#5-vulnerability-acquisition--brokered-disclosure)
  - [Ecosystem-specific platforms](#6-ecosystem-specific-platforms)
  - [Self-hosted / open-source VDP tooling](#7-self-hosted--open-source-vdp-tooling)
- [🧭 How to choose the right platform](#-how-to-choose-the-right-platform)
- [🚀 Beginner roadmap](#-beginner-roadmap-zero--first-bounty)
- [🛠️ Essential recon & tooling](#️-essential-recon--tooling)
- [📝 Writing a great report](#-writing-a-great-report)
- [⚖️ Legal, ethics & safe harbor](#️-legal-ethics--safe-harbor)
- [📚 Learning resources](#-learning-resources)
- [📖 Glossary](#-glossary)
- [🤝 Contributing](#-contributing)
- [⚠️ Disclaimer](#️-disclaimer)
- [📄 License](#-license)

---

## 🔎 How to read the tables

| Column | Meaning |
|--------|---------|
| **Platform** | Name, linked to the official site |
| **Region** | Primary operating region / HQ (🌍 = global) |
| **Programs** | `Public` (open to all), `Private` (invite-only), or `Both` |
| **Rewards** | 💰 Cash · ₿ Crypto · 🎁 Swag · 🏅 Points/Rep · 🤝 Kudos-only (VDP) |
| **Notes** | What the platform is known for |

> Access, payout methods, and program availability change often — always confirm on the platform's own site before you start. Missing or wrong data? [Open a PR](#-contributing).

---

## 🌐 Platforms

### 1. General crowdsourced platforms

The big, multi-industry marketplaces where most hunters spend their time.

| Platform | Region | Programs | Rewards | Notes |
|----------|--------|----------|---------|-------|
| [HackerOne](https://www.hackerone.com/) | 🌍 Global | Both | 💰 🎁 🏅 | Largest platform; huge public program pool, strong reputation system |
| [Bugcrowd](https://www.bugcrowd.com/) | 🌍 Global | Both | 💰 🎁 🏅 | Managed triage, VRT scoring, many enterprise & gov programs |
| [Intigriti](https://www.intigriti.com/) | 🇪🇺 Europe | Both | 💰 🏅 | Fast-growing EU platform, strong community & swag |
| [YesWeHack](https://www.yeswehack.com/) | 🇪🇺 / 🌏 | Both | 💰 🏅 | Europe + APAC; Dojo training, hunter-friendly |
| [Synack](https://www.synack.com/) | 🌍 Global | Private | 💰 | Vetted "Red Team" (SRT); requires screening & skills test |
| [Cobalt](https://www.cobalt.io/) | 🌍 Global | Private | 💰 | Pentest-as-a-Service ("Core"), vetted pentester pool |
| [Zerocopter](https://www.zerocopter.com/) | 🇳🇱 Europe | Both | 💰 | Vetted researchers, managed programs |
| [Detectify](https://detectify.com/) | 🇸🇪 Europe | Private | 💰 | Crowdsourced research feeds an automated scanner (Crowdsource) |
| [Open Bug Bounty](https://www.openbugbounty.org/) | 🌍 Global | Public | 🤝 🏅 | Free, non-intrusive (XSS/misconfig) coordinated disclosure |
| [Federacy](https://www.federacy.com/) | 🇺🇸 US | Both | 💰 | Startup-focused programs |
| [HackenProof](https://hackenproof.com/) | 🌍 Global | Both | 💰 ₿ | Web2 + Web3 crossover, crypto payouts |
| [Standoff 365](https://bugbounty.standoff365.com/) | 🇷🇺 Russia/CIS | Both | 💰 | Positive Technologies' platform |
| [BI.ZONE Bug Bounty](https://bugbounty.bi.zone/) | 🇷🇺 Russia/CIS | Both | 💰 | Enterprise programs across CIS |
| [Cyber Army Indonesia](https://cyberarmy.id/) | 🇮🇩 Indonesia | Both | 💰 | Regional SEA platform |
| [CyberTalents](https://cybertalents.com/) | 🌍 / MENA | Both | 💰 🏅 | Bug bounty + CTFs + hiring, strong in MENA |
| [Secuna](https://www.secuna.io/) | 🇵🇭 Philippines | Both | 💰 | Leading SEA platform |
| [Bugbase](https://bugbase.ai/) | 🇮🇳 India | Both | 💰 | Continuous testing + bounties |
| [BugBounter](https://bugbounter.com/) | 🇹🇷 Turkey | Both | 💰 | Regional MENA/TR platform |
| [Hackrate](https://hackrate.io/) | 🇭🇺 Europe | Both | 💰 | EU-based, managed programs |
| [GObugfree](https://gobugfree.com/) | 🇨🇭 Switzerland | Both | 💰 | Swiss platform, GDPR-focused |
| [Bug Bounty Switzerland](https://www.bugbounty.ch/) | 🇨🇭 Switzerland | Both | 💰 | Public-sector & enterprise CH programs |
| [Nordic Defender](https://nordicdefender.com/) | 🇸🇪 Nordics | Both | 💰 | Managed crowdsourced security |
| [Inspectiv](https://www.inspectiv.com/) | 🇺🇸 US | Both | 💰 | Continuous crowdsourced testing |
| [Com Olho](https://www.comolho.com/) | 🇮🇳 India | Both | 💰 | AI-assisted triage |
| [RedStorm](https://redstorm.io/) | 🇮🇩 Indonesia | Both | 💰 | Regional SEA platform |
| [Testbirds](https://www.testbirds.com/) | 🇩🇪 Europe | Private | 💰 | Crowdtesting incl. security |
| [Topcoder](https://www.topcoder.com/) | 🌍 Global | Both | 💰 | Broader crowdsourcing incl. security challenges |
| [Vulbox](https://www.vulbox.com/) | 🇨🇳 China | Both | 💰 | Major Chinese platform |
| [Butian (Qihoo 360)](https://www.butian.net/) | 🇨🇳 China | Both | 💰 | One of the largest CN platforms |
| [360 SRC](https://src.360.net/) | 🇨🇳 China | Both | 💰 | Qihoo 360 response center |
| [WhiteHub](https://whitehub.net/) | 🇻🇳 Vietnam | Both | 💰 | Leading VN platform |
| [Safehats](https://safehats.com/) | 🇮🇳 India | Both | 💰 | Managed programs |
| [Cyber3ra](https://cyber3ra.com/) | 🇮🇳 India | Public | 🏅 | India's first crowdsourced platform |
| [Bug Zero](https://bugzero.io/) | 🇱🇰 Sri Lanka | Both | 💰 | Regional South-Asia platform |
| [Bugv](https://bugv.io/) | 🇳🇵 Nepal | Both | 💰 | Nepal-based platform |
| [Capture The Bug](https://www.capturethebug.xyz/) | 🇳🇿 NZ/AU | Both | 💰 | ANZ-focused PTaaS |
| [Swarmnetics](https://swarmnetics.com/) | 🇸🇬 Singapore | Both | 💰 | SEA crowdsourced testing |
| [Dvuln](https://dvuln.com/) | 🇦🇺 Australia | Private | 💰 | Boutique offensive security |
| [Yogosha](https://yogosha.com/) | 🇫🇷 Europe | Private | 💰 | Vetted community, EU + MENA |
| [Vulnerability Lab](https://www.vulnerability-lab.com/) | 🇩🇪 Europe | Both | 💰 | Long-running research lab & programs |
| [Cyscope](https://cyscope.io/) | 🌍 Global | Both | 💰 | Continuous security platform |
| [HACKTIFY](https://hacktify.in/) | 🇮🇳 India | Both | 💰 🏅 | Training + bounty community |

> ➕ Also active / regional: BBHunt Japan, BountyTeam, Bugbop, BugBounty.am, bugbounty.jp, BugBounty.ru, Buglab, Bugloud, BugRakshak, bugsbounty.io, Crowdswarm, Cyberbay, Find The Gap, Findbug, Genbounty, Gerobug, Hackr.fi, HuntBug, HuntersPay, Huoxian, Kolahsefid, PatchDay, Ravro, Safevuln, Secur0, Teklabspace, TrustLine, TumarOne, UzHunter, Vulnscope, ZeroDay Test. *(PRs welcome to promote any of these into the table with full data.)*

---

### 2. Government & public-interest programs

National CERTs, government VDPs, and public-interest disclosure programs. Most are **kudos-only** (no cash) but count toward serious reputation.

| Platform | Region | Programs | Rewards | Notes |
|----------|--------|----------|---------|-------|
| [CISA VDP Platform](https://www.cisa.gov/resources-tools/programs/vulnerability-disclosure-policy-vdp-platform) | 🇺🇸 US | Public | 🤝 | US federal civilian agencies (operated via Bugcrowd) |
| [UK NCSC Vulnerability Reporting](https://www.ncsc.gov.uk/information/vulnerability-reporting) | 🇬🇧 UK | Public | 🤝 | UK national VDP |
| [Swiss NCSC Bug Bounty](https://www.ncsc.admin.ch/) | 🇨🇭 CH | Both | 💰 | Federal administration bug bounty |
| [NCSC-NL CVD](https://www.ncsc.nl/) | 🇳🇱 NL | Public | 🤝 | Coordinated Vulnerability Disclosure |
| [NCSC-FI CVD](https://www.kyberturvallisuuskeskus.fi/) | 🇫🇮 FI | Public | 🤝 | Finnish national cyber centre |
| [CCB Belgium CVD](https://ccb.belgium.be/) | 🇧🇪 BE | Public | 🤝 | Centre for Cybersecurity Belgium |
| [CERT Polska CVD](https://cert.pl/) | 🇵🇱 PL | Public | 🤝 | Polish national CERT |
| [DIVD](https://www.divd.nl/) | 🇳🇱 NL | Public | 🤝 | Dutch Institute for Vulnerability Disclosure |
| [Australian Government VDP](https://www.cyber.gov.au/) | 🇦🇺 AU | Public | 🤝 | ACSC-coordinated disclosure |
| [Singapore GovTech VDP](https://www.tech.gov.sg/report_vulnerability/) | 🇸🇬 SG | Public | 🤝 | Whole-of-government VDP |
| [bugbounty.sa](https://bugbounty.sa/) | 🇸🇦 KSA | Both | 💰 | Saudi national bug bounty |
| [UAE National Bug Bounty](https://csc.gov.ae/) | 🇦🇪 UAE | Both | 💰 | UAE Cyber Security Council program |
| [Qatar Bug Bounty](https://ncsa.gov.qa/) | 🇶🇦 QA | Both | 💰 | National Cyber Security Agency |
| [KISA KNVD](https://knvd.krcert.or.kr/) | 🇰🇷 KR | Public | 💰 | Korea national vulnerability DB & rewards |
| [Japan Vulnerability Notes (JVN)](https://jvn.jp/) | 🇯🇵 JP | Public | 🤝 | JPCERT/IPA coordinated disclosure |
| [NCIIPC RVDP](https://www.nciipc.gov.in/) | 🇮🇳 IN | Public | 🤝 | Critical infrastructure disclosure |
| [CERT-In RVDCP](https://www.cert-in.org.in/) | 🇮🇳 IN | Public | 🤝 | Indian national CERT |
| [HITCON ZeroDay](https://zeroday.hitcon.org/) | 🇹🇼 TW | Public | 🤝 | Taiwan vulnerability coordination |
| [NKSC Lithuania CVD](https://www.nksc.lt/) | 🇱🇹 LT | Public | 🤝 | National cyber security centre |

---

### 3. Web3 & smart-contract platforms

Crypto/DeFi bounties — the highest individual payouts in the industry (7-figure criticals exist), usually paid in crypto.

| Platform | Region | Programs | Rewards | Notes |
|----------|--------|----------|---------|-------|
| [Immunefi](https://immunefi.com/) | 🌍 Global | Both | ₿ 💰 | The dominant Web3 platform; largest bounties on record |
| [Code4rena](https://code4rena.com/) | 🌍 Global | Public | ₿ | Competitive audit contests ("wardens") |
| [Sherlock](https://www.sherlock.xyz/) | 🌍 Global | Public | ₿ | Audit contests + coverage/insurance model |
| [Cantina](https://cantina.xyz/) | 🌍 Global | Both | ₿ | Spearbit's marketplace: contests + private audits |
| [CodeHawks](https://www.codehawks.com/) | 🌍 Global | Public | ₿ | Cyfrin's competitive audit platform |
| [Hats Finance](https://hats.finance/) | 🌍 Global | Both | ₿ | Decentralized, on-chain bounties |
| [HackenProof](https://hackenproof.com/) | 🌍 Global | Both | ₿ 💰 | Web3 + Web2, crypto payouts |
| [Secure3](https://www.secure3.io/) | 🌍 Global | Both | ₿ | Audit contests + managed audits |
| [CertiK Bug Bounty](https://www.certik.com/products/bug-bounty) | 🌍 Global | Both | ₿ | Tied to CertiK's audit ecosystem |
| [Remedy (Remedium)](https://remedy.org/) | 🌍 Global | Both | ₿ | Web3 vulnerability disclosure |
| [Cyfrin / CodeHawks](https://www.cyfrin.io/) | 🌍 Global | Public | ₿ | Audits + competitive contests |
| [OpenBounty (Shentu)](https://www.openbounty.io/) | 🌍 Global | Both | ₿ | Shentu Chain bounties |
| [AuditOne](https://www.auditone.io/) | 🌍 Global | Both | ₿ | Audits + bounties marketplace |
| [BugRap](https://bugrap.io/) | 🌍 Global | Both | ₿ | Web3 bug reporting |
| [Hashlock](https://hashlock.com/) | 🇦🇺 AU | Both | ₿ | Smart-contract audits + bounties |
| [SlowMist](https://www.slowmist.com/) | 🇨🇳 CN | Both | ₿ | Blockchain security firm + disclosure |

---

### 4. AI & LLM security platforms

The newest category — prompt injection, jailbreaks, model & agent security.

| Platform | Region | Programs | Rewards | Notes |
|----------|--------|----------|---------|-------|
| [Huntr](https://huntr.com/) | 🌍 Global | Public | 💰 | Bounties for AI/ML open-source (models, libs, tooling) |
| [Gray Swan Arena](https://www.grayswan.ai/) | 🌍 Global | Public | 💰 | Red-teaming arenas & jailbreak challenges |
| [HackAPrompt](https://www.hackaprompt.com/) | 🌍 Global | Public | 💰 🏅 | Large-scale prompt-injection competitions |
| [ødin (0din)](https://0din.ai/) | 🌍 Global | Public | 💰 | Mozilla's GenAI bug bounty program |
| [Anthropic Model Safety Bounty](https://www.anthropic.com/) | 🌍 Global | Both | 💰 | Model safety / jailbreak bounties (program-based) |

---

### 5. Vulnerability acquisition & brokered disclosure

These **buy** vulnerabilities/exploits or broker disclosure to vendors. Payouts can be very high; terms differ sharply from classic bounties — read them carefully.

| Platform | Region | Programs | Rewards | Notes |
|----------|--------|----------|---------|-------|
| [Zero Day Initiative (ZDI)](https://www.zerodayinitiative.com/) | 🌍 Global | Public | 💰 | Trend Micro; buys 0-days, runs Pwn2Own |
| [SSD Secure Disclosure](https://ssd-disclosure.com/) | 🌍 Global | Public | 💰 | Acquires high-impact vulnerabilities |

---

### 6. Ecosystem-specific platforms

Focused on one software ecosystem.

| Platform | Region | Programs | Rewards | Notes |
|----------|--------|----------|---------|-------|
| [Patchstack](https://patchstack.com/) | 🌍 Global | Both | 💰 | WordPress plugin/theme security |
| [Wordfence Bug Bounty](https://www.wordfence.com/threat-intel/bug-bounty-program/) | 🌍 Global | Public | 💰 | WordPress ecosystem |
| [IssueHunt](https://issuehunt.io/) | 🌍 Global | Public | 💰 | Open-source issue bounties |

---

### 7. Self-hosted / open-source VDP tooling

For **organizations** that want to run disclosure in-house instead of on a marketplace.

| Project | Type | Notes |
|---------|------|-------|
| [security.txt](https://securitytxt.org/) | Standard (RFC 9116) | Publish a `/.well-known/security.txt` so researchers know where to report |
| [disclose.io](https://disclose.io/) | Framework | Standardized safe-harbor & disclosure policy templates |
| [Firebounty](https://firebounty.com/) | Aggregator | Search engine indexing thousands of existing programs/scopes |

---

## 🧭 How to choose the right platform

| If you are… | Start with… | Why |
|-------------|-------------|-----|
| **A complete beginner** | Bugcrowd, Intigriti, YesWeHack, Open Bug Bounty | Many public programs, good docs, forgiving communities |
| **Chasing reputation for invites** | HackerOne, Bugcrowd | Largest private-program pipelines gated on public rep |
| **In the EU / GDPR-sensitive** | Intigriti, YesWeHack, Zerocopter, GObugfree | EU-based data handling & programs |
| **In MENA / Gulf** | bugbounty.sa, CyberTalents, BugBounter | Regional programs & payouts |
| **In South / Southeast Asia** | Bugbase, Secuna, WhiteHub, RedStorm | Strong local program pools |
| **Into crypto / DeFi** | Immunefi, Code4rena, Sherlock, Cantina | Highest payouts; crypto-native |
| **Into AI / LLMs** | Huntr, Gray Swan, 0din, HackAPrompt | Prompt injection, jailbreaks, model security |
| **An elite pentester wanting steady pay** | Synack, Cobalt, Yogosha | Vetted, invite-only, more predictable income |
| **Doing pure good-will disclosure** | Government VDPs, Open Bug Bounty | Kudos + real-world impact |

**Rules of thumb**
- 💰 vs ₿: Web2 platforms pay fiat/PayPal; Web3 pays crypto — factor in tax & volatility.
- **Public first, private later:** build reputation on public programs to unlock higher-paying private invites.
- **Scope is everything:** the biggest scope with the fewest hunters usually beats a famous program everyone camps on.

---

## 🚀 Beginner roadmap (zero → first bounty)

1. **Learn the web fundamentals.** HTTP, cookies/sessions, same-origin policy, DNS, TLS.
2. **Master the OWASP Top 10.** IDOR, XSS, SSRF, auth flaws, access control — where most bounties actually live.
3. **Set up a lab.** [PortSwigger Web Security Academy](https://portswigger.net/web-security) (free), DVWA, OWASP Juice Shop, PentesterLab.
4. **Learn Burp Suite** end-to-end (proxy, Repeater, Intruder, extensions).
5. **Pick ONE public program with a big scope** and read every word of its policy and scope.
6. **Do recon** (see below), map the attack surface, and go deep on one feature.
7. **Focus on high-signal bugs first:** IDOR/BOLA, access control, and business-logic flaws are beginner-friendly and pay well.
8. **Write a clean report** (template below) with a clear PoC and realistic impact.
9. **Iterate.** Read every disclosed report you can. Rejections are tuition.
10. **Build reputation → get private invites → higher payouts.**

---

## 🛠️ Essential recon & tooling

> Use these **only against in-scope targets you're authorized to test.**

**Recon & attack surface**
- Subdomains: `subfinder`, `amass`, `assetfinder`
- Live hosts / probing: `httpx`, `naabu`
- Content discovery: `ffuf`, `feroxbuster`, `dirsearch`
- Historical URLs: `gau`, `waybackurls`, `katana`
- Templated scanning: `nuclei` (+ community templates)

**Interception & exploitation**
- [Burp Suite](https://portswigger.net/burp) (Community/Pro) — the industry standard
- [OWASP ZAP](https://www.zaproxy.org/) — free, open-source alternative
- [Caido](https://caido.io/) — modern lightweight proxy

**Specialized**
- `sqlmap` (SQLi), `nikto`, `nmap`, `gitleaks`/`trufflehog` (secrets)
- JS analysis: `linkfinder`, `getjs`, source-map extractors
- Mobile: `MobSF`, `frida`, `objection`, `apktool`

---

## 📝 Writing a great report

A good report gets triaged fast and paid more. Use this template:

```markdown
## Title
[Vuln type] on [endpoint/feature] leading to [impact]

## Summary
One or two sentences: what the bug is and why it matters.

## Steps to Reproduce
1. Go to ...
2. Send this request: ...
3. Observe ...

## Proof of Concept
[Minimal request/response, screenshot, or short video]

## Impact
What an attacker can actually do (data exposed, accounts taken over, funds moved).

## Affected Asset / Scope
Exact URL(s), parameter(s), and confirmation it is in scope.

## Remediation
Concrete fix suggestion (e.g., enforce object-level authorization).
```

**Do:** be concise, prove real impact, respect rate limits.
**Don't:** run automated scanners where forbidden, test out-of-scope assets, access more data than needed to prove the bug, or disclose publicly before resolution.

---

## ⚖️ Legal, ethics & safe harbor

- **Authorization is mandatory.** Only test assets that are **explicitly in scope** on a program you've joined. Testing anything else can be a crime (CFAA, Computer Misuse Act, and local equivalents).
- **Stay in scope.** Out-of-scope testing is the fastest way to a ban — or a lawsuit.
- **Minimize harm.** No DoS, no data exfiltration beyond proof, no pivoting, no social engineering unless explicitly allowed.
- **Read the safe-harbor clause.** Many programs adopt [disclose.io](https://disclose.io/) terms; some don't offer legal protection at all.
- **Respect disclosure timelines.** Coordinate; don't drop 0-days publicly.
- **When in doubt, ask** the program before testing an edge case.

---

## 📚 Learning resources

- [PortSwigger Web Security Academy](https://portswigger.net/web-security) — free, best-in-class
- [OWASP Top 10](https://owasp.org/www-project-top-ten/) & [Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)
- [HackerOne Hacktivity](https://hackerone.com/hacktivity) & [disclosed reports](https://github.com/reddelexc/hackerone-reports)
- [PentesterLab](https://pentesterlab.com/), [TryHackMe](https://tryhackme.com/), [Hack The Box](https://www.hackthebox.com/)
- [Bug Bounty Playbook](https://github.com/EdOverflow/bugbounty-cheatsheet) & community write-ups
- [Web3] [Secureum](https://www.secureum.xyz/), [Cyfrin Updraft](https://updraft.cyfrin.io/)

---

## 📖 Glossary

| Term | Meaning |
|------|---------|
| **VDP** | Vulnerability Disclosure Program — accepts reports, usually no cash |
| **BBP** | Bug Bounty Program — pays rewards for valid findings |
| **PTaaS** | Pentest-as-a-Service — vetted testers, time-boxed, paid engagements |
| **Scope** | Assets you're authorized to test (in-scope) vs forbidden (out-of-scope) |
| **Triage** | Platform/vendor validating and prioritizing your report |
| **Duplicate** | A bug already reported by someone else (usually unpaid) |
| **P1–P5 / Critical–Info** | Severity ratings (P1/Critical = most severe) |
| **CVSS** | Common Vulnerability Scoring System (0–10 severity) |
| **Safe harbor** | Legal protection for good-faith research within policy |
| **IDOR / BOLA** | Insecure Direct Object Reference / Broken Object Level Authorization |
| **PoC** | Proof of Concept demonstrating the vulnerability |
| **Bounty pool** | Total budget a program allocates to rewards |

---

## 🤝 Contributing

Contributions are welcome and encouraged! To add or fix a platform:

1. **Fork** this repo and create a branch.
2. Add the platform to **exactly one** category (use the precedence: Government → Web3 → AI → Acquisition → Ecosystem → General).
3. Keep entries **alphabetical-ish** within a section and fill **every column**.
4. Use the emoji legend for the **Rewards** column.
5. Only add **legitimate, active** platforms with a working official URL.
6. Open a **Pull Request** describing the change and your source.

**Please don't** add platforms that facilitate illegal activity, unauthorized access, or the sale of exploits to non-vendors.

---

## ⚠️ Disclaimer

This list is provided for **educational and informational purposes only**. Inclusion here is **not** an endorsement. Always perform testing **only** on systems you own or are **explicitly authorized** to test, and strictly within each program's published scope and rules. The maintainers are not responsible for misuse. Platform data may be outdated — verify on the official site.

---

## 📄 License

Released under [Creative Commons Attribution 4.0 (CC BY 4.0)](./LICENSE). Free to share and adapt with attribution.

<div align="center">

**⭐ If this helped you, star the repo and share it with a fellow hunter.**

*Happy (ethical) hacking.* 🐞

</div>
