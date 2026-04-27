# Boeing 737 MAX MCAS  
## Analisis Kasus: Kegagalan Software pada Sistem Kritis

Dokumen ini disusun untuk memenuhi **Tugas Mata Kuliah Etika Profesi (A)**.

---

## Informasi Akademik
- **Dosen Pengampu**: Adi Wahyu Pribadi, S.Si., M.Kom  
- **Instansi**: Universitas Pancasila, Fakultas Teknik, S1 Teknik Informatika  
- **Tahun**: 2026  

---

## Anggota Kelompok 9

| Nama                        | NPM        |
|-----------------------------|------------|
| Ridwan Odi Nugroho         | 4524210089 |
| Ririn Verdawati            | 4524210090 |
| Nur Inayah Yusrizal        | 4524210117 |
| Maria Natalia Alyssa Beli  | 4524210133 |

---

## Deskripsi Kasus

(isi)

---

## Fokus Analisis

### 1. Kompromi Engineering vs Tekanan Bisnis

Pada kasus ini, terjadi benturan antara keputusan teknis (engineering) dengan kepentingan bisnis perusahaan.

#### Secara engineering, sistem MCAS seharusnya:
- Menggunakan lebih dari satu sensor (redundansi) untuk validasi data  
- Memiliki fail-safe mechanism (sistem aman jika terjadi error)  
- Memberikan informasi yang cukup ke pilot  

#### Tekanan Bisnis:
- Boeing ingin cepat bersaing dengan Airbus (khususnya A320neo)  
- Desain diubah seminimal mungkin agar pilot tidak perlu pelatihan tambahan  
- MCAS dibuat “diam-diam” tanpa penjelasan detail ke pilot  

#### Akibat:
- MCAS hanya bergantung pada 1 sensor (single point of failure)  
- Tidak ada validasi silang antar sensor  
- Informasi sistem tidak dijelaskan dengan jelas ke pilot  

Ketika sensor error:
- Sistem membaca kondisi yang salah  
- MCAS otomatis menurunkan hidung pesawat  
- Pilot kesulitan mengendalikan situasi  

---

### 2. Whistleblowing

(isi)

---

### 3. Tanggung Jawab Developer pada Sistem Safety-Critical
Dalam sistem safety-critical, developer memiliki tanggung jawab besar karena kesalahan kecil dapat menyebabkan dampak fatal seperti kecelakaan dan kehilangan nyawa. Hal ini terlihat pada kasus Lion Air Flight 610 crash, di mana kegagalan sistem berkontribusi terhadap kecelakaan.
Menurut Komite Nasional Keselamatan Transportasi (KNKT) dalam laporan investigasi Lion Air JT610, sistem MCAS bergantung pada satu sensor saja tanpa validasi dari sensor lain, sehingga meningkatkan risiko kesalahan sistem ketika sensor tersebut mengalami gangguan. Hal ini menunjukkan bahwa developer tidak menerapkan prinsip redundansi dalam sistem yang seharusnya menjadi standar pada sistem safety-critical.

Selain itu, menurut Badan Nasional Sertifikasi Profesi (BNSP), dalam praktik rekayasa perangkat lunak, seorang developer wajib menjunjung tinggi keselamatan, keandalan sistem, serta tanggung jawab etika profesional dalam setiap pengembangan teknologi, terutama yang berkaitan dengan keselamatan manusia. Artinya, developer tidak hanya bertanggung jawab secara teknis, tetapi juga harus memastikan bahwa sistem yang dibuat aman digunakan dalam berbagai kondisi, termasuk kondisi kegagalan.

Berdasarkan kedua sumber tersebut, tanggung jawab developer dalam sistem safety-critical meliputi:
- Mengutamakan keselamatan dibandingkan kepentingan bisnis
- Menerapkan redundansi (lebih dari satu sensor atau sumber data)
- Menyediakan mekanisme fail-safe saat terjadi error
- Memberikan informasi yang jelas kepada pengguna (pilot)
- Melakukan pengujian sistem secara menyeluruh
- Menjaga etika profesional dalam pengambilan keputusan teknis

Dengan demikian, dapat disimpulkan bahwa kegagalan dalam memenuhi tanggung jawab tersebut dapat menyebabkan sistem menjadi tidak aman dan berpotensi menimbulkan kecelakaan fatal.
