# **Filter**

To applies the image a linear filter. To apply a filter to an image, this function convolves it with a kernel, which is usually a 2D matrix. This is especially helpful for adding custom filters to a picture.

## Bilateral Filter

reducing noise in photos without sacrificing clarity and definition at the corners. The bilateral filter performs filtering by taking into account both spatial distance and intensity differences.

![logo](_media/Basic%20Function/Filter/bilateral.png)

## Contour

To detect and draw the outlines of the objects or features in an image and use the contour utility to apply contour to an image by using different parameters, such as the edge detection algorithm, the contour finding algorithm, or the drawing function.

### Binary

for applications such as edge detection, contour identification, foreground-background separation, and A pixel value turns black if it is below the threshold and white otherwise.

![Sign Up](_media/Basic%20Function/Filter/binary.png)

### Binary Inverted

To produces an inverted binary picture. This indicates that white pixels turn black and black pixels turn white.

![Sign Up](_media/Basic%20Function/Filter/binary_inverted.png)

### Otsu

Reducing the difference between the foreground and background parts of the image as much as possible.

![Sign Up](_media/Basic%20Function/Filter/otsu.png)

### Triangle

To detect shapes in an image that are triangular. For instance, you could use it to find things in pictures based on their shapes.

![Sign Up](_media/Basic%20Function/Filter/triangle.png)

### Trunc

used for image thresholding, which is a type of image binarization. This function is particularly useful to limit the maximum intensity of an image. For example, use it in image processing to suppress bright regions in an image.

![Sign Up](_media/Basic%20Function/Filter/trunc.png)

### Tozero

For getting rid of dark spots in an image. Use it in image processing, for instance, to draw attention to bright regions in an image.

![Sign Up](_media/Basic%20Function/Filter/tozero.png)

### Tozero Inverted

For hiding parts of an image that are too bright. For instance, you can use it to bring out dark areas in an image when you're processing it.

![Sign Up](_media/Basic%20Function/Filter/tozero_inverted.png)

### Adaptive Gaussian

For applying different thresholds to different parts of the same image, which works better for pictures with different amounts of light. Use it in image processing to bring out details in a mammogram or use satellite images to find the location of a natural disaster.

![Sign Up](_media/Basic%20Function/Filter/adaptive_gaussian.png)

### Adaptive Mean

Helpful for enhancing particular features or regions, segmenting images with different levels of illumination, and increasing segmentation accuracy.

![Sign Up](_media/Basic%20Function/Filter/adaptive_mean.png)
