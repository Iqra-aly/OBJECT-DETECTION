# OBJECT-DETECTION
Object Detection Model for Road Conditions and Turns in Gilgit
In this group project, we embarked on an engaging journey to develop an object detection model aimed at identifying various road conditions and turns in images captured on roads in Gilgit, Baltistan. The primary goal was to enable the model to detect right turns, left turns, straight roads, and unexpected road conditions such as landslides. This project provided us with hands-on experience in data gathering, data labeling, and the implementation of object detection models, specifically YOLO (You Only Look Once).

# Data Collection and Labeling
We collected a total of 337 images from various locations in Gilgit, including Sultanabad, Jutial, and Danyore. These images were divided into a training set (70%), test set (20%), and validation set (10%). The data was meticulously labeled using Roboflow into five distinct classes: Landslides, Left-Turn, Other, Right-Turn, and Straight-Road.

# Model Training and Implementation
The YOLOv5 framework was used for the implementation of the object detection model. The training process involved setting up the environment, cloning the YOLOv5 repository, and preparing the dataset. The model was trained with the specified parameters, and the performance was evaluated on the test set.

# Results and Evaluation
The trained YOLO model was evaluated using various metrics, including precision, recall, and mean Average Precision (mAP). The results showed that the model could effectively identify and classify the different road conditions and turns. Example images from the test set were used to visualize the model's detections, showing bounding boxes and class labels.

# Conclusion
Through this project, we successfully developed an object detection model capable of identifying various road conditions and turns. The model was trained using a dataset collected from roads in Sultanabad, Jutial, and Danyore in Gilgit and annotated into five classes. By utilizing the YOLOv5 framework, we were able to achieve precise detections and classifications. The process provided us with valuable insights and practical experience in data collection, annotation, model training, and evaluation.
