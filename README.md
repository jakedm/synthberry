# synthberry

Synthberry is a software synthesizer written for the Raspberry Pi in C++11.
This is a personal project and currently work-in-progress, source may break at
any time.

## Compilation
After cloning the synthberry repository you need to retrieve the dependencies:

    git submodule update --init --recursive

Having done that, you can build the source by issuing:

    make

Now you can run synthberry as follows:

    LD_LIBRARY_PATH=externals/libserial/src/.libs bin/synthberry
