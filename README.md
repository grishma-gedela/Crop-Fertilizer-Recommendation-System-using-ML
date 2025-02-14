# 🌾 Crop & Fertilizer Recommendation System

## 📌 Overview
Farmers often face challenges in selecting the right crop and fertilizer for their soil conditions, leading to lower yields and financial losses. Our **AI-powered Crop & Fertilizer Recommendation System** leverages **machine learning** to provide data-driven insights for optimizing agricultural productivity.<br><br>

## 🎯 Problem Statement
### 🚜 Farmers struggle to determine the best crop and fertilizer for their soil conditions, resulting in:
- **Inefficient farming** due to incorrect crop choices.
- **Loss of resources** from poor decision-making.
- **Lack of precision** in manual recommendations.

## 💡 Solution
### Our **AI-powered model** takes **Nitrogen (N), Phosphorus (P), Potassium (K), Temperature, Humidity, pH, and Rainfall** as inputs and predicts the most suitable crop for cultivation.

#### 🔹 Example Input:
```bash
N = 90, P = 42, K = 43
Temperature = 20°C, Humidity = 82%
pH = 6.1, Rainfall = 202 mm
```
#### 🔹 Predicted Output:
```bash
Recommended Crop → Rice 🌾
```
<br><br>
## 🔬 Methodology
### 1️⃣ Dataset Collection
- Pre-existing crop dataset containing **soil properties & climate conditions**.

### 2️⃣ Data Preprocessing
- Handling missing values, **feature scaling**, and encoding categorical variables.

### 3️⃣ Splitting Data
- Dividing data into **training & testing** sets.

### 4️⃣ Model Training
- Implementing a **Decision Tree Classifier** for prediction.

### 5️⃣ Prediction & Evaluation
- Assessing accuracy and **recommending the best crop** based on environmental factors.
  
<br><br>
## 🛠 Tools & Technologies
- **Programming Language:** Python 🐍
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib 📊
- **Machine Learning Model:** Decision Tree Classifier 🌳
- **Development Environment:** Jupyter Notebook 📓
- **Dataset:** Crop Dataset 🌱

<br><br>
## 📊 Dataset Overview
### The dataset contains the following agricultural parameters:
✅ **Nitrogen (N), Phosphorus (P), Potassium (K)**  
✅ **Temperature, Humidity, pH, Rainfall**  
✅ **Target variable:** Recommended Crop 🌾
<br><br>
## 🚀 Key Features
### ✔ AI-powered crop recommendation based on soil & climate data.  
✔ **Improved farming efficiency** through precise suggestions.  
✔ **Machine Learning-driven decision-making** for better agricultural outcomes.  
✔ **User-friendly implementation** with clear inputs & outputs.
<br><br>
## 🎯 Results & Performance
### - **Trained Decision Tree Classifier** on agricultural data.  
- **Model tested on unseen data** to ensure accurate predictions.  
- **Feature scaling** (MinMaxScaler) used for better learning efficiency.
<br><br>
## 📌 Conclusion
### ✅ Accurate crop recommendations help farmers make **data-driven decisions**.  
✅ Analyzes key factors like **soil nutrients, weather conditions, and pH levels**.  
✅ **Boosts agricultural productivity** and promotes **sustainable farming**.  
<br><br>
## 🏆 Future Scope
### 🔹 **Integration with IoT devices** for real-time soil monitoring.  
🔹 **Mobile app implementation** for easier access to recommendations.  
🔹 **Enhanced ML models** for multi-crop prediction and adaptive learning.  

---

🚀 **Contribute, fork, and star the repository if you find it useful!** ⭐

