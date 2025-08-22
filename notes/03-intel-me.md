# Intel Management Engine (ME)

## Overview
Intel ME is a coprocessor integrated into the Platform Controller Hub (PCH).  
It provides out-of-band management and security features.

## Functions
- Remote management (AMT).
- DRM and security functions.
- Power and clock control.

## Risks
- Runs with high privileges, below OS level.
- Exploits can provide stealthy persistence.
- Vulnerabilities in AMT / ME firmware.

## Defenses
- Update ME firmware regularly.
- Disable AMT if not needed.
- Use vendor-provided ME disable tools (when supported).
