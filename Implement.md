# Edge of Time Implementation Notes

This repository was designed for Blue Dragon (Xbox 360). Porting it for **Edge of Time (EOT)** requires changes across multiple modules.

General tasks:

- Point the build system to `rebluelib/config/EOTConfig.toml` and update presets.
- Remove Unleashed specific sources from CMake until EOT pieces compile.
- Integrate shader extraction and recompilation steps in the build.
- Review kernel offsets, memory mapping and boundary issues.
