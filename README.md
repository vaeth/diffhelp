# diffhelp

(C) Martin Väth (martin at mvath.de).
This project is under the BSD license 2.0 (“3-clause BSD license”).
SPDX-License-Identifier: BSD-3-Clause

A POSIX script acting as a frontend, beautifier, and path-fixer for `diff -u`

Use `diffhelp -h` to get help.

### Installation

For installation, copy the content of `bin/` with executable permissions into
your `$PATH`. To obtain support for __zsh completion__, copy the content of
`zsh/` to a directory of your zsh's `$fpath`.

For Gentoo, there is an ebuild in the mv overlay (available over layman).
