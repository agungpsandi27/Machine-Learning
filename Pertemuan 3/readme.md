# Pertemuan 3 :

## Decision Tree Classification
Decision Tree Classification adalah algoritma pembelajaran mesin yang menggunakan struktur pohon untuk memisahkan data ke dalam kelas. Model ini bekerja dengan membagi dataset berdasarkan fitur yang memberikan informasi paling tinggi, menggunakan aturan keputusan (if-else). Setiap cabang merepresentasikan keputusan berdasarkan fitur, dan setiap daun (leaf node) mewakili hasil klasifikasi. Decision Tree populer karena mudah dipahami dan diinterpretasikan, tetapi dapat rentan terhadap overfitting jika tidak diatur dengan baik.

Berikut merupakan hasil praktikum dari penjelasan pada channel youtube Indonesia belajar [SKLearn 15](https://www.youtube.com/watch?v=5wwXKtLkyqs&list=PL2O3HdJI4voHNEv59SdXKRQVRZAFmwN9E&index=16)

- Pengenalan komponen Decision Tree: root, node, leaf

  ![image](https://github.com/user-attachments/assets/ae984a92-93fd-4dce-8ea9-415f01b2d4c8)

- Pengenalan Gini Impurity

  ![image](https://github.com/user-attachments/assets/4dc72cd9-b6d6-4a6f-b6ad-60b3357ad2b3)

- Pengenalan Information Gain

  ![image](https://github.com/user-attachments/assets/076a7d19-5bc7-482c-b162-a20e9ff8c393)

- Membangun Decision Tree

  ![image](https://github.com/user-attachments/assets/13f4e47f-94d9-44a7-8240-e867a628dae9)

- Persiapan dataset: Iris Dataset

  ![image](https://github.com/user-attachments/assets/5b8edea4-969e-474c-a4b4-edb82c35198e)

- Training model Decision Tree Classifier

  ![image](https://github.com/user-attachments/assets/db0b6fba-530d-4c7a-888a-e149921bb17f)

- Visualisasi model Decision Tree

  ![image](https://github.com/user-attachments/assets/9fc6f5c1-2701-41ab-8e0d-2d5798ff0a55)

- Evaluasi model Decision Tree

  ![image](https://github.com/user-attachments/assets/8b40efda-7e5c-412e-aa42-67246fac54ff)

## Random Forest Classification
**Random Forest Classification** adalah algoritma ensemble learning yang menggabungkan banyak decision trees untuk meningkatkan akurasi dan stabilitas prediksi. Setiap pohon dilatih pada subset data dan fitur yang dipilih secara acak (bootstrap aggregation), lalu hasil akhirnya ditentukan dengan voting mayoritas dari semua pohon. Metode ini lebih akurat dan tahan terhadap overfitting dibandingkan decision tree tunggal, serta efektif untuk data dengan banyak fitur atau outlier.

Berikut merupakan hasil praktikum dari penjelasan pada channel youtube Indonesia belajar [SKLearn 16](https://www.youtube.com/watch?v=yKovaQ6tyV8&list=PL2O3HdJI4voHNEv59SdXKRQVRZAFmwN9E&index=17)

- Proses training model Machine Learning secara umum

  ![image](https://github.com/user-attachments/assets/ac149530-89c3-44f8-95e6-5f945fa5d8f7)

- Pengenalan Ensemble Learning

  ![image](https://github.com/user-attachments/assets/a5335125-efd5-4d98-8c60-7384d2a02bb6)

- Pengenalan Bootstrap Aggregating | Bagging

  ![image](https://github.com/user-attachments/assets/61f0478a-661a-4046-a3be-ab2a1de10252)

- Pengenalan Random Forest | Hutan Acak

  ![image](https://github.com/user-attachments/assets/6184c338-7802-40e0-b7e0-550058b7e00e)

- Persiapan dataset | Iris Flower Dataset

  ![image](https://github.com/user-attachments/assets/7bc6e591-0a12-4eba-be65-dc8bae39d5ba)

- Implementasi Random Forest Classifier dengan Scikit Learn

  ![image](https://github.com/user-attachments/assets/bf4de5e2-2afe-4d62-915a-dc2e24be14aa)

- Evaluasi model  dengan Classification Report

  ![image](https://github.com/user-attachments/assets/8b0c1928-d7b6-42e5-8ee5-e4a5682de68a)
