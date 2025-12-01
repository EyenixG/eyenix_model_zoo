# EYENIX Model Zoo
<div style="margin-top: 10px; margin-bottom: 15px;">   
  <img src="./imgs/eyenix_model_zoo.png" alt="EN675 Block Diagram" style="width:100%; height:auto;"/>
  </div>

Welcome to the **EYENIX Model Zoo**, a collection of high-performance deep learning models optimized for deployment on our **NPU-integrated product lineup**.

The model zoo includes both **public models**, which are pre-trained on widely used open datasets, and **release models**, which are trained in-house on Eyenix’s proprietary datasets for real-world. Using this model zoo, you can evaluate the accuracy of each model directly on Eyenix SoCs and compare performance across tasks.   
It also provides pre-compiled binary files, allowing you to run inference on the NPU immediately without additional conversion steps.
> ⚠️ **Access Notice**  
> This Model Zoo is intended **solely for EYENIX customers under a valid contractual agreement**.  
> Please note that access and usage are limited to authorized partner companies.


## 🎯 EYENIX NPU Lineup

For detailed specs and real-world AI demos:  
> [EN675 NPU Overview](./docs/en675/README.md)  

*EN683*  
*It will be updated and shared in December.*

## ✨ Models

Eyenix provides two categories of pre-trained models, both fully optimized for Eyenix NPU platforms:

🟦 **Public Models:** 
Trained on open, publicly available datasets.
Ideal for evaluation, benchmarking, and general-purpose prototyping.

🟥 **Release Models:**
Trained in-house on Eyenix’s internal datasets for specific, real-world use cases.
Designed for high accuracy and reliability in production deployments.

> **EN675 Public Models**: 
  - [Classification](./docs/en675/Public_Model/Classification_Models.md) | [Object Detection](./docs/en675/Public_Model/Object_Detection_Models.md)

> **Release Models**:
- [EN675 Release Models](./docs/en675/Release_Model/README.md)

*EN683 will be updated and shared in December.*

## 🚀 Getting Start

To get started with the models in this zoo:

1. **Explore available models** using the links above under Public Models and Release Models. Choose a model that **fits your task** (e.g., classification, detection) and **performance requirements** (e.g., accuracy, size, inference speed).

2. Download the corresponding **.bin file** for deployment.

3. Deploy the binary to your Eyenix SoC using the provided inference SDK.  
   → For setup and usage details, please refer to the NPU SDK Guide Documentation.

## 📄 License

This repository is licensed under the **MIT License**.  
You are free to use, modify, and distribute the models and code in this repository under the terms of the license.

> See [LICENSE](./LICENSE) for more details.


## 📬 Contact

For business inquiries or technical support, please contact us at:  
📧 **[eyenix support](http://www.eyenix.com/kr/support/contact.php)**  
