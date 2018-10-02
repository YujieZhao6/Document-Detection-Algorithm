# Document Detection Algorithm
#### This project is my graduation project of Northeastern project. I desgin and implement an algorithm which can extract the dcoument part from a picture.

Skills: **Python, OpenCV, Computer Vision, Machine Learning**

## Introduction
### 1. Environment
* Pyhton 2.7
* OpenCV
* [RCF Model](https://github.com/yun-liu/rcf) (The lastest maching-learning-based edge detection algorithm)

### 2. Algorithm Architecture
<img src="https://i.loli.net/2018/10/03/5bb3c2c158bd3.png" alt="drawing" width="550"/>

## Demo
### Extract Document From Whiteboard
Original Picture
<img src="https://i.loli.net/2018/10/03/5bb3c6a236881.png" alt="drawing" width="500"/>

Edge detection picture of RCF
<img src="https://i.loli.net/2018/10/03/5bb3c6a205d2f.png" alt="drawing" width="500"/>

Hough Transform of OpenCV
<img src="https://i.loli.net/2018/10/03/5bb3c6a221442.png" alt="drawing" width="500"/>

Optimized Hough Transform image
<img src="https://i.loli.net/2018/10/03/5bb3c6a200fab.png" alt="drawing" width="500"/>

Eligible intersections image
<img src="https://i.loli.net/2018/10/03/5bb3c6a20a786.png" alt="drawing" width="500"/>

The final target area rectangle
<img src="https://i.loli.net/2018/10/03/5bb3c6a20826f.png" alt="drawing" width="500"/>

Final result by processing of all algorithms
<img src="https://i.loli.net/2018/10/03/5bb3c6a2278aa.png" alt="drawing" width="500"/>

### If you want to know algorithm detail and see more demos, please see my [paper](https://github.com/YujieZhao6/Document-Detection-Algorithm/blob/master/Design%20and%20Implementation%20of%20Document%20Detection%20Based%20on%20Deeping%20Learning--YUJIE%20ZHAO.pdf).