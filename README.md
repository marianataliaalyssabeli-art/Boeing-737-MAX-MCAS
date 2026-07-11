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

## 1. KRONOLOGI & KONTEKS

### 1.1 Latar Belakang

Kasus Boeing 737 MAX merupakan salah satu kegagalan rekayasa perangkat lunak (software engineering failure) terbesar dalam sejarah penerbangan modern. Kasus ini menjadi perhatian dunia setelah terjadinya dua kecelakaan fatal yang melibatkan Lion Air JT610 pada 29 Oktober 2018 dan Ethiopian Airlines ET302 pada 10 Maret 2019, yang mengakibatkan total 346 korban jiwa. Peristiwa tersebut memicu investigasi mendalam terhadap aspek teknis, proses sertifikasi, serta penerapan etika dan tanggung jawab profesional dalam pengembangan sistem keselamatan penerbangan.

Salah satu fokus utama investigasi adalah Maneuvering Characteristics Augmentation System (MCAS), yaitu perangkat lunak yang dirancang untuk membantu menjaga karakteristik aerodinamis Boeing 737 MAX akibat penggunaan mesin CFM LEAP-1B yang lebih besar dibandingkan seri sebelumnya. Sistem ini bekerja dengan menggerakkan horizontal stabilizer secara otomatis untuk menurunkan hidung pesawat ketika sensor mendeteksi sudut serang (Angle of Attack/AoA) yang terlalu tinggi.

Namun, berdasarkan hasil investigasi KNKT, FAA, dan NTSB, desain awal MCAS hanya menggunakan satu sensor AoA sebagai sumber data tanpa validasi silang. Ketika sensor tersebut memberikan data yang salah, MCAS menganggap pesawat berada dalam kondisi stall dan secara berulang menurunkan hidung pesawat hingga pilot kehilangan kendali. Selain itu, informasi mengenai cara kerja MCAS tidak disampaikan secara memadai kepada pilot, sehingga kasus ini menjadi contoh penting mengenai pentingnya keselamatan, transparansi, etika profesi, dan manajemen risiko dalam pengembangan sistem safety-critical.

### 1.2 Kronologi Peristiwa

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

### 1.3 Konteks Teknis

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

## 2. FAKTA KUNCI & CATATAN TRANSPARANSI

Dalam menganalisis suatu kasus etika profesi, penting untuk membedakan antara fakta yang telah dibuktikan melalui investigasi resmi dengan informasi yang masih berupa dugaan atau sedang diproses secara hukum.

### 2.1 Fakta yang Telah Terverifikasi

Berdasarkan laporan KNKT, FAA, NTSB, dan Departemen Kehakiman Amerika Serikat, fakta-fakta berikut telah terverifikasi:

- Lion Air JT610 mengalami kecelakaan pada 29 Oktober 2018 dengan korban sebanyak 189 orang.
- Ethiopian Airlines ET302 mengalami kecelakaan pada 10 Maret 2019 dengan korban sebanyak 157 orang.
- Total korban jiwa dari kedua kecelakaan mencapai 346 orang.
- MCAS menggunakan data dari satu sensor AoA pada desain awal.
- Sensor AoA pada Lion Air JT610 memberikan data yang salah sebelum dan selama penerbangan.
- MCAS aktif berulang kali berdasarkan data sensor yang salah.
- Informasi mengenai MCAS tidak dijelaskan secara lengkap kepada sebagian besar pilot maupun maskapai.
- Setelah investigasi selesai, Boeing memperbarui perangkat lunak MCAS sehingga menggunakan dua sensor AoA dan membatasi aktivasi sistem.

### 2.2 Informasi yang Masih Diperdebatkan

Beberapa informasi berikut masih menjadi bagian dari proses hukum atau analisis publik sehingga tidak dapat dinyatakan sebagai fakta yang telah terbukti secara final.

- Dugaan bahwa tekanan persaingan dengan Airbus memengaruhi keputusan teknis dalam pengembangan 737 MAX.
- Dugaan bahwa proses sertifikasi dilakukan terlalu cepat.
- Dugaan adanya pengaruh Boeing terhadap sebagian proses evaluasi regulator.
- Dugaan bahwa peringatan dari beberapa engineer tidak ditindaklanjuti secara memadai oleh manajemen.

