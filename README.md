# Reintegrated

The Reintegrated series is structured uniquely code-wise. All mods in the series get tested at the same time and a bit of Gradle magic lets them be compiled as separate mods.

- The `common` module holds all the mod metadata files and the combined datapack files.
- The `testing-1-20` and `testing-1-21` modules open Forge 1.20 and Fabric 1.21 respectively with all modules.
- The modules that start with `mod-` are placeholders to publish from.