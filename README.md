# The Emoji Demo

A tidied up version of the source for the 8k macOS terminal intro [The Emoji Demo](http://www.pouet.net/prod.php?which=76627).

# Build Prerequisites

- Install yasm: `brew install yasm``

- Download [shader_minifier.exe](https://github.com/laurentlb/Shader_Minifier/releases)

- Edit Makefile and change `SHADER_EXE` to the path where you downloaded shader_minifier executable

# Building and running

Type `make`. This will create two executables:

- textmode-final
- textmode-debug

Type `./textmode-final` or `textmode-debug`.