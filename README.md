# ⛏️ Mine vs Rock Classification

This project uses **Machine Learning** to classify sonar signals as either **Mine (metallic object)** or **Rock (non-metallic object)**.  
It is based on the **Sonar Dataset (UCI Machine Learning Repository)**, where each sample represents energy values of sonar signals bounced off different objects.

---

## 📌 Project Overview
- **Objective**: Predict whether the object detected by sonar is a **mine** or a **rock**.  
- **Dataset**: Sonar dataset with 208 samples and 60 numerical features.  
- **Techniques used**: Data preprocessing, train-test split, logistic regression, evaluation metrics.  

---

## 🛠️ Tech Stack
- **Language**: Python  
- **Libraries**:  
  - `pandas`, `numpy` → Data handling  
  - `matplotlib`, `seaborn` → Visualization  
  - `scikit-learn` → ML algorithms (Logistic Regression, train_test_split, accuracy_score)  

---

## ⚙️ Workflow
1. Load and explore the dataset  
2. Preprocess features and labels  
3. Split dataset into training & testing sets using `train_test_split`  
4. Train the model using Logistic Regression  
5. Evaluate model performance with accuracy score  

---

## 📊 Results
- Achieved **~86% accuracy** on the test set.  
- Maintains class balance using **stratified sampling**.  

---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/your-username/mine-vs-rock.git

# Install dependencies
pip install -r requirements.txt

# Run the script
python mine_vs_rock.py
