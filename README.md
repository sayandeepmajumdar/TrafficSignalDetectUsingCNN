# TrafficSignalDetectUsingCNN
We use CNN for image processing. Right now only blue colored signal will work, day by day we'll enhance this model so that it can detect all type of colored signal.

This project is basically based on TrafficSign Recognition in both image capture and video capture.
In this case we use principal of <b>Convolutional Neural Networks</b> 
In the preprocessing of data we reshape all the data to a particular dimension as cv2 from opencv does not work with different dimensions images.
Here we use K-Means Cluster algorithm to build the model
Lastly to test it we connect the model to webcam and use 3 zones over there zone0,zone1,zone2.


Drawbacks: Presently its working on blue colored images. (Work underprogress) 

<b> Installations </b>

1. Install all the dependency using <b> pip install -r requirements.txt </b>

2. Now run the command. <b> python maincode.py </b>

   It will better if you have installed virtualenv in your system. <b>(pip install virtualenv) </b>
   
   <b>Showcase</b>
   
   <img src="https://github.com/sayandeepmajumdar/TrafficSignalDetectUsingCNN/blob/master/example_screenshot.png"/>
   
   
   Try it out !!!
   
   Relax, &#128521; and have a coffee &#9749; now
