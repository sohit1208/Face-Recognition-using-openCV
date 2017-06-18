# Face-Recognition-using-openCV
To detect a face on webcam and recognize it using trained images.

Requirements-OpenCV,Python

Process:-
'dataSet' folder will store the images.
'recognizer' folder will store a 'yml' file which is configured when training alogrithm is called.
'dataSetCreator' script runs the webcam,takes the Id and stores the images in dataSet.
'trainer' will train the images from 'dataSet' and stores a 'yml' file in'recognizer' folder.
'detector' will open the webcam and recognize the faces on it against trained images and will show the best matched result
'haarcascade' is the library used to detect faces and for training purposes. 


