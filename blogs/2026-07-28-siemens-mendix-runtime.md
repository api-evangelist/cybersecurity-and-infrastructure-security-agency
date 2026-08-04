---
title: "Siemens Mendix Runtime"
url: "https://www.cisa.gov/news-events/ics-advisories/icsa-26-209-02"
date: "2026-07-28"
author: "CISA"
feed_url: "https://www.cisa.gov/cybersecurity-advisories/all.xml"
---
View CSAF Summary Mendix documentation for access rules does not adequately describe the special behavior of the System.User entity, leaving developers without sufficient guidance to configure access rules securely. This documentation gap may lead application developers to unknowingly apply overly permissive access rules to System.User, resulting in unintended exposure of sensitive user data or privilege escalation within deployed Mendix applications. A common misconfiguration identified is with the anonymous user role with a System.User entity to gain access to all stored records, even though
