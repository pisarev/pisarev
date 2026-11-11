# Yuriy Pisarev

I write Object Pascal and build tools for Delphi and Free Pascal.

## CrossPascal

I'm building [CrossPascal](https://github.com/pisarev/crosspascal) to run trained models and process images in Delphi and Lazarus applications. It uses Apache TVM for model inference and includes Pascal bindings for OpenCV and Leptonica.

The Windows x64 early access release includes 13 examples. You can resize an image, run object detection, or ask a model about a photo. Run the example's `Prepare.cmd` to download its dependencies and sample files.

[Browse the examples](https://pisarev.github.io/crosspascal-live/) or [get Early Access 017](https://github.com/pisarev/crosspascal/releases/tag/early-access-017).

## Math and plotting tools

- **[pascal-mathparser](https://github.com/pisarev/pascal-mathparser)** compiles expressions to bytecode. The virtual machine evaluates ordinary formulas without allocating memory. An optional x86-64 accelerator compiles supported bytecode to machine code and falls back to the virtual machine when needed. Supports Delphi 10.2 Tokyo through Delphi 13 and Free Pascal 3.2.2 and 3.3.1 on Windows and Linux.
- **[pascal-crossgraph](https://github.com/pisarev/pascal-crossgraph)** draws Cartesian and polar curves, marks discontinuities, intersections and extrema, and plots surfaces with contour lines. The plotting engine can run without a canvas.
- **[graphbuilder-npp](https://github.com/pisarev/graphbuilder-npp)** plots formulas from a line in Notepad++ and marks roots and extrema. It can open a Markdown report with the SVG plot in a new tab.
- **[mathparser-live](https://github.com/pisarev/mathparser-live)** runs the math and plotting tools in the browser via WebAssembly. [Try the demo](https://pisarev.github.io/mathparser-live/demo/).

These four projects use the MIT license.

## Contact

ypisareff@outlook.com
