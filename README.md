#Cybersecurity Resources

A curated collection of cybersecurity tools, labs, frameworks, training, and references. Built for practitioners working in SOC operations, penetration testing, cloud security, and GRC. Not a dump of every link on the internet. Everything here is something I've used, studied, or vetted.

Maintained by **Gabriel A** Also Know as **S3ntin3l**— Security+ | Network+ | IT & Cybersecurity Professional

---

## Table of Contents

- [SOC & Blue Team](#soc--blue-team)
- [Penetration Testing & Red Team](#penetration-testing--red-team)
- [Cloud Security](#cloud-security)
- [GRC & Compliance](#grc--compliance)
- [OSINT & Threat Intelligence](#osint--threat-intelligence)
- [Hands-On Labs & Practice](#hands-on-labs--practice)
- [SIEM & Log Analysis](#siem--log-analysis)
- [Network Security](#network-security)
- [Malware Analysis & Reverse Engineering](#malware-analysis--reverse-engineering)
- [Incident Response & DFIR](#incident-response--dfir)
- [Vulnerability Scanning & Management](#vulnerability-scanning--management)
- [Certifications & Study](#certifications--study)
- [Frameworks & Standards](#frameworks--standards)
- [Hardening Guides](#hardening-guides)
- [Threat Intelligence Feeds](#threat-intelligence-feeds)
- [Communities & News](#communities--news)

---

## SOC & Blue Team

### Training Platforms

- [LetsDefend](https://letsdefend.io/) — Simulates a real SOC environment. You get alerts, triage them, investigate, and close tickets. The SOC Analyst Learning Path is the best free blue team training available. Student discount available with .edu email.
- [CyberDefenders](https://cyberdefenders.org/) — Blue team labs focused on DFIR, threat hunting, and malware analysis. Free downloadable challenges use real breach data. Premium labs are cloud-based.
- [Blue Team Labs Online](https://blueteamlabs.online/) — Hands-on investigations and challenges for system hardening, log analysis, digital forensics, and incident response.
- [RangeForce Community Edition](https://www.rangeforce.com/) — Browser-based cyber ranges for SOC, endpoint protection, and threat response skills.
- [Microsoft Learn — Security Operations Analyst](https://learn.microsoft.com/en-us/training/paths/sc-200-mitigate-threats-using-microsoft-365-defender/) — Free training path for Microsoft Sentinel and Defender XDR. Directly maps to the SC-200 certification.

### SOC Analyst Tooling

- [Splunk](https://www.splunk.com/) — Industry-standard SIEM. Free tier available for learning with up to 500MB/day ingestion.
- [Elastic Security](https://www.elastic.co/security) — Open-source SIEM built on the Elastic Stack. Free training courses available from Elastic.
- [Wazuh](https://wazuh.com/) — Open-source SIEM, XDR, and compliance platform. Can be self-hosted or cloud-managed.
- [YARA](https://virustotal.github.io/yara/) — Pattern matching tool for malware researchers. Write rules to identify and classify malware samples.
- [Sigma Rules](https://github.com/SigmaHQ/sigma) — Generic signature format for SIEM systems. Write once, convert to Splunk/Elastic/QRadar queries.

---

## Penetration Testing & Red Team

### Frameworks & Tools

- [Metasploit](https://www.metasploit.com/) — The standard exploitation framework. Huge module library for payloads, exploits, and auxiliary functions. Open-source edition is free.
- [Burp Suite](https://portswigger.net/burp) — Web application security testing platform. Community edition is free. Industry standard for web app pentesting and bug bounty.
- [Nmap](https://nmap.org/) — Network discovery and security auditing. Identifies hosts, open ports, service versions, and OS fingerprints. Scripting engine allows custom automation.
- [Wireshark](https://www.wireshark.org/) — Deep packet analysis. Intercept and browse network traffic in real time. Essential for network forensics.
- [Gobuster](https://github.com/OJ/gobuster) — Directory and DNS brute-forcing tool written in Go. Fast and reliable for web enumeration.
- [Hashcat](https://hashcat.net/hashcat/) — Advanced password recovery tool. GPU-accelerated hash cracking.
- [John the Ripper](https://www.openwall.com/john/) — Open-source password cracker. Auto-detects hash types and supports custom wordlists.
- [Responder](https://github.com/SpiderLabs/Responder) — LLMNR/NBT-NS/MDNS poisoner for credential capture on internal networks.
- [BloodHound](https://github.com/BloodHoundAD/BloodHound) — Active Directory attack path mapping. Visualizes privilege escalation routes.
- [Impacket](https://github.com/fortra/impacket) — Python library for working with network protocols. Essential for AD attacks and lateral movement.

### Web Application Security

- [PortSwigger Web Security Academy](https://portswigger.net/web-security) — Free, structured web security training with hands-on labs. Covers SQLi, XSS, SSRF, authentication flaws, and more.
- [OWASP Top 10](https://owasp.org/www-project-top-ten/) — The standard reference for web application security risks.
- [OWASP ZAP](https://www.zaproxy.org/) — Free web application vulnerability scanner. Good for automated scanning and manual testing.
- [HackTricks](https://book.hacktricks.xyz/) — Massive reference of pentesting techniques, tricks, and methodologies.

### Operating Systems

- [Kali Linux](https://www.kali.org/) — Purpose-built pentesting distribution. Pre-loaded with hundreds of security tools.
- [Parrot OS](https://www.parrotsec.org/) — Lightweight alternative to Kali with built-in privacy tools.

---

## Cloud Security

### AWS

- [AWS Skill Builder](https://skillbuilder.aws/) — Free self-paced courses. Security learning plans available. 900+ free courses.
- [AWS Well-Architected Framework — Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html) — AWS's own security best practices documentation.
- [Prowler](https://github.com/prowler-cloud/prowler) — Open-source security assessment tool for AWS, Azure, and GCP. Checks against CIS benchmarks.
- [ScoutSuite](https://github.com/nccgroup/ScoutSuite) — Multi-cloud security auditing tool. Generates HTML reports of cloud misconfigurations.
- [CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat) — Vulnerable-by-design AWS environment for practicing cloud exploitation. Made by Rhino Security Labs.
- [Pacu](https://github.com/RhinoSecurityLabs/pacu) — AWS exploitation framework. Think Metasploit but for AWS.
- [LocalStack](https://localstack.cloud/) — Local AWS cloud emulator. Run AWS services on your machine for testing without incurring costs.

### Azure

- [Microsoft Learn — Azure Security](https://learn.microsoft.com/en-us/training/paths/secure-your-cloud-data/) — Free structured training for Azure security fundamentals.
- [AzureGoat](https://github.com/ine-labs/AzureGoat) — Vulnerable-by-design Azure environment for hands-on practice.

### Multi-Cloud

- [Cloud Security Alliance (CSA)](https://cloudsecurityalliance.org/) — Research, certifications (CCSK), and best practices for cloud security.

---

## GRC & Compliance

### Frameworks

- [NIST Cybersecurity Framework (CSF) 2.0](https://www.nist.gov/cyberframework) — The gold standard for organizing cybersecurity programs. Identify, Protect, Detect, Respond, Recover, Govern.
- [NIST SP 800-53](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final) — Security and privacy controls catalog for federal systems. Referenced across industries.
- [CIS Controls v8](https://www.cisecurity.org/controls) — Prioritized set of defensive actions. 18 controls organized by implementation group.
- [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks) — Configuration guides for hardening operating systems, cloud platforms, browsers, and applications.
- [ISO 27001](https://www.iso.org/isoiec-27001-information-security.html) — International standard for information security management systems.
- [MITRE ATT&CK](https://attack.mitre.org/) — Knowledge base of adversary tactics and techniques. Essential for threat modeling and detection engineering.
- [MITRE D3FEND](https://d3fend.mitre.org/) — Complementary framework mapping defensive countermeasures to ATT&CK techniques.

### Compliance Tools

- [OpenSCAP](https://www.open-scap.org/) — Open-source compliance scanning tool. Supports SCAP, CIS benchmarks, and STIG profiles.
- [Lynis](https://cisofy.com/lynis/) — Unix/macOS auditing tool for hardening assessment and compliance checking.

### GRC Platforms

- [Drata](https://drata.com/) — Automated compliance for SOC 2, ISO 27001, HIPAA, GDPR.
- [Vanta](https://www.vanta.com/) — Continuous compliance monitoring and audit preparation.

---

## OSINT & Threat Intelligence

### Reconnaissance Tools

- [Shodan](https://www.shodan.io/) — Search engine for internet-connected devices. Find exposed services, open ports, and vulnerable systems.
- [Censys](https://censys.io/) — Internet-wide scanning platform for discovering and monitoring exposed assets.
- [SpiderFoot](https://github.com/smicallef/spiderfoot) — Automated OSINT collection from 100+ sources. Scans domains, IPs, emails, and names.
- [Maltego](https://www.maltego.com/) — Visual link analysis platform for mapping relationships between entities.
- [theHarvester](https://github.com/laramies/theHarvester) — Email, subdomain, and name harvester from public sources.
- [Recon-ng](https://github.com/lanmaster53/recon-ng) — Web reconnaissance framework with modular architecture. API key support for richer data.
- [Amass](https://github.com/owasp-amass/amass) — Network mapping and attack surface discovery. DNS enumeration and subdomain finder.
- [OSINT Framework](https://osintframework.com/) — Categorized index of free OSINT tools and resources.

### Threat Intelligence

- [VirusTotal](https://www.virustotal.com/) — Multi-engine file and URL scanner. Free API available.
- [AbuseIPDB](https://www.abuseipdb.com/) — IP address reputation database. Report and check malicious IPs.
- [AlienVault OTX](https://otx.alienvault.com/) — Open threat exchange. Community-driven threat intelligence sharing.
- [MISP](https://www.misp-project.org/) — Open-source threat intelligence platform for sharing indicators of compromise.
- [GreyNoise](https://www.greynoise.io/) — Identifies internet background noise vs. targeted attacks. Helps reduce false positives.
- [Have I Been Pwned](https://haveibeenpwned.com/) — Check if your email or phone has been exposed in data breaches.
- [Recorded Future Vulnerability DB](https://www.recordedfuture.com/) — Free CVE database with CVSS scores, attack complexity, and affected products.
- [DNSDumpster](https://dnsdumpster.com/) — Free domain research tool for mapping DNS records, subdomains, and mail servers.
- [ExifTool](https://exiftool.org/) — Metadata extraction from images and documents. Geolocation, device details, timestamps.

---

## Hands-On Labs & Practice

### Beginner-Friendly

- [TryHackMe](https://tryhackme.com/) — Browser-based labs with guided learning paths. Cyber Defense path is built for SOC roles. Many free rooms available.
- [PicoCTF](https://picoctf.org/) — CTF platform built for students. Great for learning the basics of binary exploitation, web security, forensics, and cryptography.

### Intermediate

- [Hack The Box](https://www.hackthebox.com/) — Vulnerable machines and challenges for penetration testing practice. HTB Academy offers structured courses.
- [VulnHub](https://www.vulnhub.com/) — Downloadable vulnerable VMs. Run them locally with VirtualBox or VMware. Offline practice, beginner to expert.
- [PortSwigger Web Security Academy](https://portswigger.net/web-security) — Free web security labs. Covers the full OWASP Top 10 and beyond.

### Advanced

- [Proving Grounds (OffSec)](https://www.offsec.com/labs/) — Practice machines that mirror OSCP exam difficulty.
- [HackTheBox Pro Labs](https://www.hackthebox.com/business/professional-labs) — Enterprise-grade network simulations with Active Directory, pivoting, and lateral movement.

### Blue Team Specific

- [LetsDefend](https://letsdefend.io/) — SOC simulator. Triage alerts, investigate threats, close tickets. Student discount with .edu email.
- [CyberDefenders](https://cyberdefenders.org/) — Blue team challenges using real-world breach data. DFIR, threat hunting, malware analysis.

---

## SIEM & Log Analysis

- [Splunk](https://www.splunk.com/) — Enterprise SIEM. Free tier for learning (500MB/day).
- [Elastic Security (ELK)](https://www.elastic.co/security) — Open-source SIEM on the Elastic Stack.
- [Wazuh](https://wazuh.com/) — Open-source XDR and SIEM with compliance monitoring.
- [Graylog](https://graylog.org/) — Open-source log management and SIEM.
- [Microsoft Sentinel](https://azure.microsoft.com/en-us/products/microsoft-sentinel/) — Cloud-native SIEM on Azure.
- [Hunters](https://www.hunters.ai/) — AI-driven SIEM that correlates multiple data sources for automated investigation.

---

## Network Security

- [Wireshark](https://www.wireshark.org/) — Packet capture and analysis.
- [Nmap](https://nmap.org/) — Network scanning and service detection.
- [Zeek (formerly Bro)](https://zeek.org/) — Network analysis framework for traffic monitoring and anomaly detection.
- [Suricata](https://suricata.io/) — High-performance IDS/IPS and network security monitoring engine.
- [Snort](https://www.snort.org/) — Open-source intrusion detection/prevention system.
- [pfSense](https://www.pfsense.org/) — Open-source firewall and router.
- [Aircrack-ng](https://www.aircrack-ng.org/) — Wi-Fi security auditing suite. WEP/WPA cracking, packet capture, and network analysis.

---

## Malware Analysis & Reverse Engineering

- [Ghidra](https://ghidra-sre.org/) — NSA's open-source reverse engineering framework. Disassembler, decompiler, and scripting.
- [IDA Free](https://hex-rays.com/ida-free/) — Free version of the industry-standard disassembler.
- [REMnux](https://remnux.org/) — Linux distribution for malware analysis. Pre-loaded with analysis tools.
- [Any.Run](https://any.run/) — Interactive malware sandbox. Watch malware execute in real time.
- [Hybrid Analysis](https://www.hybrid-analysis.com/) — Free malware analysis service powered by CrowdStrike Falcon.
- [Triage Malware Sandbox](https://tria.ge/) — Advanced malware analysis sandbox with configuration extraction.
- [PE Studio](https://www.winitor.com/) — Static analysis tool for Windows executables.
- [YARA](https://virustotal.github.io/yara/) — Pattern matching for malware classification.
- [Volatility](https://www.volatilityfoundation.org/) — Memory forensics framework for analyzing RAM dumps.

---

## Incident Response & DFIR

- [Velociraptor](https://docs.velociraptor.app/) — Open-source endpoint visibility and digital forensics tool.
- [TheHive](https://thehive-project.org/) — Open-source incident response platform for SOCs.
- [Cortex](https://github.com/TheHive-Project/Cortex) — Analysis engine for observables. Integrates with TheHive.
- [KAPE](https://www.kroll.com/en/insights/publications/cyber/kroll-artifact-parser-extractor-kape) — Triage and collection tool for forensic artifacts on Windows.
- [Autopsy](https://www.autopsy.com/) — Open-source digital forensics platform.
- [Eric Zimmerman's Tools](https://ericzimmerman.github.io/) — Collection of Windows forensic tools for registry, prefetch, shellbags, and more.
- [SANS DFIR Cheat Sheets](https://www.sans.org/posters/) — Quick reference guides for forensic analysis.

---

## Vulnerability Scanning & Management

- [Nessus](https://www.tenable.com/products/nessus) — Industry-standard vulnerability scanner. Free Essentials edition for personal use.
- [OpenVAS](https://www.openvas.org/) — Open-source vulnerability scanner. Maintained by Greenbone.
- [Nuclei](https://github.com/projectdiscovery/nuclei) — Fast vulnerability scanner based on YAML templates. Community-maintained template library.
- [Nikto](https://cirt.net/Nikto2) — Web server scanner that checks for dangerous files, outdated software, and misconfigurations.
- [Lynis](https://cisofy.com/lynis/) — Unix/macOS system auditing and hardening tool.
- [rkhunter](http://rkhunter.sourceforge.net/) — Rootkit detection tool for Unix systems.
- [chkrootkit](http://www.chkrootkit.org/) — Shell script for detecting known rootkits.

---

## Certifications & Study

### Entry Level

- [CompTIA Security+](https://www.comptia.org/certifications/security) — Baseline cybersecurity certification. Widely recognized for SOC analyst and IT security roles.
- [CompTIA Network+](https://www.comptia.org/certifications/network) — Networking fundamentals. Recommended before Security+.
- [ISC2 CC (Certified in Cybersecurity)](https://www.isc2.org/certifications/cc) — Free entry-level certification from ISC2.

### Intermediate

- [CompTIA CySA+](https://www.comptia.org/certifications/cybersecurity-analyst) — Threat detection, analysis, and response. Blue team focused.
- [AWS Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/) — Foundational cloud certification.
- [Microsoft SC-200](https://learn.microsoft.com/en-us/certifications/security-operations-analyst/) — Security Operations Analyst. Covers Sentinel, Defender, and Microsoft 365 security.

### Advanced

- [CISSP](https://www.isc2.org/certifications/cissp) — The gold standard for security management. Covers 8 domains.
- [CCSP](https://www.isc2.org/certifications/ccsp) — Cloud security certification from ISC2.
- [OSCP](https://www.offsec.com/courses/pen-200/) — Hands-on penetration testing certification. 24-hour practical exam.
- [GIAC certifications](https://www.giac.org/) — Specialized certs for incident handling (GCIH), forensics (GCFE), cloud security (GCLD), and more.

### Free Study Resources

- [Professor Messer](https://www.professormesser.com/) — Free video courses for Security+, Network+, and A+.
- [Cybrary](https://www.cybrary.it/) — Free and paid cybersecurity training courses.
- [SANS Cyber Aces](https://www.sans.org/cyberaces/) — Free introductory courses from SANS.
- [IBM Cybersecurity Fundamentals](https://www.ibm.com/training/) — Free foundational course on cybersecurity tools and techniques.
- [Cisco Introduction to Cybersecurity](https://www.netacad.com/courses/cybersecurity/introduction-cybersecurity) — Free beginner course from Cisco Networking Academy.

---

## Frameworks & Standards

- [NIST CSF 2.0](https://www.nist.gov/cyberframework) — Cybersecurity framework for organizing and improving security programs.
- [NIST SP 800-53 Rev 5](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final) — Comprehensive catalog of security controls.
- [NIST SP 800-61 Rev 2](https://csrc.nist.gov/publications/detail/sp/800-61/rev-2/final) — Computer security incident handling guide.
- [MITRE ATT&CK](https://attack.mitre.org/) — Adversary tactics and techniques knowledge base.
- [MITRE D3FEND](https://d3fend.mitre.org/) — Defensive countermeasures mapped to ATT&CK.
- [CIS Controls v8](https://www.cisecurity.org/controls) — Prioritized security actions.
- [OWASP Top 10](https://owasp.org/www-project-top-ten/) — Web application security risks.
- [Kill Chain (Lockheed Martin)](https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html) — Seven-phase model of cyberattacks.
- [Diamond Model](https://www.activeresponse.org/wp-content/uploads/2013/07/diamond.pdf) — Intrusion analysis framework relating adversary, infrastructure, capability, and victim.

---

## Hardening Guides

- [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks) — Step-by-step hardening guides for Windows, macOS, Linux, AWS, Azure, Docker, Kubernetes, and more.
- [DISA STIGs](https://public.cyber.mil/stigs/) — Security Technical Implementation Guides from the DoD.
- [macOS Security Compliance Project](https://github.com/usnistgov/macos_security) — NIST-maintained macOS hardening baselines.
- [Linux Audit](https://linux-audit.com/) — Practical Linux security guides and tutorials.
- [My macOS Hardening Project](https://github.com/YOUR_USERNAME/macos-security-hardening) — Full audit write-up with Lynis, rkhunter, and hands-on remediation.

---

## Threat Intelligence Feeds

### Free Feeds

- [AlienVault OTX](https://otx.alienvault.com/) — Community-driven threat intelligence.
- [Abuse.ch](https://abuse.ch/) — Malware and botnet tracking. URLhaus, MalwareBazaar, ThreatFox, Feodo Tracker.
- [CIRCL OSINT Feeds](https://www.circl.lu/) — Phishing campaigns, malware analysis, and threat advisories from Luxembourg CERT.
- [MISP OSINT Feeds](https://www.misp-project.org/feeds/) — Aggregated feeds from multiple sources. Sector-specific indicators available.
- [Cybercrime Tracker](https://cybercrime-tracker.net/) — C2 infrastructure tracking for crimeware campaigns.
- [Malc0de Database](http://malc0de.com/database/) — Malware domain feed for DNS blocking.
- [PhishTank](https://phishtank.org/) — Community-verified phishing URL database.

### Commercial (with free tiers)

- [VirusTotal](https://www.virustotal.com/) — Multi-engine scanning with free API access.
- [GreyNoise](https://www.greynoise.io/) — Internet noise filtering. Community tier is free.
- [Recorded Future](https://www.recordedfuture.com/) — Threat intelligence platform. Free vulnerability database available.

---

## Communities & News

### News Sources

- [Krebs on Security](https://krebsonsecurity.com/) — Investigative cybersecurity journalism by Brian Krebs.
- [The Hacker News](https://thehackernews.com/) — Daily cybersecurity news and vulnerability disclosures.
- [Dark Reading](https://www.darkreading.com/) — Enterprise security news and analysis.
- [BleepingComputer](https://www.bleepingcomputer.com/) — Security news, ransomware tracking, and malware analysis.
- [SANS Internet Storm Center](https://isc.sans.edu/) — Daily threat summaries and handler diaries.

### Communities

- [r/cybersecurity](https://www.reddit.com/r/cybersecurity/) — General cybersecurity discussion.
- [r/netsec](https://www.reddit.com/r/netsec/) — Technical security content and research.
- [r/blueteamsec](https://www.reddit.com/r/blueteamsec/) — Blue team focused community.
- [SANS DFIR Discord](https://discord.gg/sans-dfir) — Community for digital forensics and incident response.
- [InfoSec Community on Discord](https://discord.gg/infosec) — Active community for all levels.

### Podcasts

- [Darknet Diaries](https://darknetdiaries.com/) — True stories from the dark side of the internet.
- [SANS Daily StormCast](https://isc.sans.edu/podcast.html) — Quick daily security news briefings.
- [Risky Business](https://risky.biz/) — Weekly information security podcast.
- [Malicious Life](https://malicious.life/) — History of cybersecurity incidents and hacking.

---

## Contributing

Found a broken link or want to suggest a resource? Open an issue or submit a PR. Quality over quantity. Every resource should be something a working professional or serious student would actually use.

---

## License

MIT

---

*Curated by Gabriel Aladegbemi — Security+ | Network+ | IT & Cybersecurity Professional*
*Last updated: March 2026*
