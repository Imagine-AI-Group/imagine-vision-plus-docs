# **Color Filter**

## BGR Filter

For changing colors into another color space, like Gray or HSV to find important information from image  (like finding edges and corners).

- Upper & Lower is a parameter range for image processing
- BGR (Blue, Green, Red)

![logo](_media/Basic%20Function/ColorFilter/BGR_Filter.png)

## HSV Filter

HSV is an alternative color representation that separates color information for change color information into three components:

- Upper & Lower is a parameter range for image processing
- Hue: Shows the color that is prevalent (e.g., red, green, blue).
- Saturation: Indicates how pure or intense a color is.
- Value: Indicates how brilliant a color is.

![logo](_media/Basic%20Function/ColorFilter/HSV_Filter.png)

## Convert Color

Color segmentation is a commonly used technique in computer vision to identify particular items or regions based on their color. It enables us to isolate or separate particular colors from an image, highlighting them for additional examination.

#### 1. BGR2BGRA

Image conversion from the BGR (Blue-Green-Red) color space to the BGRA (Blue-Green-Red-Alpha) is accomplished with the usage of BGR2BGRA. An alpha channel (A) is being added by BGRA for transparency.

- Applying transparency to photos (watermarks, for example).
- Antialiasing (producing images with soft edges).
- Blending together different transparent picture combinations.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGR2BGRA.png)

#### 2. BGR2GRAY

Image can be converted from the BGR (Blue-Green-Red) color system to grayscale using the BGR2GRAY tool. Grayscale images are frequently used for edge recognition, feature extraction, and other computer vision applications because they only have one channel, which represents the intensity or brightness of each pixel. Grayscale images further simplify visual information by removing color.

- reduce color in order to simplify the visual information in the image.
- commonly used for computer vision tasks such as feature extraction, edge detection, and more.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGR2GRAY.png)

#### 3. BGR2HLS

Use to converts the color space of a picture from BGR to HLS. People often need to do this conversion in order to do image processing tasks like object tracking, computer vision, and image analysis.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGR2HLS.png)

#### 4. BGR2HLS_FULL

It same as BGR2HLS but it will process the image in full range.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGR2HLS_FULL.png)

#### 5. BGR2HSV

used to extract a colored object out of a video or image. For instance, to get a blue object out of an image, you can change the color space from BGR to HSV and then look for a range of blue colors in the HSV image.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGR2HSV.png)

#### 6. BGR2HSV_FULL

It same as BGR2HSV but it will process the image in full range.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGR2HSV_FULL.png)

#### 7. BGR2LAB

It is useful for many image processing tasks because it is very close to how people see colors. This can be especially helpful in tasks like tracking objects, where color-based segmentation in LAB color space may work better than in BGR color space.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGR2LAB.png)

#### 8. BGR2LUV

useful for image processing tasks that benefit from the LUV color space's properties. Computer vision, for instance, uses the LUV color space a lot because it is more like how humans see colors.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGR2LUV.png)

#### 9. BGR2RGB

It changes the order of the blue and red channels, which helps people see and understand the picture better. Keep in mind that OpenCV's native format is BGR, while RGB is what most people use.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGR2RGB.png)

#### 10. BGR2RGBA

The default color space in OpenCV is BGR, which is just RGB with the bytes switched around. The RGBA color space is like RGB, but it has an extra channel called alpha that shows how opaque the pixels are. When you need to use APIs or libraries that need image data in RGBA format, this conversion can help.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGR2RGBA.png)

#### 11. BGR2XYZ

The conversion from BGR to XYZ is a linear transformation. You can change the BGR color space to the XYZ color space by multiplying two matrices. When working with images, this conversion is helpful because it lets you work with the XYZ color space instead of a different color space for each light source.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGR2XYZ.png)

#### 12. BGR2YCR_CB

Numerous video and image compression algorithms use this color space because it separates the image's luma (details) and chroma (color) data. Although the human eye is more sensitive to changes in luminance than color, this makes compression work well.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGR2YCR_CB.png)

#### 13. BGR2YUV

The YUV color encoding system is most often used for analog TV. When it encodes a color image or video, it takes into account how people see colors, so chrominance data can have a smaller bandwidth than luminance data. That's because seeing color isn't as accurate as seeing light, which lets us get higher compression rates.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGR2YUV.png)

