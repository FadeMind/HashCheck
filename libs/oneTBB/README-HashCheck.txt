HashCheck oneTBB package
========================

This directory contains the x64 oneTBB files used to build and package the
default BLAKE3 TBB fast path.

Source: https://github.com/uxlfoundation/oneTBB
Version: v2022.3.0
Commit: f1862f38f83568d96e814e469ab61f88336cc595

The bundled binary was built from the official source tag with MSVC 19.44,
CMake, Ninja, Release x64, shared-library build, static CRT, tests disabled,
and tbbmalloc disabled.

tbb12.dll SHA-256:
D0185F05EAFC80A2A0BD13D5E029E38DC33FC0823DC369C02753BCBE1F3EE8C1

Only Release|x64 HashCheck builds use this package. Win32 builds do not link
or package oneTBB.
