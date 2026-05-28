# Copilot Instructions — bio-security-baseline

> See root `.github/copilot-instructions.md` for global conventions.

Claude Code plugin voor de **Baseline Informatiebeveiliging Overheid 2 (BIO2)**. Helpt bij het implementeren van informatiebeveiliging conform BIO2 voor Nederlandse overheidsorganisaties, gebaseerd op ISO/IEC 27001/27002 en NIS2.

## Structure

```
.claude-plugin/plugin.json    # Plugin metadata (name, description, version)
skills/bio-security-baseline/
  SKILL.md                    # Skill definition — triggers, model config, scope
  reference.md                # Reference material — BIO2 maatregelen, NCSC richtlijnen
```

## Installation

```bash
claude install djimit/bio-security-baseline
```

## Typical Usage

- **BIO2 toetsing** — Toets systemen aan BIO2-maatregelen (toegangsbeheer, logging, cryptografie, kwetsbaarhedenbeheer, pentesting, incidentmanagement)
- **Forum Standaardisatie** — Check verplichte standaarden (TLS, DNSSEC, DMARC, DKIM, SPF, DANE, RPKI)
- **NCSC richtlijnen** — Pas NCSC-advies toe (webapplicaties, TLS, MFA)
- **Security by design** — Review architecturen op BIO2-compliance vanuit ontwerpfase

## Domain Keywords

BIO2, Baseline Informatiebeveiliging Overheid, ISO 27001, ISO 27002, NIS2, Cyberbeveiligingswet, security controls, toegangsbeheer, logging, cryptografie, MFA, HTTPS, TLS, DNSSEC, DMARC, DKIM, SPF, DANE, RPKI, internet.nl, NCSC, DigiToegankelijk, WCAG, EN 301 549, ENSIA, eIDAS, EUDI Wallet, SBOM, security.txt

## License

EUPL-1.2 (see `LICENSE`)
