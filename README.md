# RoadSense – Driving Scene & Object Detection

RoadSense is a deep learning project that tackles two key perception tasks in autonomous driving:

1. **Scene Classification** – Predicting the environment type, time of day, and weather condition using a custom multi-head ResNet18 model.
2. **Object Detection** – Identifying vehicles, traffic lights (with color), and road signs using YOLOv5.

The project is trained on the BDD100K dataset. Scene classification uses a shared convolutional base with three output heads for multi-task learning, while YOLOv5 is used for bounding-box object detection.

**Models Used:**
- Multi-task ResNet18 for scene, time, and weather classification
- YOLOv5 for object detection and localization

Both models were chosen for their balance between speed and performance in real-world driving datasets.

