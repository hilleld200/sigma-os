# Drivers Tasks

## Overview

Device drivers for hardware communication and abstraction.

**ONLY AT THE END OF THE KERNEL DEVELOPMENT PHASE, AFTER BASIC KERNEL FUNCTIONALITY IS IMPLEMENTED.**

## Tasks

### Phase 1: Basic Drivers

- [ ] Implement keyboard driver
- [ ] Create VGA/text mode driver
- [ ] Add timer/PIT driver
- [ ] Implement serial port driver

### Phase 2: Storage Drivers

- [ ] Create ATA/IDE hard disk driver
- [ ] Implement AHCI SATA driver
- [ ] Add floppy disk driver (if needed)
- [ ] Create RAM disk driver

### Phase 3: Input/Output Drivers

- [ ] Implement PS/2 mouse driver
- [ ] Add USB controller driver
- [ ] Create sound card driver
- [ ] Implement network card driver

### Phase 4: Advanced Drivers

- [ ] Add graphics/framebuffer driver
- [ ] Implement PCI bus driver
- [ ] Create power management driver
- [ ] Add virtualization drivers (if needed)

## Resources

- OSDev hardware documentation
- PCI specification
- Intel chipset documentation

## Notes

- Use driver framework from kernel
- Implement as loadable modules
- Focus on common hardware first
