# **Blur**

To smooth out images, which is a form of blurring. An image is warped with a normalized box filter to make the blur filter work. This is especially helpful for getting rid of noise in a picture.

## Box Blur

To apply a simple and fast blurring effect to an image and each pixel in the image with the average color of its neighboring pixels within a certain radius

![logo](_media/Basic%20Function/Blur/boxblur.png)

## Box Filter

To apply a simple and fast smoothing effect to an image and each pixel in the image with the weighted average color of its neighboring pixels within a certain radius

![logo](_media/Basic%20Function/Blur/boxfilter.png)

## Gaussian

Apply a realistic and natural-looking blurring effect to an image and replacing each pixel in the image with the weighted average color of its neighboring pixels within a certain radius, where the weights follow a Gaussian distribution

![logo](_media/Basic%20Function/Blur/gaussian.png)

## Median

Apply a noise-reducing and edge-preserving blurring effect to an image and replacing each pixel in the image with the median color of its neighboring pixels within a certain radius

![logo](_media/Basic%20Function/Blur/medianblur.png)

## Sharpen

To applies a linear filter to the image, which can be used to make it sharper. Sharpening makes the edges of an image stand out more. It works by drawing attention to fast changes in the image's color values. You can use this to make details in an image stand out more.

### Sharpen (Prewit)

It detects edges using the respective edge detection kernels.

![logo](<_media/Basic%20Function/Blur/sharpen(Prewitt).png>)

### Sharpen (Scharr)

It detects edges using the respective edge detection kernels.

![logo](<_media/Basic%20Function/Blur/sharpen(Scharr).png>)

### Sharpen (Gaussian)

It applies Gaussian blur and subtracts it to sharpen the image.

![logo](<_media/Basic%20Function/Blur/sharpen(gaussian).png>)

### Sharpen (Laplacian)

It enhances edges using a Laplacian sharpening kernel.

![logo](<_media/Basic%20Function/Blur/sharpen(laplacian).png>)

### Sharpen (Sobel)

It detects edges using the respective edge detection kernels.

![logo](<_media/Basic%20Function/Blur/sharpen(Sobel).png>)

## Unsharp Mask

Apply a realistic and natural-looking blurring effect to an image and subtracting a blurred version of the image from the original image, and then adding the result to the original image

![logo](_media/Basic%20Function/Blur/unsharpmask.png)
