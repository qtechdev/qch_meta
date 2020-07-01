# qch toolchain
qChip is a Chip8 based system consisting of several tools.

## qch_vm
The qChip virtual machine.  
Contains `spec.hpp` master file.

A program is loaded into the virtual machine and the graphics memory is exposed
for the graphics renderer.

Clock cycle is set at 500Hz for default but can be changed by the user.

## qch_asm (formerly chasm)
Converts from qChip assembly to native chip8 instructions.

## qch_dis
Converts chip8 instructions into qChip assembly.
