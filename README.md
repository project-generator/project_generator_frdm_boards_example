# Simple blinky examples

This is example how a simple blinky can be used with project generators.

Requirements:
 - make
 - GCC ARM

This only shows Makefiles for GCC ARM. Porting this to different toolchain or IDE should be simple as long as progen supports it. How to do it? Add toolchain specific files for a target to add armcc6 support for example.

Generate/build examples:

1. `progen generate -t make_gcc_arm` - this will generate all project files
2. Run `make` for a generated example, or use `progen build` to build all examples (with generation) 
