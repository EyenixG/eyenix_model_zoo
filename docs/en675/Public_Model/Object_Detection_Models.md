# Object Detection Models
These are publicly pre-trained models officially supported by the EYENIX Model Zoo: 

- Compare the original FP32(GPU) model accuracy with the INT8(NPU) accuracy optimized for fast, low-power inference on the NPU.

- The **.bin file** is a ready-to-deploy binary for direct inference on the EN675 SoC — no additional conversion needed.
- The **.cfg file** is used alongside the model binary during inference to configure user-defined options based on the model architecture, such as confidence thresholds and class settings.
  
### COCO (80classes) Model
> ⚡**Train Dataset:** COCO 2017 (train)   
> ⚡**Test Dataset:** COCO 2017 (val)   

|Model|mAP[0.50:0.95:0.05] (FP32)|mAP[0.50:0.95:0.05] (INT8)| mAP[0.50] (FP32)|mAP[0.50] (INT8)|Input Resolution(HxWxC)|Inference time|DRAM Usage|Compile Results|Cfg|
|:-----:|:---:|:---:|:---:|:---:|:-------:|:---:|:---:|:---:|:---:|
|640_640_eyenix_model_v3 (yolov5s_silu)|39.3 |36.0 |58.6 |55.1 |640x640x3|78ms  |55.5MB |[yolov5s_silu_coco.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/yolov5s_silu_coco.bin)  |[yolov5s_silu_coco.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/yolov5s_silu_coco.cfg)|
|640_640_eyenix_model_v3 (yolov5s_relu6)|38.1 |35.2 |57.6 |54.4 |640x640x3|66ms  |53.8MB |[yolov5s_relu6_coco.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/yolov5s_relu6_coco.bin)  |[yolov5s_relu6_coco.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/yolov5s_relu6_coco.cfg)|
|640_640_eyenix_model_v3 (yolov7_tiny_silu)|39.1 |35.1 |57.8 |54.0 |640x640x3|72ms  |47.0MB |[yolov7_tiny_silu_coco.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/yolov7_tiny_silu_coco.bin) |[yolov7_tiny_silu_coco.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/yolov7_tiny_silu_coco.cfg)|
|640_640_eyenix_model_v3 (yolov7_tiny_relu6)|38.2 |34.6 |56.5 |53.3 |640x640x3|61ms  |45.9MB |[yolov7_tiny_relu6_coco.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/yolov7_tiny_relu6_coco.bin)|[yolov7_tiny_relu6_coco.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/yolov7_tiny_relu6_coco.cfg)|


&#160;

### Widerface Model
> ⚡**Train Dataset:** Widerface (train)    
> ⚡**Test Dataset:** Widerface (val) 

|Model|Widerface easy (FP32)|Widerface easy (INT8)|Input Resolution(HxWxC)|Inference time|DRAM Usage|Compile Results|Cfg|
|:-----:|:---:|:---:|:---:|:---:|:-------:|:---:|:---:|
|640_640_eyenix_model_v3 (yolov7_tiny_silu)|94.4 |93.3 |640x640x3|65ms  |40.9MB |[yolov7_tiny_silu_widerface.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/yolov7_tiny_silu_widerface.bin) |[yolov7_tiny_silu_widerface.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/yolov7_tiny_silu_widerface.cfg)|
|640_640_eyenix_model_v3 (yolov7_tiny_relu6)|93.5 |91.2 |640x640x3|55ms  |40.4MB |[yolov7_tiny_relu6_widerface.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/yolov7_tiny_relu6_widerface.bin)|[yolov7_tiny_relu6_widerface.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/yolov7_tiny_relu6_widerface.cfg)|


&#160;