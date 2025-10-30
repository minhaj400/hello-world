This is a simple Implemenation assembly in linux for hello world in (x86_64 linux)

1. install nasm if not installed
   sudo apt install nasm

2. assemble the file
   nasm -f elf64 hello.asm -o hello.o

3. link it
   ld hello.o -o hello

4. run it
   ./hello

output should be:
Hello, World!
