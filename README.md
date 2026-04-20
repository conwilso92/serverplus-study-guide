# CompTIA Server+ SK0-005 Study Guide

A comprehensive study guide for the CompTIA Server+ (SK0-005) certification exam, synthesized from course materials and official exam objectives. Built as a single dark-mode HTML file with full anchor navigation.

🔗 **[View the Study Guide](https://conwilso92.github.io/serverplus-study-guide)**

---

## Coverage

All 12 chapters mapped to the 5 official exam domains:

| Domain | Weight | Chapters |
|---|---|---|
| Server Hardware | 16% | Ch. 1 |
| Server Administration | 28% | Ch. 2, 3, 4, 5 |
| Security | 20% | Ch. 6, 7 |
| Networking | 17% | Ch. 8 |
| Disaster Recovery | 19% | Ch. 9 |
| Troubleshooting | — | Ch. 10, 11, 12 |

### What's Inside

- **Chapter 1 — Server Hardware:** Rack units, form factors, cooling, power (PDU/UPS/NEMA), copper and fiber cabling, CPU architecture (NUMA, cache hierarchy), memory types (ECC, RDIMM, LRDIMM), PCIe generations, CNAs, KVM/OOB management
- **Chapter 2 — Installing & Configuring Servers:** OS installation types (PXE, unattended, bare metal), filesystem types (NTFS, EXT4, ZFS, VMFS, ReFS), LVM, volume types (MBR/GPT, dynamic disks), server roles, virtualization (Type 1/2, provisioning, vSwitch), cloud models, monitoring
- **Chapter 3 — Server Maintenance:** Out-of-band management (IPMI, BMC, iLO, iDRAC), drive types and speeds, hot-swap hardware, UEFI vs BIOS, Secure Boot, licensing models
- **Chapter 4 — Storage Technologies:** RAID levels 0/1/5/6/10/JBOD with capacity math, hardware vs software RAID, DAS/NAS/SAN/iSCSI/FC/FCoE, storage tiering, capacity planning (Base 2 vs Base 10), asset and documentation management
- **Chapter 5 — Fault Tolerance:** Active-active vs active-passive clustering, heartbeat, quorum, split-brain, load balancing algorithms, NIC teaming (LACP), redundant infrastructure
- **Chapter 6 — Securing the Server:** Physical security (mantrap, Faraday cage, bollards), fire suppression types, environmental controls, social engineering attacks, OS/hardware/application hardening, HIDS/HIPS, patch management
- **Chapter 7 — Securing Server Data & Network Access:** Symmetric vs asymmetric encryption, PKI, EFS/BitLocker/TPM, data at rest and in transit (TLS/IPsec), AH vs ESP, Active Directory, RBAC/DAC/MAC, MFA factors, SSO, media destruction methods
- **Chapter 8 — Networking & Scripting:** Full port reference table, VLANs and VLAN attacks, DNS/DHCP/APIPA, firewall types (stateful, proxy, NGFW, DMZ), scripting languages and syntax (Bash, PowerShell, Batch, VBScript)
- **Chapter 9 — Disaster Recovery:** Backup types and archive bit logic, RTO vs RPO, GFS media rotation, 3-2-1 rule, DR site types (hot/warm/cold), synchronous vs asynchronous replication, DR testing methods, backup validation
- **Chapter 10 — Troubleshooting Hardware & Software:** CompTIA's 7-step methodology, SMART diagnostics, POST/BSOD/kernel panic, memory leaks, runaway processes, SFC, clock skew, WSUS, safe mode
- **Chapter 11 — Network Connectivity & Security Issues:** Connectivity troubleshooting checklist, common error messages and root causes, full diagnostic command reference (Windows and Linux), SIEM, security tools
- **Chapter 12 — Troubleshooting Storage:** Common storage failures, RAID rebuild risk, page/swap file performance thresholds, full storage command reference, Linux log file locations

---

## Related Study Tools

Part of a broader CompTIA certification study toolkit:

| Repo | Description |
|---|---|
| [CompTia-core1-flashcards](https://github.com/conwilso92/CompTia-core1-flashcards) | A+ Core 1 interactive flashcard app |
| [CompTia-core2-flashcards](https://github.com/conwilso92/CompTia-core2-flashcards) | A+ Core 2 interactive flashcard app |
| [network-plus-flashcards](https://github.com/conwilso92/network-plus-flashcards) | Network+ interactive flashcard app |
| [network-plus-study-guide](https://github.com/conwilso92/network-plus-study-guide) | Network+ comprehensive study guide |
| [homelab](https://github.com/conwilso92/homelab) | Homelab documentation and configs |

---

## About

Built while studying for the CompTIA Server+ certification at Star V Learning Centers, Jacksonville, FL. Materials synthesized from course slide decks and official SK0-005 exam objectives.

**Certifications:** CompTIA A+ (Core 1 & Core 2 passed) · Network+ (in progress) · Server+ (in progress)
