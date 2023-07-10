# Object-Detection-using-YoloV3
This project showcases real-time object detection using the YOLOv3 (You Only Look Once) algorithm combined with the power of OpenCV. The YOLOv3 algorithm is a state-of-the-art deep learning model known for its remarkable accuracy and efficiency in detecting objects within images and videos.

To run the project :-

First Download the weight file from https://pjreddie.com/media/files/yolov3.weights and paste it inside the darknet folder(which is there inside the 'Object detection using Image' and 'Object detection using Video' folders)

The project is divided into three main files, each focusing on a different aspect of object detection:

--Image Object Detection (yolo.py) :
In this file, the project demonstrates how to utilize the pre-trained YOLOv3 model to detect objects within static images. By leveraging the powerful YOLOv3 model, it becomes possible to identify and label objects of interest, such as people, cars, animals, and various other common objects present in the image.

To run this file write the following command :
python yolo.py --image images/baggage_claim.jpg

--Video Object Detection (yolo_video.py) :
This file expands upon the image object detection by applying the YOLOv3 algorithm to real-time video streams. By utilizing OpenCV's video processing capabilities, the project enables users to detect and track objects of interest as they move within a video. The detected objects are annotated in real-time, providing a visual representation of the detected objects within the video stream.

To run this file write the following command :
python yolo_video.py --input videos/airport.mp4 --output output/airport_output.avi --yolo darknet/data

--Real-Time Camera or Webcam Object Detection (real_time_object_detection.py) :
The final file in the project demonstrates the real-time object detection capabilities using a live camera feed or webcam. By leveraging OpenCV's video capturing functionality, the project enables users to detect and track objects in real-time as they appear within the camera's field of view. This file allows for immediate interaction with the YOLOv3 model, offering a seamless and responsive object detection experience.

To run this file write the following command :
python real_time_object_detection.py

With this project, you can gain hands-on experience in utilizing pre-trained deep learning models, specifically the YOLOv3 algorithm, for real-time object detection. By combining the power of YOLOv3 with OpenCV's image and video processing capabilities, you can detect and track objects with impressive accuracy and efficiency in various contexts, ranging from individual images to real-time video streams.

