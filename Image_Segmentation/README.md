# IMAGE_SEGMENTATION

Image segmentation is the classification of an image into different groups. 
Image segmentation is an important step in image processing, and it seems everywhere if we want to analyze what’s inside the image.
For example, if we seek to find if there is a chair or person inside an indoor image, we may need image segmentation to separate objects 
and analyze each object individually to check what it is. Image segmentation usually serves as the pre-processing before pattern recognition, 
feature extraction, and compression of the image.

Image segmentation is the process of partitioning a digital image into multiple distinct regions containing each pixel(sets of pixels, also 
known as superpixels) with similar attributes.

The goal of Image segmentation is to change the representation of an image into something that is more meaningful and easier to analyze. 

Image segmentation is typically used to locate objects and boundaries(lines, curves, etc.) in images. More precisely, Image Segmentation 
is the process of assigning a label to every pixel in an image such that pixels with the same label share certain characteristics.

Of course, a common question arises:

### Why does Image Segmentation even matter?

If we take an example of Autonomous Vehicles, they need sensory input devices like cameras, radar, and lasers to allow the car to 
perceive the world around it, creating a digital map. Autonomous driving is not even possible without object detection which itself 
involves image classification/segmentation.

### How Image Segmentation works

 
Image Segmentation involves converting an image into a collection of regions of pixels that are represented by a mask or a labeled image. 
By dividing an image into segments, you can process only the important segments of the image instead of processing the entire image.

A common technique is to look for abrupt discontinuities in pixel values, which typically indicate edges that define a region.

Another common approach is to detect similarities in the regions of an image. Some techniques that follow this approach are region growing, 
clustering, and thresholding.

A variety of other approaches to perform image segmentation have been developed over the years using domain-specific knowledge to effectively 
solve segmentation problems in specific application areas.

So let us start with one of the clustering-based approaches in Image Segmentation which is K-Means clustering.


# Example Image
![image-9-1](https://user-images.githubusercontent.com/30102047/126491804-f621a747-b17f-4eab-a2bc-4442759ccd7f.png)

In the above image you can see the different clusters of colors in the image, these clusters are formed by image segmentation and These segmentations lead to better classification of objects in the image.
