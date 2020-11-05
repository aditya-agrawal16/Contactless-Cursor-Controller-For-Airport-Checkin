# Contactless-Cursor-Controller-For-Airport-Checkin
This project allows you to control your mouse cursor with your facial movements, works with just your regular webcam. Its hands-free, no wearable hardware or sensors needed.

## Code Requirements
* Numpy - 1.13.3
* OpenCV - 3.2.0
* PyAutoGUI - 0.9.36
* Dlib - 19.4.0
* Imutils - 0.4.6

## Execution
Order of Execution is as follows:

1. Follow these installation guides - [Numpy](https://pypi.org/project/numpy/), [OpenCV](https://medium.com/@akshaychandra21/f5f721f0d0b3), [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/install.html), [Dlib](https://www.learnopencv.com/install-opencv-3-and-dlib-on-windows-python-only/), [Imutils](https://github.com/jrosebr1/imutils) and install the right versions of the libraries (mentioned above).<br/>
(Note: If you feel trouble in installing dlib, you can follow this tutorial: https://www.youtube.com/watch?v=xaDJ5xnc8dc&t=1s)
2. Make sure you have the model downloaded. Read the README.txt file inside the model folder for the link. Keep the downloaded model in 'model' folder.
3. To run the application, open Powershell and run the commands given below.<br/>
(Commands shown below are for my system. I kept the folder on desktop and made virtual environment by following the video mentioned in step 1).
4. `cd .\Desktop\facerecog\myvenvpy\scripts\` <br/>
`.\activate` <br/>
`cd..` <br/>
`cd..` <br/>
`cd face_recognition` <br/>
`python mouse-control.py`
5. Once you are done with the application, press 'Esc' to exit it.

## Airline Website
1. Place the 'Airline Website' folder on your desktop.
2. Run 'index.html' in a web browser.
