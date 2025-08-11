# sigma-os

A custom operating system project built from scratch.

## Project Structure

```plaintext
sigma-os/
├── bootloader/          # Boot loader implementation
│   └── tasks.md         
├── cross-compiler/      # Cross-compilation toolchain
│   └── tasks.md         
├── kernel/              # Operating system kernel
│   └── tasks.md        
├── drivers/             # Hardware device drivers
│   └── tasks.md         
├── filesystem/          # File system implementation
│   └── tasks.md         
├── memory-management/   # Memory allocation and management
│   └── tasks.md         
├── process-management/  # Process scheduling and control
│   └── tasks.md         
├── syscalls/            # System call interface
│   └── tasks.md         
├── userspace/           # User space applications and libraries
│   └── tasks.md         
├── testing/             # Testing framework and test suites
│   └── tasks.md         
├── tools/               # Development and build tools
│   └── tasks.md         
├── docs/                # Documentation
├── build/               # Build artifacts and output
└── README.md            # This file
```

## Development Phases

1. **Phase 1: Foundation**
   - Set up cross-compiler toolchain
   - Create basic bootloader
   - Implement minimal kernel with VGA output

2. **Phase 2: Core Systems**
   - Memory management (physical and virtual)
   - Basic process management
   - Simple file system

3. **Phase 3: System Services**
   - Device drivers (keyboard, storage)
   - System call interface
   - Inter-process communication

4. **Phase 4: User Space**
   - Standard library implementation
   - Basic shell and utilities
   - Application framework

## Getting Started

Each directory contains a `tasks.md` file with detailed implementation tasks and resources for that component. Start with the cross-compiler setup, then move to the bootloader and kernel development.

## Architecture

- **Target Architecture**: x86_64
- **Boot Method**: BIOS/UEFI
- **Programming Languages**: C, Assembly
- **Build System**: Make/Custom scripts
