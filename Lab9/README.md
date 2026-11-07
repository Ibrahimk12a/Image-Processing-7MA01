# Lab 9: Morphological Operations

In this lab, I used Python and OpenCV to apply different morphological image processing techniques to a billiard balls image. I also investigated how changing the structuring element shapes and kernel sizes affects the processed images.

### 1. Apply Morphological Operations
- Loaded the billiard balls image in grayscale, resized it, and converted it into an inverted binary image using Otsu's thresholding.
- Used **Erosion** to shrink the white foreground areas and thin out the inner numbers.
- Used **Dilation** to expand the foreground regions and merge the adjacent balls together.
- Applied **Opening** and **Closing** using a 5×5 kernel to smooth contours and fill small gaps.
- Displayed the original, binarized, and four morphological operation results side by side.

### 2. Experiment with Structuring Elements
- Applied erosion and dilation using three structuring element shapes: **Square**, **Cross**, and **Ellipse**.
- Tested each shape across three different kernel sizes: **3×3**, **5×5**, and **7×7**.
- Larger kernels produced stronger effects, with 7×7 erosion nearly erasing the numbers and 7×7 dilation heavily merging the balls.
- The **Square** kernel gave the sharpest, most aggressive changes, the **Cross** kernel had the mildest effect, and the **Ellipse** kernel best preserved the natural circular shape of the balls.

Overall, I learned how erosion, dilation, opening, and closing modify binary images and how the choice of structuring element shape and size controls the final result.
