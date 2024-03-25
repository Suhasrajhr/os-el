Requirements: GNU/Linux make :- make utility Assembler :- NASM Assembler(nasm) GCC :- GNU Compiler Collection, C compiler xorriso :- A package that creates, loads, manipulates ISO 9660 filesystem images. grub-mkrescue :- utility to make ISO image QEMU :- Quick EMUlator to boot our kernel

Usage: Compile the source: $ cd src/ $ make Open created ISO in QEMU: $ qemu-system-i386 out/Terminal.iso Clean the code: $ make clean
