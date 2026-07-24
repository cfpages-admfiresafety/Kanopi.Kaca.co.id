# Topical Authority — kanopi.kaca.co.id

## Role and boundary

kanopi.kaca.co.id berperan sebagai kontraktor desain, fabrikasi, dan pemasangan kanopi kaca dengan portofolio instalasi untuk carport, teras, balkon, dapur, dan area bangunan lain. Hub edukasi ini membantu pemilik bangunan, desainer, kontraktor, pengelola properti, serta tim pengadaan menyusun brief, menilai sistem, mengoordinasikan struktur/drainase/pemasangan, dan merawat kanopi. Batasnya bukan katalog stok, daftar harga tetap, gambar kerja final, perhitungan struktur, rencana lifting/akses final, atau sumber klaim jenis/laminasi/ketebalan kaca, span, beban, angin, drainage capacity, kapasitas support/fixing, keselamatan, standar, sertifikasi, garansi, maupun performa tanpa bukti produk dan proyek yang berlaku.

## Context used

- Dua sitemap utama diperiksa: `sitemap-complete.xml` dan `video-sitemap.xml`. Sitemap lengkap memuat 136 URL unik dan selaras dengan 136 file HTML.
- Dari 136 URL sitemap lengkap, 102 memakai pola `kanopi-kaca-<kota>` dan diperlakukan sebagai satu keluarga intent komersial, bukan 102 topik geografis.
- Keluarga rute bermakna mencakup `bahan` (hub dan enam turunan), `model` (hub dan lima turunan), `pasang` (hub dan empat aplikasi), serta `warna` (hub dan empat turunan).
- Homepage publik memakai H1 “Kanopi Kaca” dan “Kontraktor Kanopi Kaca #1 Indonesia”, serta menampilkan pilihan kanopi, sistem/desain, dan portofolio instalasi.
- Navigasi homepage menguatkan opsi bahan, model gantung/geser/otomatis/sliding/spider, aplikasi balkon/carport/dapur/teras, dan pilihan tampilan.
- Mode lean dipertahankan. Isu kaca, span, beban/angin, struktur, drainage, fixing, sealant, pecah/falling glass, akses, perizinan, standar, sertifikasi, dan garansi dicatat sebagai gerbang publikasi.

## Ignored template noise

- 102 halaman pertukaran nama kota `kanopi-kaca-<kota>` dihitung, tetapi isi dan metadata berulangnya tidak dianalisis.
- Entri halaman berulang pada video sitemap tidak diperlakukan sebagai intent baru; sitemap itu memiliki 212 entri URL tetapi hanya 109 lokasi halaman unik.
- Arsip kategori/author, feed, komentar, upload, cache, manifest, verifikasi Google, dan file teknis tidak dipakai untuk memperluas taksonomi.
- README dan metadata template tidak dibaca karena sitemap XML, homepage, dan hub semantik sudah memberi konteks keputusan yang cukup.

## Topical map

| Topic ID | Parent topic | Reader outcome | Boundary | Article target |
|---|---|---|---|---:|
| KNP-01 | Dasar sistem kanopi kaca | Memahami komponen, istilah, dan batas sistem sebelum memilih | Fondasi konsep; tidak menetapkan kaca, frame, atau kapasitas sistem tertentu | 6 |
| KNP-02 | Brief dan pemilihan kanopi | Menerjemahkan fungsi, lokasi, paparan, serta anggaran menjadi shortlist | Edukasi kebutuhan lintas sistem; permintaan penawaran tetap di rute komersial | 6 |
| KNP-03 | Jenis, laminasi, dan ketebalan kaca | Menilai opsi kaca serta dokumen yang mendukung pemilihannya | Jenis, laminasi, heat treatment, interlayer, dan ketebalan wajib berdasarkan bukti aktual | 6 |
| KNP-04 | Material atap pembanding | Membandingkan kaca dengan akrilik, polycarbonate, kayu, dan opsi lain | Fokus pemilihan material; bukan klaim performa atau katalog produk | 6 |
| KNP-05 | Warna, cahaya, panas, dan tampilan | Mengendalikan transparansi, warna, glare, bayangan, dan kenyamanan visual | Klaim optik/termal hanya boleh terbit dengan data konfigurasi aktual | 6 |
| KNP-06 | Model dan mekanisme kanopi | Memahami model gantung, spider, sliding/geser, otomatis, dan fixed | Klasifikasi sistem; gerak, kapasitas, dan fail-safe memerlukan data produsen/rekayasa | 6 |
| KNP-07 | Geometri, span, kemiringan, dan drainage | Menyiapkan ukuran, panelisasi, slope, aliran air, serta titik pembuangan | Bukan penentuan span aman atau kapasitas drainase tanpa perhitungan proyek | 6 |
| KNP-08 | Frame, support, dan fixing | Mengoordinasikan rangka, bracket, anchor, sambungan, dan perlindungan korosi | Kapasitas dan kompatibilitas komponen wajib mengikuti data sistem serta substrate | 6 |
| KNP-09 | Beban, angin, dan rekayasa struktur | Mengenali load path, kondisi desain, dan pemicu review insinyur | Bukan perhitungan struktur, nilai beban, atau persetujuan kelayakan | 6 |
| KNP-10 | Pecah dan keselamatan falling glass | Mengurangi paparan risiko serta menyiapkan respons bila panel rusak | Tidak menjamin aman; keputusan retention, replacement, dan area closure perlu pihak kompeten | 6 |
| KNP-11 | Aplikasi kanopi pada bangunan | Menyusun kebutuhan khusus carport, teras, balkon, dapur, dan pintu masuk | Khusus use case; tidak mengambil intent sistem, struktur, atau halaman jasa lokasi | 6 |
| KNP-12 | Survei, desain, persetujuan, dan izin | Menghasilkan basis desain, mockup, approval, dan daftar koordinasi perizinan | Bukan gambar kerja final, izin resmi, atau deklarasi patuh | 6 |
| KNP-13 | Akses dan pemasangan | Mengoordinasikan kesiapan lokasi, lifting, toleransi, sealant, serta serah instalasi | Bukan metode kerja/lifting universal atau pengganti method statement proyek | 6 |
| KNP-14 | Pembersihan, inspeksi, dan perawatan | Menjalankan perawatan rutin serta mengenali kebocoran atau kerusakan | Tidak menjanjikan umur layanan; pecah/falling glass dimiliki KNP-10 | 6 |
| KNP-15 | Pengadaan, harga, jadwal, dan garansi | Menyiapkan RFQ, membandingkan biaya, mengatur logistik, dan membaca garansi | Harga dan garansi harus aktual; transaksi tetap berada di rute kontak | 6 |
| KNP-16 | Standar, sertifikasi, QA, dan dokumentasi | Memeriksa relevansi bukti kepatuhan dan kelengkapan serah terima | Tidak menyatakan patuh atau tersertifikasi tanpa dokumen dan verifikasi proyek | 6 |

## Internal-link rule

Setiap artikel menaut ke hub topiknya, satu artikel pendamping dalam topik yang sama, dan satu atau dua topik tetangga yang mendukung langkah berikutnya. Artikel pemilihan dapat mengarah ke rute komersial `bahan`, `model`, `pasang`, `warna`, atau `kontak-kami`; tidak ada artikel baru berbasis kota. Setiap pembahasan jenis/laminasi/ketebalan kaca, interlayer, span, load, wind, drainage, frame/support/fixing, sealant, pecah/falling glass, akses/lifting, struktur, izin, standar, sertifikasi, maintenance interval, garansi, dan harga harus menahan angka atau klaim sampai bukti produk/proyek yang relevan tersedia.

## First publication wave

Terbitkan 12 aset fondasi dan keputusan terlebih dahulu: `KNP-01-01`, `KNP-02-01`, `KNP-02-02`, `KNP-03-01`, `KNP-06-01`, `KNP-07-01`, `KNP-08-01`, `KNP-09-01`, `KNP-10-01`, `KNP-11-01`, `KNP-12-01`, dan `KNP-15-01`. Gelombang ini membangun kosakata, brief, jalur pemilihan, dan gerbang bukti tanpa menambah halaman geografis.
