# Firmware Hardening Checklist ✅

This checklist provides actionable steps to secure platform firmware.

## Configuration
- [ ] Enable **Secure Boot**
- [ ] Set strong **BIOS/UEFI password**
- [ ] Lock unused boot options
- [ ] Disable legacy boot (CSM)

## SPI Flash
- [ ] Enable **BIOS Lock Enable (BLE)**
- [ ] Protect **ME Region**
- [ ] Verify **firmware updates** are signed
- [ ] Enable write-protection

## SMM
- [ ] Lock **SMRAM**
- [ ] Audit SMI handlers
- [ ] Ensure **SMRR** and SMM lockdown enabled

## Operations
- [ ] Keep firmware **up-to-date**
- [ ] Monitor TPM PCR values
- [ ] Run **Chipsec** audits periodically
