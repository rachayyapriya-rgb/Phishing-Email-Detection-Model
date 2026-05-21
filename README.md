# Phishing Email Detection Model

## 📌 Project Overview

This project is a Machine Learning-based Phishing Email Detection System developed using Python and Scikit-learn.

The model analyzes email text and URL-related features to classify emails as:

- Phishing
- Safe (Legitimate)

The project uses Natural Language Processing (NLP) and Machine Learning algorithms to detect suspicious emails with high accuracy.

---

# 🎯 Features

- Detect phishing and legitimate emails
- Analyze suspicious keywords and URLs
- TF-IDF feature extraction
- Machine learning classification using Scikit-learn
- Accuracy score calculation
- Classification report generation
- Confusion matrix visualization

---

# 🛠 Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK

---

# 📂 Dataset

Dataset should contain:

| Column | Description |
|--------|-------------|
| text | Email content |
| label | Phishing or Safe |

Example:

| text | label |
|------|-------|
| Verify your account immediately | Phishing |
| Team meeting tomorrow at 10 AM | Safe |

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Phishing-Email-Detection.git
cd Phishing-Email-Detection
