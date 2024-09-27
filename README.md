# Final Project JCDSOL-14 Group B Purwadhika (Beta Team) 
**Saudi Arabia Used Cars Analytics and Prediction**

## Tentang Proyek
Proyek ini dikerjakan sebagai bagian dari penyelesaian Final Project dalam program Data Science di Purwadhika. Tujuan dari proyek ini adalah untuk menerapkan keterampilan dan pengetahuan yang telah diperoleh selama mengikuti program, termasuk analisis data, pemodelan statistik, dan penggunaan teknik machine learning untuk menghasilkan solusi nyata yang dapat diaplikasikan pada studi kasus dunia industri. Melalui proyek ini, diharapkan dapat memberikan wawasan dan solusi berbasis data yang mendalam bagi perusahaan atau industri yang relevan.

- Link Dataset : [Saudi Arabia Used Cars Dataset](https://www.kaggle.com/datasets/turkibintalib/saudi-arabia-used-cars-dataset)
- Link Tableau : [SAUC Analytics Dashboard](https://public.tableau.com/views/SAUC_Analytics/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)



**Konteks**\
Syarah adalah perusahaan yang bergerak di bidang jual beli mobil bekas, beroperasi di pasar yang sangat kompetitif. Proyek ini bertujuan untuk menganalisis faktor-faktor yang memengaruhi harga jual mobil bekas, seperti usia, kondisi, dan jarak tempuh. Dengan memahami faktor-faktor ini, Syarah dapat mengoptimalkan strategi penetapan harga untuk mempercepat penjualan, mengurangi penumpukan stok, dan memaksimalkan keuntungan, sehingga meningkatkan efisiensi operasional perusahaan.

**Problem Statement**\
Perusahaan kesulitan menetapkan harga jual mobil bekas yang tepat karena kurang memahami faktor-faktor utama seperti usia, kondisi, jarak tempuh, lokasi penjualan, dan kesesuaian harga dengan pasaran. Akibatnya, mobil sulit terjual, margin keuntungan menurun, dan biaya operasional meningkat. Analisis mendalam terhadap faktor-faktor tersebut diperlukan agar harga lebih akurat, sesuai pasaran, mempercepat penjualan, dan meningkatkan keuntungan.

**Goals**\
Berdasarkan permasalahan tersebut, **Syarah ingin mengetahui harga jual mobil bekas secara akurat untuk mempercepat penjualan dan meningkatkan keuntungan.** Saat ini, perusahaan ingin mengetahui faktor-faktor seperti usia mobil, kondisi mesin, jarak tempuh, dan lokasi penjualan yang membuat harga menjadi relevan dan tepat, sehingga harga yang ditetapkan sesuai dengan kondisi pasar, menghindari mobil sulit terjual, dan menekan biaya operasional yang meningkat.

**Metric Evaluation**\
Berikut adalah versi dalam bentuk poin-poin:

1. Mean Absolute Percentage Error (MAPE):
    - Digunakan sebagai metrik evaluasi utama.
2. Mean Absolute Error (MAE)
3. Root Mean Square Error (RMSE)
4. Koefisien Determinasi (R-squared)

## Data Cleaning
Dalam proses data cleaning, kami melakukan pengecekan menyeluruh terhadap semua anomali dalam dataset. Ini mencakup identifikasi dan penanganan missing values, penghapusan duplikasi, standarisasi format data, konversi tipe data yang sesuai, serta normalisasi teks. Khusus untuk outliers, kami menggunakan metode statistik seperti IQR untuk mengidentifikasinya. Outliers yang dianggap mengganggu analisis dan tidak merepresentasikan pola data yang sebenarnya kami hapus untuk memastikan kualitas dan konsistensi data, sehingga siap untuk analisis dan pemodelan lebih lanjut.

## EDA (Exploratory Data Analysis)
Dalam tahap Exploratory Data Analysis (EDA), kami melakukan analisis mendalam terhadap dataset untuk memahami karakteristik utama yang mempengaruhi pasar mobil bekas di Saudi Arabia. Fokus analisis kami mencakup distribusi harga mobil, pola jarak tempuh, dan sebaran jumlah mobil berdasarkan berbagai faktor seperti merek, model, tahun produksi, dan lokasi penjualan. Melalui analisis ini, kami berhasil mengidentifikasi tren harga, korelasi antara jarak tempuh dan nilai jual, serta preferensi pasar terhadap merek dan model tertentu, yang memberikan wawasan berharga untuk pemodelan dan pengambilan keputusan selanjutnya.

## Modelling 
Kami akan melakukan model benchmarking dengan 12 model, lalu akan memilih 3 model terbaik untuk dilakukan hyperparameter tuning.
Setelah itu akan mencari feature importances sampai kepada LIME, dan memberikan Model Implementation.

## Keuntungan Menggunakan Model Prediksi
Penggunaan model prediksi harga mobil bekas dapat memberikan beberapa keuntungan signifikan bagi web Syarah:

1. Penetapan Harga yang Akurat: Model prediksi membantu Syarah menetapkan harga jual yang lebih akurat dan kompetitif berdasarkan berbagai faktor seperti merek, model, tahun, jarak tempuh, dan kondisi mobil. Hal ini meningkatkan kepercayaan pembeli dan mempercepat proses penjualan.

2. Efisiensi Operasional: Dengan prediksi harga yang lebih tepat, Syarah dapat mengurangi waktu negosiasi, meminimalkan penyesuaian harga, dan mengoptimalkan manajemen inventaris. Ini menghasilkan proses jual-beli yang lebih efisien dan mengurangi biaya operasional.

3. Peningkatan Kepuasan Pelanggan: Harga yang transparan dan sesuai pasar meningkatkan kepuasan pelanggan. Pembeli merasa mendapatkan nilai yang sepadan, sementara penjual dapat menjual mobil mereka dengan harga yang wajar, menciptakan pengalaman positif bagi kedua belah pihak.


## Contributor Beta Team :
1. Jonathan Kurniawan Agay
2. Siti Hafsoh 
3. Alfa Isa Dewa

## Terima kasih :
1. Mas Achmad sebagai mentor
2. Mas Bayu sebagai mentor pengganti