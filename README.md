# Vehicle-Proximity-Warning-System
Detect cars nearby and warn those cars to a driver by drawing red boxes on them. <br> Designed to support drivers in the driving environment at high speed with many cars, such as racing, track driving, and driving on the highway.
<br>
- Detect objects from a real-time video and Classify(close object: red, distant object: green) dependent on proximity using a pre-trained YOLO model
- Process a video with OpenCV and Predict each object in an image of a frame through a CNN by implementing non-max suppression with IoU(Intersection over Union)
