# CPOS
Welcome to an entirely new operating system built to work on all platforms, the **C**ross **P**latform **O**perating **S**ystem. This means that, in the future, x86 and x86-64 will be supported, but other architectures such as Archimedes, SNES, Sega Saturn, MIPS, etc. will get ports that can run the same code? How, you ask?

## CPVM
The **C**ross **P**latform **V**irtual **M**achine is the heart of CPOS. It is a virtual machine to be a bridge to allow all CPOS programs to run on all ports of CPOS. Native code can be run too, but it isn't recommended, and a VM fallback is always required. A VM is also safer, since it can restrict certain actions, such as mass deletion. CPVM, in conjunction with CPOS itself, can govern native code as well to make native code not ruin the protection system.

## CPVL
The **C**ross **P**latform **V**irtual **L**anguage is the official language to compile to CPVM. It is C-based so as to not make programming difficult for us making the compiler or you programming it. Just know that all of the same C programming pitfalls (mostly) will apply here as well.
