# System Management Mode (SMM)

## What is SMM?
- A special-purpose operating mode of x86 CPUs.
- Triggered by System Management Interrupt (SMI).
- Runs with higher privilege than OS or hypervisor.

## Risks
- SMM code executes in a hidden, privileged context.
- Vulnerabilities allow attackers to hijack SMM handlers.
- Exploits enable stealthy rootkits.

## Defenses
- Lock SMRAM to prevent unauthorized access.
- Audit SMM code for unsafe memory operations.
- Use hardware protections (e.g., SMRR, SMM lockdown).
