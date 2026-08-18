# Cybersecurity VAPT & Bug Bounty Resources

![Category](https://img.shields.io/badge/category-VAPT%20%7C%20Bug%20Bounty-blue)
![Focus](https://img.shields.io/badge/focus-Web%20%26%20API%20Security-informational)
![Resources](https://img.shields.io/badge/resources-345%2B-brightgreen)
![Maintained](https://img.shields.io/badge/maintained-yes-brightgreen)

A curated bookmark list of tools, platforms, cheatsheets, learning resources, and writeups for web/API penetration testing and bug bounty hunting — organized by category for quick reference.

> Use these resources only on systems you own or are explicitly authorized to test.

## Contents

- [Bug Bounty Platforms](#bug-bounty-platforms)
- [Reconnaissance & Attack Surface Discovery](#reconnaissance-attack-surface-discovery)
- [DNS, Domain & Network Intelligence](#dns-domain-network-intelligence)
- [OSINT & Threat Intelligence](#osint-threat-intelligence)
- [Search Engines & Google Dorking](#search-engines-google-dorking)
- [File & Asset Discovery](#file-asset-discovery)
- [Source Code & Vulnerability Intelligence](#source-code-vulnerability-intelligence)
- [Secrets & API Key Validation](#secrets-api-key-validation)
- [JWT & Token Analysis](#jwt-token-analysis)
- [XSS Testing](#xss-testing)
- [SSRF & OOB Testing](#ssrf-oob-testing)
- [LFI, Command Injection & Reverse Shells](#lfi-command-injection-reverse-shells)
- [GraphQL Security Testing](#graphql-security-testing)
- [CSP & Client-Side Security](#csp-client-side-security)
- [SQL Injection Tools](#sql-injection-tools)
- [Browser Extensions](#browser-extensions)
- [Developer Utilities](#developer-utilities)
- [Burp Suite Guides & Extensions](#burp-suite-guides-extensions)
- [Cheatsheets, Checklists & Methodologies](#cheatsheets-checklists-methodologies)
- [Practice Labs & Vulnerable Apps](#practice-labs-vulnerable-apps)
- [Learning Platforms & Practice Grounds](#learning-platforms-practice-grounds)
- [Awesome Lists & Tool Collections](#awesome-lists-tool-collections)
- [Bug Bounty Writeups & Case Studies](#bug-bounty-writeups-case-studies)
- [Video Tutorials & Playlists](#video-tutorials-playlists)
- [Communities, Blogs & Podcasts](#communities-blogs-podcasts)
- [Miscellaneous](#miscellaneous)

## Bug Bounty Platforms

| Resource | Purpose | Link |
|---|---|---|
| **Ask a Hacker (Bugcrowd)** | Bug bounty / vulnerability disclosure platform | https://forum.bugcrowd.com/c/ask-a-hacker/34 |
| **BBP Finder** | Bug bounty / vulnerability disclosure platform | https://xitsec.in/bbp-finder.html |
| **Bug Bounty Platforms Collection** | Bug bounty / vulnerability disclosure platform | https://github.com/disclose/bug-bounty-platforms |
| **BugBase AI Programs** | Bug bounty / vulnerability disclosure platform | https://bugbase.ai/programs |
| **BugBase India Programs** | Bug bounty / vulnerability disclosure platform | https://bugbase.in/programs |
| **Bugbounter** | Bug bounty / vulnerability disclosure platform | https://app.bugbounter.com/ |
| **BugBounty.jp** | Bug bounty / vulnerability disclosure platform | https://bugbounty.jp/ |
| **Bugcrowd Programs** | Bug bounty / vulnerability disclosure platform | https://bugcrowd.com/engagements?category=bug_bounty&page=1&sort_by=promoted&sort_direction=desc |
| **Bugv.io** | Bug bounty / vulnerability disclosure platform | https://bugv.io/ |
| **HackerOne Bug Bounty** | Bug bounty / vulnerability disclosure platform | https://hackerone.com/opportunities/all |
| **HuntDB** | Bug bounty / vulnerability disclosure platform | https://huntdb.com/ |
| **Intigriti** | Bug bounty / vulnerability disclosure platform | https://intigriti.com/ |
| **YesWeHack** | Bug bounty / vulnerability disclosure platform | https://yeswehack.com/programs |

## Reconnaissance & Attack Surface Discovery

| Resource | Purpose | Link |
|---|---|---|
| **AI-VAPT** | Reconnaissance or exploitation tool | https://github.com/vikramrajkumarmajji/AI-VAPT?tab=readme-ov-file |
| **Argus** | Security reconnaissance and target intelligence. | https://argus.cobrasec.pro/ |
| **Censys** | Internet infrastructure, hosts, certificates, services and network exposure. | https://search.censys.io/ |
| **FileHunt** | Search and discover potentially exposed files and assets. | https://filehunt.3kh0.net/ |
| **FilePhish** | File and asset discovery research. | https://greylensresearch.github.io/filephish/ |
| **FlashFuzz** | Reconnaissance or exploitation tool | https://github.com/Ademking/FlashFuzz |
| **FOFA** | Internet-facing assets, services, technologies and infrastructure discovery. | https://en.fofa.info/ |
| **FullHunt** | Domain, subdomain, IP and external attack-surface discovery. | https://fullhunt.io/ |
| **GraphCrawler - GraphQL Security Testing** | Reconnaissance or exploitation tool | https://github.com/gsmith257-cyber/GraphCrawler |
| **Hunter.how** | Search and investigate internet-facing infrastructure. | https://hunter.how/ |
| **InstRecon** | Quick target reconnaissance and information gathering. | https://www.instrecon.site/ |
| **JWT Tool** | Reconnaissance or exploitation tool | https://github.com/ticarpi/jwt_tool |
| **linPEAS** | Reconnaissance or exploitation tool | https://github.com/peass-ng/PEASS-ng/tree/master/linPEAS |
| **MXS** | Reconnaissance or exploitation tool | https://github.com/sarperavci/MXS |
| **Netlas** | Internet asset discovery, services, domains and infrastructure. | https://netlas.io/ |
| **RootXVishal Crawler** | Web crawling, endpoint discovery and spidering. | https://crawler.rootxvishal.com/ |
| **RootXVishal Recon** | Target intelligence and reconnaissance. | https://recon.rootxvishal.com/ |
| **Scan4all** | Reconnaissance or exploitation tool | https://github.com/hktalent/scan4all |
| **Shodan** | Internet-facing hosts, services, ports, banners, certificates and exposed infrastructure. | https://www.shodan.io/ |
| **Shodan Filters** | Reconnaissance or exploitation tool | https://github.com/JavierOlmedo/shodan-filters |
| **Tiny-Scan** | Lightweight scanning and target enumeration. | https://www.tiny-scan.com/ |
| **Web-Check** | Website information gathering, technology identification and security reconnaissance. | https://web-check.xyz/check/ |
| **xnLinkFinder** | Reconnaissance or exploitation tool | https://github.com/xnl-h4ck3r/xnLinkFinder |
| **XRecon** | Reconnaissance or exploitation tool | https://xrec0n.pythonanywhere.com/ |
| **ZoomEye** | Internet-connected devices, services and infrastructure discovery. | https://www.zoomeye.ai/ |

## DNS, Domain & Network Intelligence

| Resource | Purpose | Link |
|---|---|---|
| **BGP Toolkit - Hurricane Electric** | ASN, BGP routes, prefixes and network ownership research. | https://bgp.he.net/ |
| **Netcraft SearchDNS** | DNS and domain infrastructure research. | https://searchdns.netcraft.com/ |
| **SecurityTrails** | DNS records, historical DNS, domains, subdomains and infrastructure relationships. | https://securitytrails.com/ |
| **Subdomain Finder** | Subdomain discovery. | https://recox.hackerz.space/ |
| **THC IP** | IP and network-related research. | https://ip.thc.org/ |
| **TriNetLayer Subdomain Scanner** | Subdomain and infrastructure discovery. | https://trinetlayer.com/ |
| **ViewDNS** | DNS, WHOIS, IP and domain investigation. | https://viewdns.info/ |
| **WhoXY** | Domain and WHOIS-related research. | https://www.whoxy.com/ |

## OSINT & Threat Intelligence

| Resource | Purpose | Link |
|---|---|---|
| **Behind The Email** | Email-related open-source intelligence. | https://behindtheemail.com/ |
| **Epieos - Ultimate OSINT Tool** | OSINT / information-gathering tool | https://epieos.com/ |
| **Intelligence X** | Intelligence searches across multiple data sources. | https://intelx.io/ |
| **Kagi** | Alternative general-purpose web search. | https://kagi.com/ |
| **OSINT 500 Tools** | OSINT / information-gathering tool | https://start.me/p/0Pqbdg/osint-500-tools |
| **OSINT Framework** | Directory of OSINT resources organized by investigation category. | https://osintframework.com/ |
| **OSINTNova** | Open-source intelligence and investigation workflows. | https://app.osintnova.com/ |
| **reconurge/flowsint: A modern platform for visual, flexible, and extensible graph-based investigations. For cybersecurity analysts and investigators.** | OSINT / information-gathering tool | https://github.com/reconurge/flowsint |
| **The OSINT Toolbox** | OSINT / information-gathering tool | https://github.com/The-Osint-Toolbox |
| **VirusTotal** | File, URL, domain, IP and malware intelligence. | https://www.virustotal.com/ |
| **Wayback Machine** | Historical versions of websites, URLs and web content. | https://web.archive.org/ |
| **WhatsMyName App** | OSINT / information-gathering tool | https://whatsmyname.app/ |

## Search Engines & Google Dorking

| Resource | Purpose | Link |
|---|---|---|
| **AI Dork Builder** | Generate search queries and dorks. | https://deepfind.me/tools/search-and-discovery/ai-google-dork-builder |
| **Bug Bounty Search Engine** | Search engine focused on bug-bounty reconnaissance. | https://nitinyadav00.github.io/Bug-Bounty-Search-Engine/ |
| **Deep Dork Web** | Search and dork resources for security research. | https://guilherme-moraiss.github.io/Deep-Dork-Web/ |
| **Dork Engine** | Search-dork generation. | https://dorkengine.github.io/ |
| **Dork For Me** | Search-dork assistance. | https://securitytoolkits.com/dork-for-me |
| **DorkGPT** | AI-assisted search-dork generation. | https://www.dorkgpt.com/ |
| **DorkKing** | Search-dork generation. | https://dorkking.blindf.com/ |
| **DorkSearch** | Search and discover search-engine dorks. | https://dorksearch.com/ |
| **DorkSearch2** | Search-dork discovery. | https://dorksearch.pro/ |
| **Elite Dork Forge** | Advanced search-dork generation. | https://elite-dork-forge.lovable.app/ |
| **Exploit-DB Google Hacking Database** | Established collection of Google search operators and security-focused queries. | https://www.exploit-db.com/google-hacking-database |
| **GoldenOwl Syntax** | Search syntax and query construction reference. | https://syntax.goldenowl.ai/ |
| **Google Advanced Search** | Advanced Google search filters and operators. | https://www.google.com/advanced_search |
| **Google Dorks Bug Bounty (GitHub)** | Google dorking resource for bug bounty recon | https://github.com/TakSec/google-dorks-bug-bounty |
| **Google Dorks Gist 1** | Google dorking resource for bug bounty recon | https://gist.github.com/OTaKuHP/bbfe8715e059c6dabd6109fc0676ad1c |
| **Google Dorks Gist 2** | Google dorking resource for bug bounty recon | https://gist.github.com/OTaKuHP/b7748a04caa8145f6795b498302cec4e |
| **LazyDork** | Google dorking resource for bug bounty recon | https://iamunixtz.github.io/LazyDork |
| **ReconEngines** | Reconnaissance and search resources. | https://h6nt3r.github.io/reconengines/ |
| **ReconShell Google Dorks** | Google dorking resource for bug bounty recon | https://reconshell.com/google-dorks-for-bug-bounty |
| **Recruit'em** | Search assistance for professional and social profiles. | https://recruitin.net/ |
| **Shadoh Dorks** | Search dorks for security research. | https://shadohdorks.vercel.app/ |
| **Stop Ignoring 🔎 Google Dorking and Directory Bruteforcing — Here’s Why! - Bug Bounty PoC** | Google dorking resource for bug bounty recon | https://www.youtube.com/watch?v=AeljN17ibCs |
| **TakSec Dorks** | Google dorks specifically oriented toward bug bounty reconnaissance. | https://taksec.github.io/google-dorks-bug-bounty/ |
| **Xen00rw Dorks** | Security and bug bounty search dorks. | https://dorks.xen00rw.me/ |
| **YesWeHack Google Dorking Guide** | Google dorking resource for bug bounty recon | https://yeswehack.com/blog/recon-series-5-hacker-guide-google-dorking |

## File & Asset Discovery

| Resource | Purpose | Link |
|---|---|---|
| **FileHunt** | Identify potentially exposed files and assets. | https://filehunt.3kh0.net/ |
| **FilePhish** | File and asset discovery research. | https://greylensresearch.github.io/filephish/ |

## Source Code & Vulnerability Intelligence

| Resource | Purpose | Link |
|---|---|---|
| **Exploit-DB Google Hacking Database** | Search-engine reconnaissance and query research. | https://www.exploit-db.com/google-hacking-database |
| **Grep.app** | Search publicly indexed source code for keywords, secrets, endpoints and implementation patterns. | https://grep.app/ |
| **SearchCode** | Search publicly available source code. | https://searchcode.com/ |
| **Vulners** | CVEs, vulnerabilities, advisories and exploit intelligence. | https://vulners.com/ |

## Secrets & API Key Validation

| Resource | Purpose | Link |
|---|---|---|
| **BlindF GoogleKey** | Test Google API key behavior and exposure. | https://blindf.com/googlekey/ |
| **Keyhacks** | Identify and test exposed API keys and credentials. | https://github.com/streaak/keyhacks |
| **Secrets Ninja - AWS** | AWS-related secret and credential validation. | https://secrets.ninja/aws |
| **Trinetlayer Validator** | Validate potentially exposed secrets and credentials. | https://validator.trinetlayer.com |

## JWT & Token Analysis

| Resource | Purpose | Link |
|---|---|---|
| **JWT Auditor** | Analyze JWT implementation and security properties. | https://jwtauditor.com/ |
| **Token.dev** | Decode and inspect tokens. | https://token.dev/ |

## XSS Testing

| Resource | Purpose | Link |
|---|---|---|
| **XSS Parameter Extractor** | Identify parameters relevant to XSS testing. | https://xss.bugbountyhunt.com/ |
| **XSS.Report** | Blind XSS testing and interaction monitoring. | https://xss.report/dashboard |
| **XSS0r** | Blind XSS payload management and testing. | https://xss0r.com/ |
| **XSSnow** | XSS payload generation and testing. | https://xssnow.in/index.html |

## SSRF & OOB Testing

| Resource | Purpose | Link |
|---|---|---|
| **Interactsh** | Detect out-of-band interactions generated by target systems. | https://app.interactsh.com/ |
| **Pingback.sh** | Monitor out-of-band interactions and blind vulnerabilities. | https://pingback.sh/ |

## LFI, Command Injection & Reverse Shells

| Resource | Purpose | Link |
|---|---|---|
| **ExecEvasion** | Generate and investigate LFI-oriented payload and evasion techniques. | https://dr34mhacks.github.io/ExecEvasion/index.html |
| **Reverse Shell Generator** | Generate reverse-shell commands for authorized lab and assessment environments. | https://tex2e.github.io/reverse-shell-generator/index.html |
| **RevShells** | Generate reverse-shell payloads and commands. | https://www.revshells.com/ |

## GraphQL Security Testing

| Resource | Purpose | Link |
|---|---|---|
| **GQL Hunter** | GraphQL reconnaissance and security testing. | https://gqlhunter.vercel.app/ |

## CSP & Client-Side Security

| Resource | Purpose | Link |
|---|---|---|
| **CSP Bypass** | Research and test Content Security Policy bypass scenarios. | https://cspbypass.com/ |

## SQL Injection Tools

| Resource | Purpose | Link |
|---|---|---|
| **SQLMap Command Generator** | Assist with constructing SQLMap command syntax. | https://acorzo1983.github.io/SQLMapCG/ |

## Browser Extensions

| Resource | Purpose | Link |
|---|---|---|
| **DOMLogger++** | Monitor DOM activity and assist with client-side XSS research. | https://addons.mozilla.org/en-US/firefox/addon/domloggerpp/ |
| **FancyTracker** | Analyze trackers and client-side scripts. | https://addons.mozilla.org/en-US/firefox/addon/fancytracker-ff/ |
| **Multi-Account Containers** | Isolate multiple accounts and browser sessions. | https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/ |
| **Retire.js** | Identify outdated or vulnerable JavaScript libraries. | https://addons.mozilla.org/en-US/firefox/addon/retire-js/ |

## Developer Utilities

| Resource | Purpose | Link |
|---|---|---|
| **Devina.io** | Encoding, decoding, formatting and general developer utilities. | https://devina.io/ |

## Burp Suite Guides & Extensions

| Resource | Purpose | Link |
|---|---|---|
| **BurpSuite For Pentester** | Burp Suite guide or extension | https://github.com/Ignitetechnologies/BurpSuite-For-Pentester |
| **GraphQuail - Burp GraphQL Extension** | Burp Suite guide or extension | https://github.com/forcesunseen/graphquail |
| **InQL - Burp GraphQL Testing Extension** | Burp Suite guide or extension | https://github.com/doyensec/inql |

## Cheatsheets, Checklists & Methodologies

| Resource | Purpose | Link |
|---|---|---|
| **10 Rules to Succeed in Bug Bounty** | Recon/testing methodology, roadmap, or checklist | https://webs3c.com/t/the-10-rules-to-be-successful-in-your-bug-bounty-career/123 |
| **40 Tips and Tricks for Beginners** | Recon/testing methodology, roadmap, or checklist | https://freedium.cfd/https://thegrayarea.tech/40-tips-and-tricks-to-improve-your-bug-bounties-as-a-beginner-ef302707b14a |
| **Account Takeover** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Account%20Takeover |
| **Advanced Google Dork Cheat Sheet** | Cheatsheet or payload reference for testing | https://decrypter.medium.com/advanced-google-dork-cheat-sheet-b88db1ef7c57 |
| **Advanced SQL Injection Cheatsheet** | Cheatsheet or payload reference for testing | https://github.com/kleiton0x00/Advanced-SQL-Injection-Cheatsheet |
| **API Key Leaks** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/API%20Key%20Leaks |
| **Book of Bug Bounty Tips** | Recon/testing methodology, roadmap, or checklist | https://gowsundar.gitbook.io/book-of-bugbounty-tips |
| **Bug Bounty & ChatGPT** | Recon/testing methodology, roadmap, or checklist | https://medium.com/@batuhanaydinn/bug-bounty-hunting-how-to-use-chatgpt-61d81ed85e34 |
| **Bug Bounty 101: Step-by-Step Practical Approach** | Recon/testing methodology, roadmap, or checklist | https://freedium.cfd/https://santhosh-adiga-u.medium.com/bug-bounty-101-step-by-step-practical-approach-to-recon-and-discovery-43a4f505e3d3 |
| **Bug Bounty Cheatsheet** | Cheatsheet or payload reference for testing | https://m0chan.github.io/2019/12/17/Bug-Bounty-Cheetsheet.html |
| **Bug Bounty Checklist** | Recon/testing methodology, roadmap, or checklist | https://github.com/sehno/Bug-bounty/blob/master/bugbounty_checklist.md |
| **Bug Bounty Getting Started Tips** | Recon/testing methodology, roadmap, or checklist | https://infosecwriteups.com/bug-bounty-getting-started-some-tips-600866c4d790 |
| **Bug Bounty Recon Mindmap** | Recon/testing methodology, roadmap, or checklist | https://www.figma.com/board/thQhv59LVT5jGG4M8ZsQms/Bug-Bounty-Recon-Mindmap---BB003?node-id=0-1&node-type=canvas |
| **Bug Bounty Wordlists** | Cheatsheet or payload reference for testing | https://github.com/abdallaabdalrhman/Wordlist-for-Bug-Bounty |
| **Bug Hunter Handbook** | Recon/testing methodology, roadmap, or checklist | https://gowthams.gitbook.io/bughunter-handbook/getting-started-in-bug-bounties |
| **Bug Hunting Recon Methodology Part 1** | Recon/testing methodology, roadmap, or checklist | https://systemweakness.com/bug-hunting-recon-methodology-part1-legionhunter-975b7bbe3231 |
| **Bug Hunting Recon Methodology Part 2** | Recon/testing methodology, roadmap, or checklist | https://osintteam.blog/bug-hunting-recon-methodology-part2-legionhunter-4bb925e3e1bf |
| **BugBounty.zip** | Bug bounty resources and reference material. | https://bugbounty.zip/ |
| **Burp Suite 101: Deep Into Intruder** | Recon/testing methodology, roadmap, or checklist | https://hacklido.com/blog/631-burpsuite-101-going-deep-into-intruder |
| **Burp Suite 101: Introduction and Installation** | Recon/testing methodology, roadmap, or checklist | https://hacklido.com/blog/621-burpsuite-101-introduction-and-installation |
| **Burp Suite 101: Navigation & Configuration** | Recon/testing methodology, roadmap, or checklist | https://hacklido.com/blog/624-burp-suite-101-understanding-navigation-dashboard-configuration |
| **Burp Suite 101: Proxy and Target** | Recon/testing methodology, roadmap, or checklist | https://hacklido.com/blog/625-burp-suite-101-exploring-burp-proxy-and-target-specification |
| **Burp Suite 101: Repeater and Comparer** | Recon/testing methodology, roadmap, or checklist | https://hacklido.com/blog/628-burpsuite-101-exploring-burp-repeater-and-burp-comparer |
| **Cheat Sheet Collections** | Cheatsheet or payload reference for testing | https://github.com/emadshanab/cheat-sheet-collections |
| **Clickjacking** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Clickjacking |
| **Client Side Path Traversal** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Client%20Side%20Path%20Traversal |
| **Command Injection** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Command%20Injection |
| **Content Injection Cheatsheet** | Cheatsheet or payload reference for testing | https://github.com/EdOverflow/bugbounty-cheatsheet/blob/master/cheatsheets/content-injection.md |
| **CORS Misconfiguration** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/CORS%20Misconfiguration |
| **CRLF Injection** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/CRLF%20Injection |
| **Cross-Site Request Forgery (CSRF)** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Cross-Site%20Request%20Forgery |
| **CSV Injection** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/CSV%20Injection |
| **Cybersecurity Roadmap 2022** | Recon/testing methodology, roadmap, or checklist | https://infosecwriteups.com/roadmap-to-cybersecurity-in-2022-full-read-ssrf-idor-in-graphql-gcp-pentesting-and-much-74d2d906f7d7 |
| **CyberX Society - Recon to Reward Workflow** | Recon/testing methodology, roadmap, or checklist | https://cyberxsociety.com/from-recon-to-reward-my-step-by-step-bug-bounty-workflow |
| **Denial of Service** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Denial%20of%20Service |
| **Dependency Confusion** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Dependency%20Confusion |
| **Directory Traversal** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Directory%20Traversal |
| **DNS Rebinding** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/DNS%20Rebinding |
| **DOM Clobbering** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/DOM%20Clobbering |
| **External Variable Modification** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/External%20Variable%20Modification |
| **File Inclusion** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/File%20Inclusion |
| **Galaxy Bug Bounty Checklist** | Recon/testing methodology, roadmap, or checklist | https://github.com/0xmaximus/Galaxy-Bugbounty-Checklist |
| **GraphQL Injection** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/GraphQL%20Injection |
| **Insecure Deserialization** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Deserialization |
| **Insecure Direct Object References (IDOR)** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Direct%20Object%20References |
| **Insecure Management Interface** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Management%20Interface |
| **Insecure Randomness** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Randomness |
| **Insecure Source Code Management** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Source%20Code%20Management |
| **LaTeX Injection** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/LaTeX%20Injection |
| **LDAP Injection** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/LDAP%20Injection |
| **Mass Assignment** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Mass%20Assignment |
| **Mastering the Hunt: Ultimate Guide** | Recon/testing methodology, roadmap, or checklist | https://freedium.cfd/https://osintteam.blog/mastering-the-hunt-the-ultimate-guide-to-modern-bug-bounty-hunting-416357b08abb |
| **Mastering the Skills of Bug Bounty** | Recon/testing methodology, roadmap, or checklist | https://medium.com/swlh/mastering-the-skills-of-bug-bounty-2201eb6a9f4 |
| **MSSQL Injection Cheat Sheet** | Cheatsheet or payload reference for testing | https://www.advania.co.uk/insights/blog/mssql-practical-injection-cheat-sheet |
| **Node.js Security Checklist** | Recon/testing methodology, roadmap, or checklist | https://blog.risingstack.com/node-js-security-checklist |
| **NoSQL Injection** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/NoSQL%20Injection |
| **OAuth Misconfiguration** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/OAuth%20Misconfiguration |
| **Open Redirect** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Open%20Redirect |
| **ORM Leak** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/ORM%20Leak |
| **PayloadsAllTheThings (Main)** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings |
| **Pentest Cheatsheet** | Penetration-testing commands, techniques and references. | https://anshu19981.github.io/Pentestcheatsheet/ |
| **Pentestbook Web Checklist** | Recon/testing methodology, roadmap, or checklist | https://pentestbook.six2dez.com/others/web-checklist |
| **Prompt Injection** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Prompt%20Injection |
| **Prototype Pollution** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Prototype%20Pollution |
| **Race Condition** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Race%20Condition |
| **Regular Expression** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Regular%20Expression |
| **Request Smuggling** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Request%20Smuggling |
| **SAML Injection** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/SAML%20Injection |
| **Security Checklist** | Security testing and assessment checklist. | https://aisearch.bugbountyhunt.com/security-checklist |
| **Server Side Include Injection** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Server%20Side%20Include%20Injection |
| **Server Side Request Forgery (SSRF)** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Server%20Side%20Request%20Forgery |
| **Server Side Template Injection (SSTI)** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Server%20Side%20Template%20Injection |
| **SQL Injection** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/SQL%20Injection |
| **Tabnabbing** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Tabnabbing |
| **Twitter - Infosec Tips** | Recon/testing methodology, roadmap, or checklist | https://twitter.com/yasser_elsnbary/status/1554839187626438657?s=21&t=kfOz8aqpwtWNvJeOUNyG3Q |
| **Type Juggling** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Type%20Juggling |
| **Upload Insecure Files** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Upload%20Insecure%20Files |
| **Vulnerability Checklist** | Recon/testing methodology, roadmap, or checklist | https://github.com/Az0x7/vulnerability-Checklist?tab=readme-ov-file |
| **Web Application Reconnaissance Guide** | Recon/testing methodology, roadmap, or checklist | https://shubhdhungana.medium.com/web-application-reconnaissance-guide-cybersec-shubham-dhungana-17858c967e2b |
| **Web Cache Deception** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Web%20Cache%20Deception |
| **Web Roadmap Image** | Recon/testing methodology, roadmap, or checklist | https://raw.githubusercontent.com/1ndianl33t/Bug-Bounty-Roadmaps/master/Web%20Roadmap.png |
| **Web Sockets** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Web%20Sockets |
| **When GPTs Call Home: Exploiting SSRF in ChatGPT’s Custom Actions - by SirLeeroyJenkins - Nov, 2025** | Recon/testing methodology, roadmap, or checklist | https://sirleeroyjenkins.medium.com/when-gpts-call-home-exploiting-ssrf-in-chatgpts-custom-actions-5df9df27dbe9 |
| **XPATH Injection** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XPATH%20Injection |
| **XSLT Injection** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XSLT%20Injection |
| **XXE Injection** | Cheatsheet or payload reference for testing | https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XXE%20Injection |

## Practice Labs & Vulnerable Apps

| Resource | Purpose | Link |
|---|---|---|
| **AWSGoat - Damn Vulnerable AWS Infrastructure** | Intentionally vulnerable application for hands-on practice | https://github.com/ine-labs/AWSGoat |
| **AzureGoat - Damn Vulnerable Azure Infrastructure** | Intentionally vulnerable application for hands-on practice | https://github.com/ine-labs/AzureGoat |
| **Damn Vulnerable Application Scanner (Paper)** | Intentionally vulnerable application for hands-on practice | https://ceur-ws.org/Vol-2940/paper36.pdf |
| **Damn Vulnerable Bank (Android)** | Intentionally vulnerable application for hands-on practice | https://github.com/rewanthtammana/Damn-Vulnerable-Bank |
| **Damn Vulnerable C# Application (API)** | Intentionally vulnerable application for hands-on practice | https://github.com/appsecco/dvcsharp-api |
| **Damn Vulnerable GraphQL Application** | Intentionally vulnerable application for hands-on practice | https://github.com/dolevf/Damn-Vulnerable-GraphQL-Application |
| **Damn Vulnerable Web Services (Legacy)** | Intentionally vulnerable application for hands-on practice | https://github.com/snoopysecurity/dvws |
| **Damn Vulnerable Web Services (Node)** | Intentionally vulnerable application for hands-on practice | https://github.com/snoopysecurity/dvws-node |
| **DVCA - Damn Vulnerable Cloud Application** | Intentionally vulnerable application for hands-on practice | https://github.com/m6a-UdS/dvca |
| **DVFaaS - Damn Vulnerable Functions as a Service** | Intentionally vulnerable application for hands-on practice | https://github.com/we45/DVFaaS-Damn-Vulnerable-Functions-as-a-Service |
| **DVGM - Damn Vulnerable Grade Management System** | Intentionally vulnerable application for hands-on practice | https://git.logicalhacking.com/BrowserSecurity/DVGM |
| **DVHMA - Damn Vulnerable Hybrid Mobile App** | Intentionally vulnerable application for hands-on practice | https://github.com/logicalhacking/DVHMA |
| **DVIA - Damn Vulnerable iOS App** | Intentionally vulnerable application for hands-on practice | https://github.com/prateek147/DVIA |
| **DVIA v2 - Damn Vulnerable iOS App (Swift)** | Intentionally vulnerable application for hands-on practice | https://github.com/prateek147/DVIA-v2 |
| **DVID - Damn Vulnerable IoT Device** | Intentionally vulnerable application for hands-on practice | https://github.com/Vulcainreo/DVID |
| **DVJA - Damn Vulnerable Java Application** | Intentionally vulnerable application for hands-on practice | https://github.com/appsecco/dvja |
| **DVNA - Damn Vulnerable NodeJS Application** | Intentionally vulnerable application for hands-on practice | https://github.com/appsecco/dvna |
| **DVPWA - Damn Vulnerable Python Web App** | Intentionally vulnerable application for hands-on practice | https://github.com/anxolerd/dvpwa |
| **DVRA - Damn Vulnerable Rails App** | Intentionally vulnerable application for hands-on practice | https://github.com/guilleiguaran/dvra |
| **DVRF - Damn Vulnerable Router Firmware** | Intentionally vulnerable application for hands-on practice | https://github.com/praetorian-inc/DVRF |
| **DVSA - Damn Vulnerable Serverless Application** | Intentionally vulnerable application for hands-on practice | https://github.com/OWASP/DVSA |
| **DVTA - Damn Vulnerable Thick Client App** | Intentionally vulnerable application for hands-on practice | https://github.com/srini0x00/dvta |
| **DVWA - Damn Vulnerable Web Application** | Intentionally vulnerable application for hands-on practice | https://github.com/digininja/DVWA |
| **DVWPS - Damn Vulnerable WordPress Site** | Intentionally vulnerable application for hands-on practice | https://github.com/vianasw/dvwps |
| **Tiredful-API - Broken REST API** | Intentionally vulnerable application for hands-on practice | https://github.com/payatu/Tiredful-API |
| **VAmPI - Vulnerable REST API** | Intentionally vulnerable application for hands-on practice | https://github.com/erev0s/VAmPI |

## Learning Platforms & Practice Grounds

| Resource | Purpose | Link |
|---|---|---|
| **Certified Red Team Analyst (CRTA)** | Learning platform or hands-on practice ground | https://portal.cyberwarfare.live/products/certified-red-team-analyst |
| **CTFtime Writeups** | Learning platform or hands-on practice ground | https://ctftime.org/writeups |
| **Cyber3ra Dashboard** | Learning platform or hands-on practice ground | https://cyber3ra.com/dashboard |
| **CyberWarFare Labs Support** | Learning platform or hands-on practice ground | https://labs.cyberwarfare.live/app/support |
| **Ethical Hacking Labs** | Learning platform or hands-on practice ground | https://github.com/Samsar4/Ethical-Hacking-Labs |
| **Free 350+ TryHackMe Rooms** | Learning platform or hands-on practice ground | https://sm4rty.medium.com/free-350-tryhackme-rooms-f3b7b2954b8d |
| **Hackers Arise** | Learning platform or hands-on practice ground | https://www.hackers-arise.com/ |
| **Hackersploit Tutorials** | Learning platform or hands-on practice ground | https://hackersploit.org/bug-bounty-tutorials |
| **Hacking Articles (GitHub)** | Learning platform or hands-on practice ground | https://github.com/tamim1089/hacking-articles |
| **HackingArticles Web Pentest** | Learning platform or hands-on practice ground | https://www.hackingarticles.in/web-penetration-testing |
| **HackingArticles.in** | Learning platform or hands-on practice ground | https://www.hackingarticles.in/ |
| **HackingHub** | Learning platform or hands-on practice ground | https://hackinghub.net/ |
| **HackTricks Book** | Learning platform or hands-on practice ground | https://book.hacktricks.xyz/ |
| **HackTricks Wiki** | Learning platform or hands-on practice ground | https://book.hacktricks.wiki/en/index.html |
| **How to Study Cyber Security for Free** | Learning platform or hands-on practice ground | https://medium.com/@kashishcharaya/how-to-study-cyber-security-on-your-own-for-free-a4f894dad919 |
| **Hubs Pathshala** | Learning platform or hands-on practice ground | https://pathshala.spinthehack.in/ |
| **Intro to Secure Coding** | Learning platform or hands-on practice ground | https://www.opensecuritytraining.info/IntroSecureCoding.html |
| **OverTheWire Wargames** | Learning platform or hands-on practice ground | https://overthewire.org/ |
| **PortSwigger Web Security Labs** | Learning platform or hands-on practice ground | https://portswigger.net/web-security/all-labs |
| **Secure Code Review** | Learning platform or hands-on practice ground | https://www.opensecuritytraining.info/SecureCodeReview.html |
| **Top 100 Hacking & Security E-Books** | Learning platform or hands-on practice ground | https://github.com/yeahhub/Hacking-Security-Ebooks |
| **TryHackMe Roadmap (Hunterdii)** | Learning platform or hands-on practice ground | https://github.com/Hunterdii/TryHackMe-Roadmap?tab=readme-ov-file#intro-rooms |
| **TryHackMe Roadmap (rng70)** | Learning platform or hands-on practice ground | https://github.com/rng70/TryHackMe-Roadmap?tab=readme-ov-file |

## Awesome Lists & Tool Collections

| Resource | Purpose | Link |
|---|---|---|
| **All-in-One Hacking Tool** | Curated list of hacking and security tools | https://github.com/Z4nzu/hackingtool |
| **Awesome Bug Bounty Tools** | Curated list of hacking and security tools | https://github.com/vavkamil/awesome-bugbounty-tools |
| **Awesome Ethical Hacking** | Curated list of hacking and security tools | https://github.com/husnainfareed/Awesome-Ethical-Hacking-Resources |
| **Awesome Hacker Search Engines** | Curated list of hacking and security tools | https://github.com/edoardottt/awesome-hacker-search-engines |
| **Awesome Security Hardening** | Curated list of hacking and security tools | https://github.com/decalage2/awesome-security-hardening |
| **Awesome Web Security** | Curated list of hacking and security tools | https://github.com/qazbnm456/awesome-web-security |
| **BB Resources (Voorivex)** | Curated list of hacking and security tools | https://github.com/Voorivex/bb-resouces |
| **Bug Bounty Reference (Ngalongc)** | Curated list of hacking and security tools | https://github.com/ngalongc/bug-bounty-reference |
| **Bug Bounty Toolkit** | Curated list of hacking and security tools | https://hackrootone.github.io/BugBountyToolkit |
| **BugBountyHunting.com** | Curated list of hacking and security tools | https://bugbountyhunting.com/ |
| **Cyber Security Foundations** | Curated list of hacking and security tools | https://github.com/acelakshitverma/Cyber-Security-Foundations |
| **hktalent TOP** | Curated list of hacking and security tools | https://github.com/hktalent/TOP |
| **Infosec Encyclopedia** | Curated list of hacking and security tools | https://github.com/GoVanguard/list-infosec-encyclopedia/blob/master/README.md |
| **KathanP19 Security** | Curated list of hacking and security tools | https://github.com/KathanP19 |
| **Pentest Tools List** | Curated list of hacking and security tools | https://pentestlist.com/tools |
| **Practical Cyber Security Resources** | Curated list of hacking and security tools | https://github.com/brcyrr/PracticalCyberSecurityResources |
| **Python Pentest Tools** | Curated list of hacking and security tools | https://github.com/dloss/python-pentest-tools |
| **Study Bug Bounty** | Curated list of hacking and security tools | https://github.com/bobby-lin/study-bug-bounty |
| **Webapp Exploit Tools Inventory** | Curated list of hacking and security tools | https://inventory.raw.pm/tools.html#title-tools-web-application-exploitation |
| **WebHackersWeapons** | Curated list of hacking and security tools | https://github.com/hahwul/WebHackersWeapons |
| **WebHackersWeapons (Dum7c)** | Curated list of hacking and security tools | https://github.com/Dum7c/WebHackersWeapons |
| **X0rb3l Cyber Bookmarks** | Curated list of hacking and security tools | https://x0rb3l.github.io/Cyber-Bookmarks/bookmarks.html |

## Bug Bounty Writeups & Case Studies

| Resource | Purpose | Link |
|---|---|---|
| **$13,500 Bounty - Parameter Pollution** | Bug bounty writeup / real-world case study | https://infosecwriteups.com/how-i-got-my-first-13500-bounty-through-parameter-polluting-hpp-179666b8e8bb |
| **$150 Broken Access Control - First Bounty** | Bug bounty writeup / real-world case study | https://medium.com/@BugBountyWriteups/150-broken-access-control-hackerone-bug-bounty-program-my-first-bounty-239aff71376f |
| **$49,500 Critical Bug in Instagram** | Bug bounty writeup / real-world case study | https://infosecwriteups.com/how-i-found-a-critical-bug-in-instagram-and-got-49500-bounty-from-facebook-626ff2c6a853 |
| **Admin Panel Takeover Worth $3500** | Bug bounty writeup / real-world case study | https://assassin-marcos.medium.com/breaking-the-barrier-admin-panel-takeover-worth-3500-78da79089ca3 |
| **Advanced Guide to Penetration Testing in APIs - MeetCyber** | Bug bounty writeup / real-world case study | https://medium.com/meetcyber/advanced-guide-to-penetration-testing-in-apis-part-2-practical-exploitation-mitigation-and-poc-140216b8eef3 |
| **Automating XSS and SQL Injection** | Bug bounty writeup / real-world case study | https://medium.com/@Tenebris_Venator/automating-xss-and-sql-injection-discovery-from-manual-testing-to-python-scripting-c30145ab20ac |
| **Beyond XSS - Token Storage** | Bug bounty writeup / real-world case study | https://aszx87410.github.io/beyond-xss/en/ch2/token-storage |
| **Buffer Overflow Part 1 - Memory Layout** | Bug bounty writeup / real-world case study | https://hacklido.com/blog/328-understanding-buffer-overflow-vulnerabilities-part-1-memory-layout-and-the-call-stack |
| **Buffer Overflow Part 2 - Stack Overflow** | Bug bounty writeup / real-world case study | https://hacklido.com/blog/339-understanding-buffer-overflow-vulnerabilities-part-2-stack-overflow-in-a-simple-c-program |
| **Buffer Overflow Part 3 - CPU Registers** | Bug bounty writeup / real-world case study | https://hacklido.com/blog/353-understanding-buffer-overflow-vulnerabilities-part-3-understanding-cpu-registers |
| **Buffer Overflow Part 4 - Debugging C Program** | Bug bounty writeup / real-world case study | https://hacklido.com/blog/354-understanding-buffer-overflow-vulnerabilities-part-4-debugging-a-c-program |
| **Business Logic - Broken Wallet & OTP Bypass** | Bug bounty writeup / real-world case study | https://infosecwriteups.com/business-logic-broken-wallet-hacked-otp-bypassed-d82e6591a63a |
| **Bypassing 403s - Broken Access Control** | Bug bounty writeup / real-world case study | https://shrirangdiwakar.medium.com/bypassing-403s-like-a-pro-2-100-broken-access-control-66beef4afa8c |
| **Chained 3 Bugs into Full Account Takeover** | Bug bounty writeup / real-world case study | https://infosecwriteups.com/one-endpoint-to-rule-them-all-chained-3-bugs-into-full-account-takeover-e2a71592ca7e |
| **CORS Vulnerability with Trusted Null Origin** | Bug bounty writeup / real-world case study | https://infosecwriteups.com/cors-vulnerability-with-trusted-null-origin-0f9593bd7674 |
| **Discovering IDOR from Blank Page** | Bug bounty writeup / real-world case study | https://medium.com/@kerstan/how-to-discovered-idor-from-a-blank-page-bug-bounty-tuesday-5af784533d1a |
| **From 404 to $4,000: Real Bugs Found in Forgotten Endpoints - by Monika sharma - Nov, 2025** | Bug bounty writeup / real-world case study | https://infosecwriteups.com/from-404-to-4-000-real-bugs-found-in-forgotten-endpoints-5886c06f7473 |
| **GraphQL Introspection - Sensitive Data Disclosure** | Bug bounty writeup / real-world case study | https://medium.com/@pranaybafna/graphql-introspection-leads-to-sensitive-data-disclosure-65b385452d7f |
| **How I found Vulnerability on Google Forms (Duplicate Internal — Fixed) - by Qadhafy Muhammad Tera - Nov, 2025** | Bug bounty writeup / real-world case study | https://medium.com/@ecdnts/how-i-found-vulnerability-on-google-forms-duplicate-internal-fixed-d02aa2e6357c |
| **How to Discover GraphQL Vulnerabilities** | Bug bounty writeup / real-world case study | https://www.cobalt.io/blog/deep-dive-into-graphql-pt.-2?hs_preview=mxIZUTSv-97236639291 |
| **How to JS for Pentest: Edition 2023** | Bug bounty writeup / real-world case study | https://kongsec.medium.com/how-to-js-for-bug-bounties-edition-2023-7108b56d9db6 |
| **IDOR in Image Upload Function** | Bug bounty writeup / real-world case study | https://infosecwriteups.com/gone-in-a-click-idor-vulnerabilities-in-image-upload-function-6c4817b44d8c |
| **In-Depth Analysis of 3 IDOR Bugs** | Bug bounty writeup / real-world case study | https://medium.com/@atomiczsec/one-bug-at-a-time-in-depth-analysis-of-3-idor-bugs-2fb016e21b96 |
| **InfoSec Writeups - Bug Bounty Tagged** | Bug bounty writeup / real-world case study | https://infosecwriteups.com/tagged/bug-bounty |
| **JS is the New S3 - Mining Secrets** | Bug bounty writeup / real-world case study | https://medium.com/meetcyber/js-is-the-new-s3-how-i-mined-tokens-pii-devops-secrets-from-javascript-for-bounties-13b6bdf1b829 |
| **Lessons from First 100 HackerOne Reports** | Bug bounty writeup / real-world case study | https://infosecwriteups.com/what-i-learned-from-my-first-100-hackerone-reports-6a413adbe319 |
| **Master Subdomain Hunting** | Bug bounty writeup / real-world case study | https://infosecwriteups.com/master-subdomain-hunting-art-of-finding-hidden-assets-3351b3c8467a |
| **Mastering Subfinder for Bug Bounty** | Bug bounty writeup / real-world case study | https://cybersecuritywriteups.com/mastering-subfinder-for-bug-bounty-my-secret-weapon-for-finding-hidden-subdomains-%EF%B8%8F-%EF%B8%8F-91a62d04651d |
| **OAuth Authentication Bypass leading to PII disclosure - by janlele91 - Nov, 2025** | Bug bounty writeup / real-world case study | https://medium.com/@bugbounty0901/oauth-authentication-bypass-leading-to-pii-disclosure-5d243b62d532 |
| **OAuth Misconfiguration - Full Account Takeover** | Bug bounty writeup / real-world case study | https://medium.com/@aditya043k/oauth-misconfiguration-leads-to-full-account-takeover-d93c0d0fb66c |
| **SshControl. Summary - by dj4m - Nov, 2025** | Bug bounty writeup / real-world case study | https://medium.com/@dj4msec/sshcontrol-84d4fb0ed8eb |
| **SSRF via filename - PDF Extractor (via SMTP), detailed shi- write-up - by Sevada797 - Nov, 2025** | Bug bounty writeup / real-world case study | https://medium.com/@zatikyan.sevada/ssrf-via-filename-pdf-extractor-via-smtp-detailed-shi-write-up-f494d320fa75 |
| **Subdomain Takeover Learning** | Bug bounty writeup / real-world case study | https://medium.com/@cosmicbyt3/how-i-learned-about-subdomain-takeover-e4823366b3f8 |
| **The Cache Poisoning Bible: Part 1 — Advanced Fundamentals** | Bug bounty writeup / real-world case study | https://medium.com/@Aacle/the-cache-poisoning-bible-part-1-advanced-fundamentals-2c8e9d7be2e9 |
| **When One Error Message Unlocked the Entire Kingdom: A Critical SQL Injection Tale** | Bug bounty writeup / real-world case study | https://0dayscyber.medium.com/when-one-error-message-unlocked-the-entire-kingdom-a-critical-sql-injection-tale-1655c93dd2f8 |

## Video Tutorials & Playlists

| Resource | Purpose | Link |
|---|---|---|
| **$20,000 HackerOne Data Leakage via GraphQL** | Video tutorial or walkthrough | https://www.youtube.com/watch?app=desktop&v=tJtNTqviOGg |
| **3 Tricks to Hunt Faster in Bug Bounty** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=9CiDsOI-p1s |
| **Complete Bash Scripting Course From Level 0 - Shell Scripting - Linux Administration - Devops** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=LtE30PtFXbQ |
| **Find Bugs in AI Model using Promptfoo 🔥 - Full Red Team Walkthrough + OWASP LLM Security Explained** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=7nN4xzaWyYo |
| **GraphQL Testing Tutorial Playlist** | Video tutorial or walkthrough | https://www.youtube.com/playlist?list=PLFh6J1ZHhqNhfSVt4WaF9GgOCOq9PYYBa |
| **Hidden in Plain Site: API Information Disclosure** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=jBi3a-dXsM8 |
| **How Hackers Bypass Paywalls? (Real Techniques)** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=X-fspAWAqzQ |
| **Learn Hacking Easily With DeepSeek AI** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=VTS9smS_3FI |
| **NoSQL Injection — Joseph Simon Unveils Hidden Vulnerabilities at FOXXCON Meetup November** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=jeuas_3Wd10 |
| **Recon for Bug Bounty By Hacklido** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=eK4jDaXGGhk |
| **Targeting for Bug Bounty Research** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=hYJ7ipSOplw |
| **The AI Hacking Skill Worth $150K+ (Gandalf Level 7)** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=yxzGhEv1ktE |
| **Ultimate GraphQL Recon - A Tactical Approach** | Video tutorial or walkthrough | https://www.youtube.com/watch?app=desktop&v=c_RPptC4V9I |
| **YouTube Playlist 1** | Video tutorial or walkthrough | https://www.youtube.com/watch?index=1&list=PLv7cogHXoVhXvHPzIl1dWtBiYUAL8baHj&v=BjfCWSFmIFI |
| **YouTube Playlist 2** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=5N7k0g7arYE |
| **YouTube Playlist 3** | Video tutorial or walkthrough | https://www.youtube.com/watch?list=PLbyncTkpno5FZQ3ZgpHj1BdQ7XHwfvO1w&v=RobCqW2KwGs |
| **YouTube Playlist 4** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=bHdK7TGgYKI |
| **YouTube Playlist 5** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=qOEahjuOYJo |
| **YouTube Playlist 6** | Video tutorial or walkthrough | https://www.youtube.com/watch?list=PL9gnSGHSqcnr_DxHsP7AW9ftq0AtAyYqJ&v=rZ41y93P2Qo |
| **YouTube Playlist 7** | Video tutorial or walkthrough | https://www.youtube.com/watch?list=PLyqga7AXMtPPuibxp1N0TdyDrKwP9H_jD&v=rWHvp7rUka8 |
| **YouTube Playlist 8** | Video tutorial or walkthrough | https://www.youtube.com/watch?list=PLJ18l2m4Gsa_d-WrmQYi6AcjQCxRZ0wG1&v=C_8WvR1rKpM |
| **YouTube Tutorial 1** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=ggClgbxHDLw |
| **YouTube Tutorial 2** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=G1RHa7l1Ys4 |
| **YouTube Tutorial 3** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=Ifo1vIdfyhg |
| **YouTube Tutorial 4** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=p4JgIu1mceI |
| **YouTube Tutorial 5** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=5Di0VVK9JiQ |
| **YouTube Tutorial 6** | Video tutorial or walkthrough | https://www.youtube.com/watch?v=XJXBtS1S6FY |

## Communities, Blogs & Podcasts

| Resource | Purpose | Link |
|---|---|---|
| **Critical Thinking Podcast** | Security community, blog, or podcast | https://criticalthinkingpodcast.io/ |
| **Pentester Land** | Security community, blog, or podcast | https://pentester.land/ |
| **Pentester Land Newsletters** | Security community, blog, or podcast | https://pentester.land/categories/newsletter |
| **The Hacker News** | Security community, blog, or podcast | https://thehackernews.com/ |
| **Twitter - CEOS3C** | Security community, blog, or podcast | https://twitter.com/ceos3c/status/1530847515997880320?s=21&t=KOzbQwSHgCf04T_Vx0EaDw |

## Miscellaneous

| Resource | Purpose | Link |
|---|---|---|
| **Chaos by ProjectDiscovery** | Miscellaneous security reference | https://chaos.projectdiscovery.io/ |
| **CI/CD Goat - Vulnerable CI/CD Environment** | Miscellaneous security reference | https://github.com/cider-security-research/cicd-goat |
| **First Bounty Guide** | Miscellaneous security reference | https://github.com/BehiSecc/First-Bounty?tab=readme-ov-file |
| **HowToHunt Collection** | Miscellaneous security reference | https://github.com/KathanP19/HowToHunt |
| **OWASP Threat Modeling** | Miscellaneous security reference | https://owasp.org/www-community/Threat_Modeling |
| **OWASP Web Security Testing Guide** | Miscellaneous security reference | https://github.com/OWASP/wstg/tree/master/document/4-Web_Application_Security_Testing |

---

## Contributing

Found a useful resource that's missing? Open a PR and add it under the most relevant category, keeping entries alphabetically ordered with no duplicate links.
