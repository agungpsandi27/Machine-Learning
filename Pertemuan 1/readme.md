# Pertemuan 1 : 

## Instal Jupyter Notebook dan menabahkan library
**Jupyter Notebook** adalah aplikasi berbasis web membuat dan berbagi dokumen yang berisi kode, visualisasi, serta teks deskriptif. Jupyter digunakan dalam proses analisis data, pembelajaran mesin, dan pengembangan model. 
Setelah menginstal **Jupyter Notebook** lalu menambahkan beberapa library untuk analisis data, yaitu:

![image](https://github.com/user-attachments/assets/3730127c-d7a8-41f9-840d-6412e52f0027)

- **Numpy**: Untuk komputasi numerik.  
- **Scipy**: Untuk komputasi ilmiah.  
- **Pandas**: Untuk manipulasi dan analisis data.  
- **Matplotlib**: Untuk membuat visualisasi data.  
- **Seaborn**: Untuk visualisasi data yang lebih estetik.  
- **Sklearn**: Untuk pembelajaran mesin.

## Daftar Akun pada Google Collab
**Google Colab (Collaboratory)** adalah platform cloud dari Google yang memungkinkan pengguna untuk menulis dan menjalankan kode Python secara langsung di browser. Ini menyediakan lingkungan notebook interaktif yang mendukung analisis data, pembelajaran mesin, dan pengolahan data besar dengan mudah. Colab menyediakan akses ke GPU dan TPU gratis, sehingga cocok untuk proyek yang membutuhkan komputasi intensif. Selain itu, Colab juga memungkinkan kolaborasi secara real-time, berbagi notebook, dan integrasi dengan Google Drive untuk penyimpanan file.

![image](https://github.com/user-attachments/assets/b82fea68-1731-4a1b-b1ef-7b1e199ee212)

- Daftar pada link tersebut `colab.research.google.com`

## Daftar Akun pada Kaggle
**Kaggle** adalah platform online yang menyediakan kompetisi data science, dataset, serta alat dan sumber daya untuk menganalisis data. Dibuat untuk para profesional dan penggemar data science, Kaggle memungkinkan pengguna untuk berkompetisi dalam memecahkan masalah analisis data yang kompleks, berbagi solusi, dan belajar dari komunitas global. Selain itu, Kaggle menyediakan berbagai dataset terbuka yang dapat diakses untuk eksperimen dan proyek pembelajaran mesin, serta menawarkan notebook untuk menjalankan kode secara langsung di cloud..

![image](https://github.com/user-attachments/assets/dc061a2e-41e6-4796-885f-126a211f4df4)

- Daftar pada link tersebut `kaggle.com`

## Daftar Akun pada Github
**GitHub** adalah platform berbasis web untuk hosting dan kolaborasi proyek perangkat lunak yang menggunakan sistem kontrol versi Git. GitHub memungkinkan pengembang untuk menyimpan kode sumber, melacak perubahan, serta bekerja sama dalam proyek perangkat lunak dengan tim atau komunitas. Fitur utamanya termasuk repositori untuk menyimpan kode, pull request untuk kolaborasi, dan issues untuk melacak bug atau tugas. GitHub juga mendukung dokumentasi proyek melalui README dan menyediakan alat otomatisasi untuk integrasi dan pengujian perangkat lunak..

![image](https://github.com/user-attachments/assets/b49eca61-91ac-47e4-b387-83ca55629c26)

- Daftar pada link tersebut `github.com`

## Sample Dataset pada Scikit-Learn
Scikit-learn menyediakan beberapa sample datasets untuk latihan dan eksperimen pembelajaran mesin, seperti Iris, Digits, Breast Cancer, Boston Housing, Diabetes. dataset ini dapat diakses dengan fungsi seperti `load_iris()` dan digunakan untuk berbagai tugas pembelajaran mesin.

Berikut merupakan hasil praktikum dari penjelasan pada channel youtube Indonesia belajar [SKLearn 02](https://www.youtube.com/watch?v=mSO2hJln0OY&list=PL2O3HdJI4voHNEv59SdXKRQVRZAFmwN9E&index=3)

- Load sample dataset
  
  ![image](https://github.com/user-attachments/assets/95963027-7952-45fa-b70d-40e3850aa998)

- Metadata | Deskripsi dari sample dataset

  ![image](https://github.com/user-attachments/assets/cb376ac5-91a0-41f6-b826-9977b467919a)

- Explanatory & Response Variables | Features & Target

  ![image](https://github.com/user-attachments/assets/933e6dad-ea92-470b-a399-556290742e6f)
  
- Feature & Target Names

  ![image](https://github.com/user-attachments/assets/07f63da8-1934-4705-a2ef-86cbfcfd999b)
  
- Visualisasi Data

  ![image](https://github.com/user-attachments/assets/cafd01c3-2437-4bc3-82bb-b6227ef73615)
  
- Training Set & Testing Set

  ![image](https://github.com/user-attachments/assets/1da7ae8d-b8b0-499d-851b-1947e844a6a4)
  
- Load sample dataset sebagai Pandas Data Frame

  ![image](https://github.com/user-attachments/assets/c0c3c2a6-ed82-43c7-b565-0b2782a24e07)

## Machine Learning Workflow dengan Scikit-Learn
Workflow machine learning dengan Scikit-learn:

1. Memuat Data: Ambil data dari dataset bawaan atau sumber eksternal.
2. Memisahkan Data: Bagi data menjadi pelatihan dan pengujian.
3. Preprocessing: Bersihkan atau normalisasi data (scaling).
4. Membangun Model: Pilih algoritma yang sesuai.
5. Melatih Model: Latih model menggunakan data pelatihan.
6. Evaluasi Model: Uji performa model dengan data pengujian.
7. Tuning Hyperparameter (Opsional): Optimalkan parameter model.
8. Deploy atau Prediksi: Gunakan model untuk prediksi data baru.

Berikut merupakan hasil praktikum dari penjelasan pada channel youtube Indonesia belajar [SKLearn 03](https://www.youtube.com/watch?v=tiREcHrtDLo&list=PL2O3HdJI4voHNEv59SdXKRQVRZAFmwN9E&index=4)

- Training model Machine Learning

  ![image](https://github.com/user-attachments/assets/6cafe66b-d731-4be1-97e7-081bdf6da661)

- Evaluasi model Machine Learning

  ![image](https://github.com/user-attachments/assets/c26b2ef2-7ea0-4075-83cf-ae724f3b6ca2)

- Pemanfaatan trained model machine learning

  ![image](https://github.com/user-attachments/assets/6198e427-86bd-47a1-b41b-15994529ad65)

- Deploy model Machine Learning | Dumping dan Loading model Machine Learning

  ![image](https://github.com/user-attachments/assets/5d236479-4939-47a1-b077-aa955b3a2fba)

## Data Preprocessing dengan Scikit-Learn
Data preprocessing dengan Scikit-learn meliputi:

1. Mengisi Nilai Kosong: Mengatasi data yang hilang.
2. Normalisasi/Standarisasi: Menyesuaikan skala data.
3. Konversi Kategori: Ubah data kategoris menjadi numerik.
4. Feature Selection: Pilih fitur penting untuk analisis.

Berikut merupakan hasil praktikum dari penjelasan pada channel youtube Indonesia belajar [SKLearn 04](https://www.youtube.com/watch?v=smNnhEd26Ek&list=PL2O3HdJI4voHNEv59SdXKRQVRZAFmwN9E&index=5)

- Persiapan sample dataset

  ![image](https://github.com/user-attachments/assets/fb4aab43-32ad-4a82-970c-d425932fb88b)

- Teknik data preprocessing 1: binarisasi | binarisation | binarizarion

  ![image](https://github.com/user-attachments/assets/99c2995e-baf3-4de5-b803-64b8f2cd3087)

- Teknik data preprocessing 2: scaling

  ![image](https://github.com/user-attachments/assets/fae6bce9-c1c3-4e57-9ff4-5d02f27f04c3)

- Teknik data preprocessing 3: normalisasi | normalisation | normalization

  ![image](https://github.com/user-attachments/assets/421a8d8c-e80c-4e4b-9595-a9582e76cc43)
