# Emulating Arduino Boards

This repository links to the code I have written for my MTP project:

- [Fork](https://github.com/RedDocMD/qemu/tree/uno-rev4-wifi) of QEMU containing code for emulating Arduino Uno Rev4.
- [Pinscope](https://github.com/RedDocMD/pinscope), which is a tool for plotting GPIO output.
- [Minimaprobe](https://github.com/RedDocMD/minimaprobe), a fork of [Picoprobe](https://github.com/raspberrypi/debugprobe) modded to provide OpenOCD debugging capabilities to Arduino Uno Rev4 Minima (specifically, performs the job of interpretting USB packets sent by OpenOCD and translating it to SWD signals).
- [Hex-reader](https://github.com/RedDocMD/hex-reader) reads, manipulates files in `hex` format, and converts them to ELF format.
