# Cybersecurity VAPT and Bug Bounty Reference

Professional reference of web security, API security, reconnaissance, OSINT, attack-surface discovery, vulnerability research, payload generation, and supporting tools.

Use these resources only for systems and assets that are owned by you or explicitly authorized for testing.

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
