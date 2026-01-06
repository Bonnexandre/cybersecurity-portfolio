# System Hardening – Endpoint & Server Security

## Objective
Analyze key system hardening practices used to reduce attack surface
and protect servers and endpoints from cyber and physical threats.

## Context
System hardening is a foundational defensive security practice.
Unpatched systems, exposed interfaces, and insecure configurations
are common entry points for attackers in enterprise environments.

This project focuses on operating system patching, USB attack vectors,
storage encryption, and third-party software risk.

## Analysis

### Operating System Patching
Regular patching addresses known vulnerabilities, improves system
stability, and reduces exposure to exploits. Unpatched systems are
frequently targeted in opportunistic and automated attacks.

### USB Attack Vectors
USB ports present both physical and human-based security risks.
Attackers may:
- Insert malicious USB devices directly
- Exploit human curiosity by leaving infected USB drives in public areas

Disabling USB boot options helps prevent unauthorized execution
and physical compromise.

### Self-Encrypting Drives (SEDs)
SEDs automatically encrypt data at rest using built-in hardware
encryption (e.g., AES). This protects sensitive information even if
physical access to the drive is obtained.

### Third-Party Software Risk
Third-party applications increase attack surface and can introduce
supply-chain vulnerabilities. Exploiting weaknesses in vendor software
can allow attackers to bypass perimeter defenses.

## Defensive Perspective
Effective system hardening includes:
- Regular OS and firmware patching
- Restricting or disabling unused ports
- Encrypting data at rest using SEDs
- Controlling and auditing third-party software

These controls reduce the likelihood of successful compromise and
limit attacker persistence.

## Key Takeaways
- System hardening is a core blue-team responsibility
- Physical access can lead to cyber compromise
- Supply-chain risk must be actively managed
- Defense-in-depth starts at the system level
