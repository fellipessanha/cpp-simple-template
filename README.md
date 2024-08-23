# cpp-simple-template
a simple template for c++, with CMake already working out of the box. just don't do any fancy filesystem and you should be fine

## what i'm using

1. [clang](https://apt.llvm.org/)
2. [clang-format](https://apt.llvm.org/)
3. [CMake](https://github.com/Kitware/CMake/releases)
4. [VSCode](https://code.visualstudio.com/Download)

## how to use

run `cmake -B build` to genereate `compile_commands.json` in `/build`.
then you can run `make --directory build` to build the executable file, named `template.out` by default

or you can manually make `build` and run everything from there if your program is really complex

## what it doesn't do
1. Include and sources files recursively

## useful information

1. [clang compiling documentation](https://clang.llvm.org/docs/UsersManual.html)
