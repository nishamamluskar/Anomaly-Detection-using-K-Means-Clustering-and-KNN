# Anomaly Detection using Machine Learning

This project demonstrates anomaly detection techniques using Python and Machine Learning.  
Synthetic salary data is generated and analyzed to identify unusual or anomalous values using:

- K-Means Clustering (Unsupervised Learning)
- KNN-based Anomaly Detection using PyOD (Supervised/Outlier Detection)

The project includes data generation, preprocessing, visualization, clustering, and anomaly prediction.

---

## 📌 Project Overview

Anomaly detection is used to identify rare or unusual data points that differ significantly from normal observations.

In this project:
- Fake employee names are generated using the Faker library.
- Random salary values are created.
- Artificial anomalies are inserted manually.
- Machine learning techniques are applied to detect abnormal salary values.

---
## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- PyOD
- Faker
- Jupyter Notebook

---

## 📂 Dataset

The dataset is synthetically generated using the Faker library.

Features:
- Employee Name
- Salary

Artificial anomalies were introduced manually for testing purposes.

---

## ⚙️ Workflow

### 1. Data Generation
- Generate fake employee names using Faker.
- Create random salary values.

### 2. Data Visualization
- Boxplot visualization
- Histogram visualization

### 3. Unsupervised Learning
- Apply K-Means clustering to identify unusual salary patterns.

### 4. Supervised/Outlier Detection
- Use KNN from PyOD for anomaly detection.
- Predict whether a new salary value is normal or anomalous.

---

## 📊 Visualizations

The project includes:
- Salary Distribution Histogram
- Salary Boxplot
- Cluster Visualization Scatter Plot

##📌 Example Output
-Detection of anomalous salary entries
-Clustering of salary groups
-Prediction for new salary inputs

Example:

Salary = 35 → Normal
Salary = 1005 → Normal
Extremely low salaries like 17 and 23 are detected as anomalies.

##📈 Future Improvements
-Use real-world datasets
-Apply Isolation Forest and DBSCAN
-Build an interactive dashboard
-Add performance evaluation metrics

👩‍💻 Author
Nisha Mamluskar