### 2.3 Catatan Transparansi

Dalam laporan ini, seluruh analisis etika didasarkan pada fakta yang telah dipublikasikan melalui laporan resmi KNKT, FAA, NTSB, dan dokumen Departemen Kehakiman Amerika Serikat. Sementara itu, informasi yang masih berupa dugaan tidak dijadikan dasar utama dalam penarikan kesimpulan, melainkan hanya digunakan sebagai konteks untuk memahami proses pengambilan keputusan organisasi.

Pendekatan ini bertujuan menjaga objektivitas analisis dan menghindari penyampaian informasi yang belum memiliki kepastian hukum.

---

## 3. PEMETAAN PEMANGKU KEPENTINGAN

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

## 4. ANALISIS EMPAT TEORI ETIKA

Etika umum digunakan untuk menilai apakah suatu tindakan benar atau salah berdasarkan prinsip rasional. Berikut merupakan empat analisis teori etika:

### 4.1 Utilitarianisme (Konsekuensialisme)

Utilitarianisme merupakan teori etika yang dikemukakan oleh Jeremy Bentham dan dikembangkan oleh John Stuart Mill, yang menyatakan bahwa suatu tindakan dianggap benar apabila menghasilkan manfaat terbesar bagi sebanyak mungkin orang.

Pada awal pengembangannya, Boeing berupaya mempertahankan daya saing terhadap Airbus melalui peluncuran Boeing 737 MAX tanpa memerlukan pelatihan simulator tambahan bagi pilot. Strategi tersebut diharapkan memberikan manfaat ekonomi berupa penghematan biaya pelatihan dan percepatan adopsi pesawat oleh maskapai.

Namun, keputusan tersebut justru menghasilkan dampak yang jauh lebih besar berupa hilangnya 346 nyawa, kerugian finansial miliaran dolar, penurunan kepercayaan publik terhadap industri penerbangan, serta penghentian operasi seluruh armada Boeing 737 MAX di berbagai negara.

Dengan demikian, apabila dilihat dari perspektif utilitarianisme, dampak negatif yang ditimbulkan jauh lebih besar dibandingkan manfaatnya. Oleh karena itu, tindakan tersebut dapat dinilai tidak etis.

### 4.2 Deontologi (Etika Kewajiban)

Deontologi merupakan teori etika yang dikemukakan oleh Immanuel Kant, yang menyatakan bahwa suatu tindakan dinilai benar apabila sesuai dengan kewajiban moral dan prinsip universal, tanpa bergantung pada hasil akhir.

Sebagai perusahaan yang mengembangkan sistem keselamatan penerbangan, Boeing memiliki kewajiban moral untuk:

- Mengembangkan sistem yang aman,
- Memberikan informasi yang jujur kepada pengguna,
- Melakukan pengujian secara menyeluruh,
- Mengutamakan keselamatan publik.

Fakta bahwa informasi mengenai MCAS tidak disampaikan secara memadai kepada pilot menunjukkan adanya pelanggaran terhadap kewajiban moral tersebut. Oleh karena itu, dari sudut pandang deontologi, tindakan tersebut tidak dapat dibenarkan.

### 4.3 Virtue Ethics (Etika Kebajikan)

Etika kebajikan yang dikembangkan Aristoteles menilai tindakan berdasarkan karakter moral dan kebajikan individu, seperti tanggung jawab, integritas, kejujuran, dan kehati-hatian.

Dalam kasus ini, keputusan yang diambil menunjukkan kurangnya sifat kehati-hatian (prudence), tanggung jawab (responsibility), kejujuran (honesty), dan integritas (integrity). Seorang profesional di bidang rekayasa perangkat lunak seharusnya lebih mengutamakan keselamatan pengguna dibandingkan kepentingan bisnis jangka pendek.

Dengan demikian, tindakan yang dilakukan tidak mencerminkan karakter profesional yang beretika.

### 4.4 Etika Hak/Kontraktarian

Teori hak menyatakan bahwa setiap individu memiliki hak yang harus dihormati oleh pihak lain.

Dalam konteks ini:

