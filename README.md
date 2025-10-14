\# 🎓 Student Score Prediction

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17q-OiXblx77M8Vvky0vQBB3SjF--nZ__)

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg?logo=python&logoColor=white)](https://www.python.org/)

[![Libraries](https://img.shields.io/badge/Libraries-pandas%2C%20numpy%2C%20sklearn%2C%20matplotlib%2C%20seaborn-green)](requirements.txt)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[![GitHub Repo](https://img.shields.io/badge/View%20on%20GitHub-181717?logo=github&logoColor=white)](https://github.com/MavisAkuaBoateng/student-score-prediction)


> 📘 A machine learning project that predicts students' exam scores based on academic and lifestyle factors such as study hours, sleep, attendance, and motivation.  
> Built with Python, Pandas, Scikit-learn, and Matplotlib, this project explores how behavioral and environmental variables influence learning outcomes — empowering data-driven insights for education improvement.


\## 📊 Project Overview

Students’ performance can be influenced by many academic and non-academic factors.  

This model analyzes those factors to estimate final exam scores and understand what most affects learning outcomes.



\### \*\*Dataset\*\*

\- \*\*Source:\*\* \[Student Performance Factors Dataset](https://www.kaggle.com/datasets)

\- \*\*Size:\*\* ~20 features × several hundred records

\- \*\*Target Variable:\*\* `Exam\_Score`



\## 🧠 Machine Learning Models

Two regression models were tested:



| Model Type | MAE | RMSE | R² Score | Notes |

|-------------|-----|------|-----------|-------|

| Simple Linear Regression (Study Hours only) | 2.53 | 3.51 | 0.205 | Weak correlation alone |

| Multiple Linear Regression (Study Hours + Sleep + Attendance + Motivation + Previous Scores) | \*\*1.40\*\* | \*\*2.53\*\* | \*\*0.587\*\* | Best performing |

| Polynomial Regression (degree 2) | – | – | 0.205 | No performance improvement |




\## 🔍 Key Insights

\- \*\*Study hours\*\*, \*\*attendance\*\*, and \*\*previous scores\*\* are strong positive predictors.  

\- \*\*Low motivation\*\* and \*\*less sleep\*\* tend to decrease exam performance.  

\- Linear regression worked best; polynomial regression added little benefit.




\## 🧰 Tools \& Libraries

\- Python 3.x  

\- Pandas  

\- NumPy  

\- Matplotlib / Seaborn  

\- Scikit-learn  

\- Jupyter Notebook  



\## ⚙️ How to Run Locally



\### 1️⃣ Clone this repository

```bash

git clone https://github.com/MavisAkuaBoateng/student-score-prediction.git

cd student-score-prediction



2️⃣ Install dependencies

pip install pandas numpy matplotlib seaborn scikit-learn jupyterlab



3️⃣ Add dataset

Download the Student Performance Factors dataset from Kaggle and place it inside a folder named data/

Example: data/StudentPerformanceFactors.csv



4️⃣ Run the notebook

jupyter lab

\# or

jupyter notebook



🧾 Files in this Repo

1. StudentPerformanceFactors.csv
2. Student\_Score\_Prediction.ipnyb
3. Task 1.docx
4. RAEDME.md
5. .gitignore



🪄 Author



👩‍💻 Mavis Akua Boateng

BSc. Computer Science \& Engineering | UMaT

Aspiring AI \& Systems Innovator for Africa 🌍



