# HighwayTrafficDetector

Highway Traffic Project 

Using the pre-trained model object detection from model files from Tensorflow model ZOO to detect traffic and violations on highways.

The project aims to develop a system that can detect traffic violations, particularly motorcycles entering highways, which is prohibited in Indonesia to prevent accidents. 

The system utilizes a pre-trained object detection model, to detect vehicles, counting cars and motorcycles on highways.

Object Detection Model is a pre-trained object detection model that uses the Single Shot Detector (SSD) algorithm with the MobileNet-V2 backbone and is trained on the COCO dataset. 

This model is chosen for its high accuracy and efficiency in detecting objects in images.

System Architecture The system architecture consists of the following components:

Camera: A camera is installed on the highway to capture images of the traffic.

Object Detection: The captured images are fed into the model and by specifying logic only to classid car and motorcycle for counting.

Violation Detection: The detected objects for classid motorcycle are analyzed to detect any violations, such as motorcycles entering the highway.

Alert System: If a violation is detected, an alert is shown in camera.

Advantages The system has several advantages, including:

Real-time detection: The system can detect violations in real-time, allowing for quick action to be taken.

Cost-effective: The system is cost-effective as it uses a pre-trained model and does not require extensive training data.

