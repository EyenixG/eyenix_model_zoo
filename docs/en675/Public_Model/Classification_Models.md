# Classification Models
These are publicly pre-trained models officially supported by the EYENIX Model Zoo: 

- Compare the original FP32(GPU) model accuracy with the INT8(NPU) accuracy optimized for fast, low-power inference on the NPU.

- The **.bin file** is a ready-to-deploy binary for direct inference on the EN675 SoC — no additional conversion needed.
- The **.cfg file** is used alongside the model binary during inference to configure user-defined options based on the model architecture, such as confidence thresholds and class settings.
  
### ImageNet
> ⚡**Train Dataset:** ImageNet (train)  
> ⚡**Test Dataset:** ImageNet (val)  
 
|Model|TOP-1 Accuracy (FP32)|TOP-1 Accuracy (INT8)|TOP-5 Accuracy (FP32)|TOP-5 Accuracy (INT8)|Input Resolution(HxWxC)|Inference time|DRAM Usage|Compile Results|Cfg|
|:-----:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|mobilenetv2| 71.88%| 66.6%| 90.29%| 87.2%|224 x 224 x 3| 3ms| 16.36MB|[mobilenetv2.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/mobilenetv2.bin)|[mobilenetv2.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/mobilenetv2.cfg)|


&#160;



