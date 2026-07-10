# LAPORAN UAS ETIKA PROFESI - KELOMPOK 09  
## Analisis Kasus: Boeing 737 MAX MCAS - Kegagalan Software pada Sistem Kritis

Dokumen ini disusun untuk memenuhi **Laporan UAS Mata Kuliah Etika Profesi (A)**.

---

## Informasi Akademik
- **Dosen Pengampu**: Adi Wahyu Pribadi, S.Si., M.Kom  
- **Instansi**: Universitas Pancasila, Fakultas Teknik, S1 Teknik Informatika  
- **Tahun**: 2026  

---

## Anggota Kelompok-09

| Nama                        | NPM        | Peran                     |
|-----------------------------|------------|---------------------------|
| Ridwan Odi Nugroho          | 4524210089 | Menyusun Poin 1, 10 dan 11|
| Ririn Verdawati             | 4524210090 | Menyusun Poin 8 dan 9     |
| Nur Inayah Yusrizal         | 4524210117 | Menyusun Poin 5, 6 dan 7  |
| Maria Natalia Alyssa Beli   | 4524210133 | Menyusun Poin 2, 3 dan 4  |

---

## VIDEO PRESENTASI
(masukkan tautan yt presentasi kelompok)

---

# 1. KRONOLOGI & KONTEKS

Dua kecelakaan penerbangan besar yang melibatkan pesawat Boeing 737 MAX terjadi dalam kurun waktu kurang dari lima bulan, yaitu Lion Air Flight 610 pada 29 Oktober 2018 dan Ethiopian Airlines Flight 302 crash pada 10 Maret 2019. Kedua insiden ini menewaskan total 346 orang dan menimbulkan perhatian besar dari dunia internasional.

Penerbangan Lion Air JT610 lepas landas dari Jakarta menuju Pangkal Pinang sebelum akhirnya jatuh di perairan Laut Jawa sekitar 13 menit setelah lepas landas. Sementara itu, Ethiopian Airlines ET 302 yang berangkat dari Addis Ababa menuju Nairobi mengalami kecelakaan sekitar 6 menit setelah lepas landas di wilayah dekat Bishoftu, Ethiopia.

Departemen Kehakiman Amerika Serikat pada Selasa (14/5/2024) menyatakan bahwa Boeing dapat dituntut atas kecelakaan Lion Air JT 610 dan Ethiopian Airlines ET302 yang menewaskan total 346 orang.

| Detail        | Lion Air JT610                       | Ethiopian ET302                  |
|---------------|--------------------------------------|----------------------------------|
| Tanggal       | 29 Oktober 2018                      | 10 Maret 2019                    |
| Lokasi        | Laut Jawa, dekat Karawang, Indonesia | Dekat Addis Ababa, Ethiopia      |
| Korban Jiwa   | 189 orang                            | 157 orang                        |
| Penumpang     | 181 orang                            | 149 orang                        |
| Crew          | 8 orang (2 pilot + 6 crew cabin)     | 8 orang (2 pilot + 6 crew cabin) |
| Waktu Terbang | 13 menit setelah lepas landas        | 6 menit setelah lepas landas     |

### Lion Air Flight 610 crash
Setelah lepas landas, pilot melaporkan masalah pada sistem kontrol penerbangan. Pesawat mengalami perubahan ketinggian (naik–turun) secara tidak stabil dan kesulitan dikendalikan. Data penerbangan menunjukkan hidung pesawat berulang kali terdorong ke bawah oleh sistem otomatis, hingga akhirnya pesawat jatuh ke Laut Jawa.

### Ethiopian Airlines Flight 302 crash
Beberapa menit setelah lepas landas, pilot melaporkan kesulitan mengendalikan pesawat dan meminta izin kembali ke bandara. Pesawat mengalami pergerakan tidak stabil dan penurunan tajam (nose dive) sebelum akhirnya jatuh di daratan dekat Bishoftu.

---

# 2. FAKTA KUNCI & CATATAN TRANSPARANSI

Dalam menganalisis suatu kasus etika profesi, penting untuk membedakan antara fakta yang telah dibuktikan melalui investigasi resmi dengan informasi yang masih berupa dugaan atau sedang diproses secara hukum.

## 2.1 Fakta yang Telah Terverifikasi

Berdasarkan laporan KNKT, FAA, NTSB, dan Departemen Kehakiman Amerika Serikat, fakta-fakta berikut telah terverifikasi:

- Lion Air JT610 mengalami kecelakaan pada 29 Oktober 2018 dengan korban sebanyak 189 orang.
- Ethiopian Airlines ET302 mengalami kecelakaan pada 10 Maret 2019 dengan korban sebanyak 157 orang.
- Total korban jiwa dari kedua kecelakaan mencapai 346 orang.
- MCAS menggunakan data dari satu sensor AoA pada desain awal.
- Sensor AoA pada Lion Air JT610 memberikan data yang salah sebelum dan selama penerbangan.
- MCAS aktif berulang kali berdasarkan data sensor yang salah.
- Informasi mengenai MCAS tidak dijelaskan secara lengkap kepada sebagian besar pilot maupun maskapai.
- Setelah investigasi selesai, Boeing memperbarui perangkat lunak MCAS sehingga menggunakan dua sensor AoA dan membatasi aktivasi sistem.

## 2.2 Informasi yang Masih Diperdebatkan

Beberapa informasi berikut masih menjadi bagian dari proses hukum atau analisis publik sehingga tidak dapat dinyatakan sebagai fakta yang telah terbukti secara final.

- Dugaan bahwa tekanan persaingan dengan Airbus memengaruhi keputusan teknis dalam pengembangan 737 MAX.
- Dugaan bahwa proses sertifikasi dilakukan terlalu cepat.
- Dugaan adanya pengaruh Boeing terhadap sebagian proses evaluasi regulator.
- Dugaan bahwa peringatan dari beberapa engineer tidak ditindaklanjuti secara memadai oleh manajemen.

## 2.3 Catatan Transparansi

Dalam laporan ini, seluruh analisis etika didasarkan pada fakta yang telah dipublikasikan melalui laporan resmi KNKT, FAA, NTSB, dan dokumen Departemen Kehakiman Amerika Serikat. Sementara itu, informasi yang masih berupa dugaan tidak dijadikan dasar utama dalam penarikan kesimpulan, melainkan hanya digunakan sebagai konteks untuk memahami proses pengambilan keputusan organisasi.

Pendekatan ini bertujuan menjaga objektivitas analisis dan menghindari penyampaian informasi yang belum memiliki kepastian hukum.

---

# 3. PEMETAAN PEMANGKU KEPENTINGAN

|No | Pemangku Kepentingan                     | Peran/Kontribusi|  Dampak yang Diterima| Relasi Kuas|
|---|------------------------------------------|------------|---------------------------|------------|
|1. | Eksekutif & Manajemen Boeing             | Pengambil keputusan bisnis utama; menetapkan tenggat waktu ketat demi laba.| Penurunan reputasi global, tuntutan hukum pidana/perdata, kerugian finansial miliaran dolar.| Sangat Tinggi. Memiliki kuasa finansial dan struktural untuk menekan tim engineering agar memotong prosedur keselamatan.|
|2. | Software Engineers & Developer Boeing    | Perancang arsitektur perangkat lunak dan logika sistem MCAS.| Beban moral profesional, pemeriksaan hukum oleh Departemen Kehakiman AS.| Rendah-Sedang. Memiliki pengetahuan teknis, namun terikat secara hierarkis dan tidak berdaya melawan tekanan bisnis manajemen.|
|3. | Federal Aviation Administration (FAA)    | Regulator yang memberikan sertifikasi kelayakan terbang (Organization Designation Authorization).| Kehilangan kredibilitas sebagai otoritas keselamatan udara global karena terbukti melakukan kelalaian pengawasan.| Tinggi (Regulatif). Seharusnya memegang kendali penuh, namun melakukan kompromi dengan mendelegasikan sebagian besar inspeksi kepada Boeing sendiri.|
|4. | Pilot dan Maskapai (Lion Air & Ethiopian)| Pengguna akhir (End-user) teknologi sistem navigasi penerbangan.| Kehilangan nyawa kru, kerugian armada pesawat, hancurnya nama baik maskapai secara instan.| Sangat Rendah. Tidak diberikan transparansi informasi mengenai keberadaan MCAS di awal, diposisikan sebagai konsumen pasif tanpa pilihan.|
|5. | Penumpang & Publik                       | Konsumen akhir pengguna jasa penerbangan.| Korban jiwa sebanyak 346 orang dan trauma psikologis keluarga korban.| Nol. Tidak memiliki kontrol teknis maupun manajerial dalam operasional industri.|


