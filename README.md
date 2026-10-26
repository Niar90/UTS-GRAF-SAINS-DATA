# UTS Graf Sains Data: Rekomendasi RetailRocket dengan Neo4j

Nama: Nia Ayu Agustin
NIM: 24031554081
Kelas: 2024B

Proyek ini bertujuan untuk membangun sistem rekomendasi produk menggunakan dataset RetailRocket dengan memanfaatkan database graf Neo4j. Data interaksi pengguna pada toko online diolah menjadi graf yang terdiri dari simpul pengguna (Visitor) dan produk (Item), serta relasi interaksi seperti melihat produk, menambahkan produk ke keranjang, dan membeli produk.

Proses analisis dilakukan menggunakan pendekatan Vector Space Model (VSM) untuk merepresentasikan interaksi pengguna dan produk dalam bentuk vektor. Selanjutnya, cosine similarity digunakan untuk mengukur kemiripan antar pengguna dan produk. Hasil kemiripan tersebut dimanfaatkan untuk menghasilkan rekomendasi menggunakan metode K-Nearest Neighbors (KNN).

Evaluasi sistem dilakukan menggunakan metrik Hit@5 dan NDCG@5 berdasarkan pembagian data menjadi periode training pada 1–15 Juli 2015 dan periode testing pada 1–15 Agustus 2015. Hasil pengujian menunjukkan nilai Hit@5 dan NDCG@5 sebesar 0. Hal ini dipengaruhi oleh karakteristik dataset yang sangat sparse, dengan sebagian besar pengguna hanya memiliki satu interaksi, serta evaluasi yang dilakukan pada satu pengguna.

## Sumber data
RetailRocket e-commerce dataset (Kaggle): https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset Dataset asli tidak diunggah karena berukuran besar; yang diunggah adalah hasil filter P1 dan P2.
