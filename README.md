# VECTRA

### An open initiative for independent, accessible computing.

**A new foundation for computing — designed to be open, adaptable, and privacy-conscious.**

> **Project status: Concept and architecture research.** VECTRA is not yet a functional operating system. No working kernel, installer, or production release is available.

## Vision

VECTRA is an early-stage initiative to research and develop an open-source operating system for desktop and laptop computers. Its long-term ambition is to offer individuals, businesses, educational institutions, and public institutions an alternative to proprietary desktop operating systems.

The project explores how an independently developed kernel and a modular system architecture could support greater technological autonomy, user choice, privacy, security, and accessibility.

## Principles

- **Technological autonomy:** develop and maintain VECTRA's core architecture, including an independently developed kernel, while using open standards and carefully reviewed third-party components where appropriate.
- **Privacy and user control:** make data collection and connected services transparent, configurable, and optional wherever technically and legally possible.
- **Security by design:** treat secure defaults, isolation, updates, and vulnerability handling as foundational requirements.
- **Accessibility:** design understandable experiences for people with different needs, skills, and contexts.
- **Adaptability:** explore distinct desktop experiences for personal, professional, educational, and public-sector use, built on a shared technical foundation.
- **Open collaboration:** publish design decisions and invite review and contributions as the project becomes technically ready.

## Intended editions

These are product directions, not existing releases:

| Edition concept | Intended audience |
| --- | --- |
| Personal | Individuals and everyday computing |
| Professional | Businesses and professional workflows |
| Education | Schools, universities, and learning environments |
| Public Sector | Public institutions with specific security, privacy, and administration needs |

## Research and development areas

1. System goals, requirements, and architecture
2. Boot process and kernel bring-up
3. Memory management, scheduling, and interrupts
4. Hardware abstraction and device drivers
5. Storage, filesystems, and networking
6. Security model, permissions, and update mechanisms
7. User interfaces and accessibility
8. Application compatibility and developer tooling
9. Optional AI-assisted features with explicit user and administrator controls

Compatibility with existing applications and hardware is a research objective. It is not yet implemented or guaranteed.

## Current status and first milestones

VECTRA is at the concept and architecture-research stage. The initial milestones are:

- [ ] Define scope, target hardware, and non-goals
- [ ] Write and review the system architecture proposal
- [ ] Select the initial development toolchain and target virtual machine
- [ ] Define kernel interfaces and a minimal bootable prototype
- [ ] Establish testing, security, and contribution workflows
- [ ] Publish the first reproducible technical demonstration

Milestones will be updated as evidence and implementation progress become available.

## Repository map

- `docs/` — vision, architecture, roadmap, security, privacy, governance, and kernel research
- `kernel/` — reserved for kernel source code once the design and toolchain are ready
- `boot/` — boot process research and future implementation
- `system/` — core services and system components
- `interfaces/` — interface and accessibility research
- `compatibility/` — application and hardware compatibility research
- `ai/` — optional AI integration research

## Contributing

VECTRA welcomes constructive discussion and, as implementation begins, technical contributions. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening an issue or pull request. Early feedback on architecture, security, accessibility, and project scope is especially useful.

## Governance and licensing

VECTRA intends to build an open development process and explore the creation of an independent international foundation in the future. No foundation currently exists, and no institutional partnerships or endorsements are claimed.

Software licensing will be selected per component before source code is published, with third-party license compatibility reviewed carefully. Until a license is added, do not assume that this repository's software or other materials may be reused. See [docs/governance.md](docs/governance.md) and [LICENSE-DECISION.md](LICENSE-DECISION.md).

## Disclaimer

VECTRA is an independent, early-stage project. It is not affiliated with, endorsed by, or sponsored by Microsoft, Anthropic, or any government or public institution.
