# Intel Boot Guard & Trusted Execution Technology (TXT)

## Intel Boot Guard
- Ensures only OEM-signed firmware can boot.
- Uses CPU-based Root of Trust.
- Validates BIOS before execution.

### Risks
- Misconfigured policies may reduce security.
- Cannot protect against runtime firmware exploits.

## Intel TXT
- Provides measured launch environment.
- Stores measurements in TPM PCRs.
- Used for attestation and trusted computing.

### Risks
- Complex setup, often misconfigured.
- Bypass possible if platform lacks enforcement.

## Defenses
- Enable Boot Guard in Verified Boot mode.
- Use TXT for attestation where feasible.
- Monitor TPM PCRs for integrity checking.
