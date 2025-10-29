# 🧠 MNIST Handwritten Digit & Math Symbol Classifier using TensorFlow  
**Course:** MAE 598 – Artificial Intelligence Applications  
**Author:** Vamshikrishna Gadde (ASU ID 1234697141)  
**Institution:** Arizona State University  

![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow-orange)
![Python](https://img.shields.io/badge/Language-Python-blue)
![Accuracy](https://img.shields.io/badge/Test_Accuracy-97.91%25-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📘 Overview
This repository demonstrates two deep-learning tasks:
1. **Classifying handwritten digits (0–9)** using the MNIST dataset.  
2. **Transfer learning** to fine-tune the pre-trained model for recognizing **handwritten math symbols** such as `+`, `−`, `×`, `÷`, `sin`, and `log`.

Full details and code are in your uploaded report PDF.

---

## 🧩 Repository Structure
```
MNIST-MathSymbol-Classifier/
├── README.md
├── report/HOMEWORK_2_MAE598.pdf
├── src/ (Python scripts)
├── results/ (Accuracy graphs)
├── dataset/ (Symbol images)
└── test_images/ (sample tests)
```

---

## ⚙️ How to Run
```bash
pip install tensorflow matplotlib numpy
python src/mnist_nn.py           # Train base MNIST model
python src/transfer_learning.py  # Fine-tune for math symbols
python src/test_new_model.py     # Test with custom symbol
```

---

## 🧾 Results
- **Digit classifier accuracy:** 97.9 %
- **Math symbol classifier accuracy:** ≈ 95 %
- **Framework:** TensorFlow 2 / Keras  
[Result](https://drive.google.com/file/d/1uzHs3_baDTTg9cAIuR_GJNUl7m_SsSNf/view?usp=drive_link)

📺 **Project Videos**  
- [MNIST Demo](https://drive.google.com/file/d/1v7eAatGGdpeke7R-Vak6VoMIXdZCiapO/view?usp=sharing)  
- [Transfer Learning Demo](https://drive.google.com/file/d/14lZSyeXLGcRtqAs0oFu-sAo7CrehjtLr/view?usp=drive_link)

---

## 🧠 Key Learnings
- TensorFlow simplifies end-to-end DL workflow  
- ReLU + Softmax improve performance  
- Transfer Learning saves time and data  
- Normalization enhances accuracy  

---

## 👤 Author
**Vamshikrishna Gadde**  
📧 vgadde5@asu.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/vamshikrishna-gadde9999/)  
💻 [GitHub](https://github.com/GVK-Engine/VAMSHIKRISHNA-GADDE)

---

## 🪪 License
MIT License – Free for educational use.
