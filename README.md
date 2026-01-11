# UAS Kecerdasan Buatan – Supervised Learning Classification

## Identitas Mahasiswa
Nama  : Catur Pramono  
NIM   : 312310575  
Kelas : TI.22.C.SE.1  
Mata Kuliah : TIF701 - Kecerdasan Buatan  
Dosen Pengampu : Yogi Yulianto, M.Kom  

---

## Judul Project
Prediksi Diabetes Menggunakan Machine Learning (Supervised Learning Classification)

---

## Deskripsi Project
Project ini bertujuan untuk membangun model kecerdasan buatan berbasis Supervised Learning
yang mampu memprediksi apakah seseorang menderita diabetes atau tidak berdasarkan data medis.

Dataset yang digunakan adalah **Pima Indians Diabetes Database** dari Kaggle yang berisi data
pasien wanita Pima Indians dengan beberapa fitur medis seperti Glucose, BMI, Insulin, Age, dll.

---

## Dataset
Sumber Dataset: Kaggle  
Nama Dataset: Pima Indians Diabetes Database  
Link: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database  

Target Klasifikasi:
- 0 = Tidak Diabetes
- 1 = Diabetes

---

## Tools & Library
- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- KaggleHub

---

## Tahapan Project

### 1. Exploratory Data Analysis (EDA)
- Analisis struktur dataset
- Statistik deskriptif
- Visualisasi distribusi target
- Analisis korelasi antar fitur

### 2. Pre-processing Data
- Mengganti nilai 0 yang tidak logis dengan NaN
- Mengisi missing value dengan nilai rata-rata
- Split data menjadi data training dan testing

### 3. Feature Engineering
- Standarisasi fitur menggunakan StandardScaler

### 4. Training Model
Menggunakan dua algoritma machine learning:
1. Logistic Regression
2. Random Forest Classifier

### 5. Evaluasi Model
Evaluasi menggunakan:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Hasil Pengujian Model

| Model | Akurasi |
|------|----------|
| Logistic Regression | ± 76% |
| Random Forest | ± 82% |

Model Random Forest memberikan performa terbaik dalam memprediksi diabetes.

---

## Struktur Folder Project

 ┣ dataset.csv  
 ┣ README.md  
 ┣ uas-praktek.ipynb  

---

## Kesimpulan
Berdasarkan hasil pengujian, model Random Forest memiliki akurasi lebih tinggi dibandingkan
Logistic Regression sehingga lebih cocok digunakan untuk prediksi diabetes.

Project ini telah memenuhi seluruh ketentuan UAS Kecerdasan Buatan yaitu:
- Menggunakan Python & Google Colab
- Menggunakan dataset Kaggle
- Menggunakan minimal 2 model
- Memiliki analisis di setiap tahap

---

## Author
Catur Pramono  
Teknik Informatika – Universitas Pelita Bangsa  
# uas_praktek
