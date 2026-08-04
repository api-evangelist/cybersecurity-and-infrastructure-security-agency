# Cybersecurity and Infrastructure Security Agency (cybersecurity-and-infrastructure-security-agency)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
