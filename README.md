# 🌐 Multi-Platform Virtual Infrastructure Lab

A simulated corporate network environment designed to master virtualization, Active Directory management, and cross-platform networking.

## 🏗️ Architecture Overview
This lab consists of a virtualized network hosted on **VirtualBox**, simulating a production environment with a mix of Linux and Windows Server components.

### 🖥️ The Nodes
| Node Name | OS | Role |
| :--- | :--- | :--- |
| **DC-01** | Windows Server 2022 | Primary Domain Controller / Active Directory / DNS |
| **SRV-LNX-01** | Ubuntu 24.04 LTS | Production Web Server / Docker Host |
| **SRV-DB-01** | Ubuntu 24.04 LTS | Backend Database (PostgreSQL/MySQL) |

## 🛠️ Roadmap
- [X] **Phase 1:** VirtualBox Hypervisor configuration and Host-Only networking.
- [ ] **Phase 1.5: Cloud Foundation:**
    - [x] Deploy Docker Engine and containerized dashboard (Homarr).
    - [x] Implement real-time telemetry via Netdata.
    - [ ] Jellyfin "Proof of Concept" for media delivery orchestration.
- [ ] **Phase 2:** Windows Server "Promotion" to Domain Controller (Active Directory setup).
- [ ] **Phase 3:** Linux Node joining the domain and cross-platform authentication.
- [ ] **Phase 4:** Centralized logging and monitoring via the Sentry project.
