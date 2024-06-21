# c166-dis

Disassembler for the [c166 processor family](https://en.wikipedia.org/wiki/C166_family) which was used for many mobile phones years ago. The code is preserved mainly for historical reasons.

This version has support for `#bitoffQ` and `#mask8` fields in `BFLDL` and `BFLDH` instructions.

Usage: `./c166-dis.pl <file> [start] [offset]`
