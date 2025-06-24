# Zenth Network Server

**Zenth Network Server** is a secure, open-source network management and firewall platform developed by Sky Genesis Enterprise as part of the Zenth Cloud ecosystem. Based on a fork of OPNsense, it offers advanced network routing, firewall, VPN, and monitoring features tailored for sovereign cloud infrastructure.

## 🔐 Features

- ✅ Stateful firewall with customizable rules and policies
- ✅ Advanced routing and network segmentation
- ✅ Integrated VPN support (IPSec, OpenVPN, WireGuard)
- ✅ High availability and failover capabilities
- ✅ Real-time traffic monitoring and logging
- ✅ Integration with `dhcp-server`, `dns-server`, and `ldap-server` for unified network services
- ✅ Web-based management UI with API access
- ✅ Plugin system for extensibility and custom features

## 📦 Part of the Zenth Cloud Stack

Zenth Network Server works alongside:

- `firewall-server` – Firewall-specific rule enforcement
- `dhcp-server` – Dynamic IP allocation and lease management
- `dns-server` – Domain name resolution and caching
- `ldap-server` – Centralized authentication and authorization
- `status-server` / `monitoring-server` – Network health monitoring
- `api-server` – Configuration and orchestration

## 🛠️ Technology

- Forked and customized from [OPNsense](https://opnsense.org/)
- Written in PHP and C for core components
- Secure API-first architecture for integration
- Supports containerized or bare-metal deployment

## 📖 Documentation

Complete setup, configuration, and API documentation can be found in `/docs` or on [Documentations](https://docs.zenthcloud.com).

## 🛡️ License

Zenth Network Server is licensed under the **GNU Affero General Public License v3 (AGPLv3)**. See the `LICENSE` file for full details.

---

Contributions, bug reports, and feature requests are welcome at [github.com/zenthcloud](https://github.com/zenthcloud).
