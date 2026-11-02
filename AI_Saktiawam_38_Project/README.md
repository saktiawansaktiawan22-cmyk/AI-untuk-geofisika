# Artificial Intelligence Course Projects

Repository ini berisi dua proyek analisis data untuk mata kuliah Artificial Intelligence.

## Daftar Proyek

### 1. Significant Earthquake Analysis
- Dataset: `data/significant_month.csv`
- Notebook: `notebooks/01_Significant_Earthquake_Analysis.ipynb`
- Fokus: eksplorasi magnitudo, kedalaman, tipe magnitudo, waktu, dan lokasi gempa signifikan.

### 2. Sales and Profit Prediction
- Dataset: `data/Ultimate_Sales_Profit_Dataset.xlsx`
- Notebook: `notebooks/02_Sales_Profit_Prediction.ipynb`
- Fokus: eksplorasi data penjualan dan prediksi profit menggunakan Random Forest Regressor.

## Cara Menjalankan

1. Unduh atau clone repository ini.
2. Pastikan Python sudah terpasang.
3. Install library yang diperlukan:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl jupyter
```

4. Buka folder proyek melalui VS Code atau Jupyter Notebook.
5. Jalankan notebook dari atas ke bawah agar seluruh tahapan dan visualisasi terbentuk.

## Struktur Folder

```text
AI_Course_GitHub_Project/
├── data/
│   ├── significant_month.csv
│   └── Ultimate_Sales_Profit_Dataset.xlsx
├── notebooks/
│   ├── 01_Significant_Earthquake_Analysis.ipynb
│   └── 02_Sales_Profit_Prediction.ipynb
└── README.md
```

## Catatan
Hasil analisis dan evaluasi model akan muncul setelah notebook dijalankan. Dataset gempa memiliki jumlah observasi terbatas sehingga digunakan untuk analisis eksploratif, sedangkan dataset penjualan digunakan untuk contoh regresi Machine Learning.
