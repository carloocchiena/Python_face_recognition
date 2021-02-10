# Python_face_recognition
## Static and Dynamic face recognition tests with Open CV library with Python.

You will find two .py files: 

- static.py where faces are found on pictures the user provide. Could be easily developed to search for specific faces using a training set of pictures. 
- dynamic.py where faces are found on a live webcam video stream. 

I warmly suggest you to create a virtual environment before installing the libraries since versioning can cause a lot of conflicts

python -m conda create --name myenv

I used a specific distro of Open CV:

pip install opencv-contrib-python==4.1.0.25

Probably a fast\more efficient way to perform such tasks could be to install the face_recognition library but since it requires Visual Studio and at the moment I don't have it installed on my machine, I did without it. 

The references and learning process in order to create such scriptes are from:

<a href="https://realpython.com/face-recognition-with-python/" target = "blank"> RealPython</a><br>
<a href="https://towardsdatascience.com/computer-vision-detecting-objects-using-haar-cascade-classifier-4585472829a9 " target = "blank"> TowardDataScience</a><br>
<a href="https://github.com/opencv/opencv/tree/master/data/haarcascades " target = "blank">Open CV Repo</a><br>
<a href="https://www.pythonforengineers.com/" target = "blank">Tiwari's Python for Engineers </a><br>
