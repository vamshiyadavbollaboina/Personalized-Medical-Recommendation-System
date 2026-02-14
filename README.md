# 🩺 Personalized Medical Recommendation System

An AI-driven diagnostic platform that identifies diseases with high precision and provides automated, 360° health recovery guides including medications, diets, and workouts.

---

## 🚀 Key Highlights

* **High-Precision Engine:** Achieves a verified **98.35% accuracy** using a Support Vector Classifier (SVC).
* **Integrated Health Guides:** Automates the delivery of descriptions, precautions, medications, diets, and workouts in one dashboard.
* **Real-Time Deployment:** Built with a responsive **Flask** web application for instantaneous symptom-to-disease mapping.

---

## 📊 Model Performance Benchmarking

The system was developed by evaluating multiple machine learning algorithms across 41 distinct disease classes.

| Model | Accuracy |
| :--- | :--- |
| **Support Vector Classifier (SVC)** | **98.35%** |
| Random Forest | 97.88% |
| K-Neighbors (KNN) | 95.65% |
| Gradient Boosting | 88.04% |
| Multinomial Naive Bayes | 83.70% |



---

## 🛠️ Tech Stack & Libraries

* **Language:** Python 3.10+
* **Machine Learning:** `scikit-learn`, `pandas`, `numpy`
* **Web Framework:** `Flask`
* **Frontend:** HTML5, CSS3, Bootstrap 5
* **Serialization:** `pickle` (for model deployment)

---

## 💻 Installation & Setup

### 1. Clone the Project
```bash
git clone [https://github.com/yourusername/medical-recommendation-system.git](https://github.com/yourusername/medical-recommendation-system.git)
cd medical-recommendation-system

```

### 2. Create Virtual Environment

```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate

```

### 3. Install Required Libraries

```bash
pip install flask scikit-learn pandas numpy

```

### 4. Run the Application

```bash
python app.py

```

View the app at: `http://127.0.0.1:5000`

---

## 📂 Project Structure

```text
├── app.py              # Flask Server & Routes
├── models/             # Trained .pkl model files
├── data/               # Symptom & Disease datasets
├── templates/          # index.html, result.html
├── static/             # CSS and Images
└── requirements.txt    # Library dependencies

```

---

## 🔮 Future Scope

* **Deep Learning:** Transitioning to **ANNs/Transformers** to exceed current accuracy benchmarks.
* **Clinical Integration:** Implementing **HL7 FHIR APIs** for Hospital Management System (HMS) sync.
* **IoT Expansion:** Real-time vital monitoring via wearable device integration for proactive alerts.

---
## 📄 Project Documentation

For a detailed breakdown of the methodology, dataset, and system architecture, please refer to the full project report:

[Download Project Report (PDF)](./docs/Project_Report.pdf)

**Author:** Bollaboina Vamshi yadav

