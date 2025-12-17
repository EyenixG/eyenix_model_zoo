# Release Models
The EN675 NPU supports two **object detection release models**. Each model is available with different input resolution sizes, allowing users to choose between higher accuracy or faster inference. Larger input sizes generally provide better detection performance, while smaller sizes offer lower latency—highlighting the trade-off between accuracy and speed.
> **6-Class Object Detection Model**

- Detects: Person, Car, Motorbike, Bicycle, Truck, Bus  
- Optimized for multi-class detection in real-world surveillance scenarios

> **Face Detection Model**
- Detects: Face
- Tailored for high-precision facial recognition tasks
&#160;

## **6-Class Object Detection Model**
### 🧩 **Class** : Person, Car, Motorbike, Bicycle, Truck, Bus


|Model|Binary|Cfg|HAAS Platform binary|Total DRAM Size|Inference Time|
|:-----:|:---:|:---:|:---:|:---:|:---:|
|320_320_eyenix_model_v1|[od6class_320_v1.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/od6class_320_v1.bin)|[od6class_320_v1.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/od6class_320_v1.cfg)|[320_320_eyenix_model_v1_haas_model.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model_HAAS/320_320_eyenix_model_v1_haas_model.bin)|11MB|13ms|
|512_512_eyenix_model_v1|[od6class_512_v1.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/od6class_512_v1.bin)|[od6class_512_v1.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/od6class_512_v1.cfg)|[512_512_eyenix_model_v1_haas_model.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model_HAAS/512_512_eyenix_model_v1_haas_model.bin)|18MB|20ms|
|640_640_eyenix_model_v1|[od6class_640_v1.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/od6class_640_v1.bin)|[od6class_640_v1.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/od6class_640_v1.cfg)|[640_640_eyenix_model_v1_haas_model.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model_HAAS/640_640_eyenix_model_v1_haas_model.bin)|25MB|29ms|
|384_672_eyenix_model_v2|[od6class_384_672_v2.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/od6class_384_672_v2.bin)|[od6class_384_672_v2.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/od6class_384_672_v2.cfg)|[672_384_eyenix_model_v2_haas_model.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model_HAAS/672_384_eyenix_model_v2_haas_model.bin)|22MB|28ms|
|384_672_eyenix_model_v3 (tiny) - release|[od6class_384_672_v3_release.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/od6class_384_672_v3_release.bin)|[od6class_384_672_v3_release.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/od6class_384_672_v3_release.cfg)|[EYENIX_MODEL_V3_6class_yolov7_haas_model.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model_HAAS/EYENIX_MODEL_V3_6class_yolov7_haas_model.bin)|30MB|40ms|
|384_672_eyenix_model_v3 (tiny) - update|[od6class_384_672_v3.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/od6class_384_672_v3.bin)|[od6class_384_672_v3.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/od6class_384_672_v3.cfg)|[384_672_6class_haas_model.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model_HAAS/384_672_6class_haas_model.bin)|30MB|40ms|
|512_864_eyenix_model_v3 (tiny) - update|[od6class_512_864_v3.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/od6class_512_864_v3.bin)|[od6class_512_864_v3.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/od6class_512_864_v3.cfg)|[512_864_6class_haas_model.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model_HAAS/512_864_6class_haas_model.bin)|46MB|62ms|
> ⚠️ **Caution:** 
> HAAS Platform binary must be used build_unified_bin_ai_analog.py in NPU SDK. If you don't have NPU SDK, please contact EYENIX System Solution Part.

&#160;
## **Face Detection Model**
### 🧩 **Class** : Face  