#### 14. BGRA2BGR

It changes an image from BGRA color space (Alpha, Green, Red, and Blue) to BGR color space (the three primary colors). Especially helpful when you need to get rid of the alpha channel from a BGRA image.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGRA2BGR.png)

#### 15. BGRA2GRAY

This grayscale image can be used for many things, like image processing tasks that don't need color information or tasks that need less complicated computations.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGRA2GRAY.png)

#### 16. BGRA2RGB

BGRA2RGB, it takes out the Alpha channel from the image, changing it from a BGRA image with 4 channels to an RGB image with 3 channels. A lot of the time, this function is used to process or show an image in RGB format, which is a common color space for image processing.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGRA2RGB.png)

#### 17. BGRA2RGBA

If an image is stored in BGRA format (which is common in some image libraries and software), but you need to work with it in RGBA format (which is common in other libraries and standards), this conversion can help.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/BGRA2RGBA.png)

#### 18. GRAY2BGR

This function takes in a grayscale image and turns it into a color image by making all three channels have the same grayscale values. This function comes in handy when you need to use functions or libraries that need color images as input, even if the images themselves are grayscale.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/GRAY2BGR.png)

#### 19. GRAY2BGRA

If the image you want to use is in grayscale but the function you need to use it with needs a BGRA image, this function can help. It lets you change a grayscale picture to a format that works without losing any data.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/GRAY2BGRA.png)

#### 20. GRAY2RGB

The GRAY2RGB function is essential for transforming a grayscale picture into an RGB (color) one. In grayscale photographs, each pixel value represents the brightness or intensity of that particular pixel. Pixel intensities are represented using a single channel. Usually shown in grayscale, these photographs are devoid of color information.

- Assume you use GRAY2RGB to convert an image that is initially in grayscale to RGB. The pixel values stay true to the original grayscale picture. Because the values for B, G, and R are the same, even though it has three channels, it looks grey to our eyes.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/GRAY2RGB.png)

#### 21. GRAY2RGBA

To use the grayscale image in a situation that needs RGBA images or to show it. For instance, some graphic libraries or image viewers might need images to be in RGBA format. If you change the grayscale picture to RGBA, you can use these viewers or libraries to work with it.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/GRAY2RGBA.png)

#### 22. HLS2BGR

Sometimes working in the HLS space is easier or gives better results when processing images, but the finished image needs to be saved or processed in the standard BGR format. It can be applied to a number of computer vision applications, including tracking, object detection, and image segmentation.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/HLS2BGR.png)

#### 23. HLS2BGR_FULL

It same as HLS2BGR but it will process the image in full range.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/HLS2BGR_FULL.png)

#### 24. HLS2RGB

use the RGB color space to change a color or image from the HLS color space. Since digital images are more common and easier to understand in the RGB color space, this conversion can help when you need to show or work with images that were saved in the HLS color space.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/HLS2RGB.png)

#### 25. HSV2RGB_FULL

It same as HLS2BGR but it will process the image in full range.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/HSV2RGB_FULL.png)

#### 26. LAB2BGR

It's useful to be able to convert from LAB to BGR (or RGB) when working with images because the LAB color space is more consistent with how people see colors. However, the final image needs to be stored or shown in the standard RGB or BGR color spaces.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/LAB2BGR.png)

#### 27. LAB2LBGR

This function takes an image from the LAB color space and changes it to a modified BGR color space. This can be helpful when working with images and you need to change both the lightness and color information at the same time.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/LAB2LBGR.png)

#### 28. LAB2LRGB

This function takes an image from the LAB color space and changes it to a modified RGB color space. This can be helpful when working with images and you need to change both the lightness and color information at the same time.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/LAB2LRGB.png)

#### 29. LAB2RGB

When processing images, changing them from the LAB color space to the RGB color space can be helpful because the LAB color space is better for processing but the result needs to be shown in the RGB color space, which is what most displays use.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/LAB2RGB.png)

#### 30. LBGR2LAB

For color correction and adjustment. It also helps divide images into parts based on how different colors look to different people. The LAB space is better for tasks where visual quality is important because it matches how people see differences in colors better.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/LBGR2LAB.png)

#### 31. LBGR2LUV