- Pilot memiliki hak memperoleh informasi yang lengkap mengenai sistem yang mereka operasikan.
- Penumpang memiliki hak atas keselamatan selama menggunakan layanan transportasi udara.
- Maskapai memiliki hak memperoleh produk yang aman dan sesuai spesifikasi.

Kurangnya transparansi mengenai cara kerja MCAS mengurangi kemampuan pilot dalam mengambil keputusan saat menghadapi kondisi darurat. Oleh karena itu, tindakan Boeing dapat dinilai melanggar hak-hak para pemangku kepentingan tersebut.

---

## 5. LENSA KELIMA - PANCASILA
### 5.1 Analisis Sila 1–5

### Sila 1 – Ketuhanan Yang Maha Esa
Setiap profesi rekayasa membawa amanah moral untuk tidak menyalahgunakan ilmu pengetahuan demi keuntungan yang mengorbankan nyawa manusia. Keputusan merilis MCAS tanpa validasi ganda sensor dan tanpa transparansi kepada pilot bertentangan dengan nilai keluhuran budi yang menjadi dasar tanggung jawab profesional di hadapan Tuhan dan sesama manusia.

### Sila 2 – Kemanusiaan yang Adil dan Beradab
Sila ini menuntut penghormatan terhadap harkat dan martabat manusia. Hilangnya 346 nyawa akibat kegagalan sistem yang seharusnya dapat dicegah menunjukkan pengabaian terhadap nilai kemanusiaan. Keselamatan penumpang dikorbankan demi efisiensi biaya pelatihan dan kecepatan sertifikasi.

### Sila 3 – Persatuan Indonesia
Meskipun kasus ini terjadi pada ranah internasional, dampaknya dirasakan langsung oleh Indonesia melalui kecelakaan Lion Air JT610. Sila ini menegaskan pentingnya solidaritas, perlindungan negara terhadap warganya, serta peran KNKT sebagai representasi kedaulatan investigasi nasional.

### Sila 4 – Kerakyatan yang Dipimpin oleh Hikmat Kebijaksanaan dalam Permusyawaratan/Perwakilan
Sila ini menekankan pentingnya pengambilan keputusan melalui musyawarah dengan mempertimbangkan masukan seluruh pihak, termasuk engineer yang memahami risiko teknis. Dugaan diabaikannya peringatan teknis menunjukkan lemahnya penerapan prinsip musyawarah.

### Sila 5 – Keadilan Sosial bagi Seluruh Rakyat Indonesia
Teknologi seharusnya memberikan manfaat secara adil tanpa mengorbankan keselamatan pihak lain. Dalam kasus MCAS, keuntungan ekonomi lebih banyak dinikmati perusahaan, sedangkan risiko ditanggung oleh pilot dan penumpang sehingga mencerminkan ketidakadilan sosial.

---

### 5.2 Nilai Kepancasilaan Universitas Pancasila

| Nilai | Refleksi terhadap Kasus |
|--------|--------------------------|
| **Integritas** | Tim engineering dan manajemen Boeing tidak konsisten antara pengetahuan teknis mengenai kelemahan MCAS dengan informasi yang diberikan kepada regulator maupun pilot. |
| **Kepedulian** | Keselamatan pengguna akhir kurang diprioritaskan dibanding target peluncuran produk. |
| **Harmonis** | Hubungan antara engineer, manajemen, dan regulator tidak berjalan secara seimbang sehingga mekanisme pengawasan melemah. |
| **Kolaboratif** | Kolaborasi Boeing dan FAA melalui skema ODA menimbulkan konflik kepentingan yang mengurangi independensi pengawasan. |
| **Profesionalisme** | Prioritas terhadap jadwal produksi dibanding evaluasi teknis menunjukkan pelanggaran terhadap profesionalisme keinsinyuran. |

---

## 6.  KODE ETIK PROFESI

Kasus Boeing 737 MAX MCAS berkaitan dengan kegagalan perangkat lunak pada sistem keselamatan penerbangan. Oleh karena itu, analisis menggunakan **ACM/IEEE-CS Software Engineering Code of Ethics**, **IEEE Code of Ethics**, serta **Kode Etik Insinyur Indonesia (PII)** sebagai pembanding.

