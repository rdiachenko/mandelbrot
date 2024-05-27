# Mandelbrot

Exploring various programming languages by building and plotting the Mandelbrot set.

## Zig

Build, test and run:

```shell
cd zig-mandelbrot

zig build -Doptimize=ReleaseFast \
    test \
    run --summary all \
    -- mandelbrot.png 4000x3000 -1.20,0.35 -1,0.20
```
