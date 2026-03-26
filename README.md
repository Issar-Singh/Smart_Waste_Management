# ♻️ Smart Waste Management System  

🚀 A deep learning-based image classification system that automatically categorizes waste into **wet** and **dry** types using transfer learning.

---

## 📌 Overview  
This project applies **Computer Vision and Deep Learning** to solve a real-world sustainability problem — waste segregation.  
Using **MobileNetV2**, the system classifies waste images into **wet** and **dry** categories, helping automate sorting and reduce manual effort.

---

## ✨ Key Features  
- 🔍 Automated waste classification (Wet vs Dry)  
- ⚡ Transfer learning using MobileNetV2  
- 🧠 Efficient training on limited dataset  
- 🔄 Dynamic class detection and mapping  
- 💾 Model saving for reuse (`.h5` file)  
- 🖼️ Real-time image prediction support  

---

## 🗂️ Dataset  
- 📦 Source: **Kaggle – `phenomsg/waste-classification`**  
- 📊 Original classes are automatically mapped into:
  - **Wet Waste**  
  - **Dry Waste**

### 🧾 Example Classes Detected  
- kitchen_waste  
- coffee_tea_bags  
- yard_trimmings  
- food_scraps  
- egg_shells  

---

## 🛠️ Tech Stack  
- **Language:** Python  
- **Libraries:** TensorFlow, Keras, NumPy, Matplotlib  
- **Model:** MobileNetV2 (Transfer Learning)  
- **Platform:** Google Colab / Jupyter Notebook  

---

## ⚙️ Project Workflow  
```text
1. Download dataset from Kaggle  
2. Detect and organize class folders  
3. Map classes → Wet / Dry categories  
4. Create training & validation datasets  
5. Train MobileNetV2 model  
6. Save trained model (.h5)  
7. Predict waste type from new images  
