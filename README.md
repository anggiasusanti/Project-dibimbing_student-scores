# Project-dibimbing_student-scores
Proyek ini menggunakan dua model Machine Learnign untuk memprediksi nilai (Scores (y)) belajar siswa berdasarkan jumlah jam belajar (Hours (x)).
Model yang digunakan adalah Linier Regression dan Random Forest Regression

HASIL EVALUASI MODEL
Model Linier Regression:
- MAE = 3.92
- MSE = 18.943
- R² = 0.967

Model Random Forest Regression :
- MAE = 2.778
- MSE = 13.045
- R² = 0.977

Dari evaluasi kedua model , Random Forest Regressor merupakan model yang lebih baik dibandingkan Regresi Linier,
karena:
- MAE dan MSE yang lebih kecil : prediksi lebih dekat dengan nilai sebenarnya.
- R² yang lebih tinggi : menunjukkan bahwa model Random Forest Regression mampu menjelaskan variasi data dengan lebih baik.

Regresi linier cocok jika membutuhkan model yang simpel, cepat, dan mudah diinterpretasi. Tetapi, untuk prediksi lebih akurat, terutama jika data mulai kompleks, Random Forest Regression merupakan pilihan yang tepat.

Project ini merupakan tugas mini project dari kelas Digital Skill Fair 38.0: Faculty of Data-AI Machine Learning by Dibimbing.id
