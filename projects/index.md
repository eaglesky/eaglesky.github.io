title: Projects
---

## Eye Gaze Correction with a Single Webcam Based on Eye-Replacement
(January 2015 - June 2015, UCSB)

{% image fancybox center clear /images/projects/EyeGazeCorrection.png 80% %}

This is my master's thesis. In this work I developed a system that corrects the user's gaze direction to create eye contact in video conferencing system using a single webcam.

[Paper](http://www.ece.ucsb.edu/~kuochin/homepage/papers/ISVC_2015.pdf)(11th International Symposium on Visual Computing (ISVC))
[Video](http://www.ece.ucsb.edu/~kuochin/homepage/videos/ISVC15_demo.avi)

## Virtual Reality Ball Game
(February 2015 - March 2015)

{% youtube -UsmVecCVEg %}

This is the course project of me and Yuxiang's for CS290I--Mixed and Augmented Reality at UCSB. The player can interact with the virtual ball by "blowing" it, and from the camera image we are able to extract mouth points and detect the 'blow' action by checking the change of mouth shape. The game was implemented using OpenCV and Unity3D, written mainly in C++ and C#.

[Project Page](http://eaglesky.github.io/VRBallGame/), [Source Code](https://github.com/eaglesky/VRBallGame)

## Hand Gesture Recognition App on Android Phones
(January 2014 - March 2014, UCSB)

{% image fancybox fig-25 /images/projects/hand-test.jpg %}
{% image fancybox fig-25 /images/projects/hand-test1.jpg %}
{% image fancybox fig-25 /images/projects/hand-test2.jpg %}
{% image fancybox fig-25 /images/projects/hand-test3.jpg %}

{% image fancybox center clear /images/projects/real-time.jpg /images/projects/real-time.jpg 50% %}

This is an Android app I developed that can detect and recognize user-defined hand gestures and then launch other apps according to the gestures. 

[Source Code](https://github.com/eaglesky/HandGestureApp), {% post_link HandGestureRecognition Project Page %}

## Eagle File System using Fuse
(September 2013 - December 2013, UCSB)

This project is my course project for [CS270](http://cs.ucsb.edu/~rich/class/cs270/) in UCSB(Advanced Topics in Operating Systems), mainly done by me and another student. It was written in C and tested on Eucalyptus cloud. Our file system supports all the common commands like ls, chmod, chown, touch, cat, cp(-r), rm(-r), tar gcc and so on. Our file system also supports multi-thread access, since we added multi-thread access protection. More information is in the readme file of our project [source code](https://github.com/eaglesky/eagle_fs). 

## Human Motion Recognition using Kinect
(June 2012 - May 2013, University of Science and Technology of China)

{% image fancybox fig-25 /images/projects/skeletonplayer.jpg "Action Player" %}
{% image fancybox fig-75 /images/projects/push.png 82% "Real Time Recognition" %}

My work:

 1. Developed some useful tools including data collection software and motion extraction software, using both windows API and the API provided in the Kinect SDK.
 2. Constructed training set database.
 3. Applied two machine learning algorithms to recognize various actions and postures, and wrote several MATLAB test scripts to establish accuracy of the algorithms.
 4. Developed a cross-platform action recognition library(ARLK) in C++, supporting both Kinect SDK and openNI SDK. Developed sample programs in Windows and Linux.
 5. Wrote bachelor's degree thesis based on this project.

[Project Page(ARLK docs)](/ARLK_html/index.html), [My Undergraduate Thesis(Chinese)](/downloads/GradPaper_Allen.pdf), [Source Code](https://github.com/eaglesky/ARLK)


## Robogame 2011 --- Two-wheeled Self-balancing Robot
(June 2011 - October 2011, University of Science and Technology of China)

{% image fancybox fig-25 /images/projects/water.jpg 99% %}
{% image fancybox fig-25 /images/projects/box.jpg %}
{% image fancybox fig-25 /images/projects/slope.jpg 97.4% %}
{% image fancybox fig-25 /images/projects/downslope.jpg 87% %}


This is a robot made by me and three other teammates for the robot competition held in USTC in 2011. The robot can move around on only two wheels while carrying 10 cups of water. It can also push boxes, climb a slope and go down a slope under remote control. We won the third place in acrobatic group!

[Video](http://youtu.be/eJRyVsEaUSs)