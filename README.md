# mingw-to-clang

A trivial bridge between MinGW-GCC and Clang with MinGW support. Fairly useful if target program doesn't support redefining the compiler.


## How to use
1. Make sure ``x86_64-w64-mingw32-g++`` and ``x86_64-w64-mingw32-gcc`` and in ``PATH``.
2. Add the repository to ``PATH``:

    export PATH=<path-to-repo>:${PATH}

## License
I find it hard to care about licensing two scripts, but okay, it is MIT.