---

# 4. ANALISIS EMPAT TEORI ETIKA

Etika umum digunakan untuk menilai apakah suatu tindakan benar atau salah berdasarkan prinsip rasional. Berikut merupakan empat analisis teori etika:

## 4.1 Utilitarianisme (Konsekuensialisme)

Utilitarianisme merupakan teori etika yang dikemukakan oleh Jeremy Bentham dan dikembangkan oleh John Stuart Mill, yang menyatakan bahwa suatu tindakan dianggap benar apabila menghasilkan manfaat terbesar bagi sebanyak mungkin orang.

Pada awal pengembangannya, Boeing berupaya mempertahankan daya saing terhadap Airbus melalui peluncuran Boeing 737 MAX tanpa memerlukan pelatihan simulator tambahan bagi pilot. Strategi tersebut diharapkan memberikan manfaat ekonomi berupa penghematan biaya pelatihan dan percepatan adopsi pesawat oleh maskapai.

Namun, keputusan tersebut justru menghasilkan dampak yang jauh lebih besar berupa hilangnya 346 nyawa, kerugian finansial miliaran dolar, penurunan kepercayaan publik terhadap industri penerbangan, serta penghentian operasi seluruh armada Boeing 737 MAX di berbagai negara.

Dengan demikian, apabila dilihat dari perspektif utilitarianisme, dampak negatif yang ditimbulkan jauh lebih besar dibandingkan manfaatnya. Oleh karena itu, tindakan tersebut dapat dinilai tidak etis.

## 4.2 Deontologi (Etika Kewajiban)

Deontologi merupakan teori etika yang dikemukakan oleh Immanuel Kant, yang menyatakan bahwa suatu tindakan dinilai benar apabila sesuai dengan kewajiban moral dan prinsip universal, tanpa bergantung pada hasil akhir.

Sebagai perusahaan yang mengembangkan sistem keselamatan penerbangan, Boeing memiliki kewajiban moral untuk:

- Mengembangkan sistem yang aman,
- Memberikan informasi yang jujur kepada pengguna,
- Melakukan pengujian secara menyeluruh,
- Mengutamakan keselamatan publik.

Fakta bahwa informasi mengenai MCAS tidak disampaikan secara memadai kepada pilot menunjukkan adanya pelanggaran terhadap kewajiban moral tersebut. Oleh karena itu, dari sudut pandang deontologi, tindakan tersebut tidak dapat dibenarkan.

## 4.3 Virtue Ethics (Etika Kebajikan)

Etika kebajikan yang dikembangkan Aristoteles menilai tindakan berdasarkan karakter moral dan kebajikan individu, seperti tanggung jawab, integritas, kejujuran, dan kehati-hatian.

Dalam kasus ini, keputusan yang diambil menunjukkan kurangnya sifat kehati-hatian (prudence), tanggung jawab (responsibility), kejujuran (honesty), dan integritas (integrity). Seorang profesional di bidang rekayasa perangkat lunak seharusnya lebih mengutamakan keselamatan pengguna dibandingkan kepentingan bisnis jangka pendek.

Dengan demikian, tindakan yang dilakukan tidak mencerminkan karakter profesional yang beretika.

## 4.4 Etika Hak/Kontraktarian

Teori hak menyatakan bahwa setiap individu memiliki hak yang harus dihormati oleh pihak lain.

Dalam konteks ini:

