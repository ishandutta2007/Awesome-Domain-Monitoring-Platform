# Awesome-Domain-Monitoring-Platform

## Top Domain Monitoring Platform Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Domain Intelligence, Passive DNS, WHOIS History, Certificate Transparency, Subdomain Monitoring & Attack Surface Visibility*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Domain Monitoring**. These tools help security teams, researchers, and brand protectors track domain registrations, DNS changes, certificate issuance, historical WHOIS/passive DNS data, subdomains, and potential threats across the internet.

**Examples** include DomainTools, SecurityTrails, RiskIQ PassiveTotal, Censys, WhoisXML API, Spyse, ViewDNS, Detectify, Netcraft, DomainIQ, ZeroFox, SOCRadar, Shodan Enterprise, and Red Sift (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted Certificate Transparency monitoring, passive DNS collection, subdomain discovery, WHOIS tracking, and domain intelligence tooling — ideal for security researchers, SOC teams, and organizations that want control without enterprise pricing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[DomainTools](https://www.domaintools.com/)**  
  Comprehensive domain intelligence platform with WHOIS history, DNS data, risk scoring, iris investigation tools, and monitoring for brand and infrastructure threats.

- **[SecurityTrails](https://securitytrails.com/)**  
  Massive passive DNS and domain intelligence database offering historical DNS records, subdomain enumeration, WHOIS history, and API-driven monitoring.

- **[RiskIQ PassiveTotal](https://community.riskiq.com/)** (Microsoft)  
  Passive DNS, WHOIS, SSL certificate, and infrastructure intelligence platform widely used for threat hunting and attack surface analysis.

- **[Censys](https://censys.com/)**  
  Internet-wide scanning and certificate search engine providing host, service, and Certificate Transparency data for asset discovery and monitoring.

- **[WhoisXML API](https://whoisxmlapi.com/)**  
  Extensive WHOIS, DNS, and domain data APIs with historical records, reverse lookups, and monitoring capabilities for security and research use cases.

- **[Spyse](https://spyse.com/)**  
  Internet assets search engine focused on domains, IPs, certificates, and related infrastructure intelligence.

- **[ViewDNS](https://viewdns.info/)**  
  Collection of free and paid DNS, WHOIS, and reverse lookup tools popular for quick domain and infrastructure research.

- **[Detectify](https://detectify.com/)**  
  External attack surface management and continuous security scanning platform that includes domain and subdomain monitoring.

- **[Netcraft](https://www.netcraft.com/)**  
  Long-standing internet services company offering phishing detection, domain monitoring, and digital risk protection.

- **[DomainIQ](https://www.domainiq.com/)**  
  Domain research and monitoring tools providing WHOIS, reverse WHOIS, and related intelligence.

- **[ZeroFox](https://www.zerofox.com/)**, **[SOCRadar](https://socradar.io/)**, **[Shodan Enterprise](https://www.shodan.io/)**, **[Red Sift](https://redsift.com/)**  
  Broader digital risk protection, threat intelligence, internet device search, and domain security platforms that include strong domain monitoring capabilities.

## Open-Source GitHub Projects

- **[Cert Spotter](https://github.com/SSLMate/certspotter)**  
  Lightweight, robust open-source Certificate Transparency log monitor that alerts you when SSL/TLS certificates are issued for your domains — no database required.

- **[PassiveDNS](https://github.com/gamelinux/passivedns)**  
  Network sniffer that logs DNS server replies for building your own passive DNS database, useful for incident response and historical DNS analysis.

- **[Domain Admin](https://github.com/dromara/domain-admin)**  
  Open-source domain and SSL certificate monitoring platform with expiration alerts, multi-channel notifications, Let’s Encrypt support, and multi-language UI.

- **[domain-monitor](https://github.com/nwesterhausen/domain-monitor)**  
  Self-hosted WHOIS monitoring server that tracks registration changes and expiration dates for specified domains with efficient caching to respect WHOIS rate limits.

- **[ct-exposer & Certificate Transparency tools](https://github.com/chris408/ct-exposer)**  
  OSINT tools that discover subdomains by searching public Certificate Transparency logs (crt.sh and others).

- **[Subfinder / Amass / subdomain discovery suites](https://github.com/projectdiscovery/subfinder)**  
  Widely used open-source passive and active subdomain enumeration frameworks that aggregate Certificate Transparency, passive DNS, and other public sources.

- **[DNS OSINT & recon tools](https://github.com/DelorianCS/dns-osint)**  
  Lightweight passive DNS/subdomain discovery, reverse DNS, and record lookup utilities that require no API keys.

- **[Self-hosted domain & certificate monitors](https://github.com/neok0/domain-monitor)**  
  Free domain and certificate monitoring systems that watch for newly registered look-alike domains and certificate issuance events (often via certstream).

### Additional Strong Open-Source Options

- **crt.sh** and public CT log search interfaces combined with local monitors.
- **MassDNS, dnsx, and high-performance DNS resolution tools** for validating discovered assets.
- **BadDNS and subdomain takeover detection tools** for identifying dangling DNS risks.
- **RIPE NCC DNSMON** and similar measurement projects for DNS service quality monitoring.
- Many community recon, OSINT, and Prometheus exporters focused on certificate lifetime, DNS changes, and domain portfolio tracking.

**Frameworks for building custom systems**: Run **Cert Spotter** (or similar CT monitors) for certificate alerts, collect passive DNS with **PassiveDNS** or public sources, use **Subfinder/Amass** + **dnsx** for continuous subdomain discovery, monitor WHOIS with a self-hosted **domain-monitor**, store results in a database, and alert via your preferred channels (email, Slack, webhooks, etc.).

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Domain monitoring and OSINT tools interact with public data sources and WHOIS servers. Respect rate limits, terms of service, and applicable laws. Aggressive querying can result in blocks or legal issues.
- Open-source tools provide powerful capabilities but typically lack the historical depth, global coverage, and polished alerting of commercial platforms. Validate findings and maintain your own infrastructure responsibly.

---

**Made for security researchers, SOC analysts, brand protection teams, and infrastructure owners.**  
Let's make domain monitoring and internet asset visibility more open and accessible.
