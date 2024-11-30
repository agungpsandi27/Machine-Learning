# Pertemuan 4 :

## Naive Bayes Classification
**Naive Bayes Classification** adalah algoritma klasifikasi yang berbasis pada teorema Bayes, dengan asumsi bahwa fitur-fitur input bersifat independen satu sama lain (naive). Meskipun asumsi ini sering tidak realistis, Naive Bayes sering memberikan hasil yang baik, terutama untuk teks dan data dengan fitur yang banyak. Model ini menghitung probabilitas setiap kelas berdasarkan data input dan memilih kelas dengan probabilitas tertinggi. Naive Bayes efisien dan cepat, serta sering digunakan dalam tugas-tugas seperti klasifikasi email (spam/tidak spam) dan analisis sentimen.

Berikut merupakan hasil praktikum dari penjelasan pada channel youtube Indonesia belajar [SKLearn 13](https://www.youtube.com/watch?v=Sj1ybuDDf9I&list=PL2O3HdJI4voHNEv59SdXKRQVRZAFmwN9E&index=14)

- Pengenalan Bayes Theorem | Teori Bayes | Conditional Probability

  ![image](https://github.com/user-attachments/assets/2e54ed84-022c-4db9-8e81-97969ea22db2)

  Teorema Bayes atau Bayes' Theorem adalah rumus dalam probabilitas yang digunakan untuk menghitung peluang dari suatu peristiwa berdasarkan pengetahuan sebelumnya tentang kondisi yang terkait dengan peristiwa tersebut. Teorema ini dinamai dari Thomas Bayes, seorang matematikawan Inggris, yang mengembangkan dasar-dasar teori ini pada abad ke-18. Teorema Bayes banyak digunakan dalam statistik, ilmu data, pembelajaran mesin, dan berbagai bidang lain yang melibatkan prediksi dan estimasi. Teorema Bayes membantu dalam memperbarui peluang suatu hipotesis setelah mendapatkan informasi baru. Contohnya, jika kita ingin mengetahui peluang seseorang menderita penyakit tertentu berdasarkan hasil tes, maka kita bisa menggunakan Teorema Bayes untuk menghitung probabilitas tersebut dengan mempertimbangkan informasi sebelumnya, seperti prevalensi penyakit dan sensitivitas tes.
  
- Pengenalan Naive Bayes Classification

  ![image](https://github.com/user-attachments/assets/5aaf02fa-18c9-4d7f-8a1b-bd23d2a2b000)

- Pengenalan Prior Probability

  ![image](https://github.com/user-attachments/assets/6db36960-39bc-4ad4-b9a6-5e8cee07e706)

  Distribusi probabilitas sebelumnya dari kuantitas yang tidak pasti, yang sering disebut sebagai prior , adalah distribusi probabilitas yang diasumsikan sebelum beberapa bukti diperhitungkan. Misalnya, prior dapat berupa distribusi probabilitas yang mewakili proporsi relatif pemilih yang akan memilih politisi tertentu dalam pemilihan mendatang. Kuantitas yang tidak diketahui dapat berupa parameter model atau variabel laten, bukan variabel yang dapat diamati.
  
- Pengenalan Likelihood

  ![image](https://github.com/user-attachments/assets/d548361c-3e26-4561-a65d-d68d64a14149)

  Fungsi kemungkinan (sering disebut sebagai likelihood ) mengukur seberapa baik model statistik menjelaskan data yang diamati dengan menghitung probabilitas melihat data tersebut di bawah nilai parameter model yang berbeda. Fungsi ini dibangun dari distribusi probabilitas gabungan dari variabel acak yang (mungkin) menghasilkan pengamatan. [ 1 ] [ 2 ] [ 3 ] Ketika dievaluasi pada titik data aktual, fungsi ini menjadi fungsi semata-mata dari parameter model.
  
- Pengenalan Evidence | Normalizer

  ![image](https://github.com/user-attachments/assets/7247e631-ef37-42fb-a55e-4948f289ac68)

- Pengenalan Posterior Probability

  ![image](https://github.com/user-attachments/assets/1765108f-bc39-4614-b124-204eb82052a1)

  Probabilitas posterior adalah jenis probabilitas bersyarat yang dihasilkan dari pembaruan probabilitas sebelumnya dengan informasi yang dirangkum oleh kemungkinan melalui penerapan aturan Bayes . [ 1 ] Dari perspektif epistemologis , probabilitas posterior memuat semua hal yang perlu diketahui tentang proposisi yang tidak pasti (seperti hipotesis ilmiah, atau nilai parameter), dengan pengetahuan sebelumnya dan model matematika yang menggambarkan pengamatan yang tersedia pada waktu tertentu. [ 2 ] Setelah kedatangan informasi baru, probabilitas posterior saat ini dapat berfungsi sebagai sebelumnya dalam putaran pembaruan Bayesian lainnya.
  
- Studi kasus Naive Bayes Classification

  ![image](https://github.com/user-attachments/assets/f311ca92-31d7-4481-945a-8d7051b592d9)
  ![image](https://github.com/user-attachments/assets/654dac3b-440b-4284-8d84-2067933f8de2)

- Penjelasan Algoritma yang Naïve

  ![image](https://github.com/user-attachments/assets/be26372b-4005-4727-a4cb-4375f6fa84a3)

  Algoritma naïve adalah metode atau pendekatan pemecahan masalah yang sederhana dan biasanya kurang efisien dibandingkan dengan metode yang lebih canggih. Pendekatan naïve sering kali didasarkan pada konsep brute force atau cara langsung untuk menyelesaikan masalah tanpa adanya optimasi tertentu. Pada umumnya, algoritma naïve memeriksa semua kemungkinan solusi atau melakukan proses berulang tanpa menyaring atau mengeliminasi solusi yang tidak relevan.
  
- Persiapan Dataset | Wisconsin Breast Cancer Dataset | UCI Machine Learning

  ![image](https://github.com/user-attachments/assets/53edd2f8-014d-4b98-8b76-b5c1ae27acbc)

- Implementasi Naive Bayes Classification dengan Scikit-Learn

  ![image](https://github.com/user-attachments/assets/70b7b0cd-584c-47e3-8f04-6382c55aecd6)
