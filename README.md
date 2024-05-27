# Mandelbrot

Exploring various programming languages by building and plotting the Mandelbrot set.

![Mandelbrot Set](docs/mandelbrot-set.png "Mandelbrot Set Visualization")

## Zig

Build, test and run:

```shell
cd zig-mandelbrot

zig build -Doptimize=ReleaseFast \
    test \
    run --summary all \
    -- mandelbrot.png 4000x3000 -1.8,1 0.5,-1
```
