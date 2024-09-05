# Seleksi GAIB 

## Deskripsi Singkat
Repositori ini berisi implementasi dari Q-Learning dan SARSA pada sebuah permainan sederhana dengan ketentuan sebagai berikut:
- Terdapat papan 1 dimensi (gerakan kiri kanan saja) sepanjang 10 kotak
- Terdapat lubang di titik 0, dan apel di titik 9
- Player berada pada titik 2 dan dapat bergerak ke kiri atau kanan
- Jika player jatuh ke dalam lubang, point yang didapatkan -100, jika player mendapatkan apel, point yang didapatkan +100. Jika player menempati titik lain, player akan mendapatkan point -1
- Jika player jatuh ke lubang atau mendapatkan apel, player kembali ke titik 3
- Player menang saat mendapatkan point +500
- Player kalah saat mendapatkan point -200

## Cara penggunaan
1. Pastikan python telah terinstall
2. Install semua library yang diperlukan dengan menjalankan command berikut:
   
   ```
   pip install -r requirements.txt
   ```

Berikut adalah model yang diimplementasikan pada repositori beriikut: 

**Supervised Learning (Bagian 2):**
- [v] KNN
- [v] Logistic Regression
- [v] Gaussian Naive Bayes (kalo tasknya regresi, gausah ceklis tp kasih keterangan)
- [v] CART
- [v] SVM
- [v] ANN

**Bonus yang diimplementasikan:**
- Penambahan fungsi aktivasi lain pada ANN, seperti leaky ReLU dan exponential ReLU
- - Implementasi Gradient Boosting sebagai salah satu method _ensemble learning_

**Unsupervised Learning (Bagian 3):**
- [v] K-MEANS
- [v] DBSCAN
- [v] PCA
  
**Bonus yang diimplementasikan:**
- Penambahan metode inisialisasi K-Means++ pada model K-MEANS

**Reinforcement Learning (Bagian 4):**
- [v] Q-LEARNING
- [v] SARSA
