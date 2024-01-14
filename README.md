# Data Analysis with Python

## Setup

- ``` git clone https://github.com/azissukmawan/data-analysis-with-python.git```
- ``` cd data-analysis-with-python ```
- ``` pipenv install ```
- ``` pipenv shell ```
- ``` streamlit run dashboard.py ```

## Siklus Analisis Data
![dos_98a461fc5d651c63f5292bf21753aea320230309131813](https://github.com/azissukmawan/data-analysis-with-python/assets/89589561/b01a6fbe-6783-49cc-bc1b-371b5e2376c1)

1. Mendefinisikan pertanyaan
   
Pada awal proyek analisis data, kita perlu mendefinisikan berbagai pertanyaan analisis terkait data ataupun permasalahan yang ingin diselesaikan.
Pertanyaan tersebut akan membantu kita dalam memahami masalah bisnis yang dihadapi serta tujuan yang ingin dicapai.
Bukan hanya itu, dengan adanya pertanyaan tersebut, kita akan merasa terbantu karena bisa lebih fokus pada bagian data yang relevan dengan tujuan.
Pada proses analisis data, terkadang kita diberikan data terlebih dahulu lalu mulai mendefinisikan pertanyaan analisis berdasarkan data tersebut. 
Namun, tidak jarang kita juga berangkat dari pertanyaan analisis terlebih dahulu lalu mencari data yang sesuai untuk menjawab pertanyaan tersebut.
Pada case berikut ini, ada beberapa pertanyaan yang harus di jawab dengan analisis data:
- Bagaimana performa penjualan dan revenue perusahaan dalam beberapa bulan terakhir?
- Produk apa yang paling banyak dan paling sedikit terjual?
- Bagaimana demografi pelanggan yang kita miliki?
- Kapan terakhir pelanggan melakukan transaksi?
- Seberapa sering seorang pelanggan melakukan pembelian dalam beberapa bulan terakhir?
- Berapa banyak uang yang dihabiskan pelanggan dalam beberapa bulan terakhir? 

2. Data Wrangling

Setelah kita memiliki pertanyaan analisis yang baik, tahap selanjutnya adalah data wrangling.
Pada tahap ini, Anda memulai dengan mengumpulkan data yang dibutuhkan untuk menjawab pertanyaan analisis yang telah dibuat sebelumnya.
Kemudian Anda perlu menilai kualitas dan struktur dari data tersebut.
Hal ini dilakukan untuk mengidentifikasi masalah yang terdapat dalam data serta membuat strategi pembersihan data yang sesuai.
Proses pembersihan data umumnya dilakukan dengan memodifikasi, mengganti, atau menghilangkan data yang bermasalah sehingga diperoleh dataset yang berkualitas dan terstruktur dengan baik.
FYI, pembersihan data merupakan salah satu proses yang paling menghabiskan waktu dalam proyek analisis data.
Oleh karena itu, kita sangat disarankan untuk menyediakan waktu yang cukup untuk melakukan pembersihan data.
Fase ini ada pada directory project [berikut](https://github.com/azissukmawan/data-analysis-with-python/blob/main/data-wrangling/notebook.ipynb)

3. Exploratory Data Analysis

Tahap berikutnya adalah Exploratory Data Analysis atau sering disingkat EDA.
Pada tahap inilah Anda akan melakukan eksplorasi terhadap data yang telah dibersihkan untuk memperoleh insight dan menjawab pertanyaan analisis.
Proses eksplorasi umumnya dilakukan dengan memanfaatkan berbagai teknik descriptive statistics (penggunaan konsep statistik untuk mendeskripsikan data).
Hal ini bertujuan untuk menemukan pola, hubungan, serta membangun intuisi terkait data yang diolah.
Selain menggunakan descriptive statistic, terkadang kita juga menggunakan teknik machine learning atau inferential statistic untuk memprediksi data di masa depan.
Namun, kedua teknik tersebut di luar cakupan pembahasan kita pada kelas ini.
Fase ini ada pada directory project [berikut](https://github.com/azissukmawan/data-analysis-with-python/blob/main/Exploratory-Data-Analysis/notebook.ipynb)

4. Data visualization
   
Hasil yang diperoleh dari EDA perlu divisualisasikan melalui tahap data visualization.
Pada tahap ini, kita akan menerapkan berbagai teknik dan jenis visualisasi data yang tepat untuk mengomunikasikan temuan atau insight dari hasil analisis secara efektif.
Fase ini ada pada directory project [berikut](https://github.com/azissukmawan/data-analysis-with-python/blob/main/Data-Visualization/notebook.ipynb)

5. Draw conclusion & communicate
   
Pada akhir proyek analisis data, kita perlu membuat conclusion atau kesimpulan dari hasil analisis.
Kesimpulan yang dibuat haruslah menjawab semua pertanyaan dan tujuan yang telah didefinisikan di awal.
Seperti dashboard di [streamlit](https://github.com/azissukmawan/data-analysis-with-python/blob/main/dashboard.py)

https://github.com/azissukmawan/data-analysis-with-python/assets/89589561/d19ee3a4-1ee8-4731-adb3-661fa0381690