### 6.1 ACM/IEEE-CS Software Engineering Code of Ethics (1997)

### Prinsip 1 – Public
Software engineer wajib mengutamakan kepentingan publik. Perangkat lunak hanya boleh disetujui apabila telah memenuhi standar keamanan, lolos pengujian yang memadai, serta tidak membahayakan masyarakat. MCAS dinilai belum memenuhi prinsip tersebut karena dirilis tanpa validasi sensor yang memadai.

### Prinsip 6 – Profession
Insinyur wajib menjaga integritas profesi, menjunjung standar profesional, serta melaporkan risiko yang diketahui. Dalam kasus MCAS, tekanan bisnis diduga menghambat penyampaian informasi mengenai risiko sistem.

### 6.2 IEEE Code of Ethics

IEEE mewajibkan setiap anggotanya untuk mengutamakan keselamatan, kesehatan, dan kesejahteraan masyarakat. Keputusan untuk tidak mengungkapkan seluruh informasi mengenai MCAS kepada regulator maupun pilot bertentangan dengan prinsip tersebut.

### 6.3 Kode Etik Insinyur Indonesia (PII)

Sebagai pembanding nasional, Kode Etik Insinyur Indonesia menekankan bahwa insinyur harus:

- Mengutamakan keselamatan, kesehatan, dan kesejahteraan masyarakat.
- Menjunjung keluhuran budi.
- Menyampaikan pendapat secara objektif berdasarkan fakta.

Walaupun tidak mengikat Boeing secara hukum, prinsip-prinsip tersebut menunjukkan bahwa penyembunyian informasi teknis mengenai MCAS bertentangan dengan etika profesi keinsinyuran.

### Kesimpulan

Baik ACM/IEEE maupun PII sama-sama menempatkan keselamatan publik sebagai prioritas utama. Prinsip tersebut dinilai tidak terpenuhi dalam pengembangan dan implementasi MCAS.

---

## 7. ANALISIS REGULASI & HUKUM

### 7.1 Kerangka Hukum Amerika Serikat

Regulasi utama yang berkaitan dengan kasus ini meliputi:

- **14 CFR Part 25**, yaitu standar sertifikasi pesawat kategori transport.
- **Organization Designation Authorization (ODA)**, yaitu kewenangan Boeing melakukan sebagian proses sertifikasi atas nama FAA.
- **Deferred Prosecution Agreement (DPA) Tahun 2021**, di mana Boeing membayar denda sebesar **US$243,6 juta** dan dana kompensasi **US$500 juta** bagi keluarga korban.
- Pada tahun 2024–2025, Department of Justice (DOJ) kembali mengevaluasi kepatuhan Boeing terhadap kesepakatan tersebut.

### 7.2 Kerangka Hukum Indonesia

Regulasi yang berkaitan dengan kecelakaan Lion Air JT610 meliputi:

- **UU No. 1 Tahun 2009 tentang Penerbangan**, yang mengatur kelaikudaraan, tanggung jawab operator, dan investigasi oleh KNKT.
- **UU No. 11 Tahun 2008 jo. UU No. 19 Tahun 2016 tentang ITE**, sebagai rujukan mengenai keandalan sistem elektronik.
- **UU No. 27 Tahun 2022 tentang Pelindungan Data Pribadi**, yang tidak berkaitan langsung dengan kasus karena tidak melibatkan penyalahgunaan data pribadi.

### 7.3 Tanggung Jawab Hukum dan Moral

| Aspek | Tanggung Jawab Hukum | Tanggung Jawab Moral |
|--------|----------------------|----------------------|
| **Dasar** | Putusan pengadilan dan regulator. | Prinsip etika profesi. |
| **Pihak Bertanggung Jawab** | Boeing dan pihak yang terbukti melanggar hukum. | Manajemen, engineer, regulator, dan seluruh pihak yang berkontribusi terhadap kegagalan. |
| **Status** | Proses hukum masih berkembang. | Dapat dinilai tanpa menunggu putusan hukum. |

### Catatan

