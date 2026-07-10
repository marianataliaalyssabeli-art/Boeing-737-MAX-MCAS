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

## 1.1 Latar Belakang

Kasus Boeing 737 MAX merupakan salah satu kegagalan rekayasa perangkat lunak (software engineering failure) terbesar dalam sejarah penerbangan modern. Kasus ini menjadi perhatian dunia setelah terjadinya dua kecelakaan fatal yang melibatkan Lion Air JT610 pada 29 Oktober 2018 dan Ethiopian Airlines ET302 pada 10 Maret 2019, yang mengakibatkan total 346 korban jiwa. Peristiwa tersebut memicu investigasi mendalam terhadap aspek teknis, proses sertifikasi, serta penerapan etika dan tanggung jawab profesional dalam pengembangan sistem keselamatan penerbangan.

Salah satu fokus utama investigasi adalah Maneuvering Characteristics Augmentation System (MCAS), yaitu perangkat lunak yang dirancang untuk membantu menjaga karakteristik aerodinamis Boeing 737 MAX akibat penggunaan mesin CFM LEAP-1B yang lebih besar dibandingkan seri sebelumnya. Sistem ini bekerja dengan menggerakkan horizontal stabilizer secara otomatis untuk menurunkan hidung pesawat ketika sensor mendeteksi sudut serang (Angle of Attack/AoA) yang terlalu tinggi.

Namun, berdasarkan hasil investigasi KNKT, FAA, dan NTSB, desain awal MCAS hanya menggunakan satu sensor AoA sebagai sumber data tanpa validasi silang. Ketika sensor tersebut memberikan data yang salah, MCAS menganggap pesawat berada dalam kondisi stall dan secara berulang menurunkan hidung pesawat hingga pilot kehilangan kendali. Selain itu, informasi mengenai cara kerja MCAS tidak disampaikan secara memadai kepada pilot, sehingga kasus ini menjadi contoh penting mengenai pentingnya keselamatan, transparansi, etika profesi, dan manajemen risiko dalam pengembangan sistem safety-critical.

## 1.2 Kronologi Peristiwa

29 Oktober 2018 – Lion Air JT610

- Pesawat lepas landas dari Bandara Soekarno-Hatta menuju Pangkal Pinang.
- Beberapa menit setelah lepas landas, sensor AoA memberikan data yang salah.
- MCAS aktif berulang kali dan terus menurunkan hidung pesawat.
- Pilot beberapa kali menarik kendali untuk menaikkan hidung pesawat, tetapi MCAS kembali aktif.
- Sekitar 13 menit setelah lepas landas, pesawat jatuh di Laut Jawa.
- Seluruh 189 orang di dalam pesawat meninggal dunia.

10 Maret 2019 – Ethiopian Airlines ET302

- Pesawat lepas landas dari Addis Ababa menuju Nairobi.
- Tidak lama setelah lepas landas, pilot melaporkan kesulitan mengendalikan pesawat.
- MCAS kembali aktif akibat pembacaan sensor AoA yang tidak akurat.
- Pilot meminta izin kembali ke bandara, tetapi kehilangan kendali atas pesawat.
- Sekitar 6 menit setelah lepas landas, pesawat jatuh di dekat Bishoftu.
- Seluruh 157 orang di dalam pesawat meninggal dunia.

Kemudian dilanjutkan dengan:

- 13 Maret 2019: seluruh armada Boeing 737 MAX ditunda atau dilarang terbang.
- 2020: Boeing memperbarui perangkat lunak MCAS agar menggunakan dua sensor AoA dan membatasi aktivasi sistem.
- 2024: Departemen Kehakiman Amerika Serikat kembali memproses perkara hukum terhadap Boeing terkait pelanggaran perjanjian.

## 1.3 Konteks Teknis

MCAS merupakan bagian dari Flight Control System yang bekerja secara otomatis ketika:

- Flaps berada pada posisi naik.
- Autopilot tidak aktif.
- Sensor AoA mendeteksi sudut serang tinggi.

Pada versi awal, MCAS memiliki beberapa kelemahan utama, yaitu:

- hanya menggunakan satu sensor AoA sebagai sumber data,
- tidak melakukan validasi silang terhadap sensor lainnya,
- dapat aktif berulang kali apabila data sensor tetap menunjukkan kondisi stall,
- informasi mengenai keberadaan dan cara kerja MCAS tidak dijelaskan secara memadai dalam Flight Crew Operations Manual (FCOM),
- pilot tidak memperoleh pelatihan khusus mengenai karakteristik MCAS.

Kelemahan tersebut menyebabkan sistem memiliki single point of failure, yaitu kondisi ketika kegagalan satu komponen saja dapat menyebabkan kegagalan keseluruhan sistem.

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

Kasus Boeing 737 MAX melibatkan berbagai pihak dengan kepentingan, peran, dampak yang diterima, dan relasi kuasa.

