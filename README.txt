This project is basically based on TrafficSign Recognition in both image capture and video capture.
In this case we use principal of Convolutional Neural Networks 
In the preprocessing of data we reshape all the data to a particular dimension as cv2 from opencv does not work with different dimensions images.
Here we use K-Means Cluster algorithm to build the model
Lastly to test it we connect the model to webcam and use 3 zones over there zone0,zone1,zone2.


Drawbacks: presently its working on blue colored images. (Other work under process) 