# how to run

1. fist install assemblers:

    - `sudo apt install as31 nasm`

2. assemble the program

    - `nasm -f elf64 asm.asm`

3. link the object file into an executable file

    - `ld -s -o asm asm.o`

4. execute it

    - `./asm`