|No | Pemangku Kepentingan                     | Peran/Kontribusi|  Dampak yang Diterima| Relasi Kuasa|
|---|------------------------------------------|------------|---------------------------|------------|
|1. | Eksekutif & Manajemen Boeing             | Mengambil keputusan utama terkait pengembangan dan pemasaran Boeing 737 MAX, termasuk menentukan target waktu produksi.| Mengalami penurunan reputasi, menghadapi tuntutan hukum, serta mengalami kerugian finansial yang sangat besar.| Sangat Tinggi. Memiliki wewenang untuk menentukan kebijakan perusahaan dan memengaruhi keputusan tim engineering.|
|2. | Software Engineers & Developer Boeing    | Merancang dan mengembangkan perangkat lunak MCAS agar pesawat dapat beroperasi sesuai desain.| Menghadapi tekanan profesional, pemeriksaan hukum, dan tanggung jawab moral atas sistem yang dikembangkan.| Sedang. Memiliki pengetahuan teknis, tetapi keputusan akhir tetap berada di tangan manajemen.|
|3. | Federal Aviation Administration (FAA)    | Bertugas mengawasi dan memberikan sertifikasi kelayakan pesawat sebelum digunakan secara komersial.| Mendapat kritik karena dianggap kurang teliti dalam proses pengawasan dan sertifikasi Boeing 737 MAX.| TTinggi. Memiliki kewenangan untuk menyetujui atau menolak sertifikasi pesawat, sehingga berperan penting dalam menjamin keselamatan penerbangan.|
|4. | Pilot dan Maskapai (Lion Air & Ethiopian)| Mengoperasikan pesawat dan menggunakan sistem MCAS dalam penerbangan sehari-hari.| Kehilangan kru dan pesawat, mengalami kerugian finansial, serta menurunnya kepercayaan masyarakat terhadap maskapai.| Rendah. Bergantung pada informasi dan pelatihan yang diberikan oleh Boeing serta regulator mengenai sistem pesawat.|
|5. | Penumpang & Masyarakat                   | Menggunakan layanan penerbangan sebagai konsumen akhir.| Menjadi pihak yang paling dirugikan, dengan total 346 korban jiwa serta dampak psikologis bagi keluarga korban.| Sangat Rendah. Tidak memiliki kendali terhadap desain, pengembangan, maupun pengoperasian sistem pesawat.|

Berdasarkan pemetaan tersebut, dapat dilihat bahwa manajemen Boeing dan FAA merupakan pihak yang memiliki pengaruh paling besar dalam pengambilan keputusan, sedangkan pilot, maskapai, penumpang, dan masyarakat merupakan pihak yang paling terdampak apabila terjadi kegagalan sistem. Hal ini menunjukkan pentingnya setiap pihak yang memiliki kewenangan untuk mengutamakan keselamatan, transparansi, dan tanggung jawab dalam pengembangan maupun pengawasan sistem safety-critical.

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

[2] Federal Aviation Administration (FAA), “FAA Updates on Boeing 737 MAX,” Nov. 18, 2020. [Online]. Available: https://www.faa.gov/newsroom/faa-updates-boeing-737-max-0

[3] A. et al., “Analisis Kasus Kecelakaan Lion Air JT610: Tinjauan Pidana dan Tanggung Jawab Korporasi dalam Keselamatan Penerbangan,” ResearchGate, 2024. [Online]. Available: https://www.researchgate.net/publication/384609060

[4] G. S. Widagdo, S. C. K. Datu, and H. Robbani, “Analisis kasus kecelakaan Lion Air JT610: Tinjauan pidana dan tanggung jawab korporasi dalam keselamatan penerbangan,” Decisio Law Journal, vol. 1, no. 1, pp. 34–39, 2024. [Online]. Available: https://www.researchgate.net/publication/384609060

[5] J. Bentham, An Introduction to the Principles of Morals and Legislation. [Online]. Available: https://www.econlib.org/library/Bentham/bnthPML.html

[6] I. Kant, Groundwork of the Metaphysics of Morals. [Online]. Available: https://www.earlymoderntexts.com/assets/pdfs/kant1785.pdf

[7] Association for Computing Machinery, “ACM Code of Ethics and Professional Conduct,” 2018. [Online]. Available: https://www.acm.org/code-of-ethics

[8] Institute of Electrical and Electronics Engineers, “IEEE Code of Ethics,” 2020. [Online]. Available: https://www.ieee.org/about/corporate/governance/p7-8.html

[9] Republik Indonesia, “Undang-Undang Nomor 11 Tahun 2008 tentang Informasi dan Transaksi Elektronik; Undang-Undang Nomor 8 Tahun 1999 tentang Perlindungan Konsumen; Undang-Undang Nomor 1 Tahun 2009 tentang Penerbangan.” [Online]. Available: https://peraturan.bpk.go.id