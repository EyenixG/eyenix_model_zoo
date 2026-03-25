# Release Models
The EN683 NPU supports two **object detection release models** based on the YOLOv8s architecture.  
> **6-Class Object Detection Model**

- Detects: Person, Car, Motorbike, Bicycle, Truck, Bus  
- Optimized for multi-class detection in real-world surveillance scenarios

> **Face Detection Model**
- Detects: Face
- Tailored for high-precision facial recognition tasks

&#160;

## **6-Class Object Detection Model**
### 🧩 **Class** : Person, Car, Motorbike, Bicycle, Truck, Bus
  

|Model|Train Dataset|Input Resolution(WxHxC)|Binary|Binary(xz compress)|label_file|Total DRAM Size|
|:-----:|:---:|:---:|:---:|:---:|:---:|:---:|
|yolov8s|EYENIX_DB_V2_6class|832x480x3|[eyenix_6class.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/eyenix_6class.bin)|[eyenix_6class_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/eyenix_6class_xz.bin)|[6class_labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/6class_labels.txt)|19MB|


&#160;
## **Face Detection Model**
### 🧩 **Class** : Face  

|Model  |Train Dataset|Input Resolution(WxHxC)|Binary|Binary(xz compress)|label_file|Total DRAM Size|
|:-----:|:-----------:|:---------------------:|:----:|:---:|:---:|:---:|
|yolov8s|EYENIX_DB_V2_face |832x480x3         |[eyenix_face.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/eyenix_face.bin)|[eyenix_face_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/eyenix_face_xz.bin)|[face_label.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/face_label.txt)|19MB|


&#160;


## 🏆 Performance of released model
### ▶ 6 class Model  (yolov8s 832x480x3)
- **class** : Person, Car, Motorbike, Bicycle, Truck, Bus
- Confidence threshold : 0.1
- IOU threshold : 0.5
<img src="https://github.com/user-attachments/assets/8d2f5194-6782-462a-86a5-25ae0e77051a" width="500"/>
<img src="https://github.com/user-attachments/assets/7d77b009-42fb-4aba-adb9-af7554ab9292" width="500"/>


&#160;

### ▶ Face Model (yolov8s 832x480x3)
- **class** : Face
- Confidence threshold : 0.1
- IOU threshold : 0.5

<img src="https://github.com/user-attachments/assets/dee74c32-47cf-41c8-bfd3-f0ab660d5c69" width="500"/>