For a variety of computer vision applications, including skin detection, color-based segmentation, and picture augmentation, the LUV color space is helpful. Compared to BGR, it offers a more perceptually relevant representation of color.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/LBGR2LUV.png)

#### 32. LRGB2LAB

To finds application in computer vision tasks like color-based object detection, image enhancement, and image segmentation.
It gives color representation that is more perceptually significant than RGB.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/LRGB2LAB.png)

#### 33. LRGB2LUV

For a variety of computer vision applications, including skin detection, color-based segmentation, and picture augmentation, the LUV color space is helpful. Compared to RGB, it offers a more perceptually meaningful representation of color.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/LRGB2LUV.png)

#### 34. LUV2BGR

For a variety of computer vision applications, including skin detection, color-based segmentation, and picture augmentation, the LUV color space is helpful. You can see the processed image in a more recognizable color representation by converting it back to BGR.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/LUV2BGR.png)

#### 35. LUV2LBGR

The LUV color space is useful for analyzing or changing images, but the BGR color space is needed for showing or working with the result. When working on skin detection algorithms, for instance, you might change a LUV image to a BGR image to see it better or do more research on it.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/LUV2LBGR.png)

#### 36. LUV2LRGB

To change an image's colors while maintaining the impression of intensity. It also enhancing specific color attributes is just one of the many image processing tasks for which it might be helpful. You can extract pertinent information for particular tasks in computer vision applications by converting between color spaces.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/LUV2LRGB.png)

#### 37. LUV2RGB

To change hue, saturation, and brightness, among other color attributes. It's frequently utilized for tasks related to computer vision, such as feature extraction, segmentation, and object detection. It also used to boost particular color components or correct color imbalances.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/LUV2RGB.png)

#### 38. RGB2BGR

This parameter changes an RGB image to a BGR image. It helps when you need to change something about an image in OpenCV and then use tools or libraries that expect the RGB format to show it.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/RGB2BGR.png)

#### 39. RGBA2BGRA

helpful when working with a system or library that needs the channel order to be in BGRA format. Changing your RGBA images to BGRA will make sure they work on these systems.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/RGBA2BGRA.png)

#### 40. RGBA2GRAY

Often used in computer vision tasks that don't need color information, like recognizing images, tracking them, separating them into groups, and more. In some cases, this conversion can help make computations easier and faster.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/RGBA2GRAY.png)

#### 41. RGBA2RGB

The RGBA2RGB color conversion code eliminates the alpha channel from an image with transparency (RGBA) to create a standard RGB image. It can help for removing transparency.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/RGBA2RGB.png)

#### 42. XYZ2BGR

You can use XYZ2BGR to change an image from the XYZ color space to the BGR color space. The image could have been taken with a camera or generated from other sources. This conversion is needed in order to process, display, or analyze the image further. For instance, if you want to show an XYZ picture on a computer screen, you must first change it to BGR.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/XYZ2BGR.png)

#### 43. XYZ2RGB

This change is important because it lets you accurately show and change colors in images, no matter what device was used to take or show the picture. This is especially helpful for tasks like color-based segmentation, color balancing, and color histogram equalization when working with images.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/XYZ2RGB.png)

#### 44. YCR_CB2BGR

This function changes an image from the YCrCb color space to the BGR color space, which is more commonly used in image processing. The conversion makes the contrast better and helps you tell apart important parts of an image.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/YCR_CB2BGR.png)

#### 45. YCR_CB2RGB

For many image processing tasks, it's necessary to be able to switch between color spaces. For instance, you could change the color balance or fix any color distortions. YCrCb is also often used in video codecs because it compresses chrominance information better than RGB. But for display purposes, we change it back to RGB.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/YCR_CB2RGB.png)

#### 46. YUV2BGR

In image processing, the YUV color space is useful because it is also used for video coding. It is a part of the JPEG, MPEG, and other standards for encoding video in real time. In situations where color information is important, changing YUV to BGR can be useful.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/YUV2BGR.png)

#### 47. YUV2RGB

color images and video frames are compressed with this. In order to show pictures and videos on digital devices like TVs, monitors, and cameras, you need to change the color space from YUV to RGB. In order to process images and videos for display, this conversion is often needed.

![logo](_media/Basic%20Function/ColorFilter/ColorConversion/YUV2RGB.png)
