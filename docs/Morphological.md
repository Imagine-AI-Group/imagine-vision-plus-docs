# **Morphological**

## **Black Hat**

Modifies the shape and size of objects in an image by highlighting the dark regions that are smaller than the structuring element and seen as a filter that enhances the contrast of an image.

### **Black Hat(Border Default)**

Synonymous with BORDER_REFLECT_101 and commonly used as the default for border handling during the black hat transform

![logo](<_media/Advanced%20Function/Morphological/black%20hat/blackhat(border_default).png>)

### Black Hat(Border Reflect)

Mirrors border pixels across the image's boundary and preserves symmetry in the black hat transform result.

![logo](<_media/Advanced%20Function/Morphological/black%20hat/blackhat(border_reflect).png>)

### Black Hat(Border Reflect101)

Similar to BORDER_REFLECT, it creates a symmetrical reflection pattern at the image's borders during the black hat transform.

![logo](<_media/Advanced%20Function/Morphological/black%20hat/blackhat(border_reflect101).png>)

### Black Hat(Border Constant)

Adds a continuous border with a constant value "i" to the image and border pixels are set to this constant, not affecting the black hat calculation.

![logo](<_media/Advanced%20Function/Morphological/black%20hat/blackhat(border_constant).png>)

### Black Hat(Border Isolated)

Isolates the black hat transform within the specified region of interest (ROI) and prevents influence from and use of information outside the ROI's border.

![logo](<_media/Advanced%20Function/Morphological/black%20hat/blackhat(border_isolated).png>)

### Black Hat(Border Reflect 101)

Equivalent to BORDER_REFLECT_101, maintaining a consistent symmetrical reflection pattern during the black hat transform.

![logo](<_media/Advanced%20Function/Morphological/black%20hat/blackhat(border_reflect_101).png>)

### Black Hat(Border Replicate)

Extends the image's border by copying the nearest edge pixels and helps maintain image content near borders during black hat calculation.

![logo](<_media/Advanced%20Function/Morphological/black%20hat/blackhat(border_replicate).png>)

## **Closing**

Use to smooth the contours of objects, eliminate small holes, and connect disjointed parts and useful for noise removal, edge detection, and object recognition

### Closing (Border Constant)

It adds a continuous border with a constant value "i" to the image during opening.
The border pixels are set to this constant and don't affect the opening process

![logo](<_media/Advanced%20Function/Morphological/closing/closing(border_constant).png>)

### Closing(Border Reflect)

Border pixels are mirrored across the image's boundary during opening and this maintains symmetry at the image's edges.

![logo](<_media/Advanced%20Function/Morphological/closing/closing(border_reflect).png>)

### Closing(Border Reflect101)

Essentially the same as BORDER_REFLECT_101, maintaining a consistent symmetrical reflection pattern during opening.

![logo](<_media/Advanced%20Function/Morphological/closing/closing(border_reflect101).png>)

### Closing(Border Default)

It's also equivalent to BORDER_REFLECT_101 and is commonly used as the default behavior for border handling during opening.

![logo](<_media/Advanced%20Function/Morphological/closing/closing(border_default).png>)

### Closing(Border Reflect 101)

Similar to BORDER_REFLECT, it creates a symmetrical reflection pattern at the image's borders during opening and it has unique border pixel values

![logo](<_media/Advanced%20Function/Morphological/closing/closing(border_reflect_101).png>)

### Closing(Border Replicate)

This mode extends the image's border by copying the nearest edge pixels and it ensures that the edge values are extended into the border region during opening.

![logo](<_media/Advanced%20Function/Morphological/closing/closing(border_replicate).png>)

### Closing(Border Isolated)

In this mode, opening only operates within the specified region of interest (ROI) and ignores or isolates the image's border, ensuring it doesn't influence the opening process outside the ROI

![logo](<_media/Advanced%20Function/Morphological/closing/closing(border_isolated).png>)

## **Dilation**

To apply a morphological operation to an image that enlarges the size of the foreground object and sliding a structuring element, such as a circle or a square, over the image and replacing each pixel with the maximum value of its neighbors that are covered by the structuring element

### Dilation(Border Reflect)

Border pixels are mirrored across the image boundary and this creates a symmetrical reflection pattern at the image's edges.

![logo](<_media/Advanced%20Function/Morphological/dilaton/dilaton(border_reflect).png>)

### Dilation(Border Constant)

It pads the image's border with a constant value, "i," during dilation and border pixels are set to this constant, ensuring they don't affect dilation

![logo](<_media/Advanced%20Function/Morphological/dilaton/dilaton(border_constant).png>)

### Dilation(Border Default)

Also the same as BORDER_REFLECT_101, often used as a default

![logo](<_media/Advanced%20Function/Morphological/dilaton/dilaton(border_default).png>)

### Dilation(Border Isolated)

Operates only within the specified region of interest and it doesn't consider or extend beyond this region

![logo](<_media/Advanced%20Function/Morphological/dilaton/dilaton(border_isolated).png>)

### Dilation(Border Reflect101)

Border pixels are mirrored across the image boundary and this creates a symmetrical reflection pattern at the image's edges

![logo](<_media/Advanced%20Function/Morphological/dilaton/dilaton(border_reflect101).png>)

### Dilation(Border Reflect 101)

Similar to BORDER_REFLECT but with a unique reflection pattern and maintains symmetry at the image's borders

![logo](<_media/Advanced%20Function/Morphological/dilaton/dilaton(border_reflect_101).png>)

### Dilation(Border Replicate)

It extends the image's border by copying the nearest edge pixels and the Border Replicates the values from the closest edge pixels

![logo](<_media/Advanced%20Function/Morphological/dilaton/dilaton(border_replicate).png>)

## **Erosion**

Apply a morphological operation to an image that reduces the size of the foreground object and sliding a structuring element, such as a circle or a square, over the image and replacing each pixel with the minimum value of its neighbors that are covered by the structuring element

### Erosion(Border Isolated)

This option indicates that you should not consider pixels outside the Region of Interest (ROI) when performing the erosion operation. It helps maintain the integrity of the ROI without affecting the surrounding area

![logo](<_media/Advanced%20Function/Morphological/erosian/erosian(border_isolated).png>)

### Erosion(Border Constant)

The border is filled with a constant value specified by 'i'. The image remains unchanged outside the specified region

![logo](<_media/Advanced%20Function/Morphological/erosian/erosian(border_constant).png>)

### Erosion(Border Default)

This is the same as BORDER_REFLECT_101, serving as a default option for border handling

![logo](<_media/Advanced%20Function/Morphological/erosian/erosian(border_default).png>)

### Erosion(Border Reflect)

The border pixels are mirrored. It reflects the image as if it were flipped horizontally, creating a border that mirrors the content from the center outwards

![logo](<_media/Advanced%20Function/Morphological/erosian/erosian(border_reflect).png>)

### Erosion(Border Reflect101)

This is the same as BORDER_REFLECT_101, so it reflects the border content in a similar way

![logo](<_media/Advanced%20Function/Morphological/erosian/erosian(border_reflect101).png>)

### Erosion(Border Reflect 101)

Similar to BORDER_REFLECT but with slight differences in how the border is calculated. It also mirrors the border content

![logo](<_media/Advanced%20Function/Morphological/erosian/erosian(border_reflect_101).png>)

### Erosion(Border Replicate)

The border is replicated by copying the nearest pixel value. It creates a border that appears as if the outer pixels are mirrored, creating a constant border of 'a' on the left and 'h' on the right

![logo](<_media/Advanced%20Function/Morphological/erosian/erosian(border_replicate).png>)

## **Morphological Gradient**

Type of morphological operation that modifies the shape and size of objects in an image by subtracting the eroded image from the dilated image and to find the outline of an object

### Morphological Gradient(Border Constant)

It adds a continuous border with a constant value "i" to the image during the gradient calculation and Border pixels are set to this constant and don't affect the gradient

![logo](<_media/Advanced%20Function/Morphological/morphological%20gradient/gradient(border_constant).png>)

### Morphological Gradient(Border Default)

It's also equivalent to BORDER_REFLECT_101 and serves as a commonly used default for border handling during the morphological gradient operation

![logo](<_media/Advanced%20Function/Morphological/morphological%20gradient/gradient(border_default).png>)

### Morphological Gradient(Border Isolated)

In this mode, the gradient calculation is isolated to the specified region of interest (ROI)and it disregards information from the image's border, ensuring it doesn't affect the gradient outside the ROI

![logo](<_media/Advanced%20Function/Morphological/morphological%20gradient/gradient(border_isolated).png>)

### Morphological Gradient(Border Reflect)

Border pixels are mirrored across the image's boundary during gradient calculation.
This preserves symmetry in the gradient result

![logo](<_media/Advanced%20Function/Morphological/morphological%20gradient/gradient(border_reflect).png>)

