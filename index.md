---
layout: index
title: "pkgconf"
---

`pkgconf` is a program which helps to configure compiler and linker flags for
development frameworks.  It is similar to pkg-config from freedesktop.org, providing additional
functionality while also maintaining compatibility.

`libpkgconf` is a library which provides access to most of `pkgconf`'s functionality, to allow
other tooling such as compilers and IDEs to discover and use frameworks configured by
pkgconf.  It features a stable library ABI and API designed for building bindings and other tools.
