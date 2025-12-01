
# 📘 ETS Big Data Analysis — Case A

**Nama:** KHOLID
**NIM:** 20123034
**Kelas:** A23 Informatika
**Semester:** 5

---

## 📌 Deskripsi Project

Repository ini berisi pengerjaan **ETS Big Data Analysis – Case A (Telco Customer Churn Prediction)**.
Project ini bertujuan memprediksi apakah pelanggan akan melakukan **churn** atau tetap menggunakan layanan berdasarkan fitur-fitur pelanggan seperti:

* Tenure
* Contract Type
* Monthly Charges
* Total Charges
* Internet Service
* Payment Method
* Kategori dan layanan tambahan

Analisis dilakukan menggunakan:

* **Python (scikit-learn)** sebagai modeling
* **KNIME Analytics Platform** untuk workflow visual

---

## 📂 Struktur Repository

```
ETS_BDA_20123034_Kholid/
│
├── README.md
├── ets_bda_caseA.py
├── ETS_BDA_20123034_CaseA.ipynb
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── workflow/
│   └── ETS_BDA_20123034_CaseA.knwf
│
└── laporan/
    └── Laporan_ETS_BDA_20123034_Kholid.pdf
```

---

## 🔗 Dataset

Dataset yang digunakan berada di folder:

```
data/WA_Fn-UseC_-Telco-Customer-Churn.csv
```

Dataset asli bersumber dari Kaggle:
[https://www.kaggle.com/blastchar/telco-customer-churn](https://www.kaggle.com/blastchar/telco-customer-churn)

---

## 🚀 Cara Menjalankan Script Python

Pastikan dataset ada di folder `data`.

Jalankan menggunakan CMD:

```
python ets_bda_caseA.py
```

Script akan menampilkan:

* Preprocessing
* Training Logistic Regression
* Training Decision Tree
* Akurasi model
* Classification Report
* Confusion Matrix

---

## 🧪 Hasil Model (Python)

### Logistic Regression

Accuracy: **0.7984**

### Decision Tree

Accuracy: **0.7970**

**Model terbaik:**
👉 Logistic Regression

---

## 🧩 Workflow KNIME

Workflow KNIME:

```
workflow/ETS_BDA_20123034_CaseA.knwf
```

Berisi node:

1. CSV Reader
2. Missing Value
3. Column Filter
4. One-to-Many Encoder
5. Partitioning
6. Logistic Regression Learner + Predictor + Scorer
7. Decision Tree Learner + Predictor + Scorer

---

## 📑 Laporan

Laporan ETS lengkap berada pada folder:

```
laporan/Laporan_ETS_BDA_20123034_Kholid.pdf
```

Berisi:

* Pendahuluan
* Preprocessing
* Evaluasi model
* Hasil Python
* Workflow KNIME
* Screenshot pendukung

---

## ✔ Status Project

Semua bagian ETS telah diselesaikan:

* Preprocessing ✔
* Python Modeling ✔
* KNIME Workflow ✔
* Evaluasi Model ✔
* Laporan PDF ✔
* File Repository Lengkap ✔
