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

(isi)