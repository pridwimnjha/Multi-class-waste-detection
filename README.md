## 🗑️ Multi-Class Waste Detection using YOLO

A computer vision project that detects and classifies multiple types of waste using **YOLO**, aimed at improving automated waste segregation and environmental monitoring systems.

This project extends single-class plastic bottle detection into a **multi-class waste detection system** with real-world applicability.

---

## 🚀 Features

* Multi-class object detection using YOLO
* Custom annotated dataset created using **LabelImg**
* Robust detection across varying lighting conditions and occlusions
* Easily extensible to add new waste categories

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

* Annotated ~1,100 images using **LabelImg**
* Converted annotations to YOLO format
* Applied data augmentation techniques
* Tuned hyperparameters for better generalization
* Used **weight decay** and **early stopping** to reduce overfitting
* Evaluated model performance using **precision and recall**

---

## 📊 Evaluation Metrics

* Precision
* Recall

*(mAP and per-class metrics will be added as the multi-class model training progresses.)*

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