|Model|Binary|Cfg|HAAS Platform binary|Total DRAM Size|Inference Time|
|:-----:|:---:|:---:|:---:|:---:|:---:|
|320_320_eyenix_model_face_v1|[face_320_v1.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/face_320_v1.bin)|[face_320_v1.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/face_320_v1.cfg)|[320_320_eyenix_model_face_v1_haas_model.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model_HAAS/320_320_eyenix_model_face_v1_haas_model.bin)|12MB|11ms|
|448_448_eyenix_model_face_v1|[face_448_v1.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/face_448_v1.bin)|[face_448_v1.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/face_448_v1.cfg)|[448_448_eyenix_model_face_v1_haas_model.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model_HAAS/448_448_eyenix_model_face_v1_haas_model.bin)|23MB|21ms|
|512_512_eyenix_model_face_v1|[face_512_v1.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/face_512_v1.bin)|[face_512_v1.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/face_512_v1.cfg)|[512_512_eyenix_model_face_v1_haas_model.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model_HAAS/512_512_eyenix_model_face_v1_haas_model.bin)|31MB|26ms|
|288_512_eyenix_model_face_v2|[face_288_512_v2.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/face_288_512_v2.bin)|[face_288_512_v2.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/face_288_512_v2.cfg)|[512_288_eyenix_model_face_v2_haas_model.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model_HAAS/512_288_eyenix_model_face_v2_haas_model.bin)|14MB|17ms|
|288_512_eyenix_model_face_v3 (tiny)|[face_288_512_v3.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/face_288_512_v3.bin)|[face_288_512_v3.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/face_288_512_v3.cfg)|[face_512_288_v3_haas_model.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model_HAAS/face_512_288_v3_haas_model.bin)|21MB|25ms|
|384_672_eyenix_model_face_v3 (tiny)|[face_384_672_v3.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/face_384_672_v3.bin)|[face_384_672_v3.cfg](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model/face_384_672_v3.cfg)|[face_672_384_v3_haas_model.bin](https://github.com/EyenixG/eyenix_model_zoo/releases/download/EN675_Model_HAAS/face_672_384_v3_haas_model.bin)|29MB|40ms|

> ⚠️ **Caution:** For the eyenix_face_model_v1, the maximum confidence score is **64** (not 256).  
> Please update the ClassConfTH array in npu_conf.c accordingly to ensure correct behavior.  
> HAAS Platform binary must be used build_unified_bin_ai_analog.py in NPU SDK. If you don't have NPU SDK, please contact EYENIX System Solution Part.


&#160;


## 🏆 Performance of released model
### ▶ 6 class Model
- **class** : Person, Car, Motorbike, Bicycle, Truck, Bus
- Boxes covering more than 15% of the total area have been removed

### Model - 320x320 eyenix model v1  
<img src="https://github.com/user-attachments/assets/899af614-a71a-439f-9d84-dee2ce8aa251" width="500"/>
<img src="https://github.com/user-attachments/assets/ee5a96bb-082b-41bd-8a25-b5ce878b2e43" width="500"/>

### Model - 512x512 eyenix model v1  
<img src="https://github.com/user-attachments/assets/0b2759fd-9560-4845-9223-f623fd722d0c" width="500"/>
<img src="https://github.com/user-attachments/assets/d16004b8-d40a-4724-8df4-6128170cdd91" width="500"/>

### Model - 640x640 eyenix model v1  
<img src="https://github.com/user-attachments/assets/7f493a2a-de84-49cf-8d13-d31b9bd31104" width="500"/>
<img src="https://github.com/user-attachments/assets/047ca093-57de-40b6-bd33-fd8ba8aba54f" width="500"/>

### Model - 672x384 eyenix model v2 (tiny)  
<img src="https://github.com/user-attachments/assets/b3d5a2b8-710e-4d79-9068-6e0730691dcf" width="500"/>
<img src="https://github.com/user-attachments/assets/ed533c29-82d3-434e-8f7b-d65979c0e477" width="500"/>

### Model - 672x384 eyenix model v3 (tiny) - release
<img src="https://github.com/user-attachments/assets/51fe8ebb-11e0-4a50-a491-3f6cd86f309b" width="500"/>
<img src="https://github.com/user-attachments/assets/09b1f1d0-1cb1-441c-8529-fb60206aa4e7" width="500"/>

### Model - 672x384 eyenix model v3 (tiny) - update
<img src="https://github.com/user-attachments/assets/5d05a76d-6e63-444d-9f6e-088de44e764c" width="500"/>
<img src="https://github.com/user-attachments/assets/77724a8a-7bfe-4e6b-add3-ba3b997b620f" width="500"/>

### Model - 864x512 eyenix model v3 (tiny) - update
<img src="https://github.com/user-attachments/assets/5f166ff1-5ba3-48f7-a8b0-4d9efa282de7" width="500"/>
<img src="https://github.com/user-attachments/assets/71ca8f5e-1fb4-4cbe-b1f0-6039a50e8081" width="500"/>


&#160;

### ▶ Face Model
- **class** : Face
### Model - 320x320 eyenix model v1 
<img src="https://github.com/user-attachments/assets/5cbe1988-9fdc-4568-a170-1b5fb77d4cf8" width="500"/>

### Model - 448x448 eyenix model v1 
<img src="https://github.com/user-attachments/assets/4f5fa98a-cdad-433b-ba0c-ff86d88041de" width="500"/>

### Model - 512x512 eyenix model v1 
<img src="https://github.com/user-attachments/assets/f606c711-0a5a-42a0-a8e3-d483b523b03f" width="500"/>

### Model - 512x288 eyenix model v2 (tiny)  
<img src="https://github.com/user-attachments/assets/26975d56-c64c-4015-9953-9de2b686a610" width="500"/>

### Model - 512x288 eyenix model v3 (tiny) - update
<img src="https://github.com/user-attachments/assets/62e8ab39-39d3-46cc-8b1a-38622614df1e" width="500"/>