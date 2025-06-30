# 🎓 Prediksi Performa Siswa

Proyek ini menggunakan dataset siswa sebanyak 40.000 data untuk memprediksi apakah seorang siswa akan **lulus** atau tidak, berdasarkan fitur-fitur seperti jam belajar, kehadiran, pendidikan orang tua, dan aktivitas ekstrakurikuler.

## 📌 Tujuan

- Memahami faktor-faktor yang mempengaruhi performa siswa
- Melakukan eksplorasi dan pembersihan data dunia nyata
- Membangun model machine learning untuk prediksi kelulusan siswa
- Mengetahui fitur-fitur yang paling memengaruhi hasil prediksi

## 📁 Struktur Proyek

```
student-performance-prediction/
├── data/
├── notebooks/
├── models/
├── images/
├── requirements.txt
└── README.md
```

## 📊 Tentang Dataset

- 📄 Sumber: [Kaggle - Student Performance Prediction](https://www.kaggle.com/datasets/souradippal/student-performance-prediction)
- 💡 Jumlah siswa: 40.000
- 🎯 Target: Kolom `Passed` (Yes/No)
- 🧾 Fitur: Jam belajar, kehadiran, nilai sebelumnya, ekstrakurikuler, dan lainnya

## ⚙️ Teknologi yang Digunakan

- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 📈 Model

- Algoritma: Random Forest Classifier
- Evaluasi: Classification Report, Confusion Matrix
- Output: Model yang sudah dilatih disimpan di `models/student_pass_model.pkl`

## 🚀 Cara Menjalankan Proyek

1. Clone repository ini
2. Install dependency:
   ```
   pip install -r requirements.txt
   ```
3. Jalankan notebook dari folder `notebooks/`

## 🙋‍♂️ Pembuat

Dibuat oleh **Gading Khairlambang** sebagai proyek portofolio dan pembelajaran data mining.

---

# 🎓 Student Performance Prediction

This project uses a dataset of 40,000 student records to predict whether a student will **pass** based on features such as study hours, attendance, parental education, and extracurricular activity.

## 📌 Objectives

- Understand the factors that influence student performance
- Perform real-world data exploration and cleaning
- Build a machine learning model to predict student passing status
- Identify the most important features for prediction

## 📁 Project Structure

```
student-performance-prediction/
├── data/
├── notebooks/
├── models/
├── images/
├── requirements.txt
└── README.md
```

## 📊 Dataset Overview

- 📄 Source: [Kaggle - Student Performance Prediction](https://www.kaggle.com/datasets/souradippal/student-performance-prediction)
- 💡 Total students: 40,000
- 🎯 Target: `Passed` column (Yes/No)
- 🧾 Features: Study Hours, Attendance, Previous Grades, Extracurricular, etc.

## ⚙️ Technologies Used

- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 📈 Model

- Algorithm: Random Forest Classifier
- Evaluation: Classification Report, Confusion Matrix
- Output: Trained model saved in `models/student_pass_model.pkl`

## 🚀 How to Run

1. Clone this repository
2. Install requirements:
   ```
   pip install -r requirements.txt
   ```
3. Run notebooks from the `notebooks/` directory

## 🙋‍♂️ Author

Created by **Gading Khairlambang** for portfolio and learning purpose.

## 🖼️ Visualisasi Penting

### 🔹 Feature Importance

Gambar berikut menunjukkan fitur-fitur yang paling mempengaruhi hasil prediksi apakah seorang siswa akan lulus atau tidak.

![Feature Importance](images/feature_importance.png)

**Penjelasan:**

- Fitur seperti `previous_grades` dan `study_hours_per_week` memiliki kontribusi paling besar terhadap hasil prediksi.
- Artinya, semakin tinggi nilai sebelumnya dan jam belajar per minggu, semakin besar kemungkinan siswa untuk lulus.
- Sedangkan fitur seperti `parent_education_level` mungkin memiliki pengaruh lebih rendah.