- Proses hukum Boeing masih terus berkembang sehingga beberapa aspek hukum belum berkekuatan hukum tetap.
- Penilaian moral dapat dilakukan berdasarkan fakta yang telah terverifikasi tanpa harus menunggu putusan pengadilan.
---

## 8. CHECKPOINT INTEGRITAS & ANTI-KORUPSI

Integritas merupakan salah satu nilai utama dalam profesi teknologi informasi dan rekayasa perangkat lunak. Dalam sistem yang bersifat *safety-critical* seperti Boeing 737 MAX, setiap keputusan teknis harus mengutamakan keselamatan pengguna. Kasus Boeing 737 MAX menunjukkan bahwa lemahnya integritas organisasi dapat berdampak pada hilangnya kepercayaan publik dan meningkatnya risiko terhadap keselamatan penerbangan.

### 8.1 Penyalahgunaan Kepercayaan

Masyarakat, maskapai penerbangan, dan regulator memberikan kepercayaan kepada Boeing sebagai produsen pesawat yang mampu memenuhi standar keselamatan internasional. Namun, hasil investigasi menunjukkan bahwa sistem **Maneuvering Characteristics Augmentation System (MCAS)** masih memiliki kelemahan, seperti hanya mengandalkan satu sensor *Angle of Attack* (AoA) sebagai dasar pengambilan keputusan. Kondisi tersebut meningkatkan risiko kegagalan apabila sensor mengalami kesalahan pembacaan dan menunjukkan bahwa kepercayaan yang diberikan kepada perusahaan tidak sepenuhnya diimbangi dengan penerapan prinsip keselamatan yang optimal.

### 8.2 Penyembunyian Informasi

Salah satu permasalahan utama dalam kasus ini adalah kurangnya transparansi mengenai sistem MCAS. Informasi mengenai fungsi, cara kerja, serta pengaruh MCAS terhadap kendali pesawat tidak dijelaskan secara lengkap kepada pilot maupun maskapai. Akibatnya, ketika MCAS aktif akibat kesalahan sensor, pilot mengalami kesulitan memahami penyebab kondisi tersebut dan mengambil tindakan yang tepat. Kurangnya transparansi ini menjadi salah satu faktor yang memperbesar risiko kecelakaan.

### 8.3 Konflik Kepentingan

Kasus Boeing 737 MAX menunjukkan adanya konflik kepentingan antara keselamatan penerbangan dan kepentingan bisnis perusahaan. Boeing berupaya mempercepat proses sertifikasi agar dapat segera bersaing dengan Airbus A320neo serta meminimalkan kebutuhan pelatihan tambahan bagi pilot. Tekanan bisnis tersebut diduga memengaruhi beberapa keputusan teknis dalam pengembangan MCAS sehingga aspek keselamatan tidak menjadi prioritas utama.

### 8.4 Budaya Integritas dan Whistleblowing

Budaya organisasi yang baik seharusnya mendorong setiap engineer maupun karyawan untuk melaporkan potensi bahaya tanpa rasa takut. Dalam hasil investigasi ditemukan adanya kekhawatiran dari beberapa pihak internal mengenai desain MCAS, namun masukan tersebut tidak ditindaklanjuti secara optimal. Oleh karena itu, perusahaan perlu memiliki sistem *whistleblowing* yang efektif dengan menjamin kerahasiaan pelapor, memberikan perlindungan terhadap tindakan balasan (*retaliation*), memastikan setiap laporan ditindaklanjuti secara objektif, serta melibatkan auditor independen apabila diperlukan.

### 8.5 Kaitan dengan Anti-Korupsi

Kasus Boeing 737 MAX tidak termasuk tindak pidana korupsi sebagaimana diatur dalam Undang-Undang Nomor 31 Tahun 1999 jo. Undang-Undang Nomor 20 Tahun 2001 tentang Pemberantasan Tindak Pidana Korupsi. Namun demikian, kasus ini menunjukkan pelanggaran terhadap prinsip integritas, transparansi, akuntabilitas, dan tanggung jawab profesional dalam tata kelola perusahaan (*corporate governance*). Oleh karena itu, kasus ini lebih tepat dipandang sebagai pelanggaran etika profesi dan integritas organisasi daripada tindak pidana korupsi.

