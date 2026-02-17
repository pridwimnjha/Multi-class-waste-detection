## 🗑️ Multi-Class Waste Detection using YOLO

A computer vision project that detects and classifies multiple types of waste using **YOLO**, aimed at improving automated waste segregation and environmental monitoring systems.

This project extends single-class plastic bottle detection into a **multi-class waste detection system** with real-world applicability.

---
## 📌 Link To use project 
https://huggingface.co/spaces/pridwimnjha/waste-detection-yolov11  
---

## 🚀 Features

* Created and annotated a dataset of ∼2,000 images using Labellmg and converted to YOLO format.
* The classes included glass bottle, metal can, plastic bag, plastic bottle, plastic container, and plastic wrapper.
* Applied data augmentation, tuned hyperparameters, used weight decay and early stopping to reduce overfitting.
* The model achieved an MAP@50 of 90% and an MAP@50–95 of 73.5% demonstrating strong overall detection

---

## 🧠 Supported Classes

The current model is being trained/expanded to detect the following waste categories:

* Plastic Bottle
* Plastic Bag
* Plastic Container
* Plastic Wrapper
* Metal Can
* Glass Bottle

Each class has its own labeled dataset stored in compressed format.

---

## 📁 Dataset Structure

The dataset is organized by class and stored as ZIP files:

```
Multi-class-waste-detection/
│
├── plastic_bottle.zip
├── plastic_bag.zip
├── plastic_container.zip
├── plastic_wrapper.zip
├── metal_can.zip
├── glass_bottle.zip
└── README.md
```

Each dataset contains images annotated in **YOLO format**.

---

## 🛠️ Methodology

* Annotated ~2,000 images using **LabelImg**
* Converted annotations to YOLO format
* Applied data augmentation techniques
* Tuned hyperparameters for better generalization
* Used **weight decay** and **early stopping** to reduce overfitting
* Evaluated model performance using **precision and recall**

---

## 📊 Evaluation Metrics

* Precision
* Recall
* mAP50
* mAP50-95
  
---

## 🔄 Ongoing Work

* 🔧 Merging individual class datasets into a unified multi-class dataset
* 📈 Training a single YOLO model for all waste categories
* 📊 Adding mAP@0.5 and per-class performance metrics
* 🖼️ Visualizing predictions on real-world images

---

## 📌 Future Improvements

* Add more waste categories (paper, cardboard, e-waste)
* Real-time detection using webcam or CCTV feed
* Deployment using Flask / FastAPI
* Integration with smart waste-management systems

---

## 👨‍💻 Author

**Pridwimn Jha**
Computer Science Undergraduate | Machine Learning & Computer Vision
GitHub: [https://github.com/pridwimnjha](https://github.com/pridwimnjha)

---
