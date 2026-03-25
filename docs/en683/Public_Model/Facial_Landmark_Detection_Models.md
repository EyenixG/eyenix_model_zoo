# Facial Landmark Detection Models
These are publicly pre-trained models officially supported by the EYENIX Model Zoo: 

Compare the original FP32(GPU) model accuracy with the INT8(NPU) accuracy optimized for fast, low-power inference on the NPU.

- **.bin file** : A ready-to-deploy binary for direct inference on the EN683 SoC.
- **_xz.bin file** : A compressed version of the quantized weights in XZ format. It runs the same as the .bin file but reduces size, making it more efficient for uploading to flash memory.
- **DRAM Usage** : Main memory size required for NPU operation.

### WFLW Model 

> ⚡**Train Dataset:** WFLW (train)   
> ⚡**Test Dataset:** WFLW (val)    

|Model|Accuracy (FP32)|Accuracy (INT8)|Input Resolution(HxWxC)|DRAM Usage|binary|binary(xz compress)|
|:-----:|:---:|:---:|:---:|:-------:|:---:|:---:|
| PIPNet     |55.59 |51.91 | 256x256x3 | 10.73 MB | [pipnet.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/pipnet.bin)  | [pipnet_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/pipnet_xz.bin)  |


&#160;

### widerface Model
> ⚡**Train Dataset:** widerface (train)   
> ⚡**Test Dataset:** widerface (val)   

|Model|Accuracy (FP32)|Accuracy (INT8)|Input Resolution(HxWxC)|DRAM Usage|binary|binary(xz compress)|label_file|
|:-----:|:---:|:---:|:---:|:---:|:-------:|:---:|:---:|
| RetinaFace     |Easy:88.16, Medium:81.37, Hard:51.21 |Easy:87.05, Medium:79.50, Hard:61.04 | 640x640x3 | 8.08 MB | [retinaface.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/retinaface.bin)  | [retinaface_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/retinaface_xz.bin)  | [face_label.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/face_label.txt) |
| Blazeface     |Easy:87.71, Medium:81.67, Hard:63.91 |Easy:87.21, Medium:80.19, Hard:50.10 | 640x640x3  | 8.45MB | [blazeface.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/blazeface.bin) | [blazeface_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/blazeface_xz.bin) | [face_label.txt](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/face_label.txt) |


---
&#160;
