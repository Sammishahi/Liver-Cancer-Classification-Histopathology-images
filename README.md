# 🧪 Liver Histopathology Grade Classification  
### *(Using Adapted RCC Grading Model)*

This project focuses on **grading liver histopathology images** using deep learning techniques.

The work was carried out using a **private clinical dataset** collected from **KMC Hospital, Mangalore**, and provided through **NITK** for academic research. Due to medical data privacy and institutional guidelines, the dataset is **not included** in this repository.

In this study, I **reused and adapted my previously proposed RCC grading model** for liver histopathology analysis. The model was fine-tuned to capture liver-specific tissue patterns and applied to a **3-grade classification task**. The adapted model achieved a **validation accuracy of 98.57%**, demonstrating strong performance and good generalization.

---

## ✨ Project Highlights
- 🧠 3-grade liver histopathology classification  
- 🔁 Adaptation of a custom RCC grading CNN model  
- 🎯 Attention-based and multi-scale feature learning  
- 📈 Achieved **98.57% validation accuracy**  
- 🏥 Trained on real clinical data  

---

## 🧩 Model Description
The proposed model is a **custom CNN architecture** originally developed for RCC grading and later adapted for liver histopathology classification. It includes:

- 🔍 **Attention mechanisms** to focus on important tissue regions  
- 📐 **Multi-scale feature extraction** for texture variations  
- 🔗 **Residual connections** for stable and efficient training  

This design allows the model to generalize well across different histopathology datasets.

---

## 📊 Results
- ✅ **Validation Accuracy:** **98.57%**  
- 🧪 Classification type: **3-grade liver classification**  
- 📉 Evaluation metrics:
  - Confusion matrix  
  - Precision, recall, and F1-score  

The training process was stable, and the model showed strong generalization on validation data.

---

## 📈 Comparison with Existing Work
The adapted model was compared with **LiverNet**, which reports an accuracy of approximately **97.63%** for liver histopathology classification.  
The proposed approach achieves a higher validation accuracy of **98.57%**, indicating improved feature learning and better classification performance.

---

## 🔒 Dataset Information
- **Source:** KMC Hospital, Mangalore  
- **Provided via:** NITK  
- **Dataset type:** Private medical dataset  

Due to privacy, ethical considerations, and institutional restrictions, the dataset cannot be shared publicly.  
The code in this repository can be used with any compatible liver histopathology dataset.

---

## 🛠️ Tools & Libraries
- Python  
- TensorFlow/ keras  
- OpenCV  
- NumPy  
- Matplotlib  
- scikit-learn  

---

## 📌 Note
This project was completed as part of **academic and research work** using private clinical data and is intended for **educational and research purposes only**.
