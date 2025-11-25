
## 🚀 Cara Menjalankan
1. **Clone repository ini** (atau download filenya).
2. **Install dependencies**:
   Buka terminal/CMD di folder project, lalu jalankan:
   ```bash
   pip install -r requirements.txt
````

3.  **Jalankan Jupyter Notebook**:
    ```bash
    jupyter notebook linear.ipynb
    ```

## 📊 Hasil Evaluasi Model

Model telah dilatih dan dievaluasi menggunakan metrik statistik:

| Metric | Score | Keterangan |
|--------|-------|------------|
| **MAE** | 2.6041 | Rata-rata tebakan meleset 2.6 poin. |
| **RMSE** | 3.3971 | Error cukup stabil, tidak banyak outlier. |
| **R² Score**| 98.14% | Model sangat akurat memprediksi data. |

## 🧠 Konsep Pembelajaran

Dalam notebook ini, terdapat dua pendekatan:

1.  **Pendekatan Manual (Math-heavy)**:

      - Menghitung Slope ($m$) dan Intercept ($c$) menggunakan rumus statistik dasar.
      - Membuktikan bahwa ML hanyalah matematika (Kalkulus/Statistik) yang dikerjakan komputer.

2.  **Pendekatan Scikit-Learn**:

      - Menggunakan fungsi `.fit()` dan `.predict()`.
      - Standar industri untuk efisiensi dan kemudahan penggunaan.

-----

*Project ini dibuat oleh [Nama Kamu] untuk mendalami fondasi Machine Learning & Data Science.*

```

### **Tips Tambahan:**
1.  **Ganti [Nama Kamu]** di bagian bawah README dengan nama aslimu.
2.  Jika kamu upload ke GitHub, tampilan tabel dan kode di atas akan otomatis terlihat rapi dan berwarna.

Sekarang project kamu sudah siap dipamerkan! Ada lagi yang perlu disiapkan?
```