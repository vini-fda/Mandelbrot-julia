# Mandelbrot with CUDA.jl

This is a simple visualization of the [Mandelbrot set](https://en.wikipedia.org/wiki/Mandelbrot_set) using GPU acceleration through [CUDA.jl](https://cuda.juliagpu.org/stable/). It has two implementations, one involving array broadcasting and the other is by developing our own GPU kernel.