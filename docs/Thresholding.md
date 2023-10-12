# **Thresholding**

## Adaptive Thresholding

### Adaptive Thresholding(Mean)

For each pixel in the image, we look at the average brightness of its nearby pixels defined by a small window and If the pixel's brightness is higher than this average, it becomes white; otherwise, it becomes black

![logo](_media/Basic%20Function/Thresholding/adaptive(mean).png)

### Adaptive Thresholding(Gaussian)

It calculates the threshold using a weighted average.The center pixel in the window has the most influence and brighter pixels compared to this weighted average become white; darker pixels become black.

![logo](_media/Basic%20Function/Thresholding/adaptive(gaussian).png)