### Morphological Gradient(Border Reflect 101)

Similar to BORDER_REFLECT, it creates a symmetrical reflection pattern at the image's borders during the gradient operation and it has unique border pixel values

![logo](<_media/Advanced%20Function/Morphological/morphological%20gradient/gradient(border_reflect_101).png>)

### Morphological Gradient(Border Reflect101)

Essentially the same as BORDER_REFLECT_101, maintaining a consistent symmetrical reflection pattern during the gradient

![logo](<_media/Advanced%20Function/Morphological/morphological%20gradient/gradient(border_reflect101).png>)

### Morphological Gradient(Border Replicate)

This mode extends the image's border by copying the nearest edge pixels and it maintains the image's content near the borders while calculating the gradient
![logo](<_media/Advanced%20Function/Morphological/morphological%20gradient/gradient(border_replicate).png>)

## **Opening**

Useful for noise removal, background subtraction, and used to smooth the contours of objects, fill small holes, and eliminate small protrusions

### Opening(Border Constant)

Adds a continuous border with a constant value "i" to the image and border pixels are set to this constant, not affecting the opening process

![logo](<_media/Advanced%20Function/Morphological/Opening/opening(border_constant).png>)

### Opening(Border Default)

Synonymous with BORDER_REFLECT_101 and commonly used as the default for border handling during opening

![logo](<_media/Advanced%20Function/Morphological/Opening/opening(border_default).png>)

### Opening(Border Isolated)

Isolates the opening operation within the specified region of interest (ROI) and prevents influence from and use of information outside the ROI's border

![logo](<_media/Advanced%20Function/Morphological/Opening/opening(border_isolated).png>)

### Opening(Border Reflect)

Mirrors border pixels across the image's boundary and preserves symmetry in the opening result.

![logo](<_media/Advanced%20Function/Morphological/opening/opening(border_reflect).png>)

### Opening(Border Reflect101)

Equivalent to BORDER_REFLECT_101, maintaining a consistent symmetrical reflection pattern during opening

![logo](<_media/Advanced%20Function/Morphological/Opening/opening(border_reflect101).png>)

### Opening(Border Reflect 101)

Similar to BORDER_REFLECT, it creates a symmetrical reflection pattern at the image's borders during opening and has unique border pixel values

![logo](<_media/Advanced%20Function/Morphological/Opening/opening(border_reflect_101).png>)

### Opening(Border Replicate)

Extends the image's border by copying the nearest edge pixels and helps maintain image content near borders during opening

![logo](<_media/Advanced%20Function/Morphological/Opening/opening(border_replicate).png>)

## **TopHat**

Modifies the shape and size of objects in an image by highlighting the bright regions that are smaller than the structuring element and seen as a filter that enhances the contrast of an image.

### TopHat(Border Default)

Synonymous with BORDER_REFLECT_101 and commonly used as the default for border handling during the top hat operation

![logo](<_media/Advanced%20Function/Morphological/top%20hat/tophat(border_default).png>)

### TopHat(Border Isolated)

Isolates the gradient calculation within the specified region of interest (ROI) and prevents influence from and use of information outside the ROI's border
![logo](<_media/Advanced%20Function/Morphological/top%20hat/tophat(border_isolated).png>)

### TopHat(Border Constant)

Adds a continuous border with a constant value "i" to the image and border pixels are set to this constant, not affecting the gradient

![logo](<_media/Advanced%20Function/Morphological/top%20hat/tophat(border_constant).png>)

### TopHat(Border Reflect)

Mirrors border pixels across the image's boundary and preserves symmetry in the gradient result

![logo](<_media/Advanced%20Function/Morphological/top%20hat/tophat(border_reflect).png>)

### TopHat(Border Replicate)

Extends the image's border by copying the nearest edge pixels and helps maintain image content near borders during gradient calculation

![logo](<_media/Advanced%20Function/Morphological/top%20hat/tophat(border_replicate).png>)

### TopHat(Border Reflect101)

Equivalent to BORDER_REFLECT_101, maintaining a consistent symmetrical reflection pattern during the top hat operation

![logo](<_media/Advanced%20Function/Morphological/top%20hat/tophat(border_reflect101).png>)

### TopHat(Border Reflect 101)

Similar to BORDER_REFLECT, it creates a symmetrical reflection pattern at the image's borders during the top hat operation and has unique border pixel values

![logo](<_media/Advanced%20Function/Morphological/top%20hat/tophat(border_reflect_101).png>)
