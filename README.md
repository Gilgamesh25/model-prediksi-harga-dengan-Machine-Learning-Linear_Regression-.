# model-prediksi-harga-dengan-Machine-Learning-Linear_Regression-.

Proyek ini adalah sebuah dummy project berbasis Machine Learning tingkat dasar yang bertujuan untuk memprediksi harga rumah berdasarkan variabel luas tanah. Dengan pendekatan algoritma Linear Regression (Regresi Linear), program ini mempelajari pola hubungan antara dimensi properti dan nilai jualnya, sehingga mampu memberikan estimasi harga untuk data properti baru yang dimasukkan.

Proyek ini dibangun sepenuhnya di lingkungan Google Colab dengan memanfaatkan dataset buatan berbentuk file Excel (dummy_data_rumah.xlsx).

🛠️ Fitur & Alur Kerja
Data Ingestion: Membaca dan mengolah data eksternal dari file Excel menggunakan pustaka Pandas.

Exploratory Data Analysis (EDA): Visualisasi data menggunakan grafik Scatter Plot (Seaborn/Matplotlib) untuk melihat tren korelasi sebelum pemodelan.

Data Splitting: Membagi dataset menjadi Data Training (80%) untuk melatih model dan Data Testing (20%) untuk menguji performa.

Model Training: Menggunakan algoritma Linear Regression dari Scikit-Learn untuk menemukan garis prediksi terbaik.

Model Evaluation: Mengukur tingkat akurasi model menggunakan metrik Mean Squared Error (MSE) dan R-Squared (R²) Score.

Prediction: Fitur interaktif untuk memprediksi harga rumah berdasarkan input luas tanah baru secara acak.

🚀 Teknologi & Library yang Digunakan
Bahasa Pemrograman: Python 3

Platform: Google Colaboratory

Library Utama:

Pandas & NumPy (Manipulasi & Analisis Data)

Matplotlib & Seaborn (Visualisasi Data grafik)

Scikit-Learn (Pemodelan Machine Learning & Evaluasi)
