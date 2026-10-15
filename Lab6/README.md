# Lab 6: Frequency Domain

In this lab, I worked on image filtering in the frequency domain using Fast Fourier Transform (FFT)[span_0](start_span)[span_0](end_span).

## What I did:
* **Sobel Filters:** I applied Sobel X and Sobel Y filters in the frequency domain to detect edges in the cameraman image[span_1](start_span)[span_1](end_span). I used FFT to transform the image, multiplied it with the centered Sobel kernels, and then used Inverse FFT (IFFT) to get the final result[span_2](start_span)[span_2](end_span).

## Libraries used:
* OpenCV
* NumPy
* Matplotlib
