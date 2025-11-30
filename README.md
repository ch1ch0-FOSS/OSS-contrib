# oss-contrib

Open source contributions documenting community engagement and collaborative development practices.

## What This Demonstrates

**For Open-Source Companies:**

Community engagement and collaboration skills. Ability to work within existing codebases. Documentation and testing contributions. FOSS philosophy alignment.

## Contribution Philosophy

Give back to projects used in production infrastructure. Every tool in srv-m1m stack benefits from open source work. Contributing upstream strengthens the ecosystem.

**Focus areas:**
- **Testing & Bug Reports:** Early adopter feedback for ARM64/Asahi ecosystem
- **Documentation:** Installation guides, troubleshooting, configuration examples
- **Patches:** Compatibility fixes and feature enhancements

## Projects Contributed To

| Project | Contribution Type | Status | Links |
|---------|-------------------|--------|-------|
| **Fedora Asahi** | Testing/Feedback/Bug Reports | Ongoing | [Issues](https://github.com/AsahiLinux/docs/issues), [Forum](https://discussion.fedoraproject.org) |
| **Forgejo** | Bug Reports, Feature Requests | Active | [Issues](https://codeberg.org/forgejo/forgejo/issues) |
| **systemd** | Documentation Improvements | Planned | - |
| **Ansible** | Role improvements | Planned | - |

## Contribution Log

### 2025-11
**Placeholder:** Contributions tracked once submitted to upstream projects.

**Example format:**
- **Fedora Asahi:** Reported Btrfs mount issue on M1 ([issue#123](link))
- **Forgejo:** Documentation clarification for ARM64 builds ([PR#456](link))

### Future Contributions

Contributions will be documented here chronologically as they occur.

## Contribution Areas

### Infrastructure & DevOps
- Ansible modules and playbooks
- Kubernetes operators and controllers
- systemd service improvements

### Linux & System Administration
- Fedora Asahi Remix testing and feedback
- ARM64 compatibility patches
- System automation tools

### Documentation
- Installation guides
- Troubleshooting runbooks
- Configuration examples

## Repository Structure

contributions/
├── patches/ # Submitted patches and pull requests
├── bug-reports/ # Documented bug reports with reproductions
└── documentation/ # Documentation improvements

projects/
└── contribution-summary.md # Per-project contribution tracking

documentation/
└── guides/ # Standalone guides contributed upstream


## Roadmap

**2025 Q4-Q1 2026:**
- [ ] Submit Ansible role for Forgejo deployment
- [ ] Document Btrfs tiering patterns for ARM64
- [ ] Contribute to Fedora Asahi documentation
- [ ] Report Fedora Asahi issues encountered in production

**Active testing:**
- Fedora Asahi 40+ on Mac Mini M1 (production workload)
- Forgejo 1.21+ (git hosting in production)
- systemd hardening configurations

## Contributing Guidelines

All contributions follow upstream project guidelines. Patches maintain compatibility with project coding standards. Documentation follows project style guides.

**Standards maintained:**
- Conventional commits where applicable
- Proper issue reproduction steps
- Testing performed before submission
- Documentation includes rationale

## Related Infrastructure

**Production Environment:** [fedora-asahi-srv-m1m](https://github.com/ch1ch0-FOSS/fedora-asahi-srv-m1m) - Infrastructure running projects being contributed to

**Testing Platform:** ARM64 Mac Mini M1 with Fedora Asahi provides real-world testing environment for contributions

## License

Individual contributions licensed per upstream project requirements. Documentation under MIT.

---

**Hiring Signal:** Demonstrates community engagement, willingness to contribute upstream, collaborative development practices, and production-testing mindset. Contributions documented as they occur.

**Note:** This repository serves as contribution tracking. Actual contributions submitted directly to upstream project repositories.


