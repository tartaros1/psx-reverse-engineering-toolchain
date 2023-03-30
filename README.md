# psx-reverse-engineering-toolchain
This repository gives a overview of tools that are probably useful for reverse engineering some of your old PS1 games.

## Static analysis
Currently only recommended is using [Ghidra](https://github.com/NationalSecurityAgency/ghidra) with the [ghidra_psx_ldr](https://github.com/lab313ru/ghidra_psx_ldr) plugin

## Dynamic analysis
For dynamic analysis one of the best emulators to use is [pcsx-redux](https://github.com/grumpycoders/pcsx-redux). Scripting with LUA is one of the many powerful features of this emulator. Also check out the tools/ghidra_scripts directory to import data analysed from Ghidra to the typed debugger in pcsx-redux.

## Additional tools
- For testing out parts of the functionality of your binaries it is useful to setup a psyq SDK. [NDR008](https://github.com/NDR008/VSCodePSX) has a very good tutorial for setting up an development environment for modern systems.

## If you have additional ideas feel free to create a pull request!
