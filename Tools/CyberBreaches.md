# 💻 Cyber & Data Breaches OSINT

> *Back to [Main Playbook](../README.md)*

---

## 🛠️ Tools / Outils

| Tool | Usage | Link |
|------|-------|------|
| HaveIBeenPwned | Check if email appears in known breaches | [haveibeenpwned.com](https://haveibeenpwned.com) |
| DeHashed | Search leaked credentials and PII | [dehashed.com](https://www.dehashed.com) |
| IntelX | Search pastes, leaks and dark web sources | [intelx.io](https://intelx.io) |
| LeakCheck | Credential leak verification | [leakcheck.io](https://leakcheck.io) |
| Pastebin Search | Monitor public pastes for sensitive data | [pastebin.com](https://pastebin.com) |
| Grep.app | Search across public code repositories | [grep.app](https://grep.app) |
| GitHub Dorks | Find exposed credentials in public repos | [github.com](https://github.com) |
| Shodan | Find exposed databases and services | [shodan.io](https://www.shodan.io) |
| Censys | Identify misconfigured or exposed systems | [censys.io](https://censys.io) |
| BreachDirectory | Free breach data lookup | [breachdirectory.org](https://breachdirectory.org) |

---

## 🔎 Methodology / Méthodologie

**EN**
1. Identify target email addresses, domains or usernames
2. Check known breach databases (HaveIBeenPwned, DeHashed, LeakCheck)
3. Search paste sites for exposed data (IntelX, Pastebin)
4. Search public code repositories for accidentally exposed credentials (GitHub Dorks, Grep.app)
5. Check for exposed databases or services via Shodan / Censys
6. Cross-reference findings to build a broader profile
7. Document all findings responsibly — never exploit or share raw credentials

**FR**
1. Identifier les adresses email, domaines ou pseudos cibles
2. Consulter les bases de données de fuites connues (HaveIBeenPwned, DeHashed, LeakCheck)
3. Rechercher sur les sites de paste les données exposées (IntelX, Pastebin)
4. Rechercher dans les dépôts publics les credentials accidentellement exposés (GitHub Dorks, Grep.app)
5. Vérifier les bases de données ou services exposés via Shodan / Censys
6. Recouper les résultats pour construire un profil plus large
7. Documenter tous les résultats de manière responsable — ne jamais exploiter ou partager des credentials bruts

---

## 💡 GitHub Dorks — Quick Reference

| Dork | Usage |
|------|-------|
| `filename:.env password` | Find exposed environment files |
| `filename:config.php dbpassword` | Find database credentials |
| `filename:id_rsa` | Find exposed SSH private keys |
| `"api_key" "secret"` | Find exposed API keys |
| `filename:.htpasswd` | Find exposed password files |

---

## 🚩 Key Red Flags / Signaux d'alerte

| Red Flag | Possible Implication |
|----------|---------------------|
| Credentials found in multiple breaches | High-value target or poor security hygiene |
| Corporate emails in breach databases | Potential insider threat or phishing risk |
| Exposed API keys in public repos | Active security vulnerability |
| Database exposed on Shodan | Misconfiguration or negligence |
| Credentials posted on paste sites | Active data leak in progress |

---

## ⚠️ Ethics & Legality / Éthique & Légalité

**EN** — Breach data must only be used for investigative or defensive purposes. Never exploit, redistribute or use credentials for unauthorized access. Always operate within applicable law.

**FR** — Les données de fuites ne doivent être utilisées qu'à des fins investigatives ou défensives. Ne jamais exploiter, redistribuer ou utiliser des credentials pour un accès non autorisé. Toujours opérer dans le cadre légal en vigueur.

---

## 🔗 Useful Resources / Res
