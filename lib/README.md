# `lib/` — your libraries live here

PlatformIO automatically finds any library you drop in this folder (each in its
own subfolder).

## Session 4: your Edge Impulse model

When you export your trained model from Edge Impulse as an **Arduino library**
(a `.zip`), unzip it **here**. You'll get a folder like:

```
lib/
└── your-project_inferencing/
    ├── src/
    ├── model-parameters/
    └── ...
```

Then, in `src/main.cpp`, `#include <your-project_inferencing.h>` (the exact name
matches the folder). See `examples/session04_deploy.cpp` for the full sketch.

If includes don't resolve, add `lib_ldf_mode = deep+` to `platformio.ini`.

## Don't commit the library

The exported library is about **23 MB in over 1300 files**, and you can rebuild
it from Edge Impulse whenever you need it, so `.gitignore` keeps it out of your
repository. What you commit for session 4 is **your `src/main.cpp`** — the sensor
loop, the include, and the threshold you chose.
