# Facial-Keypoint-Detection
A facial keypoint detection system combining computer vision techniques and deep learning architectures.

This is my solution to the Facial Keypoint Detection project, which is a requirement in Udacity's Computer Vision Nanodegree.

The Problem: Facial keypoints are unique to each face. As each face has unique features, it is challening to identify these keypoints for a given face. Identifying facial keypoints is important is applications like facial tracking, facial pose recognition, facial filters and emotional recognition. 

The Solution: Deep learning with convolutional neural network helps in solving this problem. In this project, a facial keypoint detection system is built combining computer vision techniques and deep learning architectures. The resulting system can take in any image with faces and predict the location of 68 distinquishing keypoints on each face.

The Loss function chosen is Smooth L1 Loss and the optimization function chosen is Adam. The model was trained for 10 epochs with a batch size of 10. 

A complete explanation of the code is providing through descriptions and comments in the Jupyter notebooks.
The model.py containts the architecture of the neural network that was trained. 
