# Bootloader Tasks

## Overview

The bootloader is responsible for initializing the system and loading the kernel into memory.

## Tasks

### Phase 1: Basic Setup

- [ ] Create basic bootloader assembly code
- [ ] Implement BIOS interrupt handling
- [ ] Set up real mode to protected mode transition
- [ ] Create basic VGA text output

### Phase 2: Memory Management

- [ ] Implement memory map detection (E820)
- [ ] Set up Global Descriptor Table (GDT)
- [ ] Enable A20 line
- [ ] Set up basic paging

### Phase 3: Kernel Loading

- [ ] Implement file system reading (FAT32/ext2)
- [ ] Load kernel from disk
- [ ] Parse ELF kernel format
- [ ] Jump to kernel entry point

### Phase 4: Advanced Features

- [ ] Implement multiboot compliance
- [ ] Add support for loading modules
- [ ] Create boot configuration system
- [ ] Add error handling and recovery

## Resources

- Intel Software Developer Manual
- OSDev Wiki bootloader tutorials
- GRUB multiboot specification

## Notes

- Target architecture: x86_64
- Boot method: BIOS/UEFI
- File format: Binary/ELF
