# Edge of Time Port

The `reblue` directory contains the main runtime. Key work needed for EOT:

- Update hard coded paths in `main.cpp` to point to your EOT game data.
- Change `user/paths.h` and registry strings to use an EOT specific name.
- Remove Sonic‐specific code and assets from the build list.
- Locate kernel call offsets and implement missing functions in `kernel/`.
- Ensure memory mapping of the base XEX matches the guest code so debug symbols line up.
