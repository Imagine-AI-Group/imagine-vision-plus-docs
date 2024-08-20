# **Feature Matching**

## Brute-Force Matching

The Brute-Force matcher takes the descriptor of one feature in the first set (image) and matches it with all other features in the second set (image).

![logo](_media/Advanced%20Function/FeatureMatching/BruteForceMatching/BruteForceMatching.png)

## AKAZE

#### DIFF_PM_G1

DIFF_PM_G1 is a type of Perona-Malik diffusivity function that favors high contrast edges over low contrast ones. This can help to enhance the visibility of edges in the image, which can be beneficial for feature detection.

![logo](_media/Advanced%20Function/FeatureMatching/AKAZE/DIFF_PM_G1.png)

#### DIFF_PM_G2

DIFF_PM_G2 is another type of Perona-Malik diffusivity function that is similar to DIFF_PM_G1, but it favors wide areas over smaller ones.

![logo](_media/Advanced%20Function/FeatureMatching/AKAZE/DIFF_PM_GM2.png)

#### Diff_Weickert

Diff_Weickert is a non-linear diffusion method that keeps edges and tries to make edges in an image easier to see, which can help with feature detection.

![logo](_media/Advanced%20Function/FeatureMatching/AKAZE/Diff_Weickert.png)

#### Diff_Charbonnier

In statistics, Diff_Charbonnier is used. It is a strong function that keeps the edges of the image and lessens the effect of outliers in the data.

![logo](_media/Advanced%20Function/FeatureMatching/AKAZE/Diff_Charbonnier.png)
