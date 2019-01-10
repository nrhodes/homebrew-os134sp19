# homebrew-os161sp19
Code for the Harvey Mudd College CS 161: Operating Systems for Spring, 2019

* Includes:

    * Qemu that works well with the xv6 OS


        TODO:
        * Support softmmu:
            * ```i386-softmmu```
            * ```x86_64-softmmu```



Need to install the following brew packages:
* mpfr
* gmp
* libmpc
* binutils
* gcc:  install with ```brew install i386-elf-gcc``` (installs binutils as well)
* gdb (i386-elf-gdb)




Need to update xv6 Makefile:
change TOOLPREFIX to:
        i386-elf-
edit jos GNUmakefile
        GCCPrefix = ie86-elf-


Useful dirs:
https://pdos.csail.mit.edu/6.828/2017/labs/lab1/
https://pdos.csail.mit.edu/6.828/2017/jos.git
