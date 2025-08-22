# Hardening & Operations

## Firmware Hardening Checklist
- Enable Secure Boot.
- Lock BIOS settings with strong password.
- Apply write-protection to SPI flash.
- Update firmware regularly (BIOS, ME, microcode).
- Disable unused features (e.g., AMT).

## Operational Best Practices
- Monitor firmware versions across fleet.
- Validate updates come from trusted vendor sources.
- Use Chipsec for periodic security checks.
- Document platform configurations.

## Incident Response
- Treat firmware compromise as hardware-level incident.
- Re-flash with trusted, verified firmware images.
- Replace hardware if integrity cannot be restored.
