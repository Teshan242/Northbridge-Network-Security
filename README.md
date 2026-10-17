# Northbridge Savings & Finance — Network Security Upgrade

A collaborative academic project demonstrating a layered network security design using **Cisco Packet Tracer**.

## 📌 Project Overview

This project explores how a fictional financial organization, Northbridge Savings & Finance, can strengthen its network infrastructure through layered security controls.

The proposed solution covers network segmentation, traffic filtering, Layer 2 security, centralized administrator authentication, secure device management, and site-to-site VPN technology.

The project brings together multiple network security mechanisms to demonstrate how they can help reduce unauthorized access and improve the protection of network resources.

## 🎯 Project Objectives

- Improve network security through VLANs and network segmentation.
- Control communication between network segments using Access Control Lists (ACLs).
- Reduce unauthorized device connections through switch port security.
- Help prevent rogue DHCP server attacks using DHCP Snooping.
- Validate ARP traffic using Dynamic ARP Inspection (DAI).
- Support centralized administrator authentication and authorization using AAA and TACACS+.
- Explore secure communication between networks using a site-to-site IPsec VPN.
- Strengthen network-device management and traffic filtering through SSH and firewall controls, where implemented.

## 🛠️ Technologies and Security Controls

| Technology | Purpose |
|---|---|
| Cisco Packet Tracer | Network design, configuration, and simulation |
| VLANs | Logical network segmentation |
| ACLs | Traffic filtering and access control |
| Switch Port Security | Restricting unauthorized device connections |
| DHCP Snooping | Protection against rogue DHCP servers |
| Dynamic ARP Inspection (DAI) | Validation of ARP traffic |
| AAA and TACACS+ | Centralized administrator authentication and authorization |
| Site-to-Site IPsec VPN | Protecting communication between networks |
| SSH | Secure remote device administration |
| Zone-Based Firewall (ZBFW) | Zone-based traffic filtering, where implemented |

## 👥 Team Contributions

### Member 1 — ACLs, Network Segmentation & Port Security

- Worked on controlling traffic between network segments using ACLs.
- Applied VLAN-based network segmentation.
- Configured switch port security to restrict unauthorized device connections.
- Focused on reducing unauthorized access and the risk of lateral movement.

### Member 2 — DHCP Snooping & Dynamic ARP Inspection (DAI)

- Worked on DHCP Snooping to help prevent rogue DHCP server attacks.
- Configured or investigated DAI to validate ARP traffic.
- Focused on Layer 2 protections against DHCP-based attacks and ARP spoofing.
- Worked on configuration checks and security verification.

### Member 3 — AAA/TACACS+ & Site-to-Site IPsec VPN

- Worked on AAA for administrator authentication and authorization.
- Integrated TACACS+ for centralized authentication services.
- Worked on a site-to-site IPsec VPN to protect communication between networks.
- Studied VPN encryption, peer authentication, and data integrity.
- Focused on checking authentication settings and VPN connectivity.

### Member 4 — Firewall Security & Secure Device Management

- Worked on firewall-based traffic filtering, including Zone-Based Firewall (ZBFW), where implemented.
- Worked on SSH-based remote device administration.
- Focused on restricting device-management access to authorized users.
- Contributed to strengthening network-device security.

> **Implementation note:** These sections describe the team's assigned areas. Consult the included Packet Tracer file, final report, configurations, and test evidence to determine which controls were implemented and successfully verified.

## 📂 Repository Structure

```text
Northbridge-Network-Security/
├── README.md
├── packet-tracer/
│   └── Northbridge-Network-Security.pkt
└── documentation/
    └── final-report.pdf
```

### Repository Contents

- **`README.md`** — Project overview, security objectives, technologies, and team contributions.
- **`packet-tracer/Northbridge-Network-Security.pkt`** — Cisco Packet Tracer network project.
- **`documentation/final-report.pdf`** — Project report and supporting documentation.

## 🧪 Testing and Verification

The following checks are relevant when evaluating the project's security controls:

- **ACLs:** Confirm that permitted traffic succeeds and prohibited traffic is blocked.
- **Port Security:** Inspect switch port-security status and verify the configured restrictions.
- **DHCP Snooping:** Check the configuration, VLAN settings, and trusted interfaces.
- **DAI:** Check the configuration and verify its behavior using suitable test traffic.
- **AAA/TACACS+:** Test administrator authentication and authorization, including the configured fallback behavior where applicable.
- **IPsec VPN:** Inspect the VPN security associations and perform appropriate connectivity tests.
- **SSH and Firewall Controls:** Verify secure management access and the intended traffic-filtering behavior.

Successful implementation should be reported only when supported by the relevant configuration and test results.

## 📚 Learning Outcomes

This collaborative project provides practical learning opportunities in:

- Network security architecture and defense in depth.
- VLAN configuration and network segmentation.
- Traffic filtering using ACLs.
- Layer 2 network security.
- Centralized authentication and authorization.
- IPsec VPN concepts and troubleshooting.
- Secure network-device administration.
- Collaborative development, documentation, and technical verification.

## 🚀 Getting Started

1. Clone or download this repository.
2. Install and open Cisco Packet Tracer.
3. Open `packet-tracer/Northbridge-Network-Security.pkt`.
4. Review the network topology and available device configurations.
5. Consult `documentation/final-report.pdf` for the project's documentation.

*The exact commands and verification results depend on the configurations included in the submitted project.*

## 🔐 Disclaimer

This project was developed for academic and educational purposes in a simulated lab environment. Northbridge Savings & Finance is a fictional organization. This project is not a production banking network and should not be treated as a production-ready security deployment.

## 🤝 Teamwork and Credits

This repository represents collaborative academic work by a four-member team. Each member was assigned specific network security controls and related documentation.

Please refer to the project files and repository history for further information about individual contributions.

**Security reminder:** Do not publish passwords, TACACS+ shared secrets, VPN pre-shared keys, private credentials, or other sensitive information in the repository.

---

**Project Domain:** Network Security  
**Platform:** Cisco Packet Tracer  
**Project Type:** Collaborative Academic Project
