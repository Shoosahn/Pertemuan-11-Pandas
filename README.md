<!-- @format -->

# Pertemuan 11 – Pandas

## Sumber Data dan Perubahan Dataset

Pada perencanaan awal, proyek ini dirancang menggunakan dataset Open Data Jawa Barat dengan judul *Jumlah Produksi Sampah Berdasarkan Kabupaten/Kota di Jawa Barat*, yang tersedia pada tautan berikut:

* [https://opendata.jabarprov.go.id/id/dataset/jumlah-produksi-sampah-berdasarkan-kabupatenkota-di-jawa-barat](https://opendata.jabarprov.go.id/id/dataset/jumlah-produksi-sampah-berdasarkan-kabupatenkota-di-jawa-barat)

Namun, pada saat proses pengambilan data dilakukan, dataset tersebut tidak dapat diakses karena URL menghasilkan respons **HTTP 404 (resource tidak ditemukan)**. Untuk menjaga keberlanjutan analisis dan memastikan penggunaan data yang valid serta resmi, dataset tersebut digantikan dengan dataset alternatif yang masih relevan, yaitu:

* [https://opendata.jabarprov.go.id/id/dataset/jumlah-sampah-yang-ditangani-berdasarkan-kabupatenkota-di-jawa-barat](https://opendata.jabarprov.go.id/id/dataset/jumlah-sampah-yang-ditangani-berdasarkan-kabupatenkota-di-jawa-barat)

Dataset pengganti ini tetap bersumber dari Open Data Jawa Barat dan menyediakan data jumlah sampah yang ditangani berdasarkan kabupaten/kota dan tahun. Meskipun terdapat perbedaan terminologi antara *produksi sampah* dan *sampah yang ditangani*, dataset ini masih sesuai dengan tujuan analisis dalam konteks latihan pengolahan dan analisis data menggunakan Pandas.

## Video

* [Tonton Video](https://drive.google.com/file/d/19bwSPB0cgPnQDGQaPQZkgYczSEqwZumy/view?usp=drive_link)


## Struktur Folder

* `main.ipynb`
  Notebook utama yang berisi seluruh proses analisis data.

* `data/`
  Folder yang berisi data sumber yang digunakan dalam analisis.

  * `disperkim-od_16984_jumlah_sampah_yang_ditangani_berdasarkan_kabupatenkota_data.csv`
    Dataset CSV sumber dari Open Data Jawa Barat mengenai jumlah sampah yang ditangani berdasarkan kabupaten/kota.

* `total_sampah_per_tahun.csv`
  File hasil rekapitulasi total sampah per tahun dalam format CSV.

* `total_sampah_per_tahun.xlsx`
  File hasil rekapitulasi total sampah per tahun dalam format Excel.

* `total_sampah_per_kabupaten_tahun.csv`
  File hasil rekapitulasi total sampah per kabupaten/kota per tahun dalam format CSV.

* `total_sampah_per_kabupaten_tahun.xlsx`
  File hasil rekapitulasi total sampah per kabupaten/kota per tahun dalam format Excel.

* `img/`
  Folder yang berisi aset gambar pendukung dokumentasi proyek.
