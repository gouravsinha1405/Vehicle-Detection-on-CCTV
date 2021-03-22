### Vehicle-Detection-on-CCTV
For viewing the notebook click on the link : https://nbviewer.jupyter.org/github/gouravsinha1405/Vehicle-Detection-on-CCTV/blob/main/Part%204%20-%20Vehicle%20Detection%20in%20videos.ipynb
- It is not always mandatory to use yolov3 to build an object detector.
- By using cv techniques only one can very much build an object detection algorithm that is cheap and effective over static cameras installed on highways.
- You can improve this framework to detect count of vehicles and can also analyse the pattern during rush hours.
- The first approach works well with static cameras installed on highways.
- The second approach using car.xml is less accurate when camera is non static. In that case we should rather use YOLO or Faster RCNN
- In first approach I used background suptraction then i create contours on vehicles.After thresholding and putting constraint n contour area I could locate the vehicles in the video. Next step was to put rectangular boxes over the vehicles.
