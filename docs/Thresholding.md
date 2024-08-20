# **Thresholding**

## Simple Thresholding

### Binary

Binary thresholding is particularly useful in image processing tasks such as edge detection, segmentation, and object detection where we need to separate out regions of an image of interest. It helps in reducing the complexity of the image, making it easier to analyze and process.

![logo](_media/Basic%20Function/Thresholding/SimpleThresholding/Binary.png)

### Binary Inverted

Binary inversion is used to invert the pixel values of an image. In the context of a binary image (an image with only two colors, typically black and white), this operation will convert white pixels to black, and black pixels to white. This can be useful in various image processing tasks such as highlighting specific objects in an image or improving the contrast for better visibility

![logo](_media/Basic%20Function/Thresholding/SimpleThresholding/BinaryInverted.png)

### Triangle

For many reasons, like image processing, computer vision tasks, or even making graphics and visualizations, these methods can be used to draw triangles on images. That is, triangles can be used to show areas of interest or to help find features in computer vision, for instance. One more thing they can be used for is drawing shapes for graphical overlays or making masks for image segmentation. For example, triangles can be used to make meshes and rebuild 3D models when they are turned into simple polygons.

![logo](_media/Basic%20Function/Thresholding/SimpleThresholding/Triangle.png)

### Truncate

When working with images, the truncation operation can help when you need to keep the image's intensity within a certain range. This can help make the image more contrasty and less affected by differences in lighting. It can also help when you want to separate the foreground and background of an image during thresholding. This can be very helpful in computer vision, medical imaging, object detection and recognition, and finding things in images.

![logo](_media/Basic%20Function/Thresholding/SimpleThresholding/Truncate.png)

### Tozero

This operation effectively gets rid of darker parts of the image to make brighter parts stand out. It can help bring out certain details or make visual information easier to understand.

- The new pixel value stays the same if the pixel value is higher than the threshold.
- New pixel value is set to 0 if the value of the pixel is less than or equal to the threshold.

![logo](_media/Basic%20Function/Thresholding/SimpleThresholding/Tozero.png)

### Tozero Inverted

If the original value of the pixel is greater than the threshold, this operation sets the value of the pixel to 0. If not, the original pixel value is kept. This thresholding method can be useful for many things, like improving image features, separating objects, or making image content easier to understand. By zeroing out some pixel values and leaving others alone, we can highlight certain areas of interest while hiding others.

![logo](_media/Basic%20Function/Thresholding/SimpleThresholding/TozeroInverted.png)

## Adaptive Thresholding

### Mean

In order to separate objects from the backdrop in an image, a technique called Mean is applied. When the lighting is inconsistent or uneven throughout an image, this technique is especially helpful.

- Outperforming global thresholding techniques like Otsu and basic thresholding, it can yield superior segmentation outcomes.
- When the photograph contains different lighting conditions, it can be especially helpful.
- A dedicated deep learning model for segmentation can be trained without the need for costly computing resources and a lengthy training period.

![logo](_media/Basic%20Function/Thresholding/AdaptiveThresholding/Mean.png)

### Gaussian

For Gaussian adaptive thresholding, a Gaussian-weighted sum of the neighborhood values is used to determine the threshold value for each pixel. In other words, the threshold value fluctuates throughout the image and is not a global constant. When an image contains various illumination conditions in different places, the Adaptive Thresholding Gaussian method proves to be quite helpful.

- Robustness to illumination Variations: It operates more skillfully on photographs with uneven or changing illumination.
- Better Object Detection: More accurate separation of objects of interest from the background.
- Enhanced Image Segmentation: This technique makes it easier to recognize specific areas or objects in images.

![logo](_media/Basic%20Function/Thresholding/AdaptiveThresholding/Gaussian.png)

## Otsu's Binarization

to automatically figure out the best threshold value for turning a grayscale image into a black-and-white image.

- Image segmentation: separating image components that are not part of the background.
- Thresholding: Finding the best threshold automatically, without having to tune it by hand.
- Preprocessing: Improving the quality of an image so that it can be analyzed further (for example, to find objects or edges).

![logo](_media/Basic%20Function/Thresholding/OtsuThresholding/Otsu.png)
