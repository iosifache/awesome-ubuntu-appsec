# Awesome AppSec in Ubuntu [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Index of categories

## Tools

### Threat modelling

- [OWASP Threat Dragon](https://snapcraft.io/threat-dragon) (snap) - threat modelling platform

### Security linters

- [Bandit](https://snapcraft.io/bandit) (snap) - Python static code analyser
- [Brakeman](https://snapcraft.io/brakeman) (snap) - static vulnerability scanner for Ruby on Rails
- [cppcheck](https://snapcraft.io/cppcheck) (snap) - C/C++ static code analyser
- [frawfinder](https://snapcraft.io/flawfinder) (snap) - C/C++ static code analyser
- [gosec](https://snapcraft.io/gosec) (snap) - Go static code analyser
- [govulncheck](https://snapcraft.io/govulncheck) (snap) - Go static code analyser
- [Ruff](https://snapcraft.io/ruff) (snap) - Python linter with security-oriented rules
- [semgrep-rules-manager](https://snapcraft.io/semgrep-rules-manager) (snap) - downloader of third-party Semgrep rules
- [Semgrep](https://snapcraft.io/semgrep) (snap) - static analysis engine for finding bugs and querying the code in 30+ programming languages
- [ShellCheck](https://snapcraft.io/shellcheck) (snap) - static doe analyser for shell scripts

### Vulnerability scanning for dependencies

- [depsdev](https://snapcraft.io/depsdev) (snap) - deps.dev client for fetching details such as dependencies, licenses, advisories, and critical health
- [OSV-Scanner](https://snapcraft.io/osv-scanner) (snap) - vulnerability scanner for projects' lists of dependencies
- [Trivy](https://snapcraft.io/trivy) (snap) - vulnerability scanner for SBOM

### Confinement

- [AppArmor](https://packages.ubuntu.com/search?searchon=sourcenames&keywords=apparmor) (package) - Linux security module implementing a MAC policy to limit the capabilities of an application
- [Snapcraft](https://snapcraft.io/snapcraft) (snap) - toolkit for creating snaps, namely cross-distro packages that are self-contained using the AppArmor LSM

### Infrastructure as code

- [Trivy](https://snapcraft.io/trivy) (snap) - vulnerability scanner for infrastructure as code

### License

- [Trivy](https://snapcraft.io/trivy) (snap) - license scanner and opinionated risk assessor

### Reverse engineering engines

- [Capstone](https://packages.ubuntu.com/search?searchon=sourcenames&keywords=capstone) (package) - disassembly framework supporting 20+ architectures
- [Ghidra](https://snapcraft.io/ghidra) (snap) - reverse engineering framework with disassembly, assembly, decompilation, graphing, and scripting capabilities
- [MobSF](https://snapcraft.io/mobsf) (snap) - Android and IOS security assessment platform, both static and dynamic
- [radare2](https://snapcraft.io/radare2) (snap) - reverse engineering toolkit with disassamblers, debuggers, and emulators

### Fuzzers

- [AFL++](https://packages.ubuntu.com/search?searchon=sourcenames&keywords=aflplusplus) (package) - coverage-based fuzzer with compile-time instrumentation and QEMU emulation

### Symbolic execution engines

- [KLEE](https://snapcraft.io/klee) (snap) - symbolic execution VM using LLVM

### Runtime process analysis

- [nsntrace](https://snapcraft.io/nsntrace) (snap) - network tracer for processes, with `.pcap` exports
- [Valgrind](https://snapcraft.io/valgrind) (snap) - memory management and thread error detector

### Web scanners

- [OWASP Zed Attack Proxy](https://snapcraft.io/zaproxy) (snap) - an extensible web app scanner
- [sublist3r](https://packages.ubuntu.com/search?searchon=sourcenames&keywords=sublist3r) (package) - subdomain enumeration tool by using OSINT or bruteforce
- [wfuzz](https://packages.ubuntu.com/search?searchon=sourcenames&keywords=wfuzz) (package) - fuzzer for any field of an HTTP request

## Contributions

Do you use Ubuntu for software development or security? Ever discovered an awesome software security tool that can be swiftly installed on Ubuntu via `apt` or `snap`, yet it's missing from this list? We'd love to hear about it!

Just follow [the contribution guide](CONTRIBUTING.md) and we'll gladly add it to this list. Your contribution could be the missing piece in someone else's Ubuntu journey. Let's collaborate and make our Ubuntu toolset even better, one addition at a time!

