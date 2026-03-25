# Face Recognition Models
These are publicly pre-trained models officially supported by the EYENIX Model Zoo: 

Compare the original FP32(GPU) model accuracy with the INT8(NPU) accuracy optimized for fast, low-power inference on the NPU.

- **.bin file** : A ready-to-deploy binary for direct inference on the EN683 SoC.
- **_xz.bin file** : A compressed version of the quantized weights in XZ format. It runs the same as the .bin file but reduces size, making it more efficient for uploading to flash memory. 
- **DRAM Usage** : Main memory size required for NPU operation.

### Align-CASIA-Webface

> ⚡**Train Dataset:** Align-CASIA-Webface   
> ⚡**Test Dataset:** LFW-funneled  

|Model|Accuracy (FP32)|Accuracy (INT8)|Input Resolution(HxWxC)|DRAM Usage|binary|binary(xz compress)|
|:-----:|:---:|:---:|:---:|:-------:|:---:|:---:|
| mobilefacenet     |99.07 |98.85 | 112x112x3  | 1.11 MB | [mobilefacenet.bin]()  | [mobilefacenet_xz.bin]()  |


&#160;

### VGGFace2 Model 

> ⚡**Train Dataset:** VGGFace2   
> ⚡**Test Dataset:** LFW-funneled  

|Model|Accuracy (FP32)|Accuracy (INT8)|Input Resolution(HxWxC)|DRAM Usage|binary|binary(xz compress)|
|:-----:|:---:|:---:|:---:|:-------:|:---:|:---:|
| FaceNet     |99.34 |99.23 | 160x160x3 | 23.11 MB | [facenet.bin]()  | [facenet_xz.bin]() |


---
&#160;
