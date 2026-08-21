## Ex: 09 Implementation-of-Erosion-and-Dilation-Using-OpenCV
## Aim
To write a Python program using OpenCV to perform morphological operations such as Erosion and Dilation on an image.

The program performs the following operations:

Image Erosion
Image Dilation
## Software Used
Anaconda – Python 3.7
Jupyter Notebook / VS Code
OpenCV (cv2)
NumPy
Matplotlib
## Algorithm
Step 1:
Import the required libraries: OpenCV, NumPy, and Matplotlib.

Step 2:
Create a blank image using NumPy.

Step 3:
Insert text onto the image using OpenCV's text drawing function.

Step 4:
Display the original image.

Step 5:
Create a structuring element (kernel) of suitable size.

Step 6: Image Erosion
Apply the erosion operation using the created kernel.
Remove pixels from the boundaries of foreground objects.
Display the eroded image.
Step 7: Image Dilation
Apply the dilation operation using the same kernel.
Add pixels to the boundaries of foreground objects.
Display the dilated image.
Step 8:
Compare the original, eroded, and dilated images.
