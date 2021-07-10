# **Finding Lane Lines on the Road** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

<img src="examples/laneLines_thirdPass.jpg" width="480" alt="Combined Image" />

Overview
---

When we drive, we use our eyes to decide where to go.  The lines on the road that show us where the lanes are act as our constant reference for where to steer the vehicle.  Naturally, one of the first things we would like to do in developing a self-driving car is to automatically detect lane lines using an algorithm.

In this project I detected lane lines in images using Python and OpenCV.  OpenCV means "Open-Source Computer Vision", which is a package that has many useful tools for analyzing images.  

To complete the project, two files were submitted: a file containing project code and a file containing a brief write up explaining my solution.
The code file is called "P1.ipynb" and the writeup template is "Writeup_of_Lesson3.pdf".



The Project Rubrics
---

1. Required Files
The project submission includes all required files:
 [Ipython notebook with code]("P1.ipynb")
 [A writeup report]("Writeup_of_Lesson3.pdf")
 
2. Lane Finding Pipeline
The output video is an annotated version of the input video.
 [Picture of Hough lines]("test_images_output\without_average_extrapolate")
 [Picture of final detected lane lines]("test_images_output\with_average_extrapolate")

In a rough sense, the left and right lane lines are accurately annotated throughout almost all of the video. Annotations can be segmented or solid lines
 [Video of Hough lines]("test_videos_output\without_average_extrapolate")

Visually, the left and right lane lines are accurately annotated by solid lines throughout most of the video.
 [Video of final detected lane lines]("test_videos_output\with_average_extrapolate")

3. Reflection
 Reflection describes the current pipeline, identifies its potential shortcomings and suggests possible improvements. 
 There is no minimum length. Writing in English is preferred but you may use any language.
 [A writeup report]("Writeup_of_Lesson3.pdf")


