# Airplanes detection with YOLO
**Dataset details:** https://universe.roboflow.com/datasets-84fcz/airplane-vgvsf/dataset/1

**Dataset description**

Dataset contains 4140 images of airplanes. For training dataset we'll take 2898 (70%) images and validate on 828 (20%).

**Model**

For object detection we will use yolov8s model from Ultralytics

**Confusion matrix**

![image](https://github.com/D2J3D/Airplanes_detection/assets/120342275/7c8fde84-9440-42de-a4ff-bcace03bb9c0)

**Loss and metrics**

![image](https://github.com/D2J3D/Airplanes_detection/assets/120342275/206b9ff0-01fb-4e88-baf6-435d742794e4)

**Planned improvments**

As the graphs shows we already have pretty nice results - the model converges and the training might me continued. 
But there are steel techniques that could be implementec for achieving better results.
- [ ] Use more data augmentation to avoid overfitting
- [ ] Use trained model for more complex task of counting airplanes on the airfield (bird's eye view shots)
