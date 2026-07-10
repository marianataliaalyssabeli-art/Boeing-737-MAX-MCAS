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

# I. KRONOLOGI & KONTEKS

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

# II. FAKTA KUNCI & CATATAN TRANSPARANSI

Fakta Terverifikasi (Berdasarkan Investigasi KNKT dan FAA):

- Single Point of Failure: Sistem MCAS hanya mengambil input dari satu sensor AoA tunggal, tanpa adanya komparasi atau validasi silang dengan sensor AoA di sisi sebelahnya. Jika sensor tunggal tersebut rusak atau mengalami error, MCAS akan tetap aktif mengeksekusi perintah nose-down.

- Penyembunyian Informasi: Boeing secara sengaja menghapus penjelasan detail mengenai sistem MCAS dari manual pelatihan pilot (Flight Crew Operations Manual) dengan tujuan agar pesawat tidak dikategorikan sebagai jenis baru yang membutuhkan pelatihan simulator mahal.

- Aktivasi Berulang: Jika pilot mencoba menarik tuas kendali untuk menaikkan hidung pesawat, MCAS akan aktif kembali secara otomatis setiap 5 detik setelah mendeteksi data AoA yang salah belum berubah, menyebabkan kelelahan fisik pada pilot (fight the software).

Informasi yang Sempat Disengketakan / Catatan Transparansi:

Asumsi Awal: Pihak produsen sempat memberikan narasi awal bahwa kecelakaan disebabkan oleh kurangnya kompetensi dan performa kru pilot (maskapai dunia ketiga). Namun, investigasi kotak hitam (Black Box) membuktikan pilot telah melakukan prosedur darurat sesuai buku petunjuk umum, tetapi sistem otomasi mengesampingkan kendali manual pilot secara agresif.

---

# III. PEMETAAN PEMANGKU KEPENTINGAN

|No | Pemangku Kepentingan                     | Peran/Kontribusi|  Dampak yang Diterima| Relasi Kuas|
|---|------------------------------------------|------------|---------------------------|------------|
|1. | Eksekutif & Manajemen Boeing             | Pengambil keputusan bisnis utama; menetapkan tenggat waktu ketat demi laba.| Penurunan reputasi global, tuntutan hukum pidana/perdata, kerugian finansial miliaran dolar.| Sangat Tinggi. Memiliki kuasa finansial dan struktural untuk menekan tim engineering agar memotong prosedur keselamatan.|
|2. | Software Engineers & Developer Boeing    | Perancang arsitektur perangkat lunak dan logika sistem MCAS.| Beban moral profesional, pemeriksaan hukum oleh Departemen Kehakiman AS.| Rendah-Sedang. Memiliki pengetahuan teknis, namun terikat secara hierarkis dan tidak berdaya melawan tekanan bisnis manajemen.|
|3. | Federal Aviation Administration (FAA)    | Regulator yang memberikan sertifikasi kelayakan terbang (Organization Designation Authorization).| Kehilangan kredibilitas sebagai otoritas keselamatan udara global karena terbukti melakukan kelalaian pengawasan.| Tinggi (Regulatif). Seharusnya memegang kendali penuh, namun melakukan kompromi dengan mendelegasikan sebagian besar inspeksi kepada Boeing sendiri.|
|4. | Pilot dan Maskapai (Lion Air & Ethiopian)| Pengguna akhir (End-user) teknologi sistem navigasi penerbangan.| Kehilangan nyawa kru, kerugian armada pesawat, hancurnya nama baik maskapai secara instan.| Sangat Rendah. Tidak diberikan transparansi informasi mengenai keberadaan MCAS di awal, diposisikan sebagai konsumen pasif tanpa pilihan.|
|5. | Penumpang & Publik                       | Konsumen akhir pengguna jasa penerbangan.| Korban jiwa sebanyak 346 orang dan trauma psikologis keluarga korban.| Nol. Tidak memiliki kontrol teknis maupun manajerial dalam operasional industri.|


---

# IV. ANALISIS EMPAT TEORI ETIKA

Etika umum digunakan untuk menilai apakah suatu tindakan benar atau salah berdasarkan prinsip rasional. Berikut merupakan empat analisis teori etika:

