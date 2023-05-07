# 8BCPU

8-bit CPU developed in Logisim following [this](https://youtube.com/playlist?list=PL26O2JyrmxV7CWzV9hCCJWMyiOlVMIF8z) series of YouTube videos by Dawit Kefyalew.

## Features
 - A Register
 - B Register
 - Memory Address Register (MAR)
 - Memory Buffer Register (MBR)
 - Instruction Register (IR)
 - Arithmetic Logic Unit (ALU)
 - Program Counter (PC)
 

## ISA
Each instruction is represented by a 4 bit opcode and 4 bit address. Each instruction has either one or no operand. Only ADD has no operand.

 | Instruction | Code |
 |-------------|------|
 | LOADA       | 0000 |
 | LOADB       | 0001 |
 | ADD         | 0010 |
 | STORE       | 0011 |
