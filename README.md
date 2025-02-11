# MySkill-PredictionModel-Portofolio

## LATAR BELAKANG
FinanKu adalah sebuah startup fintech imajiner yang memberikan fasilitas simpanan dan pinjaman kepada nasabahnya. Jasa yang mereka tawarkan di antaranya tabungan, deposito, pinjaman tanpa agunan, kartu kredit, dan pembiayaan kendaraan mobil dan motor.

Saat ini, FinanKu memiliki pelanggan sebanyak ~20.000 yang tersebar di 3 kota besar di Indonesia; Jakarta, Bandung, dan Surabaya. Angka ini cukup besar mengingat FinanKu baru berjalan selama 1,5 tahun, di mana diekspektasikan dalam 3 tahun ke depan pelanggan mereka akan berjumlah 300.000+.

Perkembangan yang cepat ini membuat para stakeholders di divisi kredit FinanKu semakin berhati-hati dalam menyalurkan kredit yang dimiliki agar tidak mengalami gagal bayar, khususnya dari lini Kartu Kredit yang memiliki fitur instant approval dalam 1 menit.

## PROBLEM STATEMENT
Kekhawatiran adanya keterlambatan pembayaran kartu kredit pada FinanKu yang akan merugikan bisnis. Sehingga orang-orang yang memiliki potensi untuk mengalami keterlambatan bayar bisa diprediksi lebih cepat untuk menentukan strategi yang sesuai dalam menghadapi kondisi di masa mendatang.

## OBJECTIVE
MEmbuat sebuah model yang dapat memprediksi setidaknya 60% dari pelanggan yang akan mengalami telat bayar kartu kredit[Accuracy & Recall di atas 60%]

## VARIABEL YANG TERSEDIA
Dari dataset yang dimiliki terdapat beberapa data yang tersedia:

* Customer ID = ID unik Customer
* Branch = Lokasi Cabang Nasabah Terdaftar
* City = Lokasi Kota Nasabah Terdaftar
* Age = Umur Nasabah Pada Periode Observasi
* Avg. Annual Income/Month = Rata-rata penghasilan nasabah dalam satu tahun
* Balance (Q1-Q4) = Saldo mengendap yang dimiliki nasabah di akhir kuartal
* Num of Products (Q1-Q4) = Jumlah kepemilikan produk nasabah di akhir kuartal
* HasCrCard (Q1-Q4) = Status kepemilikan produk kartu kredit nasabah di akhir kuartal
* Active Member (Q1-Q4) = Status keaktifan nasabah
* Unpaid Tagging = Status nasabah gagal bayar

## MODEL YANG DIGUNAKAN
1. Logistic regression
2. Gradient boosting
3. Random forest build using Scikit-Learn library
