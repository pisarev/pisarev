# Yuriy Pisarev

I write Object Pascal. Below are four repositories built on one another: a parser, a plotting engine, an editor plugin, and a browser demo.

### Published

**[pascal-mathparser](https://github.com/pisarev/pascal-mathparser)** - an expression parser and a virtual machine. A formula compiles to a flat byte array and runs by a linear pass over it, with no allocation on the path of an ordinary formula. On x86-64 an optional accelerator turns that bytecode into machine code and hands back anything it declines, so an answer is never fast but wrong. Delphi 10.2 Tokyo through 13, Free Pascal 3.2.2 and 3.3.1, Windows and Linux.

**[pascal-crossgraph](https://github.com/pisarev/pascal-crossgraph)** - a plotting engine and a visual component that draw what the parser computes: curves with their discontinuities, intersections and extrema, cartesian and polar systems, surfaces with contour lines. The engine knows nothing about a canvas and builds headless.

**[graphbuilder-npp](https://github.com/pisarev/graphbuilder-npp)** - a plugin for Notepad++. Point at a line in the editor and, if it parses as a formula, the curve appears with its roots and extrema marked. The report goes back the other way, to a new tab as Markdown with the curve embedded as SVG.

**[mathparser-live](https://github.com/pisarev/mathparser-live)** - the same engine compiled to WebAssembly. [Try it in a browser](https://pisarev.github.io/mathparser-live/demo/); nothing to install.

All four are MIT.

### What I am building now

Bindings to modern OpenCV and to Leptonica for Delphi. After that, TVM with a set of the models people actually run: the YOLO family, PaddleOCR for detection and recognition, and segmentation.

### Contact

ypisareff@outlook.com
