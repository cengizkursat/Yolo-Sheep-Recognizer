# opencv-yolo-cuda
 First attempt to create a program recognizing sheep.

How to make the program work: 

1) Firstly, install the dependencies that this program relies on. They are:

-Python 3.7.x
-OpenCV-Python (pip install opencv-contrib-python or pip install opencv-python)
-Numpy (installed alongisde OpenCV-Python if not installed already)
-Imultils (pip install imutils)

2) Download the yolo weight file from the link provided:

https://dosya.co/ab1nllscrvx9/yolov3.weights.html

3) Then, (assuming you have created a virtual environment and placed the repo inside the virtual environment)

For Picture Processing: 

3.1) Put your picture(s) inside the directory ..\opencv-yolo-cuda\images

Optional Step: If you installed the dependencies on a virtual environment, activate the virtual environment.

3.2) Execute the code "python yolo.py --image images/$NAME_OF_IMAGE.jpg --yolo yolo-coco" from Powershell.

For Video Processing: 

3.3) Put your video(s) inside the directory ..\opencv-yolo-cuda\example_videos

Optional Step: If you installed the dependencies on a virtual environment, activate the virtual environment.

3.4) Execute the code "python yolo-video-2.py --yolo yolo-coco --input example_videos/$NAMEOFVIDEO.mp4 --output output_videos/$NAMEOFOUTPUTVIDEO.mp4 --display 0"


 
