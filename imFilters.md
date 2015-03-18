# Introduction #

The **imFilters** module contains several image filters not necessarily included in Image Processing Toolbox.

# Functions #
### Generic filters ###
  * **imGaussFilter**       - Apply gaussian filter to an image, using separability
  * **imGradient**          - Compute gradient magnitude in a grayscale image
  * **imMorphoGradient**    - Morphological gradient of an image
  * **imMorphoLaplacian**   - Morphological laplacian of an image
  * **imImposedWatershed**  - Compute watershed after imposition of extended minima
  * **imrecerode**          - Perform a morphological reconstruction by erosion
  * **imHConcave**          - H-concave transformation of an image
  * **imHConvex**           - H-convex transformation of an image
  * **imdirfilter**         - Apply and combine several directional filters
  * **imMeanFilter**        - Compute mean value in the neighboorhood of each pixel
  * **imMedianFilter**      - Compute median value in the neighboorhood of each pixel
  * **imNeighborhood**      - Return the neighborhood of a given pixel

### Color and gray-scale conversions ###
  * **imOverlay**           - Add colored markers to an image (2D or 3D, grayscale or color)
  * **imAdjustDynamic**     - Rescale gray levels of image to get better dynamic
  * **imMergeBands**        - Merge 3 bands to create a 2D or 3D color image
  * **imSplitBands**        - Split the 3 bands of a 2D or 3D image
  * **double2rgb**          - Create a RGB image from double values
  * **angle2rgb**           - Convert an image of angles to color image

Back to [home](Home.md)