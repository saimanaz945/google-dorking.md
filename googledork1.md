
# Passive Reconnaissance: Domain Architecture Analysis (github.com)

This documentation tracks the initial passive reconnaissance phase of an open-source intelligence (OSINT) assessment, utilizing public registry queries to inspect core infrastructure parameters without direct network interaction.

## Target Lookup Summary
The following data maps out the public registry footprint and authoritative routing infrastructure for the target domain:

| Domain | Registered On | Expires On | Status / Security Locks | Authoritative Name Servers |
| :--- | :--- | :--- | :--- | :--- |
| **github.com** | 2007-10-09 | 2026-10-09 | • clientDeleteProhibited<br>• clientTransferProhibited<br>• clientUpdateProhibited | • dns1.p08.nsone.net (thru dns4)<br>• ns-1283.awsdns-32.org<br>• ns-1707.awsdns-21.co.uk<br>• ns-421.awsdns-52.com<br>• ns-520.awsdns-01.net |

> **Operational Note:** Gathering baseline registry metrics serves as the prerequisite phase before implementing targeted search engine optimization filtering (Google Dorking) to identify public asset distributions.
![ whois](whocis.png)




















