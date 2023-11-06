# Horizons

Imagine a presentation experience like no other, where the power of your gestures takes center stage. Imagine CAD presentations where you don't have to hold a cumbersome mosuse onto a table. Now, you can effortlessly control your presentations by simply moving your hands. Say goodbye to traditional clickers and hello to a new world of dynamic engagement. Navigate slides, emphasize key points, and captivate your audience with the fluidity of your hand movements. Your gesture-controlled presentation not only enhances your professionalism but also adds a touch of futuristic elegance to your speaking style. Step into the future of presentations with this code and let your gestures tell your story with grace and precision.
This code enables you to view your CAD Model and contol your Presentations with a touch of the future.

How to use it though? 

Install python and pip install the following packages:
opencv, mediapipe, pyautogui, enum, ctypes, comtypes, google-auth, google-auth-oauthlib.

Then, just run the code....Code.py

Gestures:
 | Palm - Resets commands 
 | Peace - Moves the cursor
 | Peace Closed - Next
 | Peace to Index Finger - Previous
 | Peace to Middle Finger - Click
 | Fist - PAN
 | Right Hand Pinch - ORBIT
 | Left Hand Pinch - ZOOM (Up for zooming out and Down for Zooming in) | 


The basis for this code is Mediapipe and OpenCV. However, Module.py is a modified version of an online available module so as to ensure smooth presentation experience. The gestures were modified, commands changed, and some functions (Audio and Brightness controller) were removed so as to ensure smooth function of the code and increase response speed.
