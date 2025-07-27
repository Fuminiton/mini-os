# Mini-OS Project

## Setting

```bash
sudo apt update && sudo apt install -y clang llvm lld qemu-system-riscv32 curl

curl -LO https://github.com/qemu/qemu/raw/v8.0.4/pc-bios/opensbi-riscv32-generic-fw_dynamic.bin
```

## Directory Structure
```bash
.
├── common.c
├── common.h
├── disk
├── kernel.c
├── kernel.h
├── kernel.ld
├── README.md
└── run.sh
```

## Memo
```bash
# check address
llvm-nm kernel.elf | grep __free_ram
```
