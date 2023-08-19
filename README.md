Assignment-DataScience-Hacktiv8
1. Tugas 1
LATAR BELAKANG
LSOA adalah area sensus yang berisi 1.000 hingga 3.000 orang. SOA dirancang untuk meningkatkan pelaporan statistik area kecil dan dibangun dari kelompok area keluaran (OA). Statistik untuk area output super lapisan bawah (LSOA) dan area output super lapisan tengah (MSOA) awalnya dirilis pada tahun 2004 untuk Inggris dan Wales. Skotlandia juga merilis statistik untuk zona data (DZ), yang setara dengan LSOA, pada tahun 2004 dan geografi menengah (IG), yang setara dengan MSOA, pada tahun 2005. Irlandia Utara memperkenalkan LSOA pada tahun 2005 tetapi tidak memiliki geografi MSOA.

TENTANG DATASET
Data ini, diwakili oleh file london_crime_by_lsoa.csv, mencakup jumlah laporan kriminal berdasarkan bulan, wilayah LSOA, dan kategori mayor/minor dari Jan 2008-Des 2016 di London Raya (London pusat dan wilayah metropolitan sekitarnya) dengan menyediakan 13.490.604 sampel dengan 7 variabel setiap.

Variabel lsoa_code, borough, major_category, minor_category, yeardan monthmerupakan variabel kategorikal , sedangkan valuemerupakan variabel numerik diskrit . Arti variabel adalah sebagai berikut:

lsoa_code: kode untuk Area Output Super Bawah di London Raya;
borough: nama umum untuk wilayah London;
major_category: kategorisasi kejahatan tingkat tinggi;
minor_category: kategorisasi kejahatan tingkat rendah dalam kategori utama;
year: tahun penghitungan dilaporkan, 2008-2016;
month: bulan dari hitungan yang dilaporkan, 1-12;
value: jumlah kejahatan kategoris yang dilaporkan setiap bulan di wilayah tertentu;
2. Tugas 2
Latar belakang
Dataset ini berisi lokasi, alamat, tipe, harga jual, dan tanggal penjualan unit bangunan yang terjual. Referensi di bidang yang lebih rumit:

BOROUGH : Kode digit untuk borough tempat properti berada; agar ini adalah Manhattan (1), Bronx (2), Brooklyn (3), Queens (4), dan Staten Island (5).
MEMBLOKIR; BANYAK : Kombinasi borough, blok, dan lot membentuk kunci unik untuk properti di New York City. Biasa disebut BBL.
KELAS BANGUNAN SAAT INI dan KELAS BANGUNAN SAAT DIJUAL : : Jenis bangunan pada berbagai titik waktu.
Perhatikan bahwa karena ini adalah kumpulan data transaksi keuangan, ada beberapa hal yang perlu diingat:

Banyak penjualan terjadi dengan jumlah dolar yang sangat kecil: $0 paling sering. Penjualan ini sebenarnya adalah pengalihan akta antar pihak: misalnya, orang tua mengalihkan kepemilikan rumah mereka kepada seorang anak setelah pindah untuk pensiun.
Kumpulan data ini menggunakan definisi keuangan dari bangunan/unit bangunan, untuk tujuan perpajakan. Dalam hal satu entitas memiliki bangunan tersebut, penjualan mencakup nilai seluruh bangunan. Jika sebuah bangunan dimiliki sedikit demi sedikit oleh penghuninya (kondominium), penjualan mengacu pada satu apartemen (atau sekelompok apartemen) yang dimiliki oleh beberapa individu.
3. Penugasan 3
Ulasan Proyek
Data tersebut terkait dengan kampanye pemasaran langsung dari lembaga perbankan Portugis. Kampanye pemasaran didasarkan pada panggilan telepon. Seringkali, lebih dari satu kontak ke klien yang sama diperlukan, untuk mengakses apakah produk (deposit berjangka bank) akan ('ya') atau tidak ('tidak') berlangganan. Ada empat dataset:

bank-additional-full.csv dengan semua contoh (41188) dan 20 input, diurutkan berdasarkan tanggal (dari Mei 2008 hingga November 2010), sangat dekat dengan data yang dianalisis dalam [Moro et al., 2014]

bank-additional.csv dengan 10% contoh (4119), dipilih secara acak dari 1), dan 20 masukan.

bank-full.csv dengan semua contoh dan 17 input, diurutkan berdasarkan tanggal (versi lama dari kumpulan data ini dengan input yang lebih sedikit).

bank.csv dengan 10% contoh dan 17 masukan, dipilih secara acak dari 3 (versi lama kumpulan data ini dengan masukan lebih sedikit).

link dataset : disini

Kumpulan data terkecil disediakan untuk menguji algoritme pembelajaran mesin yang lebih menuntut komputasi (misalnya, SVM). Tujuan klasifikasi adalah untuk memprediksi apakah klien akan berlangganan (ya/tidak) deposito berjangka (variabel y).
