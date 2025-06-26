# GPU Backend

Edge of Time's shaders and render states differ from Unleashed.

- Strip Sonic-specific hacks in `video.cpp`.
- Implement shader extraction tooling and caching under `shader/`.
- Reverse engineer where EOT stores shaders and integrate with the build pipeline.
