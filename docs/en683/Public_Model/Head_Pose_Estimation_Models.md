# Head Pose Estimation Models
These are publicly pre-trained models officially supported by the EYENIX Model Zoo: 

Compare the original FP32(GPU) model accuracy with the INT8(NPU) accuracy optimized for fast, low-power inference on the NPU.

- **.bin file** : A ready-to-deploy binary for direct inference on the EN683 SoC.
- **_xz.bin file** : A compressed version of the quantized weights in XZ format. It runs the same as the .bin file but reduces size, making it more efficient for uploading to flash memory.
- **DRAM Usage** : Main memory size required for NPU operation.
  
### 300W-LP Model
> ⚡**Train Dataset:** 300W-LP (train)   
> ⚡**Test Dataset:** AFLW2000 (val)   


|Model|MAE (FP32)|MAE (INT8)|Input Resolution(HxWxC)|DRAM Usage|binary|binary(xz compress)|
|:-----:|:---:|:---:|:---:|:-------:|:---:|:---:|
| 6DRepNet     |4.6369 |4.6433 | 224x224x3 | 7.14 MB | [6drepnet.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/6drepnet.bin) | [6drepnet_xz.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN683_MODEL/6drepnet_xz.bin)  |


---
&#160;
