# **Template Matching**

For searching and finding the location of a template image within a larger image

## TM_CCOEFF (Correlation Coefficient)

measures the correlation between the template and the image. The higher the correlation, the better the match.

![logo](_media/Advanced%20Function/TemplateMatching/)

## TM_CCOEFF_NORMED (Normalized Correlation Coefficient)

This is a normalized version of TM_CCOEFF. The correlation is adjusted to a scale between -1 and 1, making it easier to interpret the results

![logo](_media/Advanced%20Function/TemplateMatching/CCOEFF_NORMED.png)

## TM_CCORR_NORMED (Normalized Cross-Correlation)

This method measures the cross-correlation between the template and the image. A score of 1 indicates a perfect match.

![logo](_media/Advanced%20Function/TemplateMatching/)

## TM_SQDIFF (Square Difference)

calculates the squared difference between the template and the image. A lower score indicates a better match.

![logo](_media/Advanced%20Function/TemplateMatching/)

## TM_SQDIFF_NORMED (Normalized Square Difference)

This is a normalized version of TM_SQDIFF. The squared difference is adjusted to a scale between 0 and 1, making it easier to interpret the results.

![logo](_media/Advanced%20Function/TemplateMatching/)
