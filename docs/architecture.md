# Architecture — initial research outline

This document is a starting point for discussion, not a finalized architecture.

## Design goals

- A small, reviewable kernel with clearly defined responsibilities
- Explicit interfaces between kernel, drivers, and user-space services
- Modular system services
- Reproducible builds and automated tests
- A documented security model
- Hardware support introduced through defined milestones

## Proposed layers

1. **Boot and platform initialization** — firmware handoff, boot protocol, early initialization
2. **Kernel** — CPU and interrupt handling, memory management, scheduling, synchronization, system calls
3. **Drivers and hardware abstraction** — device discovery and controlled hardware access
4. **Core user-space services** — process management, storage, networking, logging, updates
5. **Security and policy** — identity, permissions, isolation, audit, secure update design
6. **Graphical environment** — composable interfaces for different audiences and accessibility needs
7. **Applications and compatibility** — native application model and researched compatibility approaches
8. **Optional AI services** — separately permissioned, disableable capabilities with clear data flows

## Decisions still required

- Initial CPU architecture and supported virtual machine
- Boot protocol and firmware targets
- Kernel design and language/toolchain
- Kernel/user-space boundary
- Driver model
- Filesystem strategy
- Update and recovery design
- Application packaging and compatibility approach

Each decision should be recorded with alternatives, rationale, risks, and validation criteria in an architecture decision record.
