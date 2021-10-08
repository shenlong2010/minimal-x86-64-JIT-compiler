# minimal-x86-64-JIT-compiler
C++ minimal JIT compiler
- Run on macOS, Linus and Windows thourgh WSL

JIT (Just-In-Time) compilation is a technique through which a program generates machine code at runtime, based on the user input.

How to compile:
g++ -std=c++14 -Wall -pedantic x_hello.cpp -o x_hello

Look at assembler code in Linux:
as chunk.s -o chunk.o
objdump -M intel -D chunk.o
