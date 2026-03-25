# Pose Estimation Models
These are publicly pre-trained models officially supported by the EYENIX Model Zoo: 

Compare the original FP32(GPU) model accuracy with the INT8(NPU) accuracy optimized for fast, low-power inference on the NPU.

- **.bin file** : A ready-to-deploy binary for direct inference on the EN683 SoC.
- **_xz.bin file** : A compressed version of the quantized weights in XZ format. It runs the same as the .bin file but reduces size, making it more efficient for uploading to flash memory.
- **DRAM Usage** : Main memory size required for NPU operation.
  
### COCO Pose (1class) Model
> ⚡**Train Dataset:**  COCO 2017 pose (train)  
> ⚡**Test Dataset:**  COCO 2017 pose (val)

|Model|mAP(pose)OKS=[0.50:0.95:0.05] (FP32)|mAP(pose)OKS=[0.50:0.95:0.05] (INT8)| mAP(pose)OKS=[0.50] (FP32)|mAP(pose)OKS=[0.50] (INT8)|Input Resolution(HxWxC)|DRAM Usage|binary|binary(xz compress)|label_file|
|:-----:|:---:|:---:|:---:|:---:|:-------:|:---:|:---:|:---:|:---:|
|yolov8s-pose|59.9 |56.1 |86.4 |85.3 |640x640x3|21MB |[yolov8s_pose.bin]()  |[yolov8s_pose_xz.bin]()|[labels.txt]()|
|yolov8m-pose|65.0 |61.1 |88.7 |88.0 |640x640x3|40MB |[yolov8m_pose.bin]()  |[yolov8m_pose_xz.bin]()|[labels.txt]()|


---
&#160;