### Kesimpulan

Kasus Boeing 737 MAX menunjukkan bahwa keberhasilan pengembangan sistem *safety-critical* tidak hanya bergantung pada kemampuan teknis, tetapi juga pada integritas organisasi. Transparansi, budaya keselamatan (*safety culture*), mekanisme *whistleblowing*, serta pengambilan keputusan yang mengutamakan keselamatan harus menjadi prioritas agar kejadian serupa tidak terulang.

---

## 9. MANAJEMEN RISIKO & OPSI 4T

Manajemen risiko merupakan proses untuk mengidentifikasi, menganalisis, mengevaluasi, dan mengendalikan risiko yang dapat memengaruhi pencapaian tujuan organisasi. Pada kasus Boeing 737 MAX, kegagalan sistem MCAS menunjukkan bahwa proses manajemen risiko belum diterapkan secara optimal. Risiko yang telah diidentifikasi seharusnya dimitigasi sejak tahap perancangan agar tidak berkembang menjadi kecelakaan fatal.

### 9.1 Identifikasi Risiko

Beberapa risiko utama yang ditemukan pada sistem MCAS adalah:

- Ketergantungan pada satu sensor *Angle of Attack* (AoA).
- Kesalahan pembacaan sensor yang memicu aktivasi MCAS secara otomatis.
- Kurangnya informasi dan pelatihan kepada pilot mengenai MCAS.
- Potensi hilangnya kendali pesawat.
- Risiko hukum, kerugian finansial, dan menurunnya kepercayaan publik.

### 9.2 Analisis Risiko Menggunakan Strategi 4T

| Risiko | Dampak | Strategi 4T | Mitigasi |
|--------|--------|-------------|----------|
| Sensor AoA memberikan data yang salah | Sangat Tinggi | **Treat (Tangani)** | Menambahkan redundansi sensor, melakukan validasi silang, dan memperbarui perangkat lunak MCAS. |
| Pilot belum memahami cara kerja MCAS | Tinggi | **Treat (Tangani)** | Memberikan pelatihan simulator, memperbarui manual penerbangan, dan menjelaskan fungsi MCAS secara menyeluruh. |
| Gugatan hukum dan kerugian finansial | Tinggi | **Transfer (Alihkan)** | Menggunakan asuransi, menyediakan dana kompensasi, dan bekerja sama dengan regulator. |
| Gangguan teknis yang tidak berdampak langsung pada keselamatan | Rendah | **Tolerate (Terima)** | Melakukan inspeksi, pemeliharaan, dan pemantauan sistem secara berkala. |
| Desain MCAS yang hanya menggunakan satu sensor (*single point of failure*) | Sangat Tinggi | **Terminate (Hilangkan)** | Mengganti desain dengan sistem yang memiliki redundansi sensor dan mekanisme *fail-safe*. |

### 9.3 Analisis

Berdasarkan hasil investigasi, penyebab utama kecelakaan Boeing 737 MAX tidak hanya berasal dari kesalahan sensor, tetapi juga karena lemahnya proses manajemen risiko. Sistem MCAS dirancang dengan ketergantungan pada satu sensor tanpa mekanisme redundansi, sementara pilot tidak memperoleh informasi dan pelatihan yang memadai. Kondisi tersebut menyebabkan risiko yang sebenarnya telah ada tidak dapat dikendalikan secara efektif.

Apabila prinsip manajemen risiko diterapkan sejak tahap perancangan, Boeing dapat mengurangi risiko melalui penggunaan lebih dari satu sensor, penerapan mekanisme *fail-safe*, pengujian sistem secara menyeluruh, serta peningkatan pelatihan bagi pilot. Selain itu, perusahaan perlu membangun budaya keselamatan (*safety culture*) agar setiap potensi risiko dapat segera dilaporkan dan ditindaklanjuti tanpa dipengaruhi kepentingan bisnis.

### Kesimpulan

Kasus Boeing 737 MAX menunjukkan bahwa penerapan manajemen risiko yang baik sangat penting dalam pengembangan sistem *safety-critical*. Strategi 4T membantu organisasi menentukan langkah mitigasi yang sesuai sehingga risiko dapat dikurangi dan keselamatan pengguna tetap menjadi prioritas utama.

