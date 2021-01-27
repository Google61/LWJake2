![Java CI](https://github.com/Google61/LWJake2/workflows/Java%20CI/badge.svg)

LWJake2 README
LWJake2 Website: https://github.com/flibitijibibo/LWJake2
=========================================================

LWJake2 is a fork of Jake2, a port of the GPL'd Quake 2 engine from id Software
to Java.

LWJake2 is distributed under the terms of the GPLv2 (see LICENSE).

The port was done completely in Java. No native libraries are used for the
game functionality.

This version of Jake2 uses the Lightweight Java Game Library (LWJGL) for
OpenGL/OpenAL bindings, rather than JOGL/JOAL.

LWJGL Website - http://www.lwjgl.org/

LWJake2 is still under development. Send bug reports and feedback to
flibitijibibo@flibitijibibo.com.

Currently LWJake2 supports GNU/Linux, Windows and Mac OSX. The LWJake2
dedicated server runs on every Java supported platform.

System Requirements:
- A computer from the last ~5 years.
- The latest version of Java.

Installation
============

- Extract the archive that this is in.
- Install Quake 2 data (see below).
- Run your respective executable (LWJake2.sh, for example)
- Play!

Installation of Quake 2 data:
By default, LWJake2 looks in its own directory for baseq2/, so by default you
need to move your baseq2/ to that folder. However, you can change this by
modifying the "cddir" cvar in your config.cfg. For example, if I wanted to
host my data in ~/.quake2, I would add the following to my config.cfg:

set cddir "/home/flibitijibibo/.quake2"

Be sure to check for "set cddir" first! LWJake2 adds this in the default config.

Credits
=======

Bytonic Software - Original Jake2 authors
-----------------------------------------
Holger Zickner <hoz@bytonic.de>
Carsten Weisse <cwei@bytonic.de>
Rene Stoeckel  <rst@bytonic.de>

Jake2 Community - Other Jake2 contributors
------------------------------------------
David Sanders - Original LWJGL implementation

12characters Games - LWJake2 authors
------------------------------------
Ethan Lee <flibitijibibo@flibitijibibo.com>
