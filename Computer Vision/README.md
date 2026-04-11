Computer Vision

Task 1: Basket Rim Detection using OpenCV

Objective
Detect the **top rim of a basket** in an image by fitting an **ellipse** using OpenCV.

---

Core Idea
The rim of the basket is approximately **elliptical**. The approach is:

1. Extract edges  
2. Find contours  
3. Filter the correct contour (rim)  
4. Fit an ellipse  

---
![Basket Rim Detection](Basket.jpeg)
---
Task 2: Center Detection of Spinning Archery Board

Objective
Detect the center of a spinning archery board in a video by fitting an **ellipse** using OpenCV.

---

Core Idea
The center of the board is red. The approach is:

1. Detect color red in appropriate region  
2. Find contours  
3. Filter the correct contour (central area)  
4. Fit an ellipse  

---

