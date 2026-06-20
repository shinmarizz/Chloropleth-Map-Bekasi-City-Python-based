# Chloropleth-Map-Bekasi-City-Python-based

# 📍 Pemetaan Jumlah Penduduk dan Persebaran Café Kota Bekasi Menggunakan Python

Repository ini berisi project pengolahan dan visualisasi data geospasial menggunakan Python untuk menghasilkan peta choropleth jumlah penduduk Kota Bekasi, peta persebaran café, serta peta interaktif sebagai sarana eksplorasi data secara dinamis.

## 📖 Deskripsi Project

Project ini memanfaatkan data spasial administrasi Kota Bekasi berformat GeoJSON yang memuat batas wilayah beserta atribut jumlah penduduk, serta data lokasi café untuk menganalisis pola persebarannya.

Pengolahan data dilakukan menggunakan beberapa library Python, yaitu:

- **GeoPandas** untuk membaca dan mengelola data spasial beserta atributnya.
- **MapClassify** untuk melakukan klasifikasi data pada peta choropleth.
- **Matplotlib** untuk membuat visualisasi peta statik.
- **Contextily** untuk menambahkan basemap.
- **Leafmap** untuk membangun peta interaktif dan eksplorasi data secara dinamis.

## 🎯 Tujuan Project

- Memvisualisasikan distribusi jumlah penduduk Kota Bekasi.
- Menampilkan persebaran café di Kota Bekasi.
- Mengembangkan visualisasi data spasial dalam bentuk statik maupun interaktif.
- Meningkatkan kemampuan pemrograman Python pada bidang geospasial.

## 🗂 Dataset

### Data Administrasi Kota Bekasi

- Format: GeoJSON
- Informasi:
  - Batas administrasi wilayah
  - Data jumlah penduduk

### Data Lokasi Café

- Format: CSV atau GeoJSON
- Informasi:
  - Nama café
  - Koordinat lokasi
  - Data pendukung lainnya

## 🛠 Library yang Digunakan

- GeoPandas
- MapClassify
- Matplotlib
- Contextily
- Leafmap
- Pandas
- NumPy

Instalasi library:

```bash
pip install geopandas mapclassify matplotlib contextily leafmap pandas numpy

Bekasi-Geospatial-Visualization/
│
├── data/
│   ├── kota_bekasi.geojson
│   ├── populasi_bekasi.geojson
│   └── landuse_bekasi.geojson
│   ├── cafe_bekasi.geojson
│   └── lpopulasi_bekasi.csv
│
├── notebook/
│   └── Chloropleth.ipynb
│
│
├── output/
│   ├── peta_choropleth_jumlah_penduduk.png
│   ├── peta_persebaran_cafe.png
│   └── pmap.html
│
├── requirements.txt
├── README.md
└── LICENSE

# 🚀 Fitur Project

- ✅ Membaca dan mengelola data spasial berformat GeoJSON.
- ✅ Membuat peta choropleth jumlah penduduk Kota Bekasi.
- ✅ Membuat peta statik persebaran café.
- ✅ Menambahkan basemap menggunakan Contextily.
- ✅ Membuat peta interaktif menggunakan Leafmap.
- ✅ Melakukan eksplorasi data spasial secara dinamis.

# 📚 Pembelajaran yang Diperoleh

Melalui project ini, saya mempelajari beberapa hal berikut:

## 🗂 Pengolahan dan Integrasi Data Spasial

Melakukan pengolahan serta integrasi data spasial dari berbagai sumber untuk kebutuhan visualisasi dan analisis.

## 🌐 Pengelolaan Data GeoJSON dengan GeoPandas

Memanfaatkan GeoPandas untuk membaca, mengelola, dan memanipulasi data spasial beserta atributnya.

## 📊 Klasifikasi Data Menggunakan MapClassify

Menerapkan metode klasifikasi untuk menghasilkan visualisasi peta choropleth yang informatif.

## 🗺 Visualisasi Peta Statik dengan Matplotlib

Membuat peta statik untuk menampilkan distribusi jumlah penduduk dan persebaran café.

## 🛰 Penambahan Basemap dengan Contextily

Mengintegrasikan basemap sebagai referensi spasial agar visualisasi lebih informatif.

## 🌍 Pembuatan Peta Interaktif dengan Leafmap

Mengembangkan peta interaktif yang memungkinkan eksplorasi data secara dinamis.

## 🎨 Styling dan Penyajian Informasi Spasial

Mempelajari teknik styling peta agar informasi dapat disampaikan secara efektif dan mudah dipahami.

# 👨‍💻 Tentang Project

Sebagai mahasiswa **Teknik Geodesi**, saya percaya bahwa kemampuan menggabungkan ilmu geospasial dengan tools pemrograman seperti **Python** merupakan keterampilan yang sangat relevan di era *data-driven* saat ini.

Project ini merupakan salah satu bentuk pengembangan kemampuan dalam bidang:

## 📍 Geographic Information System (GIS)

Pemanfaatan teknologi SIG untuk pengelolaan dan visualisasi data spasial.

## 📈 Analisis Spasial

Penerapan konsep dan metode analisis spasial untuk memperoleh informasi yang lebih bermakna dari data geospasial.

## 🗺 Visualisasi Data Geospasial

Pengembangan visualisasi peta statik maupun interaktif untuk mendukung eksplorasi dan penyampaia
