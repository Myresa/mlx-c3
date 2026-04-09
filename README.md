# C3 bindings for 42's mlx library
Basic C3 bindings to `minilibx`


# How to use
You need to compile libmlx.a from source and add it to `./linux-x64/` (see `manifest.json`) or equivalent depending on your system.

In your project, add this repo under `./lib/mlx.c3l/`.

For your `project.json`, add "mlx" as a dependency or use `--lib mlx`.
