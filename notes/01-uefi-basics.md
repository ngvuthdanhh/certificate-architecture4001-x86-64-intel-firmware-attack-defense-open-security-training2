# UEFI Basics

## What is UEFI?
UEFI (Unified Extensible Firmware Interface) is the modern replacement for legacy BIOS.  
It defines the interface between platform firmware and the operating system.

## Boot Flow
1. Reset
2. SEC (Security Phase)
3. PEI (Pre-EFI Initialization)
4. DXE (Driver eXecution Environment)
5. BDS (Boot Device Selection)
6. OS Loader

## Security Considerations
- UEFI drivers are a common attack surface.
- Unsigned DXE drivers can introduce persistent malware.
- Secure Boot ensures only trusted components are loaded.
