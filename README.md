# Armadillo-8 VM: Written in the EZ Programming Language
# WIP

An 8-bit virtual machine with 8 bytes of memory and 4 registers (A, B, C, D).

## Instruction Set
| Opcode | Description |
|--------|-------------|
| LOAD   | Load value into register |
| STORE  | Store register value into memory |
| COPY   | Copy value from one register to another |
| ADD    | Add values in registers |
| SUBTRACT | Subtract values in registers |
| JUMP TO | Jump to memory address |
| JUMP IF ZERO | Jump if current value is zero |
| STOP   | Halt execution |

## Quick Start
- Have EZ language interpreter installed
- Clone Armadillo Repo
- CD into root of Armadillo
- Run: `ez main/main.ez` to start CLi
- From CLI run `a8 run your_file.a8` OR `a8 asm your_file.a8`

## Example Armadillo-8 Assembly Language File:
```asm
LOAD 1 INTO A
LOAD 2 INTO B
STOP
```