**1. Utilitarianisme (Konsekuensialisme)**

Utilitarianisme merupakan teori etika yang dikemukakan oleh Jeremy Bentham dan dikembangkan oleh John Stuart Mill, yang menyatakan bahwa suatu tindakan dianggap benar apabila menghasilkan manfaat terbesar bagi sebanyak mungkin orang.

Dalam kasus Boeing 737 MAX, sistem MCAS dirancang untuk meningkatkan keselamatan penerbangan secara umum. Namun, dalam implementasinya, sistem tersebut justru menyebabkan kecelakaan yang menewaskan 346 orang.

Dengan demikian, apabila dilihat dari perspektif utilitarianisme, dampak negatif yang ditimbulkan jauh lebih besar dibandingkan manfaatnya. Oleh karena itu, tindakan tersebut dapat dinilai tidak etis.

**2. Deontologi (Etika Kewajiban)**

Deontologi merupakan teori etika yang dikemukakan oleh Immanuel Kant, yang menyatakan bahwa suatu tindakan dinilai benar apabila sesuai dengan kewajiban moral dan prinsip universal, tanpa bergantung pada hasil akhir.

Dalam konteks ini, kewajiban profesional dalam pengembangan sistem teknologi meliputi kejujuran, transparansi, serta tanggung jawab dalam menjaga keselamatan publik. Namun, dalam kasus ini, informasi mengenai sistem MCAS tidak disampaikan secara jelas kepada pilot.

Hal tersebut menunjukkan adanya pelanggaran terhadap kewajiban moral, sehingga tindakan ini tidak dapat dibenarkan secara deontologis.

**3. Virtue Ethics (Etika Kebajikan)**

Virtue ethics merupakan pendekatan etika yang berasal dari pemikiran Aristoteles, yang menilai tindakan berdasarkan karakter dan kebajikan individu, seperti tanggung jawab, integritas, dan kehati-hatian.

Dalam kasus ini, keputusan yang diambil menunjukkan kurangnya kehati-hatian serta tanggung jawab profesional dalam merancang sistem yang aman.
Dengan demikian, tindakan tersebut tidak mencerminkan kebajikan seorang profesional dan dinilai tidak etis menurut pendekatan virtue ethics.

**4. Etika Hak/Kontraktarian**

Menilai tindakan berdasarkan penghormatan terhadap hak-hak dasar individu yang terikat dalam kontrak sosial atau legal. Penumpang pesawat membeli tiket berdasarkan kontrak sosial tak tertulis bahwa produsen dan maskapai menjamin keamanan mereka. Pilot memiliki hak atas informasi yang akurat mengenai pesawat yang mereka kendalikan. Boeing melanggar hak hidup penumpang dan hak informasi pilot demi mempertahankan keuntungan bisnis sepihak.

---

# V. LENSA KELIMA - PANCASILA
(Analisis sila 1–5 yang relevan + Nilai Kepancasilaan UP (Integritas, Kepedulian, Harmonis, Kolaboratif, Profesionalisme).)

---

# VI.  KODE ETIK PROFESI
(ACM/IEEE, PII, IAI, atau ASME sesuai bidang kasus — pasal/klausul mana yang dilanggar atau relevan.)

---

# VII. ANALISIS REGULASI & HUKUM
(UU PDP, UU ITE, dan regulasi sektoral terkait; pemisahan tegas tanggung jawab hukum vs tanggung jawab moral.)

---

# VIII. CHECKPOINT INTEGRITAS & ANTI-KORUPSI
(Penyalahgunaan kepercayaan/kewenangan, penyembunyian, konflik kepentingan; analisis UU Tipikor bila relevan.)

---

# IX. MANAJEMEN RISIKO & OPSI 4T
(Matriks risiko (ISO 31000) dan opsi penanganan: Terima, Tangani, Transfer, Tinggalkan.)

---

# X. RANCANGAN DAMPAK & KONTROL PREVENTIF
(Rekomendasi konkret agar insiden tidak terulang serta rancangan dampak ke masyarakat.)

---

# XI. PELAJARAN UTAMA
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