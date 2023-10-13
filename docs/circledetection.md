# **Circle Detection**

## Hough Circle

To detect circles in an image, even if they are partially occluded or distorted by noise or perspective and transforming the image space into a parameter space, where each point represents a possible circle in the original image

![logo](_media/Advanced%20Function/Hough%20Circle/hough%20circle%20transform.png)

### Hough Circle (Blur)

![logo](<_media/Advanced%20Function/Hough%20Circle/hough%20circle%20transform(blur).png>)

### Hough Circle (Adapative Gaussian)

![logo](<_media/Advanced%20Function/Hough%20Circle/hough%20circle%20transform(adaptive%20gaussian).png>)

### Hough Circle (Adapative Mean)

![logo](<_media/Advanced%20Function/Hough%20Circle/hough%20circle%20transform(adaptive%20mean).png>)

### Hough Circle (Binary)

![logo](<_media/Advanced%20Function/Hough%20Circle/hough%20circle%20transform(binary).png>)

### Hough Circle (Binary_Inv)

Similar to binary thresholding but inverted.
Pixels brighter than the threshold become black, and pixels darker than the threshold become white.

![logo](<_media/Advanced%20Function/Hough%20Circle/hough%20circle%20transform(binary_inv).png>)

### Hough Circle (Otsu)

Automatically finds the best threshold value based on image statistics.
Separates objects from the background by minimizing pixel intensity variations.

![logo](<_media/Advanced%20Function/Hough%20Circle/hough%20circle%20transform(otsu).png>)

### Hough Circle (Tozero)

Pixels brighter than the threshold remain unchanged.
Pixels darker than the threshold become completely black (0).

![logo](<_media/Advanced%20Function/Hough%20Circle/hough%20circle%20transform(tozero).png>)

### Hough Circle (Tozero_Inv)

Pixels brighter than the threshold become completely white (maxval).
Pixels darker than the threshold remain unchanged.

![logo](<_media/Advanced%20Function/Hough%20Circle/hough%20circle%20transform(tozero_inv).png>)

### Hough Circle (Triangle)

Automatically finds the best threshold value based on the image histogram.
Aims to maximize the separation between objects and the background.

![logo](<_media/Advanced%20Function/Hough%20Circle/hough%20circle%20transform(triangle).png>)

### Hough Circle (Trunc)

Pixels brighter than the threshold remain unchanged.
Pixels darker than the threshold become equal to the threshold value.

![logo](<_media/Advanced%20Function/Hough%20Circle/hough%20circletransform(trunc).png>)
