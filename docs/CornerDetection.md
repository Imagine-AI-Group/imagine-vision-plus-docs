# **Corner Detection**

## Shi-Tomasi

Finds corners in the image, throws out any corners with a quality level below the one you choose, and then sorts the remaining corners from best to worst based on quality. It starts with the strongest corner and gets rid of all the corners nearby that are within the minimum distance.

- Input: The function takes a grayscale image as input.
- Number of Corners: You specify the number of corners you want to find.
- Quality Level: This is a value between 0-1, which denotes the minimum quality of corner below which everyone is rejected.
- Minimum Euclidean Distance: This is the minimum allowable distance between corners detected.

![logo](_media/Advanced%20Function/CornerDetection/ShitomasiCornerDetection.png)

## Harris

Detects corners in an image, which are areas where the brightness changes a lot from side to side.

- Block Size: This is the size of the area that is looked at for corner detection.
- K Size: This is the hole size for the Sobel derivative utilized.
- K value: This is the free parameter for the Harris detector in the equation

![logo](_media/Advanced%20Function/CornerDetection/HarrisCornerDetection.png)

## ORB

For quickly and reliably find and match features in images. It can be used for many things, such as finding objects, recognizing images, and even reconstructing 3D models.

- Keypoints: A keypoint is defined by its 2D location, size (based on the neighborhood's diameter), orientation, and a few other factors.
- Scale Factor: The scale factor tells you how much two levels are downscaled or upscaled. If the scale factor is 1.10, for instance, it means that every time you shrink the image by 10%.
- Pyramid Level: Images on the pyramid level are a quarter of the size of images on the larger level. The smallest size is 128 pixels. The level can get as high as the log-2 of the widest and tallest parts of the image.
- Edge Threshold: Any edges with intensity gradient more than maxVal are sure to be edges and those below minVal are sure to be non-edges
- Fast Threshold: The threshold is set to look at the intensity of a pixel to see if it is a corner. The threshold can be changed for different uses, but by default it is set to 20.

![logo](_media/Advanced%20Function/CornerDetection/ORBCornerDetection.png)
