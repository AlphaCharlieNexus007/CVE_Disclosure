# Security Advisory: Unauthenticated Information Disclosure in UNZ Digital / HeroSpeed Firmware

## Overview
A high-severity vulnerability has been identified in certain UNZ Digital Pvt Ltd IP cameras utilizing HeroSpeed OEM firmware. This flaw allows an unauthenticated attacker on the adjacent local network to query an embedded web management daemon and extract configuration details and administrative credentials.

## Affected Framework
* **Vendor:** UNZ Digital Pvt Ltd / OEM: HeroSpeed (HDT)
* **Target Model:** UNZ-CB-IPC-4MP
* **Firmware Tree:** V4.3.FAS0127.L34 (Build Date: 20241213)
* **Hardware Profile:** JZT31N_D41_Q38
* **Estimated CVSS:** 8.8 High (CVSS:3.1/AV:A/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H)

## Vulnerability Status
This issue has been submitted to MITRE (Candidate ID: CAN-2026-2032286) and CERT-In for coordinated vulnerability disclosure and CVE tracking. Technical Proof-of-Concept steps and concrete data extraction endpoints are currently restricted to authorized coordinating authorities and will be fully disclosed following vendor notification and remediation timelines.
