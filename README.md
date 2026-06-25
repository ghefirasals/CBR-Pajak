# CBR-Pajak

## Deskripsi Proyek

Proyek ini merupakan implementasi **Case-Based Reasoning (CBR)** untuk pengelolaan dan pencarian kasus putusan sengketa pajak. Sistem memanfaatkan teknik **Text Mining**, **TF-IDF (Term Frequency-Inverse Document Frequency)**, dan **Support Vector Machine (SVM)** untuk merepresentasikan dokumen serta melakukan klasifikasi dan retrieval kasus yang memiliki kemiripan.

## Struktur Repository

```text
CBR-Pajak/
│
├── data/
│   ├── raw/
│   │   └── .gitkeep
│   │
│   └── processed/
│       └── .gitkeep
│
├── notebooks/
│   └── CBR_Pajak_Ghefira_dan_Rachel.ipynb
│
├── requirements.txt
└── README.md
```

## Dataset

Dataset yang digunakan berupa dokumen putusan sengketa pajak yang digunakan sebagai basis kasus (case base) dalam proses Case-Based Reasoning.

* Raw data disimpan pada folder `data/raw`
* Data hasil preprocessing dapat disimpan pada folder `data/processed`

## Metode yang Digunakan

1. Data Collection
2. Text Preprocessing

   * Case Folding
   * Cleaning
   * Normalization
3. Feature Extraction menggunakan TF-IDF
4. Klasifikasi menggunakan Support Vector Machine (SVM)
5. Case Retrieval menggunakan Similarity Measurement
6. Evaluasi Model

## Requirements

Pastikan Python 3.10 atau versi yang lebih baru telah terpasang.

Install seluruh dependency dengan perintah:

```bash
pip install -r requirements.txt
```

## Cara Menjalankan Project

### 1. Clone Repository

```bash
git clone https://github.com/USERNAME/CBR-Pajak.git
cd CBR-Pajak
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Jalankan Notebook

Buka Jupyter Notebook:

```bash
jupyter notebook
```

atau Google Colab.

Kemudian buka file:

```text
notebooks/CBR_Pajak_Ghefira_dan_Rachel.ipynb
```

### 4. Jalankan Pipeline End-to-End

Jalankan seluruh cell notebook secara berurutan dari atas ke bawah:

1. Import library
2. Load dataset
3. Preprocessing data
4. Ekstraksi fitur TF-IDF
5. Training model SVM
6. Evaluasi model
7. Retrieval kasus serupa

## Output

Output yang dihasilkan meliputi:

* Dataset hasil preprocessing
* Representasi fitur TF-IDF
* Model klasifikasi SVM
* Hasil evaluasi (Accuracy, Precision, Recall, F1-Score)
* Hasil retrieval kasus yang memiliki kemiripan tertinggi

## Author

* Ghefira Salsabila
* Rachel

## Mata Kuliah

Penalaran Komputer
