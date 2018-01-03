# **Finding Lane Lines on the Road** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

<img src="output_solidYellowCurve.jpg" width="480" alt="Output Image" />

Overview
---
When we drive, we use our eyes to decide where to go.  The lines on the road that show us where the lanes are act as our constant reference for where to steer the vehicle.  Naturally, one of the first things we would like to do in developing a self-driving car is to automatically detect lane lines using an algorithm.

In this project lane lines are detected in images using Python and OpenCV.  OpenCV means "Open-Source Computer Vision", which is a package that has many useful tools for analyzing images. See the write up in writeup.md and project code in P1.ipynb for details.

What's In This Repo?
---
File | Description
---- | -----------
P1.ipynb | Jupyter notebook containing project code.
README.md | Readme file: the one you're reading right now.
writeup.md | Write up file describing the project in further detail.
solidYellowCurve.jpg | Input image (unchanged)
canny_solidYellowCurve.jpg | Image after Canny edge detection.
masked_canny_solidYellowCurve.jpg | Canny image after masking.
hough_output_solidYellowCurve.jpg | Blank image with Hough lines drawn.
output_solidYellowCurve.jpg | Input image with lane lines drawn.
solidWhiteRight.mp4 | Output video from project.
solidYellowCurve.mp4 | Output video from project.

Opening the Code
---
The project code is in a Jupyter notebook.  If you are unfamiliar with Jupyter Notebooks, check out <A HREF="https://www.packtpub.com/books/content/basics-jupyter-notebook-and-python" target="_blank">Cyrille Rossant's Basics of Jupyter Notebook and Python</A> to get started.

Jupyter is an Ipython notebook where you can run blocks of code and see results interactively.  All the code for this project is contained in a Jupyter notebook. To start Jupyter in your browser, use terminal to navigate to your project directory and then run the following command at the terminal prompt (be sure you've activated your Python 3 carnd-term1 environment as described in the [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md) installation instructions!):

`> jupyter notebook`

A browser window will appear showing the contents of the current directory.  Click on the file called "P1.ipynb".  Another browser window will appear displaying the notebook.  Follow the instructions in the notebook to complete the project.  
