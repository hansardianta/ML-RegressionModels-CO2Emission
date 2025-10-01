# ML-RegressionModels-CO2Emission

## Vehicular $CO_{2}$ Emission Prediction using Regression Models

---

## 💡 Pengantar Proyek

Proyek ini bertujuan untuk mengembangkan model *Machine Learning* **regresi** untuk memprediksi emisi karbon dioksida ($CO_{2}$) kendaraan bermotor. Emisi $CO_{2}$ kendaraan adalah kontributor utama polusi udara, dan alat prediksi ini dapat memberikan wawasan berharga untuk mendukung upaya pengendalian polusi udara, perancangan strategi pengurangan emisi, dan pengembangan kebijakan berbasis data.

Target variabel yang diprediksi adalah **CO2 Emissions (g/km)**, yang merupakan variabel kontinu, sehingga model regresi digunakan.

Dataset yang digunakan untuk proyek ini diperoleh dari Kaggle, berisi karakteristik mobil, perilaku konsumsi bahan bakar, dan variabel target emisi $CO_{2}$.

---

## 🛠️ Model dan Teknik

Dalam proyek ini, beberapa model regresi dieksplorasi dan dievaluasi. Berdasarkan analisis, ditemukan bahwa:
* Model **Decision Tree** dan **Random Forest** memberikan akurasi prediksi yang tinggi.
* Penerapan **Principal Component Analysis (PCA)** secara signifikan memperburuk performa model, menunjukkan bahwa fitur asli dataset sudah cukup informatif.
* Kinerja model dinilai menggunakan metrik **$R^2$ Score**, **Mean Absolute Error (MAE)**, dan **Mean Squared Error (MSE)**.

---

## 📁 Struktur Repositori

| File/Folder | Deskripsi |
| :--- | :--- |
| `co2.csv` | Dataset yang digunakan untuk pelatihan dan pengujian model, berisi data karakteristik kendaraan dan emisi $CO_{2}$. Sumber dataset dari **Kaggle** oleh Debajyoti Podder. |
| `CO2EmissionRegression.ipynb` | Notebook Jupyter (`.ipynb`) yang berisi seluruh alur kerja proyek, mulai dari pemuatan data, eksplorasi data, pra-pemrosesan, implementasi model regresi, hingga evaluasi performa. |
| `InfographicML (1).pdf` | **Infografis** yang menyajikan ringkasan visual proyek, metodologi, temuan utama, dan kesimpulan secara ringkas dan menarik. |
| `README.md` | File ini. |

---

## 👨‍💻 Anggota Tim

Proyek ini dikerjakan sebagai tugas kelompok oleh mahasiswa Data Science, BINUS University:

| Nama Anggota | NIM | GitHub |
| :--- | :--- | :--- |
| Adrian Marc Fedier Purnama | 2702247216 | - |
| Gervasius Russell | 2702247450 | - |
| **Hans Ardianta** | **2702249663** | [hansardianta](https://github.com/hansardianta) |
| Jonathan William Gunawan | 2702251794 | - |

---

## 🚀 Cara Menjalankan Proyek

1.  **Clone** repositori ini:
    ```bash
    git clone [https://github.com/hansardianta/ML-RegressionModels-CO2Emission.git](https://github.com/hansardianta/ML-RegressionModels-CO2Emission.git)
    ```
2.  Buka file `CO2EmissionRegression.ipynb` menggunakan Jupyter Notebook, JupyterLab, atau lingkungan pengembangan Python lainnya.
3.  Jalankan sel secara berurutan untuk mereplikasi alur kerja analisis dan pelatihan model.
