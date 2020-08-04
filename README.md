# Face-Detection-using-caffemodel
In this repo we are using the caffemodel provided by opencv for face-detection purpose

# How to use
There are two python files in this.
a. detect_faces.py is used to detect faces for the given input image
b.detect_faces_video.py is used to detect faces realtime using computer camer or raspbeerry pi camera 

# Requirements
pip install numpy 
pip install opencv
pip install imutils

# How to run the code??
To run detect_faces.py : Add a image in the same directory as in the code.(here i am using moneyheist.png)
the image can be either .png or .jpg format
python detect_faces.py --image moneyheist.png --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

To run detect_faces_video.py :
python detect_faces_video.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

