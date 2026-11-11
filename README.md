# NetworkWalks Week 2 — Footprinting, Reconnaissance & Network Scanning

Footprinting (W2-PM1) + Network Scanning (W2-PM5) | NetworkWalks Week 2 | B084C

## Penetration Testing Report Summary

| Field | Detail |
| --- | --- |
| Pentester Name | Bahati (GOLD) |
| Program / Batch | B084C — Networkwalks Cybersecurity Internship |
| Date | 9 November 2026 |
| Modules Completed | W2-PM1 (Multiple Kali Tools) — Complete \| W2-PM5 (Zenmap) — Complete |
| Target Scope | networkwalks.com (public website + DNS) and tester's own LAN, per signed Letter of Authorization NW-LOA-B082-017 |

## Contents

- [`W2-PM-FINAL-REPORT-GOLD.pdf`](./W2-PM-FINAL-REPORT-GOLD.pdf) — full penetration testing report
- [`W2-PM-FINAL-REPORT-GOLD.docx`](./W2-PM-FINAL-REPORT-GOLD.docx) — editable Word version
- [`screenshots/`](./screenshots) — raw terminal/tool output for every task

## Modules Completed

### W2-PM1 — Footprinting with Multiple Kali Tools (networkwalks.com)
Six tools run against networkwalks.com: `whois`, `whatweb`, `nslookup`, `curl -I`, `wafw00f`, `dnsrecon`. Findings include hosting provider (HostGator), CMS/version (WordPress 7.1.4), server IP, an active ModSecurity WAF, and full DNS footprint.

### W2-PM5 — Network Scanning with Zenmap
Ping scan of the tester's own LAN subnet (10.0.0.0/24) via Zenmap, including live host discovery, IP/MAC identification, and topology visualization.

## Liability Disclaimer

This repository documents educational, authorized security testing performed under the NetworkWalks Cybersecurity Internship (Batch B084C). All activities were carried out strictly within the scope and dates authorized in writing by the Client (Networkwalks), per Letter of Authorization NW-LOA-B082-017. No exploitation, unauthorized access, or disruptive activity was attempted. Findings are recorded for educational purposes only.
