# Lab 6: Frequency Domain

In this lab, I worked on image filtering in the frequency domain using Fast Fourier Transform (FFT).

## What I did:
* **Sobel Filters:** I applied Sobel X and Sobel Y filters in the frequency domain to detect edges in the cameraman image. I used FFT to transform the image, multiplied it with the centered Sobel kernels, and then used Inverse FFT (IFFT) to get the final result.

## Libraries used:
* OpenCV
* NumPy
* Matplotlib
