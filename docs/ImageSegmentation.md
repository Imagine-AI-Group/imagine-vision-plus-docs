# **Image Segmentation**

## Image Segmentation with Watershed Algorithm

Uses some prior information or user input to guide the segmentation process and by marking some pixels as foreground or background, and using them as seeds for the flooding process. can produce accurate and robust segmentation results, but it may also suffer from over-segmentation or under-segmentation problems if the markers are not well-chosen or well-distributed

![logo](_media/Advanced%20Function/Image%20segmentation/watershed%20page.png)

## Step-by-step how to use watershed

### step 1 (thresholding)

1. Locate the "Threshold" input field, enter a value between 0 and 255, and press Enter.
2. Locate the "Maximum value" input field, enter a value between 0 and 255, and press Enter.
3. Choose a thresholding type from "ThresholdType 1" dropdown.
4. Choose a thresholding type from "ThresholdType 2" dropdown.

![logo](<_media/Advanced%20Function/Image%20segmentation/watershed%20thresholding(1).png>)

#### \*In thresholding we can't do otsu and triangle together

![logo](_media/Advanced%20Function/Image%20segmentation/wateshed%20fail.PNG)

### step 2 (noise removal)

1. Choose an option from the "morphological operation" dropdown.
2. Enter a numeric value in the "Kernel" input field.
3. Enter a numeric value in the "Anchor X" input field (between -1 and 210).
4. Enter a numeric value in the "Anchor Y" input field (between -1 and 210).
5. Enter a numeric value in the "Iterations" input field (between 0 and 255).
6. Select an option from the "Border Type" dropdown.

![logo](_media/Advanced%20Function/Image%20segmentation/watershed%20morph.png)

### (Sure Background and Foreground Area)

### step 3(dailation)

1. Enter a numeric value in the "Anchor X 1" input field (between -1 and 210).
2. Enter a numeric value in the "Anchor Y 1" input field (between -1 and 210).
3. Enter a numeric value in the "Iterations 1" input field (between 0 and 255).
4. Select an option from the "Border Type 1" dropdown.

![logo](_media/Advanced%20Function/Image%20segmentation/watershed%20dailation.png)

### step 4 (distance Transform)

1. Select an option from the "Distance Type" dropdown.
2. Select an option from the "Mask Size" dropdown.

![logo](_media/Advanced%20Function/Image%20segmentation/watershed%20dist.png)

### step 5

1. Enter a numeric value in the "Threshold" input field (between 0.00 and 0.99) the maximum value in the dist_transform image. The threshold value determines which pixels areconsidered as foreground (objects) and which are considered as background. Pixels with values greater than or equal to this threshold are considered as foreground.

2. Enter a numeric value in the "Maximum value" input field (between 0 and 255) indicating that they are part of the foreground or objects.

3. Select an option from the "Threshold Type" dropdown For example, you can use binary thresholding, where pixels above the threshold become 255 (foreground) and others become 0 (background).

![logo](<_media/Advanced%20Function/Image%20segmentation/watershed%20thresholding(2).png>)

### step 6

After entering values for the desired parameters in each step, locate the "Process" button.
Click on the "Process" button to submit the form and execute the Watershed function with the provided input values.
