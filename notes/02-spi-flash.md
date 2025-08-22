# SPI Flash

## Flash Layout
- **Descriptor Region**: Defines access permissions
- **ME Region**: Intel Management Engine
- **BIOS Region**: Firmware (UEFI/BIOS)
- **GbE Region**: Gigabit Ethernet configuration

## Risks
- Unauthorized firmware write → persistent implants
- SPI write protection bypasses

## Defenses
- Enable BIOS Lock Enable (BLE)
- Protect ME and descriptor regions
- Verify firmware updates (signed)
