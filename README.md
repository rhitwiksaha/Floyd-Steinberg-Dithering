# Floyd-Steinberg-Dithering

Floyd–Steinberg dithering is an image dithering algorithm first published in 1976 by Robert W. Floyd and Louis Steinberg. 

The algorithm achieves dithering using error diffusion, meaning it pushes (adds) the residual quantization error of a pixel onto its neighboring pixels, to be dealt with later.

The algorithm scans the image from left to right, top to bottom, quantizing pixel values one by one. Each time the quantization error is transferred to the neighboring pixels, while not affecting the pixels that already have been quantized. Hence, if a number of pixels have been rounded downwards, it becomes more likely that the next pixel is rounded upwards, such that on average, the quantization error is close to zero.

![Screenshot](https://github.com/rhitwiksaha/Floyd-Steinberg-Dithering/blob/master/ss.png?raw=true)
