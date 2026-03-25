# Classification Models
These are publicly pre-trained models officially supported by the EYENIX Model Zoo:

Compare the original FP32(GPU) model accuracy with the INT8(NPU) accuracy optimized for fast, low-power inference on the NPU.

- **.bin file** : A ready-to-deploy binary for direct inference on the EN683 SoC.
- **_xz.bin file** : A compressed version of the quantized weights in XZ format. It runs the same as the .bin file but reduces size, making it more efficient for uploading to flash memory.
- **DRAM Usage** : Main memory size required for NPU operation.

### ImageNet
> ⚡**Train Dataset:** ImageNet (train)  
> ⚡**Test Dataset:** ImageNet (val)  


|Model|TOP-1 Accuracy (FP32)|TOP-1 Accuracy (INT8)|TOP-5 Accuracy (FP32)|TOP-5 Accuracy (INT8)|Input Resolution(HxWxC)|DRAM Usage|binary|binary(xz compress)|label_file|
|:-----:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|mobilenetv2|71.88%|67.67%|90.29%|89.92%|224 x 224 x 3|3.7MB|[mobilenetv2.bin]()|[mobilenetv2_xz.bin]()|[labels.txt]()|
|Resnet18|69.76%|69.39%|89.08%|88.88%|224 x 224 x 3|13MB|[resnet18.bin]()|[resnet18_xz.bin]()|[labels.txt]()|
|Resnet34|73.31%|73.07%|91.42%|91.28%|224 x 224 x 3|23MB|[resnet34.bin]()|[resnet34_xz.bin]()|[labels.txt]()|
|Resnet50|76.13%|75.81%|92.86%|92.82%|224 x 224 x 3|27MB|[resnet50.bin]()|[resnet50_xz.bin]()|[labels.txt]()|
|Resnet101|77.38%|77.04%|93.55%|93.43%|224 x 224 x 3|46MB|[resnet101.bin]()|[resnet101_xz.bin]()|[labels.txt]()|
|Resnet152|78.32%|77.34%|94.05%|93.54%|224 x 224 x 3|62MB|[resnet152.bin]()|[resnet152_xz.bin]()|[labels.txt]()|
|Efficientnet-lite0|72.13%|71.93%|90.44%|90.35%|224 x 224 x 3|5.6MB|[efficientnet_lite0.bin]()|[efficientnet_lite0_xz.bin]()|[labels.txt]()|
|Efficientnet-lite1|74.91%|74.71%|92.15%|92.1%|240 x 240 x 3|6.1MB|[efficientnet_lite1.bin]()|[efficientnet_lite1_xz.bin]()|[labels.txt]()|
|Efficientnet-lite2|77.2%|77.01%|93.63%|93.48%|260 x 260 x 3|6.8MB|[efficientnet_lite2.bin]()|[efficientnet_lite2_xz.bin]()|[labels.txt]()|
|Efficientnet-lite3|78.89%|78.66%|94.38%|94.23%|280 x 280 x 3|9.3MB|[efficientnet_lite3.bin]()|[efficientnet_lite3_xz.bin]()|[labels.txt]()|
|Efficientnet-lite4|80.37%|80.08%|95.03%|94.96%|300 x 300 x 3|14MB|[efficientnet_lite4.bin]()|[efficientnet_lite4_xz.bin]()|[labels.txt]()|
|Osnet_1.0|74.66%|73.33%|92.13%|91.38%|224 x 224 x 3|5.9MB|[osnet_1.0.bin]()|[osnet_1.0_xz.bin]() |[labels.txt]()|  


---
&#160;
