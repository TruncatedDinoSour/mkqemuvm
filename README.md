# Mkqemuvm

> A simple wrapper around qemu to make virtual machines

# Requirements

- mlocalte
- fzf
- qemu
- edk2-ovmf

# Installation

## Manual

```bash
sudo install -Dm755 mkqemuvm /usr/local/bin
```

## Packages

- Linux
  - Gentoo linux: [app-emulation/mkqemuvm::dinolay](https://ari-web.xyz/gentooatom/app-emulation/mkqemuvm)

# Configuration

Configured though environment variables

- `__BASH_RUNAS` -- the "sudo" program to use
- `BIOS` -- The BIOS file to look for
- `VM_NAME_DISALOWED_CHARS` -- Disallowed characters in the VM name
- `DRIVE_FORMATS` -- Drive formats you want to be available though `qemu-img`
- `FZF_FLAGS` -- The flags to pass to FZF

Or just edit ~/.config/mkqemuvm.conf
