# AudioMoth-Wytham-Woods

Firmware for the AudioMoth device, customized for Wytham Woods.

## Building

1. Ensure the GNU Arm Embedded Toolchain is installed at `/opt/gcc-arm-none-eabi-10.3-2021.10/`.

2. Navigate to the `build` directory and run `make`:

   ```bash
   cd build
   make
   ```

This generates the following output files:
- `audiomoth.bin` (binary image for flashing)
- `audiomoth.hex` (Intel HEX format)
- `audiomoth.axf` (ELF executable)
- `audiomoth.lst` (disassembly listing)

## Cleaning

Run `make clean` in the `build` directory to remove build artifacts.