# Parking Space Detection using YOLOv8 🚗🅿️

A deep learning project using YOLOv8 to detect and classify parking spaces as empty or occupied.

## 📂 Dataset

- Dataset: [PKLot - Parking Lot Dataset](https://www.kaggle.com/datasets/ammarnassanalhajali/pklot-dataset)
- Dataset is not included in this repo due to size.
- You can download it from Kaggle and follow the preprocessing steps in the notebook.

## 📊 Model Overview

- Model: YOLOv8 (Ultralytics)
- Classes: space, space-empty, space-occupied
- Evaluation: Achieved high mAP and precision during training on 14K+ images

## 🧪 Project Contents

- 📒 ParkingSpaceDetection.ipynb – Full training and inference workflow in Google Colab
- 📸 output.png – Example prediction result
- 📝 PKLot_dataset_info.txt – Info about dataset usage

## 🚀 How to Run

1. Download the PKLot dataset from Kaggle.
2. Upload it to your Google Drive and mount it in the Colab notebook.
3. Run the notebook step-by-step.
4. The trained model and predictions will be stored in YOLOv8's runs directory.

## 🛠 Tech Stack

- Python
- YOLOv8
- Google Colab
- Pycocotools, Albumentations, FiftyOne
