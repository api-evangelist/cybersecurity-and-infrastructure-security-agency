# Cybersecurity and Infrastructure Security Agency (cybersecurity-and-infrastructure-security-agency)

The Cybersecurity and Infrastructure Security Agency (CISA) is the United States federal civilian cybersecurity agency, part of the Department of Homeland Security. CISA reduces cybersecurity and physical security risk for the nation, coordinates federal civilian cyber defense, and partners with state, local, tribal, and territorial governments and the private sector. CISA publishes a number of public, unauthenticated machine-readable feeds, including the Known Exploited Vulnerabilities (KEV) catalog (mandatorily remediated by federal civilian agencies under Binding Operational Directive 22-01), Cybersecurity Advisories, and Common Security Advisory Framework (CSAF) advisories. CISA also operates an Automated Indicator Sharing (AIS) TAXII 2.1 server that delivers STIX cyber threat indicators to vetted partners under a Terms of Use and Interconnection Agreement.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cybersecurity-and-infrastructure-security-agency/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cybersecurity-and-infrastructure-security-agency/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Advisories
- AIS
- Binding Operational Directive
- CSAF
- CVE
- CWE
- Cybersecurity
- Federal Government
- Government
- ICS-CERT
- Information Sharing
- KEV
- Known Exploited Vulnerabilities
- Risk Management
- Security
- STIX
- TAXII
- Threat Intelligence
- Vulnerability Management

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### CISA Known Exploited Vulnerabilities (KEV) Catalog

The KEV catalog is CISA's authoritative list of vulnerabilities actively exploited in the wild. The full catalog is published as JSON and CSV at cisa.gov/sites/default/files/feeds, mirrored on GitHub at cisagov/kev-data, and accompanied by a versioned JSON Schema. Federal civilian agencies must remediate KEV entries by the per-entry dueDate under BOD 22-01.

- **Human URL:** [https://www.cisa.gov/known-exploited-vulnerabilities-catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)
- **Base URL:** `https://www.cisa.gov`

#### Tags

- BOD 22-01
- CVE
- CWE
- Federal Government
- JSON Feed
- KEV
- Vulnerability Management

#### Properties

- [Documentation](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)
- [J S O N Feed](https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.json)
- [C S V Feed](https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.csv)
- [JSON Schema](https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities_schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Git Hub Mirror](https://github.com/cisagov/kev-data)
- [OpenAPI](openapi/cisa-kev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisa-kev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisa-kev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Capabilities](capabilities/cisa-kev-capabilities.yml)
- [Rules](rules/cisa-kev-rules.yml)

### CISA Automated Indicator Sharing (AIS) TAXII Server

CISA's Automated Indicator Sharing (AIS) program uses a TAXII 2.1 server to deliver STIX-formatted cyber threat indicators (CTI) and defensive measures (DM) to vetted partners. AIS includes AIS PUBLIC, FEDGOV, and CISCP feed communities. Connection requires a static IP, a Terms of Use, and an Interconnection Agreement; commercial data aggregators also redistribute AIS content to subscribers.

- **Human URL:** [https://www.cisa.gov/topics/cyber-threats-and-advisories/information-sharing/automated-indicator-sharing-ais](https://www.cisa.gov/topics/cyber-threats-and-advisories/information-sharing/automated-indicator-sharing-ais)

#### Tags

- AIS
- Information Sharing
- STIX
- TAXII
- Threat Intelligence

#### Properties

- [Documentation](https://www.cisa.gov/topics/cyber-threats-and-advisories/information-sharing/automated-indicator-sharing-ais)
- [Connection Guide](https://www.cisa.gov/resources-tools/resources/automated-indicator-sharing-ais-taxii-server-connection-guide)
- [T A X I I Documentation](https://www.cisa.gov/automated-indicator-sharing-ais-20-documents-more-information)
- [Postman Collection](collections/cisa-kev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisa-kev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CISA Cybersecurity Advisories

CISA publishes Cybersecurity Advisories (CSAs), Industrial Control Systems Advisories (ICSAs), and Common Security Advisory Framework (CSAF) JSON documents describing tactics, techniques, indicators, and required mitigations for active threats. Advisories are browsable on cisa.gov and many are exported as machine-readable CSAF JSON.

- **Human URL:** [https://www.cisa.gov/news-events/cybersecurity-advisories](https://www.cisa.gov/news-events/cybersecurity-advisories)

#### Tags

- Advisories
- CSAF
- ICS-CERT
- Threat Intelligence

#### Properties

- [Documentation](https://www.cisa.gov/news-events/cybersecurity-advisories)
- [I C S Advisories](https://www.cisa.gov/news-events/ics-advisories)
- [C S A F](https://www.cisa.gov/news-events/cybersecurity-advisories/csaf)
- [Postman Collection](collections/cisa-kev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisa-kev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/cisagov)
- [Website](https://www.cisa.gov)
- [K E V Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)
- [Advisories](https://www.cisa.gov/news-events/cybersecurity-advisories)
- [Topics](https://www.cisa.gov/topics)
- [Resources And Tools](https://www.cisa.gov/resources-tools)
- [News And Events](https://www.cisa.gov/news-events)
- [GitHub Organization](https://github.com/cisagov)
- [K E V Data Mirror](https://github.com/cisagov/kev-data)
- [Contact Us](https://www.cisa.gov/about/contact-us)
- [Privacy Policy](https://www.cisa.gov/privacy-policy)
- [JSON-LD](json-ld/cisa-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/cisa-kev-vulnerability-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](vocabulary/cisa-vocabulary.yml)
- [Capabilities](capabilities/cisa-kev-capabilities.yml)
- [Rules](rules/cisa-kev-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
