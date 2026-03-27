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
- 🖼️ Image-based prediction support  

---

## 🗂️ Dataset  
- 📦 Source: Kaggle – `phenomsg/waste-classification`  
- 📊 Original dataset classes are automatically mapped into:
  - **Wet Waste**  
  - **Dry Waste**

### 🧾 Example Classes  
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
1. Download dataset from Kaggle  
2. Detect and organize class folders  
3. Map classes into wet and dry categories  
4. Create training and validation datasets  
5. Train MobileNetV2 model using transfer learning  
6. Save trained model (`.h5`)  
7. Predict waste type from new images  

---

## 🤖 Model Details  
- Base Model: **MobileNetV2**  
- Technique: Transfer Learning  
- Output: Binary classification (Wet / Dry)  

**Saved Model File:**  
`swm_wet_dry_mobilenetv2.h5`

---

## 📊 Sample Prediction  
Prediction: **DRY (0.74)**  

---

## 🌍 Real-World Impact  
This project demonstrates how AI can:
- Improve waste segregation  
- Support recycling systems  
- Reduce environmental impact  
- Enable smart waste management solutions  

---

## ▶️ How to Run  

```bash
# Clone the repository
git clone https://github.com/your-username/smart-waste-management.git

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook Smart_Waste_Management.ipynb

# Run all cells