---

## 10. RANCANGAN DAMPAK & KONTROL PREVENTIF
Kasus Boeing 737 MAX menunjukkan bahwa pengembangan perangkat lunak pada sistem safety-critical harus mengutamakan keselamatan publik di atas kepentingan bisnis. Oleh karena itu, diperlukan berbagai langkah preventif yang melibatkan aspek teknis, organisasi, serta regulasi agar kejadian serupa tidak terulang di masa mendatang.

Dari aspek teknis, sistem Maneuvering Characteristics Augmentation System (MCAS) sebaiknya menggunakan lebih dari satu sensor Angle of Attack (AoA) sehingga data dapat divalidasi sebelum sistem mengambil keputusan. Selain itu, perangkat lunak harus memiliki mekanisme fail-safe, yaitu kemampuan sistem untuk berpindah ke kondisi aman ketika mendeteksi kesalahan sensor atau data yang tidak valid. Pengujian perangkat lunak juga harus dilakukan secara menyeluruh melalui proses testing, verification, dan validation, termasuk simulasi pada berbagai kondisi operasional maupun keadaan darurat.

Dari aspek organisasi, perusahaan harus menerapkan budaya keselamatan (safety culture) yang menempatkan keselamatan pengguna sebagai prioritas utama. Dokumentasi teknis mengenai seluruh fungsi sistem harus disampaikan secara lengkap kepada maskapai dan pilot, disertai pelatihan yang memadai mengenai penggunaan sistem serta prosedur penanganan kondisi darurat. Perusahaan juga perlu menyediakan mekanisme whistleblowing yang aman sehingga setiap potensi risiko dapat dilaporkan dan ditindaklanjuti tanpa adanya tekanan terhadap pelapor.

Dari aspek regulasi, otoritas penerbangan perlu memperkuat proses sertifikasi dan audit terhadap perangkat lunak yang digunakan pada sistem keselamatan penerbangan. Setiap perubahan perangkat lunak harus melalui evaluasi independen sebelum memperoleh izin operasional sehingga risiko kegagalan dapat diminimalkan.

Penerapan rekomendasi tersebut diharapkan dapat meningkatkan keselamatan penerbangan, mengurangi risiko kecelakaan akibat kegagalan perangkat lunak, meningkatkan kepercayaan masyarakat terhadap industri penerbangan, serta mendorong perusahaan untuk lebih mengutamakan transparansi, tanggung jawab profesional, dan etika dalam setiap proses pengembangan teknologi.

---

## 11. PELAJARAN UTAMA
Kasus Boeing 737 MAX memberikan pelajaran bahwa keberhasilan suatu teknologi tidak hanya ditentukan oleh kecanggihan perangkat lunak, tetapi juga oleh penerapan etika profesi, tanggung jawab moral, dan kepatuhan terhadap standar keselamatan. Dalam pengembangan sistem safety-critical, setiap keputusan teknis harus mempertimbangkan dampaknya terhadap keselamatan manusia karena kesalahan kecil sekalipun dapat menimbulkan konsekuensi yang sangat besar.

Pelajaran utama yang dapat diambil adalah bahwa keselamatan publik harus selalu menjadi prioritas utama dibandingkan kepentingan bisnis maupun persaingan industri. Pengembang perangkat lunak, engineer, manajemen perusahaan, dan regulator memiliki tanggung jawab bersama untuk memastikan bahwa setiap sistem telah dirancang, diuji, dan dioperasikan sesuai dengan standar keselamatan yang berlaku.

Kasus ini juga menegaskan pentingnya penerapan prinsip transparansi, integritas, dan profesionalisme. Informasi mengenai fungsi, keterbatasan, serta risiko suatu sistem harus disampaikan secara lengkap kepada seluruh pengguna agar mereka dapat mengambil keputusan yang tepat ketika menghadapi kondisi darurat. Selain itu, organisasi harus membangun budaya yang mendukung keterbukaan terhadap kritik dan laporan potensi bahaya melalui mekanisme whistleblowing, sehingga setiap permasalahan dapat diidentifikasi dan diperbaiki sebelum menimbulkan dampak yang lebih besar.

