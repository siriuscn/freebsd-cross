# freebsd-cross

Cross compiler ( GCC ) for FreeBSD 9 x86_64 on Linux container.

Complier path is at /usr/local/cross-compiler/bin. It has been added to your PATH environment variable.

You can run like this:

x86_64-pc-freebsd9-gcc -o test test.c

or 

x86_64-pc-freebsd9-g++ -o test test.cpp
