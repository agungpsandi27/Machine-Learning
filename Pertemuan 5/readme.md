# Pertemuan 5 :

## Classification dengan KNN
**Classification dengan KNN** (K-Nearest Neighbors) adalah algoritma yang mengklasifikasikan data berdasarkan kedekatannya dengan data lainnya. Untuk setiap titik data yang ingin diprediksi, KNN mencari K titik terdekat dari data pelatihan dan memberikan prediksi berdasarkan mayoritas kelas dari K tetangga terdekat tersebut. KNN adalah metode non-parametrik yang sederhana dan efektif, namun membutuhkan waktu komputasi yang lebih lama pada dataset besar, karena harus menghitung jarak ke semua titik data untuk setiap prediksi.

Berikut merupakan hasil praktikum dari penjelasan pada channel youtube Indonesia belajar [SKLearn 06](https://www.youtube.com/watch?v=4zARMcgc7hA&list=PL2O3HdJI4voHNEv59SdXKRQVRZAFmwN9E&index=7)

- Persiapan sample dataset

  ![image](https://github.com/user-attachments/assets/f2f778ff-0409-4cb8-8dea-ff096b608be4)

- Visualisasi dataset

  ![image](https://github.com/user-attachments/assets/8ad436b9-ec60-4abf-80e6-717c82ab1b94)

- Pengantar classiﬁcation dengan K-Nearest Neighbours | KNN
  
  K-Nearest Neighbors (K-NN) adalah salah satu algoritma yang digunakan dalam machine learning untuk klasifikasi (dan juga regresi). Algoritma ini termasuk ke dalam kategori lazy learning, di mana ia tidak membangun model eksplisit selama proses pelatihan, melainkan menyimpan semua contoh data latih dan melakukan klasifikasi baru berdasarkan data tersebut
  
- Preprocessing dataset dengan Label Binarizer

  ![image](https://github.com/user-attachments/assets/116218b5-7f78-4f10-9a26-8744cc549b5f)
  ![image](https://github.com/user-attachments/assets/dd4f2e9d-6a0e-4cc6-b99d-3919982f318b)
  ![image](https://github.com/user-attachments/assets/2498cdf6-02eb-4a74-881e-17861a8f8dfb)

- Training KNN Classification Model

  ![image](https://github.com/user-attachments/assets/7c77d802-ab97-4443-8f6a-a6f24b3771ed)

- Prediksi dengan KNN Classification Model

  ![image](https://github.com/user-attachments/assets/cff56e78-3f58-4a03-80f0-cb98cc1152a0)
  ![image](https://github.com/user-attachments/assets/1aa15037-1673-474e-acde-b3f564dfb3f3)
  ![image](https://github.com/user-attachments/assets/f7b4b1d2-8b36-44b5-be9f-fba2638966c4)

- Visualisasi Nearest Neighbours

  ![image](https://github.com/user-attachments/assets/10f74f39-06fa-463f-a196-407da28a4d28)
  ![image](https://github.com/user-attachments/assets/1b4a83ed-bf77-48a4-b3a3-6c1ac751e912)
  ![image](https://github.com/user-attachments/assets/ab956a34-e9a2-4a80-9024-64b2396d35d4)

- Kalkulasi jarak dengan Euclidean Distance

  ![image](https://github.com/user-attachments/assets/2f20e2ec-4313-46bd-a50a-92de76cbf785)
  ![image](https://github.com/user-attachments/assets/fc38b314-105e-49a5-9c84-b7c784a9ff6d)
  ![image](https://github.com/user-attachments/assets/2f1871c1-d787-458c-bd31-07213a3db8dc)
  ![image](https://github.com/user-attachments/assets/fc39ce44-14d4-4bbb-8dba-d8f952be6cc7)

- Evaluasi KNN Classification Model | Persiapan testing set

  
- Evaluasi model dengan accuracy score
- Evaluasi model dengan precision score
- Evaluasi model dengan recall score
- Evaluasi model dengan F1 score
- Evaluasi model dengan classification report
- Evaluasi model dengan Mathews Correlation Coefficient
