# Gesture Volume Control-OpenCV
The Aim of this project is to develop a real time Gesture Volume Control System. The main motive of this type
of system is basically to automate the things in our system in
order to make the things become easier to control.

# REQUIREMENTS
-opencv-python
-mediapipe
-numpy
-pycaw
# METHODOLOGY/APPROACH
-Detect hand landmarks
-Calculate the distance between thumb tip and index finger tip.
-Map the distance of thumb tip and index finger tip with volume range. For my case, distance between thumb tip and index finger tip was within -the range of 30 – 350 and the volume range was from -63.5 – 0.0.

![image](https://user-images.githubusercontent.com/60054130/124419060-6e3a5f80-dd7a-11eb-8bb8-76b910e84728.png)

![image](https://github.com/pratham-bhatnagar/Gesture-Volume-Control/blob/master/images/hand_landmarks_docs.png)
