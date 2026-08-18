# Cybersecurity VAPT & Bug Bounty Reference

![Category](https://img.shields.io/badge/category-VAPT%20%7C%20Bug%20Bounty-blue)
![Focus](https://img.shields.io/badge/focus-Web%20%26%20API%20Security-informational)
![Maintained](https://img.shields.io/badge/maintained-yes-brightgreen)
![License](https://img.shields.io/badge/use-authorized%20testing%20only-critical)

A curated, categorized reference of web security, API security, reconnaissance, OSINT, attack-surface discovery, vulnerability research, payload generation, learning platforms, and supporting tools for penetration testing and bug bounty hunting.

> **Scope of use:** Every resource listed here is intended strictly for systems and assets that you own or are explicitly authorized to test. Unauthorized testing against third-party systems is illegal.

---

## Table of Contents

1. [Quick Tool Selection](#1-quick-tool-selection)
2. [Reconnaissance and Attack Surface Discovery](#2-reconnaissance-and-attack-surface-discovery)
3. [DNS, Domains, IP and Network Intelligence](#3-dns-domains-ip-and-network-intelligence)
4. [OSINT and Threat Intelligence](#4-osint-and-threat-intelligence)
5. [Search Engines and Dorking](#5-search-engines-and-dorking)
6. [Bug Bounty Dork Collections](#6-bug-bounty-dork-collections)
7. [File and Asset Discovery](#7-file-and-asset-discovery)
8. [Source Code and Vulnerability Intelligence](#8-source-code-and-vulnerability-intelligence)
9. [Secrets, API Keys and Credential Validation](#9-secrets-api-keys-and-credential-validation)
10. [JWT and Token Analysis](#10-jwt-and-token-analysis)
11. [XSS Testing](#11-xss-testing)
12. [SSRF, OOB and Blind Vulnerability Testing](#12-ssrf-oob-and-blind-vulnerability-testing)
13. [LFI, Command Injection and Payload Generation](#13-lfi-command-injection-and-payload-generation)
14. [GraphQL Security Testing](#14-graphql-security-testing)
15. [CSP and Client-Side Security](#15-csp-and-client-side-security)
16. [SQL Injection Support](#16-sql-injection-support)
17. [Browser Extensions](#17-browser-extensions)
18. [Developer and Analysis Utilities](#18-developer-and-analysis-utilities)
19. [Pentesting Cheatsheets and Checklists](#19-pentesting-cheatsheets-and-checklists)
20. [Recommended VAPT Workflow](#20-recommended-vapt-workflow)
21. [Reference Notes](#21-reference-notes)
22. [Additional Curated Resources](#22-additional-curated-resources)
    - [Bug Bounty Platforms](#bug-bounty-platforms)
    - [Practice Labs and Vulnerable Applications](#practice-labs-and-vulnerable-applications)
    - [Learning Platforms and Practice Grounds](#learning-platforms-and-practice-grounds)
    - [Roadmaps, Checklists and Methodologies](#roadmaps-checklists-and-methodologies)
    - [Cheatsheets, Payloads and Wordlists](#cheatsheets-payloads-and-wordlists)
    - [Awesome Lists and Curated Tool Collections](#awesome-lists-and-curated-tool-collections)
    - [OSINT Tools (Additional)](#osint-tools-additional)
    - [Google Dorking Resources (Additional)](#google-dorking-resources-additional)
    - [Burp Suite Guides and Extensions](#burp-suite-guides-and-extensions)
    - [Reconnaissance and Exploitation Tools (Additional)](#reconnaissance-and-exploitation-tools-additional)
    - [Bug Bounty Writeups and Case Studies](#bug-bounty-writeups-and-case-studies)
    - [Video Tutorials and Playlists](#video-tutorials-and-playlists)
    - [Communities, Blogs, News and Podcasts](#communities-blogs-news-and-podcasts)
    - [Miscellaneous References](#miscellaneous-references)

---

# 1. Quick Tool Selection

Use this section as the fastest way to select an appropriate resource.

| Objective | Recommended Resources |
|---|---|
| Discover exposed internet assets | Shodan, Censys, FOFA, ZoomEye, Netlas, FullHunt |
| Discover subdomains | SecurityTrails, TriNetLayer, Subdomain Finder, ViewDNS |
| Investigate historical assets | Wayback Machine, VirusTotal, Intelligence X |
| Search exposed services | Shodan, Censys, FOFA, ZoomEye, Hunter.how |
| Search public source code | Grep.app, SearchCode |
| Search known vulnerabilities | Vulners, Exploit-DB GHDB |
| Generate search dorks | DorkGPT, AI Dork Builder, DorkKing, Elite Dork Forge |
| Find bug-bounty-specific dorks | TakSec Dorks, Xen00rw Dorks, Deep Dork Web |
| Search exposed files | FileHunt, FilePhish |
| Analyze JWTs | Token.dev, JWT Auditor |
| Test XSS | XSSnow, XSS0r, XSS.Report, XSS Parameter Extractor |
| Test SSRF/OOB behavior | Interactsh, Pingback.sh |
| Generate reverse-shell payloads | RevShells, Reverse Shell Generator |
| Generate LFI payloads | ExecEvasion |
| Test GraphQL | GQL Hunter |
| Review JavaScript dependencies | Retire.js |
| Validate exposed secrets | Secrets Ninja, Keyhacks, Trinetlayer Validator |
| Research CSP bypasses | CSP Bypass |
| Generate SQLMap commands | SQLMap Command Generator |
| General reconnaissance | Web-Check, InstRecon, Tiny-Scan, Argus |

---

# 2. Reconnaissance and Attack Surface Discovery

## 2.1 Internet Asset Search Engines

### Shodan
**Category:** Attack Surface / Service Discovery  
**Use:** Internet-facing hosts, services, ports, banners, certificates and exposed infrastructure.

https://www.shodan.io/

### Censys
**Category:** Attack Surface / Certificate Intelligence  
**Use:** Internet infrastructure, hosts, certificates, services and network exposure.

https://search.censys.io/

### FOFA
**Category:** Cyberspace Search  
**Use:** Internet-facing assets, services, technologies and infrastructure discovery.

https://en.fofa.info/

### FullHunt
**Category:** Attack Surface Management  
**Use:** Domain, subdomain, IP and external attack-surface discovery.

https://fullhunt.io/

### Hunter.how
**Category:** Internet Asset Search  
**Use:** Search and investigate internet-facing infrastructure.

https://hunter.how/

### Netlas
**Category:** Attack Surface / Asset Discovery  
**Use:** Internet asset discovery, services, domains and infrastructure.

https://netlas.io/

### ZoomEye
**Category:** Cyberspace Search  
**Use:** Internet-connected devices, services and infrastructure discovery.

https://www.zoomeye.ai/

---

## 2.2 Reconnaissance Platforms

### Argus
**Category:** Reconnaissance  
**Use:** Security reconnaissance and target intelligence.

https://argus.cobrasec.pro/

### InstRecon
**Category:** Reconnaissance  
**Use:** Quick target reconnaissance and information gathering.

https://www.instrecon.site/

### RootXVishal Recon
**Category:** Reconnaissance  
**Use:** Target intelligence and reconnaissance.

https://recon.rootxvishal.com/

### Tiny-Scan
**Category:** Reconnaissance  
**Use:** Lightweight scanning and target enumeration.

https://www.tiny-scan.com/

### Web-Check
**Category:** Web Reconnaissance  
**Use:** Website information gathering, technology identification and security reconnaissance.

https://web-check.xyz/check/

---

## 2.3 Crawling and Endpoint Discovery

### RootXVishal Crawler
**Category:** Web Crawling  
**Use:** Web crawling, endpoint discovery and spidering.

https://crawler.rootxvishal.com/

### FileHunt
**Category:** File Discovery  
**Use:** Search and discover potentially exposed files and assets.

https://filehunt.3kh0.net/

### FilePhish
**Category:** File Discovery  
**Use:** File and asset discovery research.

https://greylensresearch.github.io/filephish/

---

# 3. DNS, Domains, IP and Network Intelligence

## 3.1 DNS and Domain Intelligence

### SecurityTrails
**Category:** DNS / Domain Intelligence  
**Use:** DNS records, historical DNS, domains, subdomains and infrastructure relationships.

https://securitytrails.com/

### Subdomain Finder
**Category:** Subdomain Enumeration  
**Use:** Subdomain discovery.

https://recox.hackerz.space/

### TriNetLayer Subdomain Scanner
**Category:** Subdomain Enumeration  
**Use:** Subdomain and infrastructure discovery.

https://trinetlayer.com/

### ViewDNS
**Category:** DNS / Network Intelligence  
**Use:** DNS, WHOIS, IP and domain investigation.

https://viewdns.info/

### WhoXY
**Category:** WHOIS / Domain Intelligence  
**Use:** Domain and WHOIS-related research.

https://www.whoxy.com/

---

## 3.2 Network and Routing Intelligence

### BGP Toolkit - Hurricane Electric
**Category:** BGP / ASN / Network Intelligence  
**Use:** ASN, BGP routes, prefixes and network ownership research.

https://bgp.he.net/

### Netcraft SearchDNS
**Category:** DNS Intelligence  
**Use:** DNS and domain infrastructure research.

https://searchdns.netcraft.com/

### THC IP
**Category:** IP Intelligence  
**Use:** IP and network-related research.

https://ip.thc.org/

---

# 4. OSINT and Threat Intelligence

### Behind The Email
**Category:** Email OSINT  
**Use:** Email-related open-source intelligence.

https://behindtheemail.com/

### Intelligence X
**Category:** OSINT / Threat Intelligence  
**Use:** Intelligence searches across multiple data sources.

https://intelx.io/

### OSINT Framework
**Category:** OSINT Directory  
**Use:** Directory of OSINT resources organized by investigation category.

https://osintframework.com/

### OSINTNova
**Category:** OSINT  
**Use:** Open-source intelligence and investigation workflows.

https://app.osintnova.com/

### VirusTotal
**Category:** Threat Intelligence  
**Use:** File, URL, domain, IP and malware intelligence.

https://www.virustotal.com/

### Wayback Machine
**Category:** Historical Web Intelligence  
**Use:** Historical versions of websites, URLs and web content.

https://web.archive.org/

### Kagi
**Category:** Search Engine  
**Use:** Alternative general-purpose web search.

https://kagi.com/

---

# 5. Search Engines and Dorking

## 5.1 General Search and Syntax

### Google Advanced Search
**Category:** Search  
**Use:** Advanced Google search filters and operators.

https://www.google.com/advanced_search

### GoldenOwl Syntax
**Category:** Search Syntax  
**Use:** Search syntax and query construction reference.

https://syntax.goldenowl.ai/

### Recruit'em
**Category:** Search / OSINT  
**Use:** Search assistance for professional and social profiles.

https://recruitin.net/

---

## 5.2 Dork Generators

### AI Dork Builder
**Category:** AI / Dork Generation  
**Use:** Generate search queries and dorks.

https://deepfind.me/tools/search-and-discovery/ai-google-dork-builder

### DorkGPT
**Category:** AI / Dork Generation  
**Use:** AI-assisted search-dork generation.

https://www.dorkgpt.com/

### DorkKing
**Category:** Dork Generation  
**Use:** Search-dork generation.

https://dorkking.blindf.com/

### Dork Engine
**Category:** Dork Generation  
**Use:** Search-dork generation.

https://dorkengine.github.io/

### DorkSearch
**Category:** Dork Search  
**Use:** Search and discover search-engine dorks.

https://dorksearch.com/

### DorkSearch2
**Category:** Dork Search  
**Use:** Search-dork discovery.

https://dorksearch.pro/

### Elite Dork Forge
**Category:** Dork Generation  
**Use:** Advanced search-dork generation.

https://elite-dork-forge.lovable.app/

---

# 6. Bug Bounty Dork Collections

### Bug Bounty Search Engine
**Category:** Bug Bounty Recon  
**Use:** Search engine focused on bug-bounty reconnaissance.

https://nitinyadav00.github.io/Bug-Bounty-Search-Engine/

### Deep Dork Web
**Category:** Bug Bounty Dorks  
**Use:** Search and dork resources for security research.

https://guilherme-moraiss.github.io/Deep-Dork-Web/

### Dork For Me
**Category:** Search / Dorking  
**Use:** Search-dork assistance.

https://securitytoolkits.com/dork-for-me

### Exploit-DB Google Hacking Database
**Category:** Search / Dork Reference  
**Use:** Established collection of Google search operators and security-focused queries.

https://www.exploit-db.com/google-hacking-database

### ReconEngines
**Category:** Recon / Dorking  
**Use:** Reconnaissance and search resources.

https://h6nt3r.github.io/reconengines/

### Shadoh Dorks
**Category:** Bug Bounty Dorks  
**Use:** Search dorks for security research.

https://shadohdorks.vercel.app/

### TakSec Dorks
**Category:** Bug Bounty Dorks  
**Use:** Google dorks specifically oriented toward bug bounty reconnaissance.

https://taksec.github.io/google-dorks-bug-bounty/

### Xen00rw Dorks
**Category:** Bug Bounty Dorks  
**Use:** Security and bug bounty search dorks.

https://dorks.xen00rw.me/

---

# 7. File and Asset Discovery

### FileHunt
**Category:** File Discovery  
**Use:** Identify potentially exposed files and assets.

https://filehunt.3kh0.net/

### FilePhish
**Category:** File Discovery  
**Use:** File and asset discovery research.

https://greylensresearch.github.io/filephish/

---

# 8. Source Code and Vulnerability Intelligence

## 8.1 Source Code Search

### Grep.app
**Category:** Source Code Search  
**Use:** Search publicly indexed source code for keywords, secrets, endpoints and implementation patterns.

https://grep.app/

### SearchCode
**Category:** Source Code Search  
**Use:** Search publicly available source code.

https://searchcode.com/

---

## 8.2 Vulnerability Intelligence

### Vulners
**Category:** Vulnerability Intelligence  
**Use:** CVEs, vulnerabilities, advisories and exploit intelligence.

https://vulners.com/

### Exploit-DB Google Hacking Database
**Category:** Security Research  
**Use:** Search-engine reconnaissance and query research.

https://www.exploit-db.com/google-hacking-database

---

# 9. Secrets, API Keys and Credential Validation

### Keyhacks
**Category:** Secret / API Key Validation  
**Use:** Identify and test exposed API keys and credentials.

https://github.com/streaak/keyhacks

### Secrets Ninja - AWS
**Category:** AWS Secret Validation  
**Use:** AWS-related secret and credential validation.

https://secrets.ninja/aws

### Trinetlayer Validator
**Category:** Secret Validation  
**Use:** Validate potentially exposed secrets and credentials.

https://validator.trinetlayer.com

### BlindF GoogleKey
**Category:** Google API Key Testing  
**Use:** Test Google API key behavior and exposure.

https://blindf.com/googlekey/

---

# 10. JWT and Token Analysis

### JWT Auditor
**Category:** JWT Security  
**Use:** Analyze JWT implementation and security properties.

https://jwtauditor.com/

### Token.dev
**Category:** JWT / Token Analysis  
**Use:** Decode and inspect tokens.

https://token.dev/

---

# 11. XSS Testing

## 11.1 XSS Payload and Testing Platforms

### XSSnow
**Category:** XSS  
**Use:** XSS payload generation and testing.

https://xssnow.in/index.html

### XSS0r
**Category:** Blind XSS  
**Use:** Blind XSS payload management and testing.

https://xss0r.com/

### XSS.Report
**Category:** Blind XSS  
**Use:** Blind XSS testing and interaction monitoring.

https://xss.report/dashboard

### XSS Parameter Extractor
**Category:** XSS Reconnaissance  
**Use:** Identify parameters relevant to XSS testing.

https://xss.bugbountyhunt.com/

---

# 12. SSRF, OOB and Blind Vulnerability Testing

### Interactsh
**Category:** OOB / SSRF  
**Use:** Detect out-of-band interactions generated by target systems.

https://app.interactsh.com/

### Pingback.sh
**Category:** OOB / SSRF / Blind Testing  
**Use:** Monitor out-of-band interactions and blind vulnerabilities.

https://pingback.sh/

---

# 13. LFI, Command Injection and Payload Generation

## 13.1 LFI and Evasion

### ExecEvasion
**Category:** LFI / Payload Generation  
**Use:** Generate and investigate LFI-oriented payload and evasion techniques.

https://dr34mhacks.github.io/ExecEvasion/index.html

---

## 13.2 Reverse Shell Generation

### Reverse Shell Generator
**Category:** Reverse Shells  
**Use:** Generate reverse-shell commands for authorized lab and assessment environments.

https://tex2e.github.io/reverse-shell-generator/index.html

### RevShells
**Category:** Reverse Shells  
**Use:** Generate reverse-shell payloads and commands.

https://www.revshells.com/

---

# 14. GraphQL Security Testing

### GQL Hunter
**Category:** GraphQL Security  
**Use:** GraphQL reconnaissance and security testing.

https://gqlhunter.vercel.app/

---

# 15. CSP and Client-Side Security

### CSP Bypass
**Category:** CSP / Web Security  
**Use:** Research and test Content Security Policy bypass scenarios.

https://cspbypass.com/

---

# 16. SQL Injection Support

### SQLMap Command Generator
**Category:** SQL Injection / SQLMap  
**Use:** Assist with constructing SQLMap command syntax.

https://acorzo1983.github.io/SQLMapCG/

---

# 17. Browser Extensions

## Firefox

### DOMLogger++
**Category:** Browser Security / XSS  
**Use:** Monitor DOM activity and assist with client-side XSS research.

https://addons.mozilla.org/en-US/firefox/addon/domloggerpp/

### FancyTracker
**Category:** Browser / Tracking Analysis  
**Use:** Analyze trackers and client-side scripts.

https://addons.mozilla.org/en-US/firefox/addon/fancytracker-ff/

### Multi-Account Containers
**Category:** Browser Session Isolation  
**Use:** Isolate multiple accounts and browser sessions.

https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/

### Retire.js
**Category:** JavaScript Security  
**Use:** Identify outdated or vulnerable JavaScript libraries.

https://addons.mozilla.org/en-US/firefox/addon/retire-js/

---

# 18. Developer and Analysis Utilities

### Devina.io
**Category:** Developer / Security Utilities  
**Use:** Encoding, decoding, formatting and general developer utilities.

https://devina.io/

---

# 19. Pentesting Cheatsheets and Checklists

### BugBounty.zip
**Category:** Bug Bounty Reference  
**Use:** Bug bounty resources and reference material.

https://bugbounty.zip/

### Pentest Cheatsheet
**Category:** Pentesting Reference  
**Use:** Penetration-testing commands, techniques and references.

https://anshu19981.github.io/Pentestcheatsheet/

### Security Checklist
**Category:** Security Assessment Checklist  
**Use:** Security testing and assessment checklist.

https://aisearch.bugbountyhunt.com/security-checklist

---

# 20. Recommended VAPT Workflow

The following workflow provides a practical structure for an authorized web or API assessment.

## Phase 1 - Scope and Asset Identification

**Primary objective:** Establish the complete authorized attack surface.

Recommended resources:

- FullHunt
- Netlas
- Shodan
- Censys
- FOFA
- ZoomEye

Record:

- Root domains
- Subdomains
- IP addresses
- Autonomous Systems
- Cloud assets
- Exposed services
- Technology fingerprints
- Certificate relationships

---

## Phase 2 - Domain and DNS Enumeration

**Primary objective:** Identify domain relationships and infrastructure.

Recommended resources:

- SecurityTrails
- ViewDNS
- TriNetLayer Subdomain Scanner
- Subdomain Finder
- BGP Toolkit
- Netcraft SearchDNS
- WhoXY

Record:

- A/AAAA records
- CNAME records
- MX records
- NS records
- TXT records
- Historical DNS
- Related domains
- ASN and IP ownership

---

## Phase 3 - Historical and OSINT Research

**Primary objective:** Identify previously exposed or forgotten assets.

Recommended resources:

- Wayback Machine
- VirusTotal
- Intelligence X
- OSINT Framework
- OSINTNova
- Behind The Email

Look for:

- Old endpoints
- Deprecated subdomains
- Historical application versions
- Exposed documents
- Development environments
- Legacy APIs
- Publicly disclosed information

---

## Phase 4 - Web Crawling and Endpoint Discovery

**Primary objective:** Build an endpoint inventory.

Recommended resources:

- RootXVishal Crawler
- Web-Check
- FileHunt
- FilePhish
- InstRecon
- Tiny-Scan

Record:

- URLs
- API endpoints
- Parameters
- JavaScript files
- Static resources
- File paths
- Authentication boundaries

---

## Phase 5 - Search Engine and Dorking Research

**Primary objective:** Identify publicly indexed resources relevant to the authorized scope.

Recommended resources:

- Google Advanced Search
- Exploit-DB GHDB
- TakSec Dorks
- Xen00rw Dorks
- Deep Dork Web
- DorkGPT
- AI Dork Builder
- DorkSearch
- DorkKing

Use dorking primarily for:

- Publicly indexed application resources
- Legacy endpoints
- Documentation
- Public files
- Development artifacts
- Technology identification

---

## Phase 6 - Source Code and Dependency Research

**Primary objective:** Identify implementation details and vulnerable dependencies.

Recommended resources:

- Grep.app
- SearchCode
- Vulners
- Retire.js

Investigate:

- API endpoints
- Hardcoded configuration
- Client-side secrets
- Third-party libraries
- Vulnerable dependencies
- Framework versions
- Security-sensitive functionality

---

## Phase 7 - Authentication and Token Testing

**Primary objective:** Assess authentication and authorization mechanisms.

Recommended resources:

- Token.dev
- JWT Auditor
- Keyhacks
- Secrets Ninja
- Trinetlayer Validator

Test areas may include:

- JWT structure and claims
- Token validation
- Algorithm handling
- Expiration
- Key exposure
- API key exposure
- Authorization boundaries

---

## Phase 8 - Vulnerability-Specific Testing

Select tools according to the application's attack surface.

### XSS

- XSSnow
- XSS0r
- XSS.Report
- XSS Parameter Extractor

### SSRF / OOB

- Interactsh
- Pingback.sh

### GraphQL

- GQL Hunter

### SQL Injection

- SQLMap Command Generator

### LFI

- ExecEvasion

### CSP

- CSP Bypass

### Reverse Shells

- RevShells
- Reverse Shell Generator

---

## Phase 9 - Validation

Validate findings before reporting.

For each finding:

1. Confirm that the behavior is reproducible.
2. Determine whether exploitation is actually possible.
3. Identify the affected component.
4. Determine the security boundary being crossed.
5. Assess confidentiality, integrity and availability impact.
6. Capture the minimum evidence required.
7. Avoid unnecessary access to sensitive information.
8. Confirm that testing remains within scope.

---

## Phase 10 - Reporting

For each confirmed vulnerability, document:

- Vulnerability title
- Severity
- Affected URL or endpoint
- Description
- Technical details
- Preconditions
- Steps to reproduce
- Proof of concept
- Impact
- CWE
- OWASP mapping where applicable
- Recommendation
- References
- Supporting evidence

---

# 21. Reference Notes

## Tool Selection Principles

Do not treat a tool result as a confirmed vulnerability.

A discovery tool can identify:

- A host
- A service
- A technology
- A potentially exposed secret
- An endpoint
- A historical artifact
- A suspicious configuration

A vulnerability should be reported only after appropriate validation demonstrates a security impact.

## Recommended Evidence Collection

Maintain a consistent evidence structure during assessments:

```text
01-scope/
02-recon/
03-subdomains/
04-hosts/
05-urls/
06-endpoints/
07-javascript/
08-authentication/
09-vulnerabilities/
10-evidence/
11-report/
```

For each confirmed finding, maintain:

```text
finding-name/
├── request.txt
├── response.txt
├── screenshots/
├── poc/
└── notes.md
```

## Operational Rule

Always verify:

1. The target is in scope.
2. The test is permitted by the engagement rules.
3. The technique does not cause unnecessary disruption.
4. Sensitive information is handled appropriately.
5. Evidence is sufficient to reproduce the issue.
6. The final severity reflects demonstrated impact rather than tool output alone.

---


---

# 22. Additional Curated Resources

The following resources were consolidated from an external bookmark collection. They supplement the categories above with extra platforms, practice labs, learning material, cheatsheets, writeups and videos for bug bounty and VAPT work.

### Bug Bounty Platforms

- [Ask a Hacker (Bugcrowd)](https://forum.bugcrowd.com/c/ask-a-hacker/34)
- [BBP Finder](https://xitsec.in/bbp-finder.html)
- [Bug Bounty Platforms Collection](https://github.com/disclose/bug-bounty-platforms)
- [BugBase AI Programs](https://bugbase.ai/programs)
- [BugBase India Programs](https://bugbase.in/programs)
- [Bugbounter](https://app.bugbounter.com/)
- [BugBounty.jp](https://bugbounty.jp/)
- [Bugcrowd Programs](https://bugcrowd.com/engagements?category=bug_bounty&page=1&sort_by=promoted&sort_direction=desc)
- [Bugv.io](https://bugv.io/)
- [HackerOne Bug Bounty](https://hackerone.com/opportunities/all)
- [HuntDB](https://huntdb.com/)
- [Intigriti](https://intigriti.com/)
- [YesWeHack](https://yeswehack.com/programs)

### Practice Labs and Vulnerable Applications

- [AWSGoat - Damn Vulnerable AWS Infrastructure](https://github.com/ine-labs/AWSGoat)
- [AzureGoat - Damn Vulnerable Azure Infrastructure](https://github.com/ine-labs/AzureGoat)
- [Damn Vulnerable Application Scanner (Paper)](https://ceur-ws.org/Vol-2940/paper36.pdf)
- [Damn Vulnerable Bank (Android)](https://github.com/rewanthtammana/Damn-Vulnerable-Bank)
- [Damn Vulnerable C# Application (API)](https://github.com/appsecco/dvcsharp-api)
- [Damn Vulnerable GraphQL Application](https://github.com/dolevf/Damn-Vulnerable-GraphQL-Application)
- [Damn Vulnerable Web Services (Legacy)](https://github.com/snoopysecurity/dvws)
- [Damn Vulnerable Web Services (Node)](https://github.com/snoopysecurity/dvws-node)
- [DVCA - Damn Vulnerable Cloud Application](https://github.com/m6a-UdS/dvca)
- [DVFaaS - Damn Vulnerable Functions as a Service](https://github.com/we45/DVFaaS-Damn-Vulnerable-Functions-as-a-Service)
- [DVGM - Damn Vulnerable Grade Management System](https://git.logicalhacking.com/BrowserSecurity/DVGM)
- [DVHMA - Damn Vulnerable Hybrid Mobile App](https://github.com/logicalhacking/DVHMA)
- [DVIA - Damn Vulnerable iOS App](https://github.com/prateek147/DVIA)
- [DVIA v2 - Damn Vulnerable iOS App (Swift)](https://github.com/prateek147/DVIA-v2)
- [DVID - Damn Vulnerable IoT Device](https://github.com/Vulcainreo/DVID)
- [DVJA - Damn Vulnerable Java Application](https://github.com/appsecco/dvja)
- [DVNA - Damn Vulnerable NodeJS Application](https://github.com/appsecco/dvna)
- [DVPWA - Damn Vulnerable Python Web App](https://github.com/anxolerd/dvpwa)
- [DVRA - Damn Vulnerable Rails App](https://github.com/guilleiguaran/dvra)
- [DVRF - Damn Vulnerable Router Firmware](https://github.com/praetorian-inc/DVRF)
- [DVSA - Damn Vulnerable Serverless Application](https://github.com/OWASP/DVSA)
- [DVTA - Damn Vulnerable Thick Client App](https://github.com/srini0x00/dvta)
- [DVWA - Damn Vulnerable Web Application](https://github.com/digininja/DVWA)
- [DVWPS - Damn Vulnerable WordPress Site](https://github.com/vianasw/dvwps)
- [Tiredful-API - Broken REST API](https://github.com/payatu/Tiredful-API)
- [VAmPI - Vulnerable REST API](https://github.com/erev0s/VAmPI)

### Learning Platforms and Practice Grounds

- [Certified Red Team Analyst (CRTA)](https://portal.cyberwarfare.live/products/certified-red-team-analyst)
- [CTFtime Writeups](https://ctftime.org/writeups)
- [Cyber3ra Dashboard](https://cyber3ra.com/dashboard)
- [CyberWarFare Labs Support](https://labs.cyberwarfare.live/app/support)
- [Ethical Hacking Labs](https://github.com/Samsar4/Ethical-Hacking-Labs)
- [Free 350+ TryHackMe Rooms](https://sm4rty.medium.com/free-350-tryhackme-rooms-f3b7b2954b8d)
- [Hackers Arise](https://www.hackers-arise.com/)
- [Hackersploit Tutorials](https://hackersploit.org/bug-bounty-tutorials)
- [Hacking Articles (GitHub)](https://github.com/tamim1089/hacking-articles)
- [HackingArticles Web Pentest](https://www.hackingarticles.in/web-penetration-testing)
- [HackingArticles.in](https://www.hackingarticles.in/)
- [HackingHub](https://hackinghub.net/)
- [HackTricks Book](https://book.hacktricks.xyz/)
- [HackTricks Wiki](https://book.hacktricks.wiki/en/index.html)
- [How to Study Cyber Security for Free](https://medium.com/@kashishcharaya/how-to-study-cyber-security-on-your-own-for-free-a4f894dad919)
- [Hubs Pathshala](https://pathshala.spinthehack.in/)
- [Intro to Secure Coding](https://www.opensecuritytraining.info/IntroSecureCoding.html)
- [OverTheWire Wargames](https://overthewire.org/)
- [PortSwigger Web Security Labs](https://portswigger.net/web-security/all-labs)
- [Secure Code Review](https://www.opensecuritytraining.info/SecureCodeReview.html)
- [Top 100 Hacking & Security E-Books](https://github.com/yeahhub/Hacking-Security-Ebooks)
- [TryHackMe Roadmap (Hunterdii)](https://github.com/Hunterdii/TryHackMe-Roadmap?tab=readme-ov-file#intro-rooms)
- [TryHackMe Roadmap (rng70)](https://github.com/rng70/TryHackMe-Roadmap?tab=readme-ov-file)

### Roadmaps, Checklists and Methodologies

- [10 Rules to Succeed in Bug Bounty](https://webs3c.com/t/the-10-rules-to-be-successful-in-your-bug-bounty-career/123)
- [40 Tips and Tricks for Beginners](https://freedium.cfd/https://thegrayarea.tech/40-tips-and-tricks-to-improve-your-bug-bounties-as-a-beginner-ef302707b14a)
- [Book of Bug Bounty Tips](https://gowsundar.gitbook.io/book-of-bugbounty-tips)
- [Bug Bounty & ChatGPT](https://medium.com/@batuhanaydinn/bug-bounty-hunting-how-to-use-chatgpt-61d81ed85e34)
- [Bug Bounty 101: Step-by-Step Practical Approach](https://freedium.cfd/https://santhosh-adiga-u.medium.com/bug-bounty-101-step-by-step-practical-approach-to-recon-and-discovery-43a4f505e3d3)
- [Bug Bounty Checklist](https://github.com/sehno/Bug-bounty/blob/master/bugbounty_checklist.md)
- [Bug Bounty Getting Started Tips](https://infosecwriteups.com/bug-bounty-getting-started-some-tips-600866c4d790)
- [Bug Bounty Recon Mindmap](https://www.figma.com/board/thQhv59LVT5jGG4M8ZsQms/Bug-Bounty-Recon-Mindmap---BB003?node-id=0-1&node-type=canvas)
- [Bug Hunter Handbook](https://gowthams.gitbook.io/bughunter-handbook/getting-started-in-bug-bounties)
- [Bug Hunting Recon Methodology Part 1](https://systemweakness.com/bug-hunting-recon-methodology-part1-legionhunter-975b7bbe3231)
- [Bug Hunting Recon Methodology Part 2](https://osintteam.blog/bug-hunting-recon-methodology-part2-legionhunter-4bb925e3e1bf)
- [Burp Suite 101: Deep Into Intruder](https://hacklido.com/blog/631-burpsuite-101-going-deep-into-intruder)
- [Burp Suite 101: Introduction and Installation](https://hacklido.com/blog/621-burpsuite-101-introduction-and-installation)
- [Burp Suite 101: Navigation & Configuration](https://hacklido.com/blog/624-burp-suite-101-understanding-navigation-dashboard-configuration)
- [Burp Suite 101: Proxy and Target](https://hacklido.com/blog/625-burp-suite-101-exploring-burp-proxy-and-target-specification)
- [Burp Suite 101: Repeater and Comparer](https://hacklido.com/blog/628-burpsuite-101-exploring-burp-repeater-and-burp-comparer)
- [Cybersecurity Roadmap 2022](https://infosecwriteups.com/roadmap-to-cybersecurity-in-2022-full-read-ssrf-idor-in-graphql-gcp-pentesting-and-much-74d2d906f7d7)
- [CyberX Society - Recon to Reward Workflow](https://cyberxsociety.com/from-recon-to-reward-my-step-by-step-bug-bounty-workflow)
- [Galaxy Bug Bounty Checklist](https://github.com/0xmaximus/Galaxy-Bugbounty-Checklist)
- [Mastering the Hunt: Ultimate Guide](https://freedium.cfd/https://osintteam.blog/mastering-the-hunt-the-ultimate-guide-to-modern-bug-bounty-hunting-416357b08abb)
- [Mastering the Skills of Bug Bounty](https://medium.com/swlh/mastering-the-skills-of-bug-bounty-2201eb6a9f4)
- [Node.js Security Checklist](https://blog.risingstack.com/node-js-security-checklist)
- [Pentestbook Web Checklist](https://pentestbook.six2dez.com/others/web-checklist)
- [Twitter - Infosec Tips](https://twitter.com/yasser_elsnbary/status/1554839187626438657?s=21&t=kfOz8aqpwtWNvJeOUNyG3Q)
- [Vulnerability Checklist](https://github.com/Az0x7/vulnerability-Checklist?tab=readme-ov-file)
- [Web Application Reconnaissance Guide](https://shubhdhungana.medium.com/web-application-reconnaissance-guide-cybersec-shubham-dhungana-17858c967e2b)
- [Web Roadmap Image](https://raw.githubusercontent.com/1ndianl33t/Bug-Bounty-Roadmaps/master/Web%20Roadmap.png)
- [When GPTs Call Home: Exploiting SSRF in ChatGPT’s Custom Actions | by SirLeeroyJenkins | Nov, 2025](https://sirleeroyjenkins.medium.com/when-gpts-call-home-exploiting-ssrf-in-chatgpts-custom-actions-5df9df27dbe9)

### Cheatsheets, Payloads and Wordlists

- [Account Takeover](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Account%20Takeover)
- [Advanced Google Dork Cheat Sheet](https://decrypter.medium.com/advanced-google-dork-cheat-sheet-b88db1ef7c57)
- [Advanced SQL Injection Cheatsheet](https://github.com/kleiton0x00/Advanced-SQL-Injection-Cheatsheet)
- [API Key Leaks](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/API%20Key%20Leaks)
- [Bug Bounty Cheatsheet](https://m0chan.github.io/2019/12/17/Bug-Bounty-Cheetsheet.html)
- [Bug Bounty Wordlists](https://github.com/abdallaabdalrhman/Wordlist-for-Bug-Bounty)
- [Cheat Sheet Collections](https://github.com/emadshanab/cheat-sheet-collections)
- [Clickjacking](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Clickjacking)
- [Client Side Path Traversal](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Client%20Side%20Path%20Traversal)
- [Command Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Command%20Injection)
- [Content Injection Cheatsheet](https://github.com/EdOverflow/bugbounty-cheatsheet/blob/master/cheatsheets/content-injection.md)
- [CORS Misconfiguration](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/CORS%20Misconfiguration)
- [CRLF Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/CRLF%20Injection)
- [Cross-Site Request Forgery (CSRF)](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Cross-Site%20Request%20Forgery)
- [CSV Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/CSV%20Injection)
- [Denial of Service](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Denial%20of%20Service)
- [Dependency Confusion](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Dependency%20Confusion)
- [Directory Traversal](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Directory%20Traversal)
- [DNS Rebinding](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/DNS%20Rebinding)
- [DOM Clobbering](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/DOM%20Clobbering)
- [External Variable Modification](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/External%20Variable%20Modification)
- [File Inclusion](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/File%20Inclusion)
- [GraphQL Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/GraphQL%20Injection)
- [Insecure Deserialization](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Deserialization)
- [Insecure Direct Object References (IDOR)](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Direct%20Object%20References)
- [Insecure Management Interface](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Management%20Interface)
- [Insecure Randomness](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Randomness)
- [Insecure Source Code Management](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Source%20Code%20Management)
- [LaTeX Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/LaTeX%20Injection)
- [LDAP Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/LDAP%20Injection)
- [Mass Assignment](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Mass%20Assignment)
- [MSSQL Injection Cheat Sheet](https://www.advania.co.uk/insights/blog/mssql-practical-injection-cheat-sheet)
- [NoSQL Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/NoSQL%20Injection)
- [OAuth Misconfiguration](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/OAuth%20Misconfiguration)
- [Open Redirect](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Open%20Redirect)
- [ORM Leak](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/ORM%20Leak)
- [PayloadsAllTheThings (Main)](https://github.com/swisskyrepo/PayloadsAllTheThings)
- [Prompt Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Prompt%20Injection)
- [Prototype Pollution](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Prototype%20Pollution)
- [Race Condition](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Race%20Condition)
- [Regular Expression](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Regular%20Expression)
- [Request Smuggling](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Request%20Smuggling)
- [SAML Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/SAML%20Injection)
- [Server Side Include Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Server%20Side%20Include%20Injection)
- [Server Side Request Forgery (SSRF)](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Server%20Side%20Request%20Forgery)
- [Server Side Template Injection (SSTI)](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Server%20Side%20Template%20Injection)
- [SQL Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/SQL%20Injection)
- [Tabnabbing](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Tabnabbing)
- [Type Juggling](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Type%20Juggling)
- [Upload Insecure Files](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Upload%20Insecure%20Files)
- [Web Cache Deception](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Web%20Cache%20Deception)
- [Web Sockets](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Web%20Sockets)
- [XPATH Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XPATH%20Injection)
- [XSLT Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XSLT%20Injection)
- [XXE Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XXE%20Injection)

### Awesome Lists and Curated Tool Collections

- [All-in-One Hacking Tool](https://github.com/Z4nzu/hackingtool)
- [Awesome Bug Bounty Tools](https://github.com/vavkamil/awesome-bugbounty-tools)
- [Awesome Ethical Hacking](https://github.com/husnainfareed/Awesome-Ethical-Hacking-Resources)
- [Awesome Hacker Search Engines](https://github.com/edoardottt/awesome-hacker-search-engines)
- [Awesome Security Hardening](https://github.com/decalage2/awesome-security-hardening)
- [Awesome Web Security](https://github.com/qazbnm456/awesome-web-security)
- [BB Resources (Voorivex)](https://github.com/Voorivex/bb-resouces)
- [Bug Bounty Reference (Ngalongc)](https://github.com/ngalongc/bug-bounty-reference)
- [Bug Bounty Toolkit](https://hackrootone.github.io/BugBountyToolkit)
- [BugBountyHunting.com](https://bugbountyhunting.com/)
- [Cyber Security Foundations](https://github.com/acelakshitverma/Cyber-Security-Foundations)
- [hktalent TOP](https://github.com/hktalent/TOP)
- [Infosec Encyclopedia](https://github.com/GoVanguard/list-infosec-encyclopedia/blob/master/README.md)
- [KathanP19 Security](https://github.com/KathanP19)
- [Pentest Tools List](https://pentestlist.com/tools)
- [Practical Cyber Security Resources](https://github.com/brcyrr/PracticalCyberSecurityResources)
- [Python Pentest Tools](https://github.com/dloss/python-pentest-tools)
- [Study Bug Bounty](https://github.com/bobby-lin/study-bug-bounty)
- [Webapp Exploit Tools Inventory](https://inventory.raw.pm/tools.html#title-tools-web-application-exploitation)
- [WebHackersWeapons](https://github.com/hahwul/WebHackersWeapons)
- [WebHackersWeapons (Dum7c)](https://github.com/Dum7c/WebHackersWeapons)
- [X0rb3l Cyber Bookmarks](https://x0rb3l.github.io/Cyber-Bookmarks/bookmarks.html)

### OSINT Tools (Additional)

- [Epieos - Ultimate OSINT Tool](https://epieos.com/)
- [OSINT 500 Tools](https://start.me/p/0Pqbdg/osint-500-tools)
- [reconurge/flowsint: A modern platform for visual, flexible, and extensible graph-based investigations. For cybersecurity analysts and investigators.](https://github.com/reconurge/flowsint)
- [The OSINT Toolbox](https://github.com/The-Osint-Toolbox)
- [WhatsMyName App](https://whatsmyname.app/)

### Google Dorking Resources (Additional)

- [Google Dorks Bug Bounty (GitHub)](https://github.com/TakSec/google-dorks-bug-bounty)
- [Google Dorks Gist 1](https://gist.github.com/OTaKuHP/bbfe8715e059c6dabd6109fc0676ad1c)
- [Google Dorks Gist 2](https://gist.github.com/OTaKuHP/b7748a04caa8145f6795b498302cec4e)
- [LazyDork](https://iamunixtz.github.io/LazyDork)
- [ReconShell Google Dorks](https://reconshell.com/google-dorks-for-bug-bounty)
- [Stop Ignoring 🔎 Google Dorking and Directory Bruteforcing — Here’s Why! | Bug Bounty PoC](https://www.youtube.com/watch?v=AeljN17ibCs)
- [YesWeHack Google Dorking Guide](https://yeswehack.com/blog/recon-series-5-hacker-guide-google-dorking)

### Burp Suite Guides and Extensions

- [BurpSuite For Pentester](https://github.com/Ignitetechnologies/BurpSuite-For-Pentester)
- [GraphQuail - Burp GraphQL Extension](https://github.com/forcesunseen/graphquail)
- [InQL - Burp GraphQL Testing Extension](https://github.com/doyensec/inql)

### Reconnaissance and Exploitation Tools (Additional)

- [AI-VAPT](https://github.com/vikramrajkumarmajji/AI-VAPT?tab=readme-ov-file)
- [FlashFuzz](https://github.com/Ademking/FlashFuzz)
- [GraphCrawler - GraphQL Security Testing](https://github.com/gsmith257-cyber/GraphCrawler)
- [JWT Tool](https://github.com/ticarpi/jwt_tool)
- [linPEAS](https://github.com/peass-ng/PEASS-ng/tree/master/linPEAS)
- [MXS](https://github.com/sarperavci/MXS)
- [Scan4all](https://github.com/hktalent/scan4all)
- [Shodan Filters](https://github.com/JavierOlmedo/shodan-filters)
- [xnLinkFinder](https://github.com/xnl-h4ck3r/xnLinkFinder)
- [XRecon](https://xrec0n.pythonanywhere.com/)

### Bug Bounty Writeups and Case Studies

- [$13,500 Bounty - Parameter Pollution](https://infosecwriteups.com/how-i-got-my-first-13500-bounty-through-parameter-polluting-hpp-179666b8e8bb)
- [$150 Broken Access Control - First Bounty](https://medium.com/@BugBountyWriteups/150-broken-access-control-hackerone-bug-bounty-program-my-first-bounty-239aff71376f)
- [$49,500 Critical Bug in Instagram](https://infosecwriteups.com/how-i-found-a-critical-bug-in-instagram-and-got-49500-bounty-from-facebook-626ff2c6a853)
- [Admin Panel Takeover Worth $3500](https://assassin-marcos.medium.com/breaking-the-barrier-admin-panel-takeover-worth-3500-78da79089ca3)
- [Advanced Guide to Penetration Testing in APIs | MeetCyber](https://medium.com/meetcyber/advanced-guide-to-penetration-testing-in-apis-part-2-practical-exploitation-mitigation-and-poc-140216b8eef3)
- [Automating XSS and SQL Injection](https://medium.com/@Tenebris_Venator/automating-xss-and-sql-injection-discovery-from-manual-testing-to-python-scripting-c30145ab20ac)
- [Beyond XSS - Token Storage](https://aszx87410.github.io/beyond-xss/en/ch2/token-storage)
- [Buffer Overflow Part 1 - Memory Layout](https://hacklido.com/blog/328-understanding-buffer-overflow-vulnerabilities-part-1-memory-layout-and-the-call-stack)
- [Buffer Overflow Part 2 - Stack Overflow](https://hacklido.com/blog/339-understanding-buffer-overflow-vulnerabilities-part-2-stack-overflow-in-a-simple-c-program)
- [Buffer Overflow Part 3 - CPU Registers](https://hacklido.com/blog/353-understanding-buffer-overflow-vulnerabilities-part-3-understanding-cpu-registers)
- [Buffer Overflow Part 4 - Debugging C Program](https://hacklido.com/blog/354-understanding-buffer-overflow-vulnerabilities-part-4-debugging-a-c-program)
- [Business Logic - Broken Wallet & OTP Bypass](https://infosecwriteups.com/business-logic-broken-wallet-hacked-otp-bypassed-d82e6591a63a)
- [Bypassing 403s - Broken Access Control](https://shrirangdiwakar.medium.com/bypassing-403s-like-a-pro-2-100-broken-access-control-66beef4afa8c)
- [Chained 3 Bugs into Full Account Takeover](https://infosecwriteups.com/one-endpoint-to-rule-them-all-chained-3-bugs-into-full-account-takeover-e2a71592ca7e)
- [CORS Vulnerability with Trusted Null Origin](https://infosecwriteups.com/cors-vulnerability-with-trusted-null-origin-0f9593bd7674)
- [Discovering IDOR from Blank Page](https://medium.com/@kerstan/how-to-discovered-idor-from-a-blank-page-bug-bounty-tuesday-5af784533d1a)
- [From 404 to $4,000: Real Bugs Found in Forgotten Endpoints | by Monika sharma | Nov, 2025](https://infosecwriteups.com/from-404-to-4-000-real-bugs-found-in-forgotten-endpoints-5886c06f7473)
- [GraphQL Introspection - Sensitive Data Disclosure](https://medium.com/@pranaybafna/graphql-introspection-leads-to-sensitive-data-disclosure-65b385452d7f)
- [How I found Vulnerability on Google Forms (Duplicate Internal — Fixed) | by Qadhafy Muhammad Tera | Nov, 2025](https://medium.com/@ecdnts/how-i-found-vulnerability-on-google-forms-duplicate-internal-fixed-d02aa2e6357c)
- [How to Discover GraphQL Vulnerabilities](https://www.cobalt.io/blog/deep-dive-into-graphql-pt.-2?hs_preview=mxIZUTSv-97236639291)
- [How to JS for Pentest: Edition 2023](https://kongsec.medium.com/how-to-js-for-bug-bounties-edition-2023-7108b56d9db6)
- [IDOR in Image Upload Function](https://infosecwriteups.com/gone-in-a-click-idor-vulnerabilities-in-image-upload-function-6c4817b44d8c)
- [In-Depth Analysis of 3 IDOR Bugs](https://medium.com/@atomiczsec/one-bug-at-a-time-in-depth-analysis-of-3-idor-bugs-2fb016e21b96)
- [InfoSec Writeups - Bug Bounty Tagged](https://infosecwriteups.com/tagged/bug-bounty)
- [JS is the New S3 - Mining Secrets](https://medium.com/meetcyber/js-is-the-new-s3-how-i-mined-tokens-pii-devops-secrets-from-javascript-for-bounties-13b6bdf1b829)
- [Lessons from First 100 HackerOne Reports](https://infosecwriteups.com/what-i-learned-from-my-first-100-hackerone-reports-6a413adbe319)
- [Master Subdomain Hunting](https://infosecwriteups.com/master-subdomain-hunting-art-of-finding-hidden-assets-3351b3c8467a)
- [Mastering Subfinder for Bug Bounty](https://cybersecuritywriteups.com/mastering-subfinder-for-bug-bounty-my-secret-weapon-for-finding-hidden-subdomains-%EF%B8%8F-%EF%B8%8F-91a62d04651d)
- [OAuth Authentication Bypass leading to PII disclosure | by janlele91 | Nov, 2025](https://medium.com/@bugbounty0901/oauth-authentication-bypass-leading-to-pii-disclosure-5d243b62d532)
- [OAuth Misconfiguration - Full Account Takeover](https://medium.com/@aditya043k/oauth-misconfiguration-leads-to-full-account-takeover-d93c0d0fb66c)
- [SshControl. Summary | by dj4m | Nov, 2025](https://medium.com/@dj4msec/sshcontrol-84d4fb0ed8eb)
- [SSRF via filename - PDF Extractor (via SMTP), detailed shi- write-up | by Sevada797 | Nov, 2025](https://medium.com/@zatikyan.sevada/ssrf-via-filename-pdf-extractor-via-smtp-detailed-shi-write-up-f494d320fa75)
- [Subdomain Takeover Learning](https://medium.com/@cosmicbyt3/how-i-learned-about-subdomain-takeover-e4823366b3f8)
- [The Cache Poisoning Bible: Part 1 — Advanced Fundamentals](https://medium.com/@Aacle/the-cache-poisoning-bible-part-1-advanced-fundamentals-2c8e9d7be2e9)
- [When One Error Message Unlocked the Entire Kingdom: A Critical SQL Injection Tale](https://0dayscyber.medium.com/when-one-error-message-unlocked-the-entire-kingdom-a-critical-sql-injection-tale-1655c93dd2f8)

### Video Tutorials and Playlists

- [$20,000 HackerOne Data Leakage via GraphQL](https://www.youtube.com/watch?app=desktop&v=tJtNTqviOGg)
- [3 Tricks to Hunt Faster in Bug Bounty](https://www.youtube.com/watch?v=9CiDsOI-p1s)
- [Complete Bash Scripting Course From Level 0 | Shell Scripting | Linux Administration | Devops](https://www.youtube.com/watch?v=LtE30PtFXbQ)
- [Find Bugs in AI Model using Promptfoo 🔥 | Full Red Team Walkthrough + OWASP LLM Security Explained](https://www.youtube.com/watch?v=7nN4xzaWyYo)
- [GraphQL Testing Tutorial Playlist](https://www.youtube.com/playlist?list=PLFh6J1ZHhqNhfSVt4WaF9GgOCOq9PYYBa)
- [Hidden in Plain Site: API Information Disclosure](https://www.youtube.com/watch?v=jBi3a-dXsM8)
- [How Hackers Bypass Paywalls? (Real Techniques)](https://www.youtube.com/watch?v=X-fspAWAqzQ)
- [Learn Hacking Easily With DeepSeek AI](https://www.youtube.com/watch?v=VTS9smS_3FI)
- [NoSQL Injection — Joseph Simon Unveils Hidden Vulnerabilities at FOXXCON Meetup November](https://www.youtube.com/watch?v=jeuas_3Wd10)
- [Recon for Bug Bounty By Hacklido](https://www.youtube.com/watch?v=eK4jDaXGGhk)
- [Targeting for Bug Bounty Research](https://www.youtube.com/watch?v=hYJ7ipSOplw)
- [The AI Hacking Skill Worth $150K+ (Gandalf Level 7)](https://www.youtube.com/watch?v=yxzGhEv1ktE)
- [Ultimate GraphQL Recon - A Tactical Approach](https://www.youtube.com/watch?app=desktop&v=c_RPptC4V9I)
- [YouTube Playlist 1](https://www.youtube.com/watch?index=1&list=PLv7cogHXoVhXvHPzIl1dWtBiYUAL8baHj&v=BjfCWSFmIFI)
- [YouTube Playlist 2](https://www.youtube.com/watch?v=5N7k0g7arYE)
- [YouTube Playlist 3](https://www.youtube.com/watch?list=PLbyncTkpno5FZQ3ZgpHj1BdQ7XHwfvO1w&v=RobCqW2KwGs)
- [YouTube Playlist 4](https://www.youtube.com/watch?v=bHdK7TGgYKI)
- [YouTube Playlist 5](https://www.youtube.com/watch?v=qOEahjuOYJo)
- [YouTube Playlist 6](https://www.youtube.com/watch?list=PL9gnSGHSqcnr_DxHsP7AW9ftq0AtAyYqJ&v=rZ41y93P2Qo)
- [YouTube Playlist 7](https://www.youtube.com/watch?list=PLyqga7AXMtPPuibxp1N0TdyDrKwP9H_jD&v=rWHvp7rUka8)
- [YouTube Playlist 8](https://www.youtube.com/watch?list=PLJ18l2m4Gsa_d-WrmQYi6AcjQCxRZ0wG1&v=C_8WvR1rKpM)
- [YouTube Tutorial 1](https://www.youtube.com/watch?v=ggClgbxHDLw)
- [YouTube Tutorial 2](https://www.youtube.com/watch?v=G1RHa7l1Ys4)
- [YouTube Tutorial 3](https://www.youtube.com/watch?v=Ifo1vIdfyhg)
- [YouTube Tutorial 4](https://www.youtube.com/watch?v=p4JgIu1mceI)
- [YouTube Tutorial 5](https://www.youtube.com/watch?v=5Di0VVK9JiQ)
- [YouTube Tutorial 6](https://www.youtube.com/watch?v=XJXBtS1S6FY)

### Communities, Blogs, News and Podcasts

- [Critical Thinking Podcast](https://criticalthinkingpodcast.io/)
- [Pentester Land](https://pentester.land/)
- [Pentester Land Newsletters](https://pentester.land/categories/newsletter)
- [The Hacker News](https://thehackernews.com/)
- [Twitter - CEOS3C](https://twitter.com/ceos3c/status/1530847515997880320?s=21&t=KOzbQwSHgCf04T_Vx0EaDw)

### Miscellaneous References

- [Chaos by ProjectDiscovery](https://chaos.projectdiscovery.io/)
- [CI/CD Goat - Vulnerable CI/CD Environment](https://github.com/cider-security-research/cicd-goat)
- [First Bounty Guide](https://github.com/BehiSecc/First-Bounty?tab=readme-ov-file)
- [HowToHunt Collection](https://github.com/KathanP19/HowToHunt)
- [OWASP Threat Modeling](https://owasp.org/www-community/Threat_Modeling)
- [OWASP Web Security Testing Guide](https://github.com/OWASP/wstg/tree/master/document/4-Web_Application_Security_Testing)

---

## Maintenance

When adding a new resource, place it under the most specific applicable category and use this format:

```markdown
### Tool Name
**Category:** Category Name  
**Use:** Short description of the tool's primary purpose.

https://example.com/
```

Keep entries:

- Alphabetically ordered within each section where practical.
- Free of duplicate URLs.
- Limited to one canonical URL per tool.
- Descriptive but concise.
- Focused on the tool's primary security use case.
