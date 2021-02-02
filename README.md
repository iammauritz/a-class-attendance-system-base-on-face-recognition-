# A class attendance system base on face recognition

This is my attempt to make a Face recognition system for classroom or attendance. <br>
The system is based on baidu API.<br>
UI interface is Japanese.<br>
All functions have been integrated in face.py<br>
When the system is closed, a txt file consisting of attendance of all the students is generated.<br>
My level is limited. There may be bugs in the project. Welcome to propose solutions.<br>

# Requirement
python 3.8,opencv-python

# Get the access_token of the baidu API
For detailed Japanese manual, please refer to my graduate study 2.<br>
Or you can use mine instead of trying to get the access_token.<br>
I have written them down in img_api2.py.<br>

# Want to run it on your own
1) Put the face images in./img/face folder and name the images by the person's name.<br>
2) Run face.py to recognize people. Their attendance will be registered in ログ.txt.<br>
