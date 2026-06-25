# CBR Putusan Pajak

## Deskripsi

Proyek Case-Based Reasoning (CBR) untuk klasifikasi dan retrieval dokumen putusan sengketa pajak menggunakan TF-IDF dan Support Vector Machine (SVM).

## Struktur Folder

```text
data/
├── raw/
├── processed/

notebooks/
├── CBR_Pajak.ipynb
```

## Instalasi

```bash
pip install -r requirements.txt
```

## Menjalankan Program

1. Buka Jupyter Notebook atau Google Colab.
2. Jalankan notebook:

```text
notebooks/CBR_Pajak.ipynb
```

3. Jalankan seluruh cell dari atas ke bawah.

## Metode

- Case-Based Reasoning (CBR)
- Text Preprocessing
- TF-IDF Vectorization
- Support Vector Machine (SVM)
- Cosine Similarity

## Dataset

30 dokumen putusan sengketa pajak.

## Output

- Case Base
- Retrieval kasus serupa
- Evaluasi Accuracy, Precision, Recall, dan F1-Score
