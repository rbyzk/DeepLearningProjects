# 🥔 Potato Leaf Disease Detection using Deep Learning

This project applies **Convolutional Neural Networks (CNNs)** and **Transfer Learning** to classify potato leaves as either **healthy** or affected by **late blight** disease — a serious fungal infection that threatens crop yield.

🧪 Powered by deep learning and built for real-world agricultural use cases, the model aims to provide fast and accurate leaf health diagnostics.

---

## 📌 Project Highlights

✅ Built and trained a custom CNN model from scratch  
🧠 Applied transfer learning using **VGG16**, **MobileNetV2**, and **EfficientNetB0**  
📊 Compared model performance using accuracy, recall, and confusion matrices  
⚖️ Tackled data imbalance with augmentation and careful evaluation  
🧬 Focused on improving recall for the minority class (Late Blight)  

---

## 📂 Dataset Overview

- **Classes**: `Healthy`, `Late Blight`  
- **Total Samples**: 430+ images  
  - 363 healthy  
  - 67 diseased  
- **Format**: JPG images categorized in folders  
- **Source**: Publicly available agricultural image dataset

---

## 🧠 Models Used

- 🔨 **Custom CNN**: Simple architecture with BatchNorm and Dropout  
- 🔁 **Transfer Learning**:
  - VGG16
  - MobileNetV2
  - EfficientNetB0

Each model was trained using ImageDataGenerator and evaluated on a held-out validation set.

---

## 📈 Evaluation Metrics

- Accuracy  
- Confusion Matrix  
- **Recall for Late Blight** (prioritized due to class imbalance)  
- Training time and inference speed  

---

## 🔬 Key Findings

- Custom CNN performed well but overfitting was observed  
- VGG16 and EfficientNetB0 achieved **100% recall** on late blight class  
- MobileNetV2 was fastest but slightly lower in accuracy  
- Dataset augmentation improved model generalization  
- Model comparison helped identify the most robust choice for deployment

---

## 🚀 Future Work

- Collect more diseased samples for class balance  
- Deploy the best-performing model as a **mobile app** or **web dashboard**  
- Add early blight as a third class for multi-class classification  
- Experiment with Grad-CAM for visual explanations

---

## ⬇️ Installation & Exploration  

📘 Kaggle Notebook: [Potato Leaf Disease Detection🌱 🥔](https://www.kaggle.com/code/beyzakucuk/potato-leaf-disease-detection)

If you found this project insightful or valuable, feel free to **👍 UPVOTE** and leave a comment — your feedback is always welcome!

---

## 🤝 Contributing  
Contributions are always welcome!  
If you have suggestions, improvements, or want to collaborate, feel free to **fork this repo** and submit a pull request.

---

## 👩‍💻 About Me

I'm **Beyza Küçük** — a **Data Scientist & Data Analyst**, passionate about building ML/DL solutions that are interpretable, effective, and impactful.

- 🌐 **Kaggle**: [kaggle.com/beyzakucuk](https://www.kaggle.com/beyzakucuk)  
- 💻 **GitHub**: [github.com/beyzakucuk](https://github.com/beyzakucuk)  

---
 
✨ If this repository was helpful, please give it a ⭐ star and share it with others.

---

📜 License  
This repository is licensed under the **MIT License**. See the LICENSE file for more information.
