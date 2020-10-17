# LuaJIT 2.1.0 (using Meson)

This repository mirrors the source code for LuaJIT on the [latest default branch](https://github.com/LuaJIT/LuaJIT) with the addition of `meson.build` configuration files for building LuaJIT using Meson.

You can find more information about LuaJIT in [LuaJIT's homepage](http://luajit.org/).

## How to use

Using meson from the root directory of this project:

```
meson setup build
meson compile -C build
```

Learn more about Meson and how to use it from the [Meson Quick guide](https://mesonbuild.com/Quick-guide.html).

## What is LuaJIT?

README for LuaJIT 2.1.0-beta3

```
LuaJIT is a Just-In-Time (JIT) compiler for the Lua programming language.

Project Homepage: https://luajit.org/

LuaJIT is Copyright (C) 2005-2020 Mike Pall.
LuaJIT is free software, released under the MIT license.
See full Copyright Notice in the COPYRIGHT file or in luajit.h.

Documentation for LuaJIT is available in HTML format.
Please point your favorite browser to:

 doc/luajit.html
```

## Attributions

This repository was based off of https://github.com/franko/luajit which provides a meson-ified setup for LuaJIT v2.0.5. For targetting the latest default branch (v2.1.0-beta3 and beyond), this repository was created as a fork of the LuaJIT git mirror https://github.com/LuaJIT/LuaJIT.
