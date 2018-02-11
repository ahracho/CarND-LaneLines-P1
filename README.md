# **Finding Lane Lines on the Road** 

## Overview
---

This repository is for the first project of **Udacity Nanodegree - Self-driving Car Engineer : Finding Lane Lines Proejct**.  )It is forked from https://github.com/udacity/CarND-LaneLines-P1).  


The goal of this project is to detect left and right lane lines from images taken from vehicles.  

Important concepts used here are Canny Edge Detect and Hough Transformation. Detection based on color is not used because lanes can be various color: white to yellow. Instead, images are converted in gray scale, and Canny Detection is used to find the points color is dynamically changed. After that, Hough Transformation is used to transform detected points into lines.  

To average detected lines, I used simple algebra and you can find the details in writeup.md file.

## Outputs
---
This project has 3 types of outputs:
1. Single Image : Saved in test_images_output folder.
2. Video : Saved in test_videos_output folder.
3. writeup.md : Description of algorithms used in this project. 