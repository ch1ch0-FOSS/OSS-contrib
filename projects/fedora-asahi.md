# Fedora Asahi Remix Contributions

## Overview

Testing and feedback for Fedora Asahi Remix on Apple Silicon hardware.

## Hardware Tested

- Mac Mini M1 (2020)
- 16GB RAM
- 512GB SSD

## Areas of Focus

### Service Deployment
- systemd user services on ARM64
- PostgreSQL performance characteristics
- Container runtime compatibility

### Storage & Filesystem
- External drive mounting and permissions
- `/mnt/data` persistent storage patterns
- APFS interoperability

### Networking
- IPv4/IPv6 dual-stack configuration
- SSH server hardening
- localhost-only service binding

## Issues Reported

1. **systemd user service lingering**: Documented behavior and workarounds
2. **ARM64 package availability**: Tested alternative sources
3. **Performance baselines**: Established reference metrics for M1 hardware

## Documentation Contributions

- Installation guides for self-hosted services
- ARM64-specific troubleshooting procedures
- Performance tuning recommendations

## Status

Active testing and feedback ongoing. Primary workstation since deployment.

