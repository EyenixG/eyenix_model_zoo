# Instance Segmentation Models
These are publicly pre-trained models officially supported by the EYENIX Model Zoo: 

Compare the original FP32(GPU) model accuracy with the INT8(NPU) accuracy optimized for fast, low-power inference on the NPU.

- **.bin file** : A ready-to-deploy binary for direct inference on the EN683 SoC.
- **_xz.bin file** : A compressed version of the quantized weights in XZ format. It runs the same as the .bin file but reduces size, making it more efficient for uploading to flash memory.
- **DRAM Usage** : Main memory size required for NPU operation.
  
### COCO (80classes) Model
> ⚡**Train Dataset:**  COCO 2017 (train)  
> ⚡**Test Dataset:**  COCO 2017 (val)

|Model|mAP(mask)IOU=[0.50:0.95:0.05] (FP32)|mAP(mask)IOU=[0.50:0.95:0.05] (INT8)| mAP(mask)IOU=[0.50] (FP32)|mAP(mask)IOU=[0.50] (INT8)|Input Resolution(HxWxC)|DRAM Usage|binary|binary(xz compress)|label_file|
|:-----:|:---:|:---:|:---:|:---:|:-------:|:---:|:---:|:---:|:---:|
|yolov8s-seg|36.5 |36.2 |58.1 |57.4 |640x640x3|22MB |[yolov8s_seg.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov8s_seg.bin)  |[yolov8s_seg_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov8s_seg_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|
|yolov8m-seg|40.3 |39.9 |63.3 |62.5 |640x640x3|46MB |[yolov8m_seg.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov8m_seg.bin)  |[yolov8m_seg_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov8m_seg_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|

---
&#160;

