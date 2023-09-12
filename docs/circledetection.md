# **CircleDetection**

## Hough Circle


to detect circles in an image, even if they are partially occluded or distorted by noise or perspective and transforming the image space into a parameter space, where each point represents a possible circle in the original image

![logo](_media/AdvanceFunction/HoughCircle/hough%20circle%20transform.png)

### Hough Circle (blur)

![logo](<_media/AdvanceFunction/HoughCircle/hough%20circle%20transform(apply%20blur).png>)

### Hough Circle (adapative gaussian)

![logo](<_media/AdvanceFunction/HoughCircle/hough%20circle%20transform(adaptive%20gaussian).png>)

### Hough Circle (adapative mean)

![logo](<_media/AdvanceFunction/HoughCircle/hough%20circle%20transform(adaptive%20mean).png>)

### Hough Circle (binary)

![logo](<_media/AdvanceFunction/HoughCircle/hough%20circle%20transform(binary).png>)

### Hough Circle (binary_Inv)

Similar to binary thresholding but inverted.
Pixels brighter than the threshold become black, and pixels darker than the threshold become white.

![logo](<_media/AdvanceFunction/HoughCircle/hough%20circle%20transform(binary_inv).png>)

### Hough Circle (otsu)

Automatically finds the best threshold value based on image statistics.
Separates objects from the background by minimizing pixel intensity variations.

![logo](<_media/AdvanceFunction/HoughCircle/hough%20circle%20transform(otsu).png>)

### Hough Circle (tozero)

Pixels brighter than the threshold remain unchanged.
Pixels darker than the threshold become completely black (0).

![logo](<_media/AdvanceFunction/HoughCircle/hough%20circle%20transform(tozero).png>)

### Hough Circle (tozero_Inv)

Pixels brighter than the threshold become completely white (maxval).
Pixels darker than the threshold remain unchanged.

![logo](<_media/AdvanceFunction/HoughCircle/hough%20circle%20transform(tozero_Inv).png>)

### Hough Circle (triangle)

Automatically finds the best threshold value based on the image histogram.
Aims to maximize the separation between objects and the background.

![logo](<_media/AdvanceFunction/HoughCircle/hough%20circle%20transform(triangle).png>)

### Hough Circle (trunc)

Pixels brighter than the threshold remain unchanged.
Pixels darker than the threshold become equal to the threshold value.

![logo](<_media/AdvanceFunction/HoughCircle/hough%20circle%20transform(trunc).png>)
