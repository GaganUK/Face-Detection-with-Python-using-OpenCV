# Face-Detection-with-Python-using-OpenCV

# Computer Vision:

Computer vision is an interdisciplinary scientific field that deals with how computers can gain high-level understanding from digital images or videos.

# How a computer sees an image?

A computer sees an image as 0's and 1's. Pixels is the smallest unit in an image. A digital image is a 2D array of pixels. Each pixel is charachterised by it (x, y) coordinares and its value.

When we take a digital image, it is stored as a combination of pixels. Each pixel has different number of channels. If its a grayscale image, it has only one image, it contains three channels : Red, Green, Blue (RGB)

![github-small](images/RGB.svg.png)

# OpenCV

OpenCV was started at Intel in the year 1999 by Gary Bradsky.

# Face Detection:

Face Detection is a technique that identifies or locates human faces in digital images.
It is different from Face Recognition.
It merely detects the presence of faces in an image while facial recognition involves identifying whose face it is.

# Haar feature-based cascade classifiers:

Haar-like features are digital image features used in obeject recognition.
Haar cascasde classifier employs a Machine Learning approach for visual object detection which is capable of processing images extremely rapidly and achieving high detection rates. This can be attributed to three main reasons:

1) Haar classifier employs "Integral Image" conceptwhich allows the feature used by the detector to be computed very quickly.
2) The learning algorithm is based on AdaBoost. It selects small number of important features from a large set and gives highly efficient classifiers.
3) More complex classifiers are combined to form a "cascade" which discard and non-face regions in an image, therby spending more computation on promising object-like regions

# Haar Features:
![](images/haar.png)

# Haar Cascade Files:

OpenCV comes with a lot pre-trained classifiers. For instance, there are classifiers for smile, eye, faces, etc. 
They come in the form of XML files.
Or you can download the XML files uploaded in this repositories. 

For more information on OpenCV you can click the link below:

![](inline/icon48.png) https://docs.opencv.org/3.4/d2/d99/tutorial_js_face_detection.html
