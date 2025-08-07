# 🚨 Evaluating Machine Learning Models for Effective Fake URL Detection

This project explores and compares machine learning models to identify malicious URLs effectively. It focuses on phishing, spam, malware, and benign URLs using the **Random Forest** and **K-Nearest Neighbors (KNN)** models, along with **Mutual Information** for feature selection.

---

## 📘 Abstract

The rise in phishing and malicious URLs poses serious cybersecurity threats. This project evaluates machine learning models to detect fake URLs, aiming to:
- Compare performance of KNN vs. Random Forest
- Use Mutual Information (MI) for selecting informative features
- Improve accuracy and efficiency of detection systems

---

## 📂 Project Structure

```
📁 fake-url-detection/
│
├── 📜 MODEL_TRAINING.ipynb       # Google colab notebook for model training & evaluation
├── 📁 dataset/                   # Dataset used (e.g., URL-2016)
├── 📁 results/                   # Visualizations or result metrics
└── 📄 README.md                  # Project documentation
```

---

## 🧠 Machine Learning Models Used

### 🔹 K-Nearest Neighbors (KNN)
- Simple, instance-based learning
- Predicts based on similarity (Euclidean distance)

### 🔸 Random Forest
- Ensemble learning with decision trees
- Better accuracy, robustness, and generalization
- Final model selected based on performance

---

## 🧪 Feature Selection: Mutual Information (MI)

Used to rank and select features based on the amount of information they provide about the target label.

### MI Feature Selection Steps:
1. Collect all feature and target data
2. Compute Mutual Information scores
3. Rank features from most to least informative
4. Select top features to train the model

---

## 📊 Model Comparison

| Model         | Accuracy | Strengths                             |
|---------------|----------|----------------------------------------|
| KNN           | Moderate | Simple, quick but less effective on large datasets |
| Random Forest | High     | Accurate, handles large & complex data well |

✅ **Random Forest outperformed KNN** in detecting fake URLs.

---

## 🔐 URL Categories Detected

- **Phishing URLs**: Designed to steal sensitive info
- **Spam URLs**: Promotional or irrelevant links
- **Malware URLs**: Distribute malicious software
- **Benign URLs**: Safe and legitimate websites

---

## 🚀 How to Run the Project

1. Clone this repository:
```bash
git clone https://github.com/your-username/fake-url-detection.git
cd fake-url-detection
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch the notebook:
```bash
Google colab  notebook MODEL_TRAINING.ipynb
```

---

## 🎯 Key Learnings

- Gained practical understanding of KNN & Random Forest
- Performed model evaluation using accuracy, precision, recall, F1-score
- Applied feature selection using Mutual Information to improve accuracy
- Concluded Random Forest as the superior model

---

## 👨‍💻 Internship Details

- **Intern Name:** Uppara Prakash  
- **Program:** M.Sc. Computer Science  
- **Institution:** Central University of Tamil Nadu  
- **Internship Location:** IIIT Dharwad  
- **Guide:** Dr. Pavan Kumar C

---

## 📬 Contact

For questions or collaboration:
- 📧 Email: prakashcutn07@gmail.com.com
- 🌐 GitHub: [Upppara Prakash][(https://github.com/PRAKASHMS7/malicious-url-classifier)]