- Pilot memiliki hak memperoleh informasi yang lengkap mengenai sistem yang mereka operasikan.
- Penumpang memiliki hak atas keselamatan selama menggunakan layanan transportasi udara.
- Maskapai memiliki hak memperoleh produk yang aman dan sesuai spesifikasi.

Kurangnya transparansi mengenai cara kerja MCAS mengurangi kemampuan pilot dalam mengambil keputusan saat menghadapi kondisi darurat. Oleh karena itu, tindakan Boeing dapat dinilai melanggar hak-hak para pemangku kepentingan tersebut.

---

# 5. LENSA KELIMA - PANCASILA
(Analisis sila 1–5 yang relevan + Nilai Kepancasilaan UP (Integritas, Kepedulian, Harmonis, Kolaboratif, Profesionalisme).)

---

# 6.  KODE ETIK PROFESI
(ACM/IEEE, PII, IAI, atau ASME sesuai bidang kasus — pasal/klausul mana yang dilanggar atau relevan.)

---

# 7. ANALISIS REGULASI & HUKUM
(UU PDP, UU ITE, dan regulasi sektoral terkait; pemisahan tegas tanggung jawab hukum vs tanggung jawab moral.)

---

# 8. CHECKPOINT INTEGRITAS & ANTI-KORUPSI
(Penyalahgunaan kepercayaan/kewenangan, penyembunyian, konflik kepentingan; analisis UU Tipikor bila relevan.)

---

# 9. MANAJEMEN RISIKO & OPSI 4T
(Matriks risiko (ISO 31000) dan opsi penanganan: Terima, Tangani, Transfer, Tinggalkan.)

---

# 10. RANCANGAN DAMPAK & KONTROL PREVENTIF
(Rekomendasi konkret agar insiden tidak terulang serta rancangan dampak ke masyarakat.)

---

# 11. PELAJARAN UTAMA
(Refleksi pelajaran utama + untuk dafpus --> daftar sumber yang dapat diperiksa (utamakan sumber primer).)

---

# DAFTAR PUSTAKA

[1] R. K. Nistanto and R. Wahyudi, “KNKT Terbitkan Laporan Lion Air JT610, Ungkap Penyebab Kecelakaan,” Kompas.com, Oct. 25, 2019. [Online]. Available: https://tekno.kompas.com/read/2019/10/25/15420657/knkt-terbitkan-laporan-lion-air-jt610-ungkap-penyebab-kecelakaan?page=all

[2] A. et al., “Analisis Kasus Kecelakaan Lion Air JT610: Tinjauan Pidana dan Tanggung Jawab Korporasi dalam Keselamatan Penerbangan,” ResearchGate, 2024. [Online]. Available: https://www.researchgate.net/publication/384609060

[3] G. S. Widagdo, S. C. K. Datu, and H. Robbani, “Analisis kasus kecelakaan Lion Air JT610: Tinjauan pidana dan tanggung jawab korporasi dalam keselamatan penerbangan,” Decisio Law Journal, vol. 1, no. 1, pp. 34–39, 2024. [Online]. Available: https://www.researchgate.net/publication/384609060

[4] J. Bentham, An Introduction to the Principles of Morals and Legislation. [Online]. Available: https://www.econlib.org/library/Bentham/bnthPML.html

[5] I. Kant, Groundwork of the Metaphysics of Morals. [Online]. Available: https://www.earlymoderntexts.com/assets/pdfs/kant1785.pdf

[6] Association for Computing Machinery, “ACM Code of Ethics and Professional Conduct,” 2018. [Online]. Available: https://www.acm.org/code-of-ethics

[7] Institute of Electrical and Electronics Engineers, “IEEE Code of Ethics,” 2020. [Online]. Available: https://www.ieee.org/about/corporate/governance/p7-8.html

[8] Republik Indonesia, “Undang-Undang Nomor 11 Tahun 2008 tentang Informasi dan Transaksi Elektronik; Undang-Undang Nomor 8 Tahun 1999 tentang Perlindungan Konsumen; Undang-Undang Nomor 1 Tahun 2009 tentang Penerbangan.” [Online]. Available: https://peraturan.bpk.go.id