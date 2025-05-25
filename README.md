# 🌾 Crop Disease Detection using EfficientNet and ResNet50

This project focuses on detecting crop diseases across **15 distinct classes** using deep learning models built with **PyTorch**, specifically leveraging **EfficientNet** and **ResNet50**. It compares the performance of these two architectures on the **Bangladeshi Crops Disease Dataset**, offering robust classification capabilities to support early disease detection and improve agricultural management.

---

## 📊 Dataset

**Dataset:** [Bangladeshi Crops Disease Dataset](https://www.kaggle.com/datasets/nafishamoin/bangladeshi-crops-disease-dataset)  
**Total Classes:** 15 crop disease categories

---

## ✨ Features

- Implemented using **PyTorch**, **EfficientNet**, and **ResNet50**
- **Data Preprocessing**:
  - Data augmentation for classes with fewer than 2000 images
  - Calculated **weighted loss** for class imbalance
- **Training**:
  - Includes **checkpointing** and **early stopping** to optimize performance and prevent overfitting
- **Evaluation Metrics**:
  - Precision
  - Recall
  - F1-score
  - Accuracy
  - Confusion matrix




## 📊 Results

### 🔷 EfficientNet

**Loss Curve:**

![EfficientNet Loss & Accuracy Curve](https://github.com/mushfiq525/Crop-Disease-Detection/blob/main/Crop%20disease%20detection%20EfficientNet/images/loss%26accuracy.png)

**ROC Curve:**

![EfficientNet ROC Curve](https://github.com/mushfiq525/Crop-Disease-Detection/blob/main/Crop%20disease%20detection%20EfficientNet/images/roc.png)

**Confusion Matrix**

![EfficientNet Confusion Matrix](https://github.com/mushfiq525/Crop-Disease-Detection/blob/main/Crop%20disease%20detection%20EfficientNet/images/confusion%20matrix.png)

---

### 🔶 ResNet50

**Loss & Accuracy Curve:**

![ResNet50 Loss Curve](https://github.com/mushfiq525/Crop-Disease-Detection/blob/main/Crop%20disease%20detection%20ResNet50/imgs/Screenshot%202025-05-25%20133854.png)

**ROC Curve:**

![ResNet50 ROC Curve](https://github.com/mushfiq525/Crop-Disease-Detection/blob/main/Crop%20disease%20detection%20ResNet50/imgs/roc.png)

**Confusion Matrix**

![ResNet50 Confusion Matrix](https://github.com/mushfiq525/Crop-Disease-Detection/blob/main/Crop%20disease%20detection%20ResNet50/imgs/conf%20matrix.png)


## Predictions

![Predictions](https://github.com/mushfiq525/Crop-Disease-Detection/blob/main/Crop%20disease%20detection%20EfficientNet/images/pred.png)



