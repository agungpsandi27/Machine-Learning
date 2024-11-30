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

  ![image](https://github.com/user-attachments/assets/b0bf3141-2bc2-447d-9489-cbeda4635d38)

- Evaluasi model dengan accuracy score

  ![image](https://github.com/user-attachments/assets/52b48976-2a49-45dd-ba3e-d0e30c0b4931)

- Evaluasi model dengan precision score

  ![image](https://github.com/user-attachments/assets/646d389b-ce91-41de-91de-a341942a4abb)

- Evaluasi model dengan recall score

  ![image](https://github.com/user-attachments/assets/34327e76-fad8-409e-af90-cfdc05762f94)

- Evaluasi model dengan F1 score

  ![image](https://github.com/user-attachments/assets/601b581b-3757-45e0-a5ff-973340ce42d4)

- Evaluasi model dengan classification report

  ![image](https://github.com/user-attachments/assets/12150d58-3288-4d9a-95c6-669c2aa4d55a)

- Evaluasi model dengan Mathews Correlation Coefficient

  ![image](https://github.com/user-attachments/assets/2b7b1719-c843-45b9-b9e6-571e71cba09c)

  ## Support Vector Machine Classification
  **Support Vector Machine (SVM) Classification** adalah algoritma pembelajaran mesin yang digunakan untuk klasifikasi dengan mencari hyperplane yang memisahkan kelas-kelas dalam data dengan margin terbesar. SVM berusaha untuk menemukan batas keputusan (hyperplane) yang memaksimalkan jarak antara titik data dari masing-masing kelas, yang membuat model lebih general dan lebih baik dalam mengklasifikasikan data baru. SVM efektif untuk data yang memiliki dimensi tinggi dan dapat menggunakan kernel untuk menangani data non-linear.

Berikut merupakan hasil praktikum dari penjelasan pada channel youtube Indonesia belajar [SKLearn 14](https://www.youtube.com/watch?v=z69XYXpvVrE&list=PL2O3HdJI4voHNEv59SdXKRQVRZAFmwN9E&index=15)

- Pengenalan Decision Boundary & Hyperplane
  Decision boundary adalah batas yang memisahkan ruang fitur ke dalam wilayah berbeda yang sesuai dengan kelas yang berbeda. Batas ini menentukan keputusan klasifikasi untuk sebuah data baru. Hyperplane adalah generalisasi dari sebuah bidang datar ke dimensi yang lebih tinggi. Dalam ruang n-dimensi, hyperplane adalah subruang dengan dimensi n-1.

- Pengenalan Support Vector & Maximum Margin
  Support vectors adalah titik-titik data yang paling dekat dengan hyperplane yang memisahkan kelas-kelas. Titik-titik ini sangat penting karena mereka menentukan posisi dan orientasi dari hyperplane. Margin adalah jarak antara hyperplane dan support vectors terdekat dari setiap kelas. SVM bertujuan untuk menemukan hyperplane yang memaksimalkan margin ini, sehingga klasifikasi menjadi sebaik mungkin dengan batas yang optimal.

- Pengenalan kondisi Linearly Inseparable dan Kernel Tricks
  Linearly inseparable merujuk pada situasi di mana tidak mungkin menemukan hyperplane yang dapat memisahkan dua kelas data dengan jelas dalam ruang fitur asli. Untuk mengatasi masalah ini, Support Vector Machine (SVM) menggunakan teknik yang dikenal sebagai Kernel Trick. 
  
- Pengenalan MNIST Handwritten Digits Dataset
  
  ![image](https://github.com/user-attachments/assets/83c0863c-1726-48a5-934c-a18eb1dad0f2)
  ![image](https://github.com/user-attachments/assets/899f6e0c-05d6-4b8a-a35f-0e215bc866b8)
  ![image](https://github.com/user-attachments/assets/c4c9e943-7c81-4db1-8aa6-d30621fd76c1)

- Klasifikasi dengan Support Vector Classifier | SVC

  ![image](https://github.com/user-attachments/assets/346686d1-2089-434a-94d6-7fda04b6806d)
  ![image](https://github.com/user-attachments/assets/945bf3a8-0c39-44d3-aa5b-ff1d57674baf)

- Hyperparameter Tuning dengan Grid Search

  ![image](https://github.com/user-attachments/assets/18b5b729-538f-4db4-b51f-498df9a7a6a8)
  ![image](https://github.com/user-attachments/assets/0f4d6ac8-3056-4dfc-a748-0960cb983a71)
  ![image](https://github.com/user-attachments/assets/5034ebdb-23ce-4cb7-bca6-a074462b88f9)

- Evaluasi Model

  ![image](https://github.com/user-attachments/assets/984bf2e5-5638-4beb-9811-fc05f4c657b0)

