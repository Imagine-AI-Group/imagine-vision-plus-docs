# **Thresholding**

## adaptive thresholding

### adaptive thresholding(mean)

For each pixel in the image, we look at the average brightness of its nearby pixels defined by a small window and If the pixel's brightness is higher than this average, it becomes white; otherwise, it becomes black

![logo](_media/BasicFunction/Thresholding/adaptive%20mean.png)


### adaptive thresholding(gaussian)

it calculates the threshold using a weighted average.The center pixel in the window has the most influence and brighter pixels compared to this weighted average become white; darker pixels become black.

![logo](_media/BasicFunction/Thresholding/adaptive%20gaussian.png)