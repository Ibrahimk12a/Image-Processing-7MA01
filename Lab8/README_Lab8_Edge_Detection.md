# Lab 8: Edge Detection

In this lab, I used Python and OpenCV to apply different edge detection methods to a butterfly image. I also compared how changing the Canny thresholds affects the detected edges.

### 1. Apply Edge Detection Methods
- Converted the butterfly image to grayscale and applied Gaussian blur.
- Used **Sobel** and **Prewitt** to detect edges in different directions.
- Used **Canny** to detect clear and thin edges.
- Displayed the original image and the three edge detection results.

### 2. Investigate the Effect of Canny Thresholds
- Applied Canny using three threshold pairs: **(30, 90)**, **(50, 150)**, and **(100, 200)**.
- Displayed the three results side by side to compare them.
- Lower thresholds detected more details and background noise, while higher thresholds detected fewer edges.
- The middle thresholds provided a better balance between details and noise.

Overall, I learned how Sobel, Prewitt, and Canny detect image edges and how Canny thresholds change the results.
