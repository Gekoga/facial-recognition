# Facial Recognition Project

Facial recognition project, using python.

## Features

#### Create own dataset

By adding folders with pictures in the dataset folder. Encoding makes use of 128-dimensional face encoding, build in the face_recognition library.  
The naming convention I used for the folders is _firstname_lastname_, and this naming convention is then used by the facial recognition to add to recognised face immediately.

#### Recognizing faces from images

The images stored in the examples folder can be used to test the encoded faces before starting a videostream. The faces which are recognized will get the name which is 
used for the dataset, faces which aren't defined in the dataset get the name _Unknown_.

## Libraries

For the Computer vision **OpenCV-Python** will be used.  
For the Machine learning **dlib** and **face_recognition** will be used.

#### Other packages used

- cmake
- imutils

### Used links and helpfull information

Project base:  
https://pyimagesearch.com/2018/06/18/face-recognition-with-opencv-python-and-deep-learning/
