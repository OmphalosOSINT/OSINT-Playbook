# 🌐 Infrastructure & Network OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

### Search Engines for Connected Devices & Cyberspace

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| Shodan | Search engine for internet-connected devices — dorks: `port:`, `org:`, `country:`, `product:` | Moteur de recherche pour appareils connectés — dorks : `port:`, `org:`, `country:`, `product:` | Censys, ZoomEye, FOFA | Freemium | 🇺🇸 USA | [shodan.io](https://www.shodan.io) |
| Censys | Internet infrastructure scanning with strong certificate and TLS fingerprint search | Scan d'infrastructures internet avec recherche puissante sur certificats et empreintes TLS | Shodan, ZoomEye | Freemium | 🇺🇸 USA | [censys.io](https://censys.io) |
| ZoomEye | Chinese cyberspace search engine covering IPv4/IPv6 — dorks: `app:`, `country:`, `port:` | Moteur de recherche chinois du cyberespace couvrant IPv4/IPv6 | Shodan, FOFA | Freemium | 🇨🇳 China | [zoomeye.ai](https://www.zoomeye.ai) |
| FOFA | Cyberspace mapping with favicon hash and TLS certificate pivoting | Cartographie du cyberespace avec pivoting par hash favicon et certificats TLS | Shodan, Censys, ZoomEye | Freemium | 🇨🇳 China | [fofa.info](https://fofa.info) |
| Quake 360 | Cyberspace mapping by Qihoo 360, strong ICS/SCADA and Chinese infrastructure coverage | Cartographie du cyberespace par Qihoo 360, forte couverture ICS/SCADA et infrastructures chinoises | Shodan, FOFA | Freemium | 🇨🇳 China | [quake.360.net](https://quake.360.net) |
| Netlas | Internet-wide scanning with regex search, temporal history and Maltego integration | Scanner internet avec recherche regex, historique temporel et intégration Maltego | Shodan, Censys | Freemium (50 req/day free) | 🌐 International | [app.netlas.io](https://app.netlas.io) |
| Criminal IP | AI-powered IP threat intelligence and risk scoring (VPN/proxy/Tor detection) | Renseignement sur les menaces IP et scoring de risque par IA (détection VPN/proxy/Tor) | GreyNoise, AbuseIPDB | Freemium | 🇰🇷 South Korea | [criminalip.io](https://www.criminalip.io) |
| GreyNoise | Internet scan traffic analysis and IP qualification via global honeypot network | Analyse du trafic de scan internet et qualification des IPs via réseau mondial de honeypots | Shodan, AbuseIPDB | Freemium | 🇺🇸 USA | [greynoise.io](https://www.greynoise.io) |
| Onyphe | French cyber threat intelligence aggregating active scans and passive DNS data | Cyber threat intelligence français agrégeant scans actifs et données DNS passives | Shodan, LeakIX | Freemium | 🇫🇷 France | [onyphe.io](https://www.onyphe.io) |
| LeakIX | European platform detecting exposed services and active data leaks in real time | Plateforme européenne détectant services exposés et fuites de données actives en temps réel | Shodan, FullHunt | Freemium | 🇪🇺 Europe | [leakix.net](https://leakix.net) |
| FullHunt | External attack surface management — continuous discovery and exposure monitoring | Gestion de la surface d'attaque externe, découverte continue et surveillance des expositions | Censys, Netlas | Freemium | 🌐 International | [fullhunt.io](https://fullhunt.io) |
| SynapsInt | Unified OSINT engine with multi-pivot: Domain / IP / ASN / SSL / Email / Phone | Moteur OSINT unifié avec pivots multiples : Domaine / IP / ASN / SSL / Email / Téléphone | Maltego, SpiderFoot | Freemium | 🌐 International | [synapsint.com](https://synapsint.com) |

### WHOIS & Domain Intelligence

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| WhoisXML API | Comprehensive domain, IP and DNS intelligence, 25B+ WHOIS records, reverse WHOIS, predictive threat feeds | Renseignement domaine, IP et DNS, 25Mds d'enregistrements WHOIS, reverse WHOIS, flux de menaces prédictifs | SecurityTrails, BigDomainData | Freemium | 🌐 International | [whoisxmlapi.com](https://main.whoisxmlapi.com) |
| SecurityTrails | DNS history since 2008, subdomain enumeration and passive DNS infrastructure intelligence | Historique DNS depuis 2008, énumération de sous-domaines et DNS passif | WhoisXML API, ViewDNS | Freemium (50 req/mo free) | 🇺🇸 USA | [securitytrails.com](https://securitytrails.com) |
| BigDomainData | Historical WHOIS database of 668M+ domains, granular reverse WHOIS filtering and fuzzy domain generation | Base WHOIS historique de 668M+ domaines, filtres reverse WHOIS granulaires et génération de domaines similaires | WhoisXML API | Paid | 🌐 International | [bigdomaindata.com](https://www.bigdomaindata.com) |
| ViewDNS | Multi-tool for DNS/IP investigation, IP history, reverse IP/NS/MX/WHOIS, geographic firewall tests | Boîte à outils DNS/IP, historique IP, lookups inversés, tests d'accessibilité géographique | SecurityTrails, CentralOps | Free | 🌐 International | [viewdns.info](https://viewdns.info) |
| DNS History | DNS archive since 2009, 66B+ records searchable by NS, MX or IP to pivot across shared infrastructure | Archive DNS depuis 2009, 66Mds d'enregistrements recherchables par NS, MX ou IP | SecurityTrails, ViewDNS | Free | 🌐 International | [dnshistory.org](https://dnshistory.org) |
| CentralOps | All-in-one online network tools, Domain Dossier and Email Dossier without signup | Outils réseau tout-en-un, dossiers complets domaine et email sans inscription | ViewDNS, MXToolbox | Free | 🌐 International | [centralops.net](https://centralops.net) |
| Whoistory | Russian .RU domain WHOIS history and registration database since 2006 | Historique d'enregistrement WHOIS des domaines .RU russes depuis 2006 | WhoisXML API | Free | 🇷🇺 Russia | [whoistory.com](https://whoistory.com) |
| IPinfo | Comprehensive IP intelligence, geolocation, ASN, privacy detection, hosted domains | Renseignement IP complet, géolocalisation, ASN, détection VPN/proxy, domaines hébergés | MaxMind, ip-api.com | Freemium (unlimited free tier) | 🇺🇸 USA | [ipinfo.io](https://ipinfo.io) |
| MyIP.ms | IP hosting history, co-hosted sites discovery and real-time blacklist check | Historique d'hébergement IP, découverte de sites co-hébergés et vérification de blacklist | IPinfo, ViewDNS | Freemium | 🌐 International | [myip.ms](https://myip.ms) |

### Subdomain Enumeration

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| crt.sh | Certificate Transparency log search engine, discover subdomains via SSL/TLS certificate records, bypasses Cloudflare | Moteur de recherche dans les logs Certificate Transparency, découvrir les sous-domaines via les certificats SSL/TLS | SecurityTrails, SubdomainRadar | Free | 🌐 International | [crt.sh](https://crt.sh) |
| SubdomainRadar | All-in-one subdomain enumeration with port scanning and vulnerability detection | Énumération de sous-domaines tout-en-un avec scan de ports et détection de vulnérabilités | SecurityTrails, C99 | Freemium | 🌐 International | [subdomainradar.io](https://subdomainradar.io) |
| C99 Subdomain Finder | Subdomain discovery with Cloudflare bypass detection and historical records | Découverte de sous-domaines avec détection de bypass Cloudflare et historique | SubdomainRadar, crt.sh | Freemium | 🌐 International | [subdomainfinder.c99.nl](https://subdomainfinder.c99.nl) |
| PugRecon | Passive subdomain enumeration, billions of indexed records, discreet non-intrusive approach | Énumération passive de sous-domaines, milliards d'entrées indexées, approche discrète non intrusive | SecurityTrails, crt.sh | Freemium | 🌐 International | [pugrecon.com](https://pugrecon.com) |
| NMapper | Web interface for CLI OSINT tools (Nmap, Sublist3r, Amass, theHarvester, WPScan) | Interface web pour outils CLI OSINT (Nmap, Sublist3r, Amass, theHarvester, WPScan) | SubdomainRadar | Free | 🌐 International | [nmmapper.com](https://www.nmmapper.com) |

### ASN & BGP Intelligence

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| BGP Toolkit (HE) | ASN and IP prefix mapping, Certificate Search, Super Traceroute and global Looking Glass | Cartographie ASN et préfixes IP, recherche de certificats, Super Traceroute et Looking Glass mondial | BGP.Tools, ASNLookup | Free | 🇺🇸 USA | [bgp.he.net](https://bgp.he.net) |
| BGP.Tools | Real-time BGP data browser — ASN, prefix, DNS and MAC address lookup | Navigateur BGP temps réel — lookup par ASN, préfixe, DNS et adresse MAC | BGP Toolkit HE | Free | 🌐 International | [bgp.tools](https://bgp.tools) |
| ASNLookup | Simple ASN and IP lookup with free API and bulk processing capability | Lookup ASN et IP avec API gratuite et traitement en masse | BGP.Tools, IPinfo | Free | 🌐 International | [asnlookup.com](https://asnlookup.com) |

### Web Reconnaissance

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| Web-Check | Open-source all-in-one website recon, 30+ checks: DNS, SSL, headers, tech stack, threats, WHOIS | Outil de reconnaissance web open source, 30+ modules : DNS, SSL, headers, stack technique, menaces, WHOIS | Wappalyzer, BuiltWith | Free (self-hostable) | 🌐 International | [web-check.as93.net](https://web-check.as93.net) |
| BuiltWith | Technology stack detection for any website (60,000+ technologies tracked) | Détection du stack technologique de n'importe quel site web (60 000+ technologies suivies) | Wappalyzer, Web-Check | Freemium | 🇦🇺 Australia | [builtwith.com](https://builtwith.com) |
| Wayback Machine | Web archive and deleted content recovery (800B+ pages since 1996) | Archives web et récupération de contenu supprimé (800Mds de pages depuis 1996) | archive.ph, CachedView | Free | 🇺🇸 USA | [web.archive.org](https://web.archive.org) |
| archive.ph | On-demand web archiving creating permanent snapshots, resistant to deletion | Archivage web à la demande créant des snapshots permanents résistants à la suppression | Wayback Machine | Free | 🌐 International | [archive.ph](https://archive.ph) |

### Source Code & File Search

| Tool | Usage (English) | Usages (French) | Alternatives | 💰 | 🌍 | Link |
|------|----------------|-----------------|--------------|----|----|------|
| PublicWWW | Source code search across 500M+ pages, pivot by shared Analytics IDs, ad codes or tracking pixels | Recherche dans le code source de 500M+ pages, pivot par identifiants Analytics partagés, codes pub ou pixels de tracking | NerdyData | Freemium | 🌐 International | [publicwww.com](https://publicwww.com) |
| NerdyData | Source code search with tech stack and company data enrichment | Recherche dans le code source avec enrichissement du stack technologique | PublicWWW | Freemium | 🇺🇸 USA | [nerdydata.com](https://www.nerdydata.com) |
| Grep.app | Regex search across public GitHub repositories, find exposed credentials and secrets | Recherche regex dans les dépôts GitHub publics, détecter credentials exposés et secrets | Searchcode, GitHub Search | Free | 🌐 International | [grep.app](https://grep.app) |
| NAPALM FTP Indexer | Search engine for publicly accessible FTP servers (316M+ files across 1,200+ servers) | Moteur de recherche dans les FTP publics (316M+ fichiers sur 1 200+ serveurs) | Shodan (FTP banner) | Free | 🌐 International | [searchftps.net](https://www.searchftps.net) |
| Google Hacking Database (GHDB) | Community-maintained index of Google Dorks by category (sensitive data, exposed devices, login portals) | Index communautaire de Google Dorks par catégorie (données sensibles, équipements exposés, portails de connexion) | Exploit-DB, IntelTechniques | Free | 🇺🇸 USA | [exploit-db.com/google-hacking-database](https://www.exploit-db.com/google-hacking-database) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Start with WHOIS — domain registration, registrant contact, nameservers, registration date
2. Check DNS history (SecurityTrails, ViewDNS IP History) — find the real IP before Cloudflare
3. Enumerate subdomains (crt.sh, SubdomainRadar, SecurityTrails) — expose hidden infrastructure
4. Scan exposed services (Shodan, Censys, FOFA) — identify open ports and technologies
5. Check ASN and IP netblocks (BGP Toolkit, IPinfo) — map hosting and ownership
6. Search source code (PublicWWW, Grep.app) — find shared tracking IDs or exposed credentials
7. Archive everything — pages and services disappear fast

**FR**
1. Commencer par le WHOIS, enregistrement du domaine, contact registrant, nameservers, date d'enregistrement
2. Vérifier l'historique DNS (SecurityTrails, ViewDNS IP History), retrouver l'IP réelle avant Cloudflare
3. Énumérer les sous-domaines (crt.sh, SubdomainRadar, SecurityTrails), exposer l'infrastructure cachée
4. Scanner les services exposés (Shodan, Censys, FOFA), identifier les ports ouverts et technologies
5. Vérifier les ASN et blocs IP (BGP Toolkit, IPinfo), cartographier l'hébergement et la propriété
6. Rechercher dans le code source (PublicWWW, Grep.app), trouver des ID de tracking partagés ou credentials exposés
7. Tout archiver, les pages et services disparaissent vite

---

## 💡 Google Dorks — Quick Reference

**ENG**
| Operator | Usage | Example |
|----------|-------|---------|
| `site:` | Search within a specific domain | `site:target.com filetype:pdf` |
| `filetype:` | Search for specific file types | `filetype:env "DB_PASSWORD"` |
| `intitle:` | Search in page titles | `intitle:"index of" "backup"` |
| `inurl:` | Search in URLs | `inurl:admin inurl:login` |
| `intext:` | Search for text in page body | `intext:"api_key" site:target.com` |
| `"..."` | Exact phrase search | `"John Doe" "Montreal"` |
| `-` | Exclude a term | `site:target.com -www` |

**FR**
| Opérateur | Usages | Exemple |
|-----------|--------|---------|
| `site:` | Faire une recherche avec un nom de domaine spécifique | `site:target.com filetype:pdf` |
| `filetype:` | Faire une recherche d'un type de fichier spécifique | `filetype:env "DB_PASSWORD"` |
| `intitle:` | Cherhcher dans le titre | `intitle:"index of" "backup"` |
| `inurl:` | Chercher dans l'URL | `inurl:admin inurl:login` |
| `intext:` | Chercher dans le corps de texte | `intext:"api_key" site:target.com` |
| `"..."` | Recherche exacte d'une phrase | `"John Doe" "Montreal"` |
| `-` | Exclure un terme | `site:target.com -www` |

---

## 💡 Cloudflare Bypass Workflow

**ENG**
When a target uses Cloudflare (IP masking), use these techniques to find the real server IP:

1. **crt.sh** — search SSL certificates issued before Cloudflare was deployed
2. **SecurityTrails / ViewDNS IP History** — historical DNS A records showing past direct IPs
3. **Shodan / Censys** — search `ssl.cert.subject.cn:"target.com"` for direct TLS fingerprints
4. **PublicWWW** — find the Analytics or AdSense ID and look for unclouded subdomains sharing it
5. **Subdomains** — dev, staging, mail and API subdomains are often not behind Cloudflare

**FR**
Lorsqu’une cible utilise **Cloudflare (masquage d’IP)**, utilisez les techniques suivantes pour trouver l’adresse IP réelle du serveur :

1. **crt.sh** — rechercher les certificats SSL émis **avant la mise en place de Cloudflare**
2. **SecurityTrails / ViewDNS IP History** — consulter l’historique des enregistrements DNS **A** pour voir les anciennes adresses IP directes
3. **Shodan / Censys** — rechercher `ssl.cert.subject.cn:"target.com"` afin d’identifier des **empreintes TLS directes**
4. **PublicWWW** — trouver l’ID **Analytics ou AdSense** et rechercher des **sous-domaines non protégés par Cloudflare** qui partagent cet identifiant
5. **Sous-domaines** — les sous-domaines **dev, staging, mail ou API** ne sont souvent **pas protégés par Cloudflare**.

---

## 🔗 Useful Resources / Ressources utiles

- [Google Hacking Database](https://www.exploit-db.com/google-hacking-database)
- [Bellingcat Online Investigation Toolkit](https://docs.google.com/spreadsheets/d/18rtqh8EG2q1xBo2cLNyhIDuK9jrPGwYr9DI2UncoqJQ)
- [Shodan Dorks Cheatsheet](https://github.com/jakejarvis/awesome-shodan-queries)
- [SecurityTrails Blog](https://securitytrails.com/blog)
