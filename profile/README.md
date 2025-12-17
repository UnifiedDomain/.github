# UnifiedDomain

**Open, Linux-first enterprise identity and trust platform**

UnifiedDomain is an open-source platform for centralized **identity, authentication, authorization, and device trust** in modern, offline, and critical infrastructure environments.

It is designed as a **domain-level trust control plane**, not a traditional directory service.


## What UnifiedDomain is

UnifiedDomain provides a unified authority for:

- User and device identity
- Authentication (passwordless, certificate-based, hardware-backed)
- Centralized authorization (roles, groups, policies)
- Device trust and posture
- Secure domain joins for Linux and macOS
- Audit, compliance, and forensic visibility
- Explicit trust relationships between domains

UnifiedDomain is **Linux-first**, **on-prem capable**, and **cloud-optional** by design.


## What UnifiedDomain is not

UnifiedDomain is **not**:

- A clone of Active Directory
- A Windows domain controller
- A Group Policy replacement
- A configuration management or software deployment tool

Where possible, UnifiedDomain integrates with existing tools instead of re-implementing them.


## Core design principles

- **Identity-centric, not OS-centric**
- **Explicit trust, not implicit magic**
- **Declarative policy, not silent mutation**
- **Hardware-backed security first**
- **Offline and air-gapped capable**
- **Auditable by default**


## Key capabilities (planned and in progress)

- Central identity directory (users, groups, devices)
- Kerberos-based authentication
- Certificate-based and hardware-backed login (e.g. YubiKey, smartcards)
- Centralized authorization for:
  - SSH / RDP gateways
  - VPNs
  - Wi-Fi (802.1X)
  - Applications and services
- Device enrollment and trust lifecycle
- Domain and cross-domain trust relationships
- DNS-based service discovery
- Comprehensive audit and security logging


## Target environments

UnifiedDomain is built for:

- Linux-first organizations
- Hybrid Linux / macOS environments
- Critical infrastructure (KRITIS / OT)
- Air-gapped or offline networks
- Enterprises reducing dependence on proprietary identity systems
- MSPs and multi-tenant environments


## Project status

UnifiedDomain is in **early development**.

The initial focus is on:
- Core identity and authentication
- Secure device enrollment
- Centralized authorization
- Clean, well-defined APIs

Stability, clarity, and correctness take priority over feature count.


## Contributing

Contributions are welcome once the core architecture is published.

If you are interested in:
- Identity and access management
- Linux authentication internals
- Security architecture
- Distributed systems
- Enterprise infrastructure

…you will feel at home here.


## Philosophy

UnifiedDomain exists because modern organizations need **enterprise trust without legacy coupling**.

No opaque behavior.  
No hidden dependencies.  
No assumptions about the cloud.  

Just a clear, auditable foundation for identity and trust.
