# Lua Wii U

This is [Lua 5.4.0](https://www.lua.org/versions.html) with a Wii U specific makefile.

## Compiling

Make sure to have [devkitPro](https://devkitpro.org/wiki/Getting_Started) installed.

* Run `make` to compile
* Run `make install` to install lua into your `wut` installation

## Using Lua
In your project you can then include the usual Lua headers like `lua.h` or `lua.hpp`.

Also remember to link against the Lua library via `-llua`.