# About
This is my atempt at booting a multi-threaded kernel. 

# How to Run
1. Install nasm
2. Install qemu
3. compile the assembly file
```bash
nasm -f bin ./boot.asm -o ./boot.bin
```
4. run it using qemu
```bash
qemu-system-x86_64 -hda ./boot.bin
```
