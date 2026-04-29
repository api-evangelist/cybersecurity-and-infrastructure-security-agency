# Cybersecurity and Infrastructure Security Agency (cybersecurity-and-infrastructure-security-agency)

The Cybersecurity and Infrastructure Security Agency (CISA) is the United States federal civilian cybersecurity agency, part of the Department of Homeland Security. CISA reduces cybersecurity and physical security risk for the nation, coordinates federal civilian cyber defense, and partners with state, local, tribal, territorial governments and the private sector. CISA publishes a number of public, unauthenticated machine-readable feeds, including the Known Exploited Vulnerabilities (KEV) catalog, Cybersecurity Advisories, and Common Security Advisory Framework (CSAF) advisories. CISA also operates an Automated Indicator Sharing (AIS) TAXII 2.1 server delivering STIX threat indicators to vetted partners.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cybersecurity-and-infrastructure-security-agency/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party
- **x-type:** government

## Tags

- Advisories, AIS, Binding Operational Directive, CSAF, CVE, CWE, Cybersecurity, Federal Government, Government, ICS-CERT, Information Sharing, KEV, Known Exploited Vulnerabilities, Risk Management, Security, STIX, TAXII, Threat Intelligence, Vulnerability Management

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-04-28

## APIs

### CISA Known Exploited Vulnerabilities (KEV) Catalog

The authoritative list of vulnerabilities actively exploited in the wild, published as JSON and CSV at `cisa.gov/sites/default/files/feeds`, mirrored on GitHub at `cisagov/kev-data`, and accompanied by a versioned JSON Schema. Federal civilian agencies must remediate KEV entries by the per-entry `dueDate` under BOD 22-01.

- **Human URL:** https://www.cisa.gov/known-exploited-vulnerabilities-catalog
- **JSON Feed:** https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.json
- **CSV Feed:** https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.csv
- **JSON Schema:** https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities_schema.json
- **GitHub Mirror:** https://github.com/cisagov/kev-data
- **OpenAPI:** [openapi/cisa-kev-openapi.yml](openapi/cisa-kev-openapi.yml)
- **Capabilities:** [capabilities/cisa-kev-capabilities.yml](capabilities/cisa-kev-capabilities.yml)
- **Rules:** [rules/cisa-kev-rules.yml](rules/cisa-kev-rules.yml)

### CISA Automated Indicator Sharing (AIS) TAXII Server

A TAXII 2.1 server delivering STIX-formatted cyber threat indicators (CTI) and defensive measures (DM) to vetted partners. Communities include AIS PUBLIC, FEDGOV, and CISCP. Connection requires a static IP, a Terms of Use, and an Interconnection Agreement.

- **Human URL:** https://www.cisa.gov/topics/cyber-threats-and-advisories/information-sharing/automated-indicator-sharing-ais

### CISA Cybersecurity Advisories

CSAs, ICSAs, and CSAF JSON documents describing tactics, techniques, indicators, and required mitigations.

- **Human URL:** https://www.cisa.gov/news-events/cybersecurity-advisories

## Capabilities

- Download and parse the KEV catalog (JSON / CSV)
- Validate KEV entries against the published JSON Schema
- Subscribe to STIX/TAXII threat indicators via AIS
- Consume Cybersecurity and ICS Advisories (HTML and CSAF JSON)
- Track BOD 22-01 compliance deadlines per CVE

## Use Cases

- Vulnerability management programs prioritizing remediation by KEV
- SIEM / SOAR enrichment with KEV and CISA advisories
- Federal agency BOD 22-01 compliance reporting
- Threat intelligence platforms ingesting AIS STIX feeds
- ICS / OT defenders consuming ICS-CERT advisories

## Common Resources

- [CISA Website](https://www.cisa.gov)
- [KEV Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)
- [Advisories](https://www.cisa.gov/news-events/cybersecurity-advisories)
- [Resources and Tools](https://www.cisa.gov/resources-tools)
- [GitHub Organization](https://github.com/cisagov)
- [JSON-LD Context](json-ld/cisa-context.jsonld)
- [KEV Vulnerability Schema](json-schema/cisa-kev-vulnerability-schema.json)
- [Vocabulary](vocabulary/cisa-vocabulary.yml)
- [Capabilities](capabilities/cisa-kev-capabilities.yml)
- [Rules](rules/cisa-kev-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
