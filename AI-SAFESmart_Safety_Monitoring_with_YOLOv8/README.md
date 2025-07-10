# 🦺 AI-SAFE: Smart Safety Monitoring with YOLOv8

This project presents a real-world application of computer vision for workplace safety. Using the YOLOv8 object detection model, it automatically detects missing personal protective equipment (PPE) — such as helmets, vests, gloves, and goggles — on construction or industrial sites. The system performs detection, violation logging, statistical trend analysis, and model export for deployment.

---

## 🧠 Project Highlights

✅ Built a custom PPE violation detection pipeline using YOLOv8  
🛠️ Trained on a multi-class PPE dataset with 6 object categories  
📦 Performed object detection and recorded safety violations (e.g., `no-helmet`, `no-vest`)  
📊 Logged violation timestamps for time-series trend analysis  
🧪 Evaluated detection performance with mAP, precision, and recall  
📤 Exported model in ONNX, TorchScript, and TFLite formats for deployment  
📸 Visualized predictions with annotated test images  
🧾 Used real-world data from a Roboflow dataset  

---

## 📁 Dataset Summary

- **Source**: Roboflow (PPE Detection – 6 Classes)  
- **Classes**: `person`, `helmet`, `vest`, `goggles`, `gloves`, `boots`  
- **Structure**: Train / Validation / Test split with YOLO format  
- **Data Format**: `data.yaml`, image/label folders  

---

## ⚙️ Techniques Used

- YOLOv8 object detection (via `ultralytics` package)  
- Data preprocessing & annotation format checking  
- Training with early stopping & model checkpointing  
- Inference on test images  
- CSV logging of detected violations  
- Time-based trend visualizations (hourly, daily)  
- Exporting trained model to `.onnx`, `.torchscript`, and `.tflite`  

---

## 📊 Sample Outputs

- 🧾 Violation Logs  
- 🕒 Hourly & daily violation charts  
- 🖼️ Annotated prediction images  
- 📦 Trained YOLOv8 model weights in multiple formats  

---

## 🔮 Future Improvements

- 🎥 Real-time video stream detection with OpenCV  
- 🚨 Live alert system for detected violations  
- 🌐 Web dashboard integration  
- 💡 Model fine-tuning with more diverse PPE datasets
  

---
##  ⬇️ Installation & Exploration  

📘 Kaggle Notebook: [AI-SAFE: Smart Safety Monitoring with YOLOv8](https://www.kaggle.com/code/beyzakucuk/ai-safe-smart-safety-monitoring-with-yolov8)

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

✨ If this repository was helpful, please give it a ⭐ star and share it with others.

---

## 📜 License

This project is licensed under the MIT License. Feel free to use, modify, and share with attribution.

