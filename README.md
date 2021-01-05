# instafilter-using-python

# Project description

 Modifiy images using Instagram-like filters in python

You can easily install this library by using the pip command – pip install instafilter. I hope you will not get any errors while installing this library.

The other library we need for creating Instagram filters is the Open Source Computer Vision Library of Python which is OpenCV. If you have never worked with OpenCV you can easily install it by using a pip command – pip install opencv-python. To use OpenCV we do not import it by the same name, we import it by the name of cv2 (import cv2). Let’s create Instagram filters with Python:

!pip install instafilter
!pip install Opencv-python

from instafilter import Instafilter

model = Instafilter("Lo-fi")
new_image = model("myimage.jpg")

# To save the image, use cv2
import cv2
cv2.imwrite("modified-img.jpg", new_image)


The same way ou can use other filter names available.

