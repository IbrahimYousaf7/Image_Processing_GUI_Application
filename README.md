# Image_Processing Techniques using GUI Application

# First Cell

The code in the first cell contains image filters such as average,laplacian,histogram equaliztion,thresholding,clustering, laplacian of gausian and adaptive thresholding. This code is for images only. 

When you run the code you will be taken to a tkinter window and will have to select and image to perform the filters on.

# Image Filters 

## Average Filter:

Functionality: Blurs an image by averaging the pixel values in the neighborhood defined by a kernel.
Effect: Smooths out noise and reduces high-frequency details, resulting in a softer appearance.

## Histogram Equalization:

Functionality: Improves contrast in an image by redistributing intensity values.
Effect: Enhances the overall brightness and contrast, making details more visible, especially in images with poor lighting or uneven contrast.

## Thresholding:

Functionality: Segments an image into a binary form based on a threshold value.
Effect: Converts grayscale images into binary images where pixels are either black or white, based on whether their intensity is above or below the threshold.

## Laplacian Filter:

Functionality: Detects edges in an image by measuring the rate of change of intensity.
Effect: Emphasizes regions of rapid intensity change, highlighting edges and fine details in the image.

## Clustering:

Functionality: Groups similar pixels together based on their color attributes.
Effect: Reduces the number of colors in an image while preserving its structure, often used for image segmentation and compression.

## Laplacian of Gaussian (LoG):

Functionality: Enhances edges while smoothing out noise using a combination of Gaussian smoothing and Laplacian edge detection.
Effect: Provides precise edge detection and noise reduction, useful for applications requiring accurate edge localization.

## Adaptive Thresholding:

Functionality: Computes different thresholds for different regions of the image, adapting to local variations.
Effect: Improves thresholding results in images with varying lighting conditions or uneven backgrounds, ensuring consistent binary segmentation.


These filters collectively provide a range of tools for enhancing, analyzing, and segmenting images, catering to diverse needs in computer vision and image processing applications.

# Second Cell

The code in the second cell contains image filters such as average,laplacian,histogram equaliztion,thresholding,clustering, laplacian of gausian and adaptive thresholding(but for a video). This code is for videos where each of the filter can be applied to any frame of a video. The filters can be applied on any frame of the video and I have included functionality that enable you to naviage through the frames of the video.
(The next and previous buttons have been included in the tkinter window to enable you to navigate through the frames of the video and each filter can be applied in the frame that you are on)

When you run the code you will be taken to a tkinter window and will have to select a video to perform the filters on (which will be done frame by frame just like an image).

# Third Cell

The code in the third cell contains custom erosion and dialtion funcions that have been developed by me form scratch and have been compared to the erosion and dilation functions of opencv.

When you run the code you will be taken to a tkinter where you have to select an image and the results will be displayed on the tkinter window.

## Erosion:

Functionality: Erosion is a morphological operation that reduces the boundaries of foreground objects (usually white) in an image.

Operation: It works by sliding a kernel (structuring element) over the image. For each pixel under the kernel, if all pixels in the kernel are white, the pixel remains white; otherwise, it becomes black (eroded).

Effect: Erosion shrinks the boundaries of objects and removes small objects and details. It is useful for noise reduction and separating connected objects.

## Dilation:

Functionality: Dilation is a morphological operation that expands the boundaries of foreground objects in an image.

Operation: Like erosion, it slides a kernel over the image. For each pixel under the kernel, if at least one pixel in the kernel is white, the pixel becomes white (dilated); otherwise, it remains black.

Effect: Dilation increases the size of foreground objects, fills in gaps, and joins broken parts of an object. It is useful for joining broken lines, filling holes, and generally making objects more visible.








