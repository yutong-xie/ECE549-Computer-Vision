# ECE549-Computer-Vision-Machine Problem 

In the simplest terms, computer vision is the discipline of “teaching machines how to see.” This field dates back more than fifty years, but the recent explosive growth of digital imaging and machine learning technologies makes the problems of automated image interpretation more exciting and relevant than ever. There are two major themes in the computer vision literature: 3D geometry and recognition. This course provide a coherent perspective on the different aspects of computer vision, and give us the ability to understand state-of-the-art vision literature and implement components that are fundamental to many modern vision systems.

There are totally 5 machine problems including in this course. 

## Machine Problem Description 


### Machine Problem 0
In this mp, I reviewed the calculus and linear algebra knowledge. Also, I tried to combine and align the Prokudin-Gorskii’s black-and-white (grayscale) image composites based on **SSD** and **ZNCC**. Given three grayscale channels, I could reproduce the original RGB images, which have great quality.

### Machine Problem 1
In mp1, I proved that the vanishing points of lines on the plane lie on the vanishing line of the plane and I derived the ellipse projected by sphere satisfied an equation about the center and radius of sphere. Also, I estimated the albedo and surface normals to implement shape from shading. 

### Machine Problem 2
In mp2, I simulated optical flow induced on the image of a static scene due to camera motion and visualized the optical flow using python. Then, I built a basic contour detector using derivative of Gaussian ﬁlters and non-maximum suppression on **BSDS** dataset. What's more, I implemented a Laplacian blob detector and tested it on given image. 

### Machine Problem 3
In this mp, I first estimated homography transform to register and stich image pairs using **RANSAC** algorithm. Then, I implemented an algorithm to estimate the fundamental matrix to register pairs of images, as well as attempt camera calibration, trangulation. Meanwhile, I implemented the single-view camera calibration and realized fronto-parallel warps. 

### Machine Problem 4
In mp4, I improved the BaseNet for digit recognition by using data normalizaion, data augmentation, deeper network, and normalization layers. The accuracy improved from 87% to 93%. Then, I built my own semantic segmentation model on the Stanford Background Dataset based on **U-Net** and achieved a mAP of 0.59 and mIoU of 0.54. Also, I built on top of a **ResNet** pre-trained model for semantic segmentation task and achieved a mAP of 0.63 and a mIoU of 0.51. 


