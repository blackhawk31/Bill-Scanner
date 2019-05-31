# Bill-Scanner

This project was done to understand how to apply image processing, to detect objects and apply perspective transform, and get a good understanding and programming practise. If you are new to opencv and computer vision, then this is a good start to boost your confidence and to get familiar with different terminologies. I highly recommend to go and check out  https://www.pyimagesearch.com/ by Adrian Rosebrock. He has done an excellent job in explaining and implementing these programs in the best possible way.

Document scanning can be broken down into three distinct and simple steps.
### The first step is to apply edge detection.
### The second step is to find the contours in the image that represent the document we want to scan.
### And the final step is to apply a perspective transform to obtain a top-down, 90-degree view of the image, just as if we scanned the document.

Optionally, you can also apply thresholding to obtain a nice, clean black and white feel to the piece of paper.