Sebagai mahasiswa Teknologi Informasi, kasus Boeing 737 MAX menjadi pengingat bahwa keberhasilan suatu sistem tidak hanya diukur dari aspek teknis, tetapi juga dari kemampuan sistem tersebut dalam melindungi keselamatan manusia serta menjaga kepercayaan masyarakat. Oleh karena itu, setiap proses pengembangan perangkat lunak harus selalu mengedepankan kualitas, etika profesi, transparansi, dan tanggung jawab sosial agar teknologi yang dihasilkan memberikan manfaat yang sebesar-besarnya bagi masyarakat.

---

## DAFTAR PUSTAKA

[1] R. K. Nistanto and R. Wahyudi, “KNKT Terbitkan Laporan Lion Air JT610, Ungkap Penyebab Kecelakaan,” Kompas.com, Oct. 25, 2019. [Online]. Available: https://tekno.kompas.com/read/2019/10/25/15420657/knkt-terbitkan-laporan-lion-air-jt610-ungkap-penyebab-kecelakaan?page=all

[2] Federal Aviation Administration (FAA), “FAA Updates on Boeing 737 MAX,” Nov. 18, 2020. [Online]. Available: https://www.faa.gov/newsroom/faa-updates-boeing-737-max-0

[3] G. S. Widagdo, S. C. K. Datu, and H. Robbani, “Analisis kasus kecelakaan Lion Air JT610: Tinjauan pidana dan tanggung jawab korporasi dalam keselamatan penerbangan,” Decisio Law Journal, vol. 1, no. 1, pp. 34–39, 2024. [Online]. Available: https://www.researchgate.net/publication/384609060

[4] J. Bentham, An Introduction to the Principles of Morals and Legislation. [Online]. Available: https://www.econlib.org/library/Bentham/bnthPML.html

[5] I. Kant, Groundwork of the Metaphysics of Morals. [Online]. Available: https://www.earlymoderntexts.com/assets/pdfs/kant1785.pdf

[6] Association for Computing Machinery, “ACM Code of Ethics and Professional Conduct,” 2018. [Online]. Available: https://www.acm.org/code-of-ethics

[7] Institute of Electrical and Electronics Engineers, “IEEE Code of Ethics,” 2020. [Online]. Available: https://www.ieee.org/about/corporate/governance/p7-8.html

[8] Republik Indonesia, “Undang-Undang Nomor 11 Tahun 2008 tentang Informasi dan Transaksi Elektronik; Undang-Undang Nomor 8 Tahun 1999 tentang Perlindungan Konsumen; Undang-Undang Nomor 1 Tahun 2009 tentang Penerbangan.” [Online]. Available: https://peraturan.bpk.go.id

[9] International Organization for Standardization, *ISO 31000:2018 Risk Management — Guidelines*. Geneva, Switzerland: ISO, 2018. [Online]. Available: https://www.iso.org/obp/ui/en/#iso:std:iso:31000:ed-2:v1:en

[10] Komite Nasional Keselamatan Transportasi, *Aircraft Accident Investigation Report: Preliminary Report – PT Lion Mentari Airlines Boeing 737-8 (MAX), PK-LQP, Tanjung Karawang, West Java, Republic of Indonesia, 29 October 2018*. Jakarta, Indonesia: KNKT, 2018. [Online]. Available: https://knkt.go.id/Repo/Files/Laporan/Penerbangan/2018/PK-LQP%20Preliminary%20Report.pdf

[11] National Transportation Safety Board, *Safety Recommendation Report: Assumptions Used in the Safety Assessment Process and the Effects of Multiple Alerts and Indications on Pilot Performance*. Washington, DC, USA: NTSB, Sep. 26, 2019. [Online]. Available: https://www.ntsb.gov/news/press-releases/Pages/NR20190926.aspx

[12] Badan Pembinaan Ideologi Pancasila (BPIP). Pendidikan Pancasila untuk Perguruan Tinggi. Jakarta: BPIP. Available: https://bpip.go.id

[13] Persatuan Insinyur Indonesia (PII). Kode Etik Insinyur Indonesia (KEI). Available: https://pii.or.id