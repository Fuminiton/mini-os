# Mini-OS Project


## Table of Contents
1. [Setting](# setting)
2. [Directory Structure](# directory-structure)

## Setting

```bash
sudo apt update && sudo apt install -y clang llvm lld qemu-system-riscv32 curl

curl -LO https://github.com/qemu/qemu/raw/v8.0.4/pc-bios/opensbi-riscv32-generic-fw_dynamic.bin
```

## Directory Structure

```bash
.
├── disk
├── kernel.c
├── kernel.elf
├── kernel.ld
├── README.md
└── run.sh
```

