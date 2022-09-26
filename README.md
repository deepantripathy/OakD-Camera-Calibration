"# OakD-Camera-Calibration" 
Files and their purpose

Answer 1: 
Created depth_capture_color.py to click color pictures of target(in our case it was a 2x2 image of a chess board) 
Caliberated the camera using opencv.caliberateCamera() and calculated the camera matrix = Intrinsic matrix * Extrinsic matrix

Answer 2
Created program calculate_dimensions.py to take calculate sides of our target using the perspective projection equation and calculated the length and width of our chess board.

Answer 3
No its not feasible. I ran the RGB stream from mono camera using program depth_capture_mono.py and the depth_capture_stereo.py but got an error saying camera unrecognizable


Answer 4 
Ran the calibration test from luxinos documentation
Luxinos caliberation Intrinsic matrix:
[[485.76662085   0.         314.22305371]
 [  0.         484.6142758  177.89428718]
 [  0.           0.           1.        ]]

Our program Intrinsic matrix:
[[396.25760498   0.         313.0033623 ]
 [  0.         411.10607861 251.44362313]
 [  0.           0.           1.        ]]


