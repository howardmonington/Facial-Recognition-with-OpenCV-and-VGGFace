# Facial Recognition with OpenCV and VGGFace

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is to use OpenCV in order to identify a face and eyes in a picture. Then combine OpenCV with the VGGFace Neural Network in order to perform one shot learning and idenfity faces in a webcam feed.


### Methods Used
* Deep Learning
* Data Visualization
* Utilizing Pretrained Models
* Face and Eye Detection
* Facial Recognition

### Technologies
* Python
* jupyter
* Matplotlib
* JavaScript
* OpenCV
* VGG Face Neural Network


## Project Description
OpenCV is a library of programming functions mainly aimed at real-time computer vision. It has many uses, such as to identify objects, classify human actions in videos, remove red eyes from images, following eye movements, and more. In this project, I use OpenCV to detect faces and eyes in images using OpenCV's Haar feature-based cascade classifier. This classifier also returns the location, height, and width of the face. I use that information in order to crop out the face from images and videos. From there, I use the VGGFace pretrained Neural Network to convert the face into a 2622 dimensional vector representation. From this representation, I use the cosine similarity metric to determine if a face is similar to other faces. Finally, I put all of this together in order to perform real-time facial recognition using my webcam.



## Featured Notebooks/Analysis/Deliverables
* [Notebook](https://github.com/lukemonington/facial_recognition_opencv/blob/main/main_ai.ipynb)


## Contributing Members

**[Luke Monington](https://github.com/lukemonington)**

## Contact
* I can be reached at lukemonington@aol.com.
