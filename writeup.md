# **Finding Lane Lines on the Road** 

---

**Finding Lane Lines on the Road**

The goals of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect the work in a written report

---

### Reflection

### 1. Pipeline description

My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I used Gaussian smoothing and Canny Edge Detection. After that, suitable region was masked and lines were detected by Hough Tranform.

In order to draw a single line on the left and right lanes, I used Linear Regression by Python numpy + polyfit.


### 2. Potential shortcomings


One potential shortcoming would be when a curve was analyzed.


### 3. Possible improvements

A possible improvement would be to use Polynomial curve fitting.

