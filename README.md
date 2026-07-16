# Bakery Market Basket Analysis & Smart Bundling Strategy 🍞☕

Project ini bertujuan untuk menganalisis pola pembelian pelanggan di sebuah toko roti dan merancang strategi *bundling* produk untuk menghabiskan stok yang kurang laku (*Inventory Clearance*).

## 📌 Latar Belakang
Toko roti seringkali memiliki produk unggulan (*Fast Moving*) dan produk yang jarang dilirik (*Slow Moving*). Jika dibiarkan, produk lambat ini akan menjadi *dead stock*. Project ini menggunakan pendekatan *Data-Driven* untuk memasangkan produk mati tersebut dengan produk laris.

## 🛠️ Metode & Algoritma yang Digunakan
1. **Data Preprocessing & Cleaning:** Menghapus data non-produk (Voucher, Adjustment, dll).
2. **Exploratory Data Analysis (EDA):** Menemukan *Top 10 Best Selling Items* dan analisis tren waktu.
3. **Market Basket Analysis (Apriori):** Mencari aturan asosiasi (*Association Rules*) antar produk.
4. **Co-occurrence Frequency Analysis:** Algoritma "Brute Force" untuk menghitung probabilitas irisan himpunan pada barang langka.

## 🚀 Hasil & Rekomendasi Bisnis
Sistem berhasil menemukan pasangan *bundling* terbaik. Contoh rekomendasi:
* **Morning Booster:** Beli Kopi, tebus murah *Mighty Protein* (Probabilitas kecocokan: 82%).
* **Perfect Match:** Beli Roti, diskon 50% untuk *Bread Pudding* (Probabilitas kecocokan: 100%).

## 💻 Cara Menjalankan
Buka file `[NAMA_FILE_ANDA].ipynb` menggunakan Jupyter Notebook atau Google Colab.

## 📚 Libraries Used
* Pandas
* Matplotlib & Seaborn
* MLxtend (Apriori)
