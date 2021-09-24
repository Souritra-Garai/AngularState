# Angular State
Class to find the angular position, velocity and acceleration using a rotary encoder.

Installation
--------------------------------------------------------------------------------

To install this library, just place this entire folder as a subfolder in your `project/lib/targets/libraries` folder.

When installed, this library should look like:

`project/lib/targets/libraries/AngularState`              (this library's folder)
`project/lib/targets/libraries/AngularState/AngularState.cpp`     (the library implementation file)
`project/lib/targets/libraries/AngularState/AngularState.h`       (the library description file)
`project/lib/targets/libraries/AngularState/keywords.txt` (the syntax coloring file)
`project/lib/targets/libraries/AngularState/examples`     (the examples in the "open" menu)
`project/lib/targets/libraries/AngularState/readme.txt`   (this file)

Building
--------------------------------------------------------------------------------

After this library is installed, you just have to start the Arduino application. You may see a few warning messages as it's built.

To use this library in a sketch, go to the Sketch | Import Library menu and select AngularState.  This will add a corresponding line to the top of your sketch:

```#include <AngularState.h>```

To stop using this library, delete that line from your sketch.

Geeky information:
After a successful build of this library, a new file named `AngularState.o` will appear in `project/lib/targets/libraries/AngularState`. This file is the built/compiled library code.

If you choose to modify the code for this library (i.e. "AngularState.cpp" or "AngularState.h"), then you must first 'unbuild' this library by deleting the "AngularState.o" file. The new "AngularState.o" with your code will appear after the next press of "verify".

