# ball-tracking-with-opencv
# This is based on some code from Hemant Kumar and Adrian Rosenbrock
Code to track a ball using opencv and plotting graph of its position vs time.

required : python3 along with these libraries: numpy, matplotlib, pandas, opencv.
For installation of opencv in GNU/Linux, use this https://docs.opencv.org/2.4/doc/tutorials/introduction/linux_install/linux_install.html

Command to run code:
`python3 ball_tracking.py`  
this will use camera of laptop for video capture.

You can also process a using an argument:  
`python3 ball_tracking.py --video file.mp4`  

This will generate a .csv file of the detected ball positions and a .svg plot.
The processing can be interrupted by pressing q or by closing the video window.