# Chloropleth-Map-Bekasi-City-Python-based

📍 Pemetaan Jumlah Penduduk dan Persebaran Café Kota Bekasi Menggunakan Python

Repository ini berisi project pengolahan dan visualisasi data geospasial menggunakan Python untuk menghasilkan peta jumlah penduduk Kota Bekasi serta peta persebaran café. Project ini dikembangkan sebagai bagian dari upaya untuk meningkatkan kemampuan dalam bidang GIS, analisis spasial, dan visualisasi data geospasial.

📖 Deskripsi Project

Pada project ini digunakan data spasial administrasi Kota Bekasi berformat GeoJSON yang memuat batas wilayah beserta atribut jumlah penduduk, serta data lokasi café untuk menganalisis pola persebarannya.

Pengolahan data dilakukan menggunakan beberapa library Python, antara lain:

GeoPandas → membaca dan mengelola data spasial beserta atributnya.
MapClassify → melakukan klasifikasi data untuk peta choropleth.
Matplotlib → membuat visualisasi peta statik.
Contextily → menambahkan basemap pada peta.
Leafmap → membangun peta interaktif dan eksplorasi data secara dinamis.
🎯 Tujuan Project
Memvisualisasikan distribusi jumlah penduduk Kota Bekasi.
Menampilkan pola persebaran café di Kota Bekasi.
Mengembangkan peta interaktif untuk eksplorasi data spasial.
Meningkatkan kemampuan pemrograman Python dalam bidang geospasial.
🗂 Dataset
Data Administrasi Kota Bekasi
Format: GeoJSON
Informasi:
Batas administrasi wilayah
Atribut jumlah penduduk
Data Lokasi Café
Format: CSV/GeoJSON
Informasi:
Nama café
Koordinat lokasi
Data pendukung lainnya
🛠 Library yang Digunakan
geopandas
matplotlib
mapclassify
contextily
leafmap
pandas
numpy

Instalasi:

pip install geopandas matplotlib mapclassify contextily leafmap pandas numpy
📌 Output Visualisasi
1. Peta Choropleth Statik Jumlah Penduduk Kota Bekasi

Visualisasi distribusi jumlah penduduk antarwilayah menggunakan klasifikasi data sehingga perbedaan kepadatan penduduk dapat terlihat dengan jelas.

Output:

output/peta_choropleth_jumlah_penduduk.png
2. Peta Statik Persebaran Café Kota Bekasi

Visualisasi lokasi café untuk melihat pola sebaran dan konsentrasi aktivitas ekonomi di Kota Bekasi.

Output:

output/peta_persebaran_cafe.png
3. Peta Interaktif Jumlah Penduduk Kota Bekasi

Peta interaktif yang memungkinkan pengguna untuk:

Zoom in dan zoom out.
Navigasi antarwilayah.
Menampilkan informasi atribut secara interaktif.
Eksplorasi data secara dinamis.

Output:

output/peta_interaktif_jumlah_penduduk.html
📁 Struktur Repository
Bekasi-Geospatial-Visualization/
│
├── data/
│   ├── batas_administrasi_bekasi.geojson
│   ├── jumlah_penduduk.csv
│   └── lokasi_cafe.csv
│
├── notebook/
│   └── Bekasi_Geospatial_Visualization.ipynb
│
├── scripts/
│   ├── choropleth_population.py
│   ├── cafe_distribution.py
│   └── interactive_map.py
│
├── output/
│   ├── peta_choropleth_jumlah_penduduk.png
│   ├── peta_persebaran_cafe.png
│   └── peta_interaktif_jumlah_penduduk.html
│
├── requirements.txt
├── README.md
└── LICENSE
🚀 Fitur Project

✅ Membaca dan mengolah data spasial GeoJSON
✅ Membuat peta choropleth jumlah penduduk
✅ Visualisasi persebaran café secara statik
✅ Menambahkan basemap menggunakan Contextily
✅ Membuat peta interaktif menggunakan Leafmap
✅ Eksplorasi data spasial secara dinamis

📚 Pembelajaran yang Diperoleh

Melalui project ini, saya mempelajari:

Pengolahan dan integrasi data spasial.
Pengelolaan data GeoJSON menggunakan GeoPandas.
Klasifikasi data menggunakan MapClassify.
Visualisasi peta statik dengan Matplotlib.
Penambahan basemap menggunakan Contextily.
Pembuatan peta interaktif menggunakan Leafmap.
Teknik styling peta agar informasi dapat tersampaikan secara efektif dan mudah dipahami.
👨‍💻 About

Sebagai mahasiswa Teknik Geodesi, saya percaya bahwa kemampuan menggabungkan ilmu geospasial dengan tools pemrograman seperti Python merupakan keterampilan yang sangat relevan di era data-driven saat ini. Project ini menjadi salah satu bentuk pengembangan kemampuan dalam bidang GIS, geospatial analysis, dan data visualization.
