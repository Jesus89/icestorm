#Debian packaging

This is a test debian packaging repository for Icestorm Project.

You can find packages here: https://launchpad.net/~jesus-arroyo/+archive/ubuntu/icestorm

###Instructions

```bash
git clone icestorm.git icestorm
tar -czvf icestorm_0.0.0.1.orig.tar.gz icestorm
cd icestorm
git checkout debian
debuild -S -sa
dput ppa:jesus-arroyo/icestorm ../icestorm_0.0.0.1-1~trusty_source.changes
```

#Icestorm

Project IceStorm aims at documenting the bitstream format of Lattice iCE40
FPGAs and providing simple tools for analyzing and creating bitstream files.

See http://www.clifford.at/icestorm/ for more information.

Most of Project IceStorm is licensed under the ISC license:

  Permission to use, copy, modify, and/or distribute this software for any
  purpose with or without fee is hereby granted, provided that the above
  copyright notice and this permission notice appear in all copies.

  THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
  WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
  MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
  ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
  WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
  ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
  OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
