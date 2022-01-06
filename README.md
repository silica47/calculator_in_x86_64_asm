# calculator_in_x86_64_asm

```
nasm -f elf64 calculator.asm -o calculator.o
ld calculator.o -o calculator
./calculator
