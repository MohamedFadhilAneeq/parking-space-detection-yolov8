# Parking Space Detection using YOLOv8 🚗🅿️

A deep learning project that detects and classifies parking spaces as empty or occupied using the YOLOv8 model trained on the PKLot dataset.

## 📂 Dataset

- Dataset used: [PKLot - Parking Lot Dataset](https://www.kaggle.com/datasets/ammarnassanalhajali/pklot-dataset)
- COCO-annotated data was converted to YOLO format for model training
- Due to size, the dataset is not included in this repository

## 🧠 Model

- Model: YOLOv8n (Ultralytics 8.3.168)
- Classes trained: `space-empty`, `space-occupied`
- Trained on: 14,3316 instances over 2483 images
- Training Time: ~1 hour (20 epochs on T4 GPU in Colab)

### 🧪 Performance Results

| Metric      | Value   |
|-------------|---------|
| Precision   | 0.998   |
| Recall      | 0.998   |
| mAP@0.5     | 0.994   |
| mAP@0.5:0.95| 0.965   |

## 📒 Contents

| File                         | Description |
|------------------------------|-------------|
| ParkingSpaceDetection.ipynb  | Jupyter notebook (Colab) with full pipeline |
| dataset.yaml                 | Dataset class and path configuration |
| output.png                   | Sample output with bounding boxes (optional) |
| PKLot_dataset_info.txt       | Reference to dataset source on Kaggle |
| README.md                    | This file |

## 🚀 How to Run

1. Clone this repo
2. Download the PKLot dataset from Kaggle
3. Mount your Google Drive in Colab and follow notebook instructions
4. Run the notebook to preprocess, train, and predict

## 🛠 Tools & Libraries

- Python 3.11
- YOLOv8 (Ultralytics)
- Google Colab
- COCO Format
- OpenCV, Albumentations, FiftyOne

---

📌 Developed by Mohamed Fadhil Aneeq H | 2024
