# Yolov5-with-MediaPipe
This repository is used to store the code that uses the combination of mediapipe and yolov5, which realizes the detection of a specific area with yolo around the hand detected by mediapipe
# my idea
Most of the time, when we are detecting objects around our hands, there will be a lot of distractors that affect our detection, which will result in detections that we don't want. Use MediaPipe to fix the detection frame to a range, and feed the detection frame to yolo in real time, which can meet the needs of specific scenarios
![image](https://user-images.githubusercontent.com/41555798/188525354-08fee876-e0b0-4c4b-be54-8dcb954d0dc1.png)

As shown in the figure above, when using yolov5 to detect the pencil in the hand, you only need to use MediaPipe to obtain the hand detection frame. After the hand detection frame information is obtained, use yolov5 to detect the pencil in the detection frame.
