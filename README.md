# Face-Recognition
A Minor Small project which trains the dataset of Images and afterward can be use for face detection of that person. I the project i used numpy, openCV and faceRecognition python packages. For front face training data i used the haarcascade_frontalface_default.xml file. 



### =============== Prerequisites ================
=> Numpy :- pip install numpy


=> OpenCV :- run pip install opencv-contrib-python


=> FaceRecognition :- pip install face-recognition

####  ============ Command for Annaconda Prompt =========

=> Numpy :- conda install numpy

=> OpenCV :- conda install -c menpo opencv

=> FaceRecognition :- conda install -c akode face_recognition_models


Note: Please install opencv-contrib-python package instead of opencv-contrib as it contains the main modules and also contrib modules.

## How to run code

Run tester.py script on powershell or cmd to train and recogniz on training images and to predict test images:



#### python tester.py


1.Place some test images in TestImages folder that to be predict by tester.py 

2.Place Images for training the classifier in trainingImages folder.If want to train clasifier to recognize multiple people then add each persons folder in separate label markes as 0,1,2,etc and then add their names along with labels in tester.py/videoTester.py file in 'name' variable.

3.To generate test images for training classifier use videoimg.py file.

4.To do test run via tester.py give the path of image in test_img variable

5.Use "videoTester.py" script for predicting faces realtime via your webcam.

## **** (Ensure that run tester.py should run first since it generates trainingData.yml file that is further use in "videoTester.py" script.)


### ============= Images =====================

![alt text](https://github.com/aj14799/Face-Recognition/blob/master/Screenshots/Screenshot%20(243).png)


![alt text](https://github.com/aj14799/Face-Recognition/blob/master/Screenshots/Screenshot%20(244).png)


![alt text](https://github.com/aj14799/Face-Recognition/blob/master/Screenshots/Screenshot%20(245).png)


![alt text](https://github.com/aj14799/Face-Recognition/blob/master/Screenshots/Screenshot%20(246).png)


![alt text](https://github.com/aj14799/Face-Recognition/blob/master/Screenshots/Screenshot%20(247).png)


![alt text](https://github.com/aj14799/Face-Recognition/blob/master/Screenshots/Screenshot%20(248).png)

