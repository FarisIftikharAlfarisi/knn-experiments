# Eksperimen Variasi Algoritma KNN

## Tentang Proyek
Proyek ini mengeksplorasi berbagai modifikasi algoritma K-Nearest Neighbors (KNN) untuk meningkatkan akurasi klasifikasi. Kami menguji 4 varian algoritma dan membandingkannya dengan KNN standar.

## Algoritma yang Diuji
1. **WAKNN (Weighted KNN)**  
   KNN dengan pembobotan berdasarkan jarak

2. **KSVNN (K-Support Vector NN)**  
   Hybrid antara KNN dan Support Vector Machine

3. **MKNN (Modified KNN)**  
   KNN dengan optimasi parameter

4. **FuzzyKNN**  
   KNN dengan pendekatan logika fuzzy

## Dataset
Kami menggunakan dua dataset untuk pengujian:
- **Data Iris**: Dataset klasik dengan 150 sampel bunga iris
- **Data Diabetes**: Dataset medis dengan 768 sampel untuk prediksi diabetes

## Hasil Pengujian
| Algoritma   | Data Iris | Data Diabetes |
|------------|----------|--------------|
| WAKNN      | 90%      | 71%          |
| KSVNN      | 93%      | 75%          |
| MKNN       | 100%     | 68%          |
| FuzzyKNN   | 97%      | 73%          |
| KNN Standar| 69%      | 68%          |

## Teknologi
- Python 3.8+
- Scikit-learn
- NumPy
- Pandas
- Matplotlib/Seaborn

## Tim
- Ridwan Syarif Abidin
- Faris Itikhar Alfarisi
- Rangga Driya Nugraha
