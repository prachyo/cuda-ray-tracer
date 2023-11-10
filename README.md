cuda-ray-tracer
===

This is a very simple ray tracing project based off Peter Shirley's [Ray Tracing in One Weekend][1] project. The original project has been updated so that the ray tracer runs much faster on the GPU using CUDA.

Running
-------

This project assumes some familiarity with Nvidia's CUDA. To run the program, you can simply use the Makefile to create an executable using `make cudart` and then the output image using `make out.ppm`.

[1]: https://raytracing.github.io/books/RayTracingInOneWeekend.html

Output
-------

![Final output](https://raytracing.github.io/images/img-1.21-book1-final.jpg)
