# Lane & Vehicle Detection System

OpenCV image processing algorithm for lane & vehicle detection in autonomous cars

# Features to Complete

* Processed frame for canny edges and hough lines (Done)
* Cut areas outside region of interest to remove noise (Not efficient yet - use cv2.warpPerspective() to make a linear model, then form histogram of x-coordinate with most white/yellow pixels)
* Overlaid two averaged lines per frame (Not smooth - should fix into a rolling average)
* Filled rectangular area between lines (Done)
* Transform captured frame into non-distorted frame using cv2.undistort() (TODO)
* Vehicle & traffic sign detection (TODO - train ML model to do this)
* Lane detection for side mirrors (TODO)
