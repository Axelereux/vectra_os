# Kernel design — research questions

VECTRA intends to investigate an independently developed kernel. No kernel implementation currently exists.

## Initial research topics

- CPU architecture and privilege levels
- Boot protocol and early initialization
- Interrupt and exception handling
- Physical and virtual memory management
- Thread and process scheduling
- Synchronization primitives
- System call interface
- Driver architecture and hardware abstraction
- Kernel debugging, tracing, and test strategy
- Isolation and security boundaries

## First demonstrator

A realistic first milestone is a minimal kernel that boots reproducibly in a virtual machine, initializes a serial console, reports basic platform information, and can be tested automatically.

This milestone does not constitute a usable operating system.
