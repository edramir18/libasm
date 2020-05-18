# LIBASM

## TUTORIAL

- https://cs.lmu.edu/~ray/notes/nasmtutorial/
- https://www.nasm.us/doc/
- https://aaronbloomfield.github.io/pdr/book/x86-64bit-asm-chapter.pdf
- http://www.egr.unlv.edu/~ed/assembly64.pdf
- https://www.felixcloutier.com/x86/
- https://sigsegv.pl/osx-bsd-syscalls/

## Difencia AT&T e Intel sintaxis

https://imada.sdu.dk/~kslarsen/Courses/dm546-2019-spring/Material/IntelnATT.htm

## REGISTERS
|64 bits|32 bits|16 bits|H 8bits|L 8bits|Description |Preserved|
|:-----:|:-----:|:-----:|:-----:|:-----:|------------|:-------:|
|rax    |eax    |ax     |ah     |al     |Return Value|No       |
|rbx    |ebx    |bx     |bh     |bl     |            |Yes      |
|rcx    |ecx    |cx     |ch     |cl     |4rd Argument|No       |
|rdx    |edx    |dx     |dh     |dl     |3rd Argument|No       |
|rsi    |esi    |si     |       |sil    |2nd Argument|No       |
|rdi    |edi    |di     |       |dil    |1st Argument|No       |
|rbp    |ebp    |bp     |       |bpl    |Frame ptr   |Yes      |
|rsp    |esp    |sp     |       |spl    |Stack ptr   |Yes      |
|r8     |r8d    |r8w    |       |r8b    |5th Argument|No       |
|r9     |r9d    |r9w    |       |r9b    |6th Argument|No       |
|r10    |r10d   |r10w   |       |r10b   |            |No       |
|r11    |r11d   |r11w   |       |r11b   |            |No       |
|r12    |r12d   |r12w   |       |r12b   |            |Yes      |
|r13    |r13d   |r13w   |       |r13b   |            |Yes      |
|r14    |r14d   |r14w   |       |r14b   |            |Yes      |
|r15    |r15d   |r15w   |       |r15b   |            |Yes      |

## Functions

*inc* Incrementa en 1 el valor de un registro

*dec* Decrementa en 1 el valor de un registro