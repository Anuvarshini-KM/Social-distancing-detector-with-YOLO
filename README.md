SOCIAL DISTANCING DETECTOR

Initially ,make sure that you have installed all the dependencies in the requirement list.

Create a new folder in the drive.
Yolo weights must be installed too,which can be installed from here.
https://pjreddie.com/media/files/yolov3.weights

And then make sure that the USE_GPU = TRUE in the file.

At last ,to get the output,use
python social_distancing_detector.py --input pedestrians.mp4 --output output.avi --display 0

Use display 1 to get the output


