# Cat Recognition System with Color-based Image Processing

In everyday life, the application of image processing techniques can be applied in various ways.
One of the information in the image that can be used inprocessing is color. An object can be recognized
by paying attention to the color of the object. In application, the objects that are recognized can vary, for example
is animal recognition. Cat is one of the objects that can be recognized by utilizing color-based image processing.

Method: 
- create simple color database consisting mean RGB colors of cat's segmented image

Recognition steps:
1. Edge detection (Canny) to detect cat body's egdes
2. Image segmentation using drawContour (openCV) + bitwise AND
3. Calculate mean RGB for the segmented area
4. Color matching using euclidean distance of mean RGB with cats in the database



https://informatika.stei.itb.ac.id/~rinaldi.munir/Citra/2021-2022/Makalah/Makalah_IF4073_Citra_2022%20(9).pdf
