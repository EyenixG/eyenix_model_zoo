# Object Detection Models
These are publicly pre-trained models officially supported by the EYENIX Model Zoo: 

Compare the original FP32(GPU) model accuracy with the INT8(NPU) accuracy optimized for fast, low-power inference on the NPU.

- **.bin file** : A ready-to-deploy binary for direct inference on the EN683 SoC.
- **_xz.bin file** : A compressed version of the quantized weights in XZ format. It runs the same as the .bin file but reduces size, making it more efficient for uploading to flash memory.
- **DRAM Usage** : Main memory size required for NPU operation.
  
### COCO (80classes) Model
> ⚡**Train Dataset:** COCO 2017 (train)  
> ⚡**Test Dataset:** COCO 2017 (val)   


|Model|mAP[0.50:0.95:0.05] (FP32)|mAP[0.50:0.95:0.05] (INT8)| mAP[0.50] (FP32)|mAP[0.50] (INT8)|Input Resolution(HxWxC)|DRAM Usage|binary|binary(xz compress)|label_file|
|:-----:|:---:|:---:|:---:|:---:|:-------:|:---:|:---:|:---:|:---:|
|yolov5s|37.4 |35.5 |56.8 |55.3 |640x640x3|17MB |[yolov5s.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov5s.bin)  |[yolov5s_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov5s_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|
|yolov5m|45.3 |43.6 |64.1 |63.2 |640x640x3|36MB |[yolov5m.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov5m.bin)  |[yolov5m_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov5m_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|
|yolov6m|50.0 |49.5 |66.9 |66.5 |640x640x3|53MB |[yolov6m.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov6m.bin)  |[yolov6m_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov6m_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|
|yolov7 |50.9 |49.8 |69.5 |69.0 |640x640x3|60MB |[yolov7.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov7.bin)   |[yolov7_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov7_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|
|yolov8n|37.4 |36.2 |52.9 |51.8 |640x640x3|11MB |[yolov8n.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov8n.bin)  |[yolov8n_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov8n_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|
|yolov8s|44.9 |44.3 |62.1 |61.4 |640x640x3|20MB |[yolov8s.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov8s.bin)  |[yolov8s_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov8s_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|
|yolov8m|50.3 |47.0 |67.5 |64.0 |640x640x3|41MB |[yolov8m.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov8m.bin)  |[yolov8m_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov8m_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|
|yolov8l|54.0 |49.5 |70.0 |66.6 |640x640x3|63MB |[yolov8l.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov8l.bin)  |[yolov8l_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov8l_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|
|yolov9t|38.0 |37.3 |53.1 |52.2 |640x640x3|11MB |[yolov9t.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov9t.bin)  |[yolov9t_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov9s_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|
|yolov9s|46.3 |45.8 |62.8 |62.3 |640x640x3|17MB |[yolov9s.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov9s.bin)  |[yolov9s_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov9s_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|
|yolov9m|51.2 |50.9 |68.4 |68.0 |640x640x3|39MB |[yolov9m.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov9m.bin)  |[yolov9m_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov9m_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|
|yolov9c|52.6 |52.1 |69.7 |69.4 |640x640x3|46MB |[yolov9c.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov9c.bin)  |[yolov9c_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolov9c_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|
|yolox-s|40.5 |39.6 |59.3 |58.7 |640x640x3|32MB |[yolox-s.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolox_s.bin)  |[yolox-s_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolox_s_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|
|yolox-m|46.9 |46.1 |65.6 |65.4 |640x640x3|45MB |[yolox-m.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolox_m.bin)  |[yolox-m_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/yolox_m_xz.bin)|[labels.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/coco_label.txt)|

---
&#160;
