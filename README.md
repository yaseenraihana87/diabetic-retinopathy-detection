# 🩺 Diabetic Retinopathy Detection using Deep Learning

## 📌 Project Overview

This project is a Deep Learning-based application for detecting **Diabetic Retinopathy (DR)** from retinal fundus images. It uses **Transfer Learning with InceptionV3** to classify retinal images into one of five diabetic retinopathy stages. A **Gradio** interface is included within the notebook for interactive image prediction.

---

## 🎯 Objectives

* Detect diabetic retinopathy from retinal fundus images.
* Classify images into five disease stages.
* Provide a simple and interactive prediction interface.
* Demonstrate the application of Deep Learning in medical image analysis.

---

## 🧠 Model Details

* **Architecture:** InceptionV3
* **Framework:** TensorFlow / Keras
* **Transfer Learning:** Yes
* **Input Image Size:** 224 × 224
* **Classes:** 5

### Disease Classes

* No_DR
* Mild
* Moderate
* Severe
* Proliferative_DR

---

## 📊 Model Performance

| Metric              |      Value |
| ------------------- | ---------: |
| Training Accuracy   | **97.01%** |
| Validation Accuracy | **80.00%** |

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Pillow
* Gradio
* Google Colab

---

## 📂 Repository Structure

```text
diabetic-retinopathy-detection/
│
├── DR_Training.ipynb
├── README.md
├── requirements.txt
└── screenshots/
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/<your-github-username>/diabetic-retinopathy-detection.git
cd diabetic-retinopathy-detection
```

### 2. Install the required libraries

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

Open **DR_Training.ipynb** using Google Colab or Jupyter Notebook.

### 4. Run all cells

The notebook includes:

* Data loading
* Image preprocessing
* Model training
* Model evaluation
* Model saving
* Gradio-based prediction interface

At the end of the notebook, run the Gradio section to launch the application.

---

## 📸 Screenshots

Add screenshots of:

* Home Screen
* Image Upload
* Prediction Result

Place them inside the `screenshots` folder.

---

## 📌 Note

The trained model file (`dr_model.keras`) and dataset are **not included** in this repository because of GitHub file size limitations. The notebook contains the complete workflow to train and save the model.

---

## 🚀 Future Improvements

* Improve validation accuracy using data augmentation and hyperparameter tuning.
* Deploy the Gradio application online.
* Add Grad-CAM visualization for model explainability.
* Generate downloadable prediction reports.
* Improve the user interface with additional medical information.

---

## 👨‍💻 Author

**Yaseen Raihana S**

Machine Learning | Deep Learning | Software Engineering

---

## 📄 License

This project is intended for educational and research purposes only. It should not be used as a substitute for professional medical diagnosis.
