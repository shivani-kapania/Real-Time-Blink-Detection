# Real-Time-Blink-Detection

To build our blink detector, we’ll be computing a metric called the eye aspect ratio (EAR). EAR is based on the ratio of distances between facial landmarks of the eyes.

Now we can apply facial landmark detection to localize important regions of the face, including eyes, eyebrows, nose, ears, and mouth. In terms of blink detection, we are only interested in two sets of facial structures — the eyes.

Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the remainder of the region:

![alt text](https://github.com/shivani-kapania/Real-Time-Blink-Detection/blob/master/EAR%20equation.png)

## Dependencies ##

* Numpy
* Dlib
* OpenCV
 
