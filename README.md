# Overview
Matos Fashion merupakan sebuah startup yang tengah naik daun di dunia e-commerce fashion, sedang menghadapi tantangan dalam mengelola dan mengategorikan inventaris produk yang terus bertambah. Fokus utama mereka adalah dua jenis produk, yaitu kaos dan hoodie. Untuk meningkatkan efisiensi operasional serta mempermudah pengalaman belanja pelanggan, Matos Fashion berencana mengembangkan sistem klasifikasi produk otomatis menggunakan foto produk. Sistem ini nantinya diharapkan bisa mengategorikan produk tidak hanya berdasarkan jenisnya (seperti kaos atau hoodie), tetapi juga warnanya (merah, kuning, biru, hitam, atau putih).


# Klasifikasi Multi Label
Klasifikasi multilabel merupakan salah satu kasus dalam machine learning di mana sebuah instance (data) dapat menjadi bagian dari beberapa kelas atau label pada saat yang bersamaan. Tidak seperti klasifikasi biner atau multikelas tradisional, di mana instance (data) ditetapkan ke hanya satu kelas/ kategori, klasifikasi multilabel memungkinkan beberapa label ditetapkan ke sebuah instance (data).

# Metrik Evaluasi
Digunakan metrik Exact Match Ratio pada kasus klasifikasi multilabel dikarenakan metrik ini mampu mengukur seberapa akurat prediksi model dalam memprediksi semua label secara tepat untuk setiap sampel, dimana prediksi dianggap benar jika dan hanya jika semua label yang diprediksi sama persis dengan label sebenarnya. Berikut Formula dari metrik Exact Match Ratio:
 
# Hasil
Kita berhasil mendapatkan skor Kaggle sebesar 0.98 dan mendapatkan peringkat 19 dari 145 peserta dari peserta nasional. Kemudian dari peringkat private score Kaggle peringkat 1-20 mempunyai nilai yang hampir sama di angka 0.98 dan 0.99.

# Teknik
Menggunakan pendekatan teknik segmentasi pada preprocessing datasetnya. Selanjutnya menggunakan Pytorch untuk frameworknya, dan hyperparameter tuning model ResNet50_Weights.IMAGENET1K_V1