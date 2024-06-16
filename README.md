# Digital-Image-Processing-Projects
This repository includes the mini projects that have been done during fall semester.

## Changing Color of an Object in the Image
*Take the logo of the university (AYBU) and change the colors of the logo according to the following color table using your last digit of your student ID number "d". Make the foreground color "d" and background color "9-d".* 

## Generating a circular black frame around an image
*Write a Matlab code to generate a circular black frame around your image.*

## Finding Histogram
*Write the Matlab command for finding the histogram of your double grayscale image. You will obtain a figure as given right as an example. Display and report your grayscale image together with its histogram side by side in the same figure window and comment on where most of the pixels are distributed heavily.*

## Finding Normalized 3 bins Histogram
*This time find the histogram of your double grayscale image using 3 bins and assign the histogram output to a variable. Normalize the histogram result by dividing it to the total number of pixels in the image. Plot the histogram of your image by using the "bar()" command and report the graph together with your grayscale image side by side in the same figure window. Write the percentages of pixels in "dark gray", "medium gray" and "light gray" bins.*

## Contrast Enhancement Using Piecewise Linear Transformation
*Now, you will apply piecewise linear transformation with 2 linear pieces to enhance the double grayscale image. Try a few different parameters and report the results. Determine and report the best parameters (a and ya) as you can to enhance your image. Remember that L=1 for double grayscale images. Display and report the obtained images and their histogram side by side in the same figure window.*

## Contrast Enhancement Using Gamma Transformation
*Try to enhance the contrast of the original double grayscale image using gamma transformation. Determine and report the best parameters as you can to enhance your image. Display and report the transformed image and its histogram side by side in the same figure window.*

## Histogram & Adaptive Histogram Equalization
*Enhance the contrast of the original double grayscale image by using the histogram equalization method and adaptive histogram equalization method. Display and report the resultant images together with previous low contrast image side by side in the same figure window.*

## Adding Uniform Random Noise to Image
*Write your own Matlab code to add random values(noise) between -0.2d and +0.2d to every pixel of your images. Repeat it by adding random values between -0.3d and +0.3d. Display and report the resultant images side by side in the same figure window. Draw the histograms of the original and the noisy yourName _gray images side by side in another figure.*

## Adding Gaussian Random Noise to Image
*Write your own Matlab code to add Gaussian random noise with μ=0 and σ=0.1d  to every pixel of your images. Do not use “imnoise” function. Repeat it with μ=0 and σ=0.2d. Display and report the resultant images side by side in the same figure. Draw the histograms of the original and the noisy yourName _gray images side by side in another figure.*

## Image Smoothing by Averaging Filter
*Write your own Matlab function(with a double for loop) to make a 7x7 pixel averaging filter.*

## Adding Salt&Pepper Noise to the Image
*Write your own Matlab code to add 1d% (if the last digit of your ID is 7, then 17%, i.e. the probability of a pixel to be noisy should be 0.17) salt&pepper noise to your images. Do not use “imnoise” function. Repeat it by adding 2d% salt&pepper noise. Display and report the resultant images side by side in the same figure. Draw the histograms of the original and the noisy yourName _gray images side by side in another figure.*

## Median Filtering
*Write your own Matlab function(with a double for loop) to make a 3x3 pixel median filter (No padding, DO NOT USE medfilt, medfilt2, ordfilt2, imfilter, conv2 functions). Denoise your salt&pepper noised images in Part 9 with your median filter. Apply 3x3 averaging filter on the same salt&pepper noised images. Display and report the obtained images side by side in the same figure window together with their titles.*

## Plotting the values of a pixel row
*In this part, you will plot the values of the pixels in a row you select in your double grayscale image(use subplot). From the graph, try to find in which pixel the brightness is the highest. Then indicate the row you have plotted by making that row white and display using imshow (use subplot).*

![image](https://github.com/hypatiash/Digital-Image-Processing-Projects/assets/142400240/5accd440-b570-4b3e-aaa6-3eca1f21a213)

## Finding the horizontal 1st order derivative
*Take the horizontal first order derivative of your double grayscale image(without white line). Then plot the same row (which you selected in Q1) of your image derivative (use subplot). Draw a white line on the same row of the image derivative as in question 1 and display (use subplot).*

![image](https://github.com/hypatiash/Digital-Image-Processing-Projects/assets/142400240/19d08c90-c51a-4e9f-942e-c7250021a544)

## Finding the horizontal 2nd order derivative
*Take the horizontal second order derivative of your double grayscale image(without white line) and take its absolute value. Then plot the same row of your image as in Q1 (use subplot. Draw a white line on the same row of the derivative image as in previous questions and display (use subplot).*

## High-Boost Sharpening
*Sharpen your double grayscale image using “High-Boost” sharpening method with just applying a single mask to your image. Display the sharpened image (use subplot).*

## Unsharp Masking
*Sharpen your double grayscale image using “Unsharp Masking” method with 3x3 weighted averaging filter. First apply the weighted averaging filter to your image and display the result (use subplot). Then use it for “Unsharp Masking” sharpening of your image and display the sharpened image (use subplot).*

## Coding Dilation
*Write a Matlab script with a double for loop to implement dilation morphological operation and dilate your binary image with the 3x3 structural element “se1=[1 1 1; 1 1 1; 1 1 1]”.*

## Finding the edges
*Write a Matlab code that finds the edges of your name by using morphological operations.*

## Skin color detection in YCbCr color space
*Convert your RGB color image into YCbCr color space. Mark the pixels with skin color as white and others as black using the following YCbCr thresholds: Y > 80 , 85 < Cb <135, 135 < Cr < 180*

![image](https://github.com/hypatiash/Digital-Image-Processing-Projects/assets/142400240/7a418b16-f599-44d9-8a7e-169573f408f9)

## Adding a periodic noise to image in frequency domain
*Take the FFT of your original grayscale image and add a periodic sinusoidal noise by changing just the cth vertical frequency coefficient with a proper value.*

![image](https://github.com/hypatiash/Digital-Image-Processing-Projects/assets/142400240/ea993d8e-d11d-425b-be53-bb3373578217)

## Distorting image by blurring in frequency domain
*Take the FFT of your original grayscale image. Then blur your photo(using its FFT) with an "n x n" averaging filter in frequency domain.*

![image](https://github.com/hypatiash/Digital-Image-Processing-Projects/assets/142400240/d19c399d-8e97-43b4-af88-b8560b2e3eef)

## Reconstructing blurred image by inverse filtering
*Deblur your blurred image in frequency domain. Display the blurred and deblurred images on the same graph by using subplot();.*

## Image compression using FFT
*You will compress your grayscale image by deleting some of its highest frequency FFT coefficients. Preserve only half the size of rows and columns of coefficients in the center of the image FFT. (Don't forget to use fftshift and ifftshift). Display the original grayscale image, compressed image and its fft coefficients side by side by using subplot();.*

![image](https://github.com/hypatiash/Digital-Image-Processing-Projects/assets/142400240/805b1e4f-8852-4271-86a5-a7c6ee3333f8)



