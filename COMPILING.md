To compile the Mesen-SX Libretro core you will need a version of clang/gcc that supports C++14. Run "make" from the "Libretro" subfolder to build the Libretro core. LTO gives a large performance boost (25-30%+), so turning it off is not recommended.

Example msys/*nix Build command for x86-64
`LTO=true MESENPLATFORM=x64 make`