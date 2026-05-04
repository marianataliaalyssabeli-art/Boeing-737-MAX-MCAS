# TUGAS ETIKA PROFESI - KELOMPOK 09  
## Analisis Kasus: Boeing 737 MAX MCAS - Kegagalan Software pada Sistem Kritis

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

# I DESKRIPSI KASUS

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

# II FOKUS ANALISIS

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

Whistleblowing merupakan tindakan seseorang dalam organisasi untuk mengungkapkan informasi terkait pelanggaran, kesalahan, atau praktik yang berpotensi membahayakan kepada pihak internal maupun eksternal yang berwenang. Dalam konteks kasus Boeing 737 MAX, whistleblowing menjadi aspek penting karena adanya dugaan bahwa beberapa pihak internal telah mengetahui potensi risiko dari sistem MCAS sebelum terjadinya kecelakaan.
Dalam investigasi yang dilakukan setelah kecelakaan, ditemukan bahwa terdapat karyawan Boeing yang menyampaikan kekhawatiran terkait desain MCAS dan kurangnya transparansi informasi kepada pilot. Namun, informasi tersebut tidak ditindaklanjuti secara memadai oleh manajemen. Selain itu, terdapat indikasi bahwa tekanan untuk mempercepat sertifikasi dan produksi pesawat membuat suara-suara kritis dari internal organisasi tidak mendapatkan perhatian yang semestinya.

Peran whistleblower sangat penting dalam sistem safety-critical karena mereka dapat menjadi “garis pertahanan terakhir” dalam mencegah terjadinya kegagalan sistem. Dengan melaporkan potensi bahaya sejak dini, organisasi memiliki kesempatan untuk melakukan evaluasi dan perbaikan sebelum risiko tersebut berkembang menjadi kecelakaan.

Namun, dalam praktiknya, whistleblowing sering menghadapi berbagai hambatan, seperti:
- Takut terhadap tekanan atau sanksi dari perusahaan
- Budaya organisasi yang tidak terbuka terhadap kritik
- Kurangnya perlindungan bagi pelapor (whistleblower)
- Adanya konflik kepentingan antara keselamatan dan target bisnis

Dalam kasus Boeing, kurang optimalnya mekanisme whistleblowing dan tidak adanya tindak lanjut yang serius terhadap laporan internal menunjukkan lemahnya budaya keselamatan (safety culture) dalam organisasi. Hal ini berkontribusi pada tidak terdeteksinya risiko secara lebih awal.

Oleh karena itu, penting bagi perusahaan, khususnya yang bergerak di bidang teknologi dan transportasi, untuk:
- Menyediakan saluran whistleblowing yang aman dan anonim
- Memberikan perlindungan hukum bagi pelapor
- Menindaklanjuti setiap laporan secara objektif dan transparan
- Membangun budaya organisasi yang mengutamakan keselamatan
Dengan adanya sistem whistleblowing yang efektif, potensi kegagalan sistem seperti pada kasus Boeing 737 MAX dapat di minimalkan, sehingga keselamatan pengguna dapat lebih terjamin.

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

---

# III ANALISIS ETIKA, MORAL, dan ETIKA PROFESI

Berdasarkan fokus permasalahan yang telah dibahas pada BAB II, seperti adanya kompromi antara engineering dan kepentingan bisnis, lemahnya mekanisme whistleblowing, serta kurangnya tanggung jawab dalam pengembangan sistem safety-critical, maka diperlukan analisis lebih lanjut dari sudut pandang etika, moral, dan etika profesi untuk menilai apakah tindakan tersebut dapat dibenarkan atau tidak.

Berdasarkan fokus permasalahan yang telah dibahas pada BAB II, seperti adanya kompromi antara engineering dan kepentingan bisnis, lemahnya mekanisme whistleblowing, serta kurangnya tanggung jawab dalam pengembangan sistem safety-critical, maka diperlukan analisis lebih lanjut dari sudut pandang etika, moral, dan etika profesi untuk menilai apakah tindakan tersebut dapat dibenarkan atau tidak.

Analisis ini bertujuan untuk membedakan secara jelas antara moral (nilai pribadi), etika umum (prinsip sosial), dan etika profesi (standar formal dalam bidang pekerjaan), serta mengevaluasi bagaimana ketiganya gagal diterapkan dalam kasus sistem MCAS (Maneuvering Characteristics Augmentation System).

**1. Analisis Etika**

Etika umum digunakan untuk menilai apakah suatu tindakan benar atau salah berdasarkan prinsip rasional.

a. Utilitarianisme (Konsekuensialisme)
Utilitarianisme merupakan teori etika yang dikemukakan oleh Jeremy Bentham dan dikembangkan oleh John Stuart Mill, yang menyatakan bahwa suatu tindakan dianggap benar apabila menghasilkan manfaat terbesar bagi sebanyak mungkin orang.

Dalam kasus Boeing 737 MAX, sistem MCAS dirancang untuk meningkatkan keselamatan penerbangan secara umum. Namun, dalam implementasinya, sistem tersebut justru menyebabkan kecelakaan yang menewaskan 346 orang.

Dengan demikian, apabila dilihat dari perspektif utilitarianisme, dampak negatif yang ditimbulkan jauh lebih besar dibandingkan manfaatnya. Oleh karena itu, tindakan tersebut dapat dinilai tidak etis.

b. Deontologi (Etika Kewajiban)
Deontologi merupakan teori etika yang dikemukakan oleh Immanuel Kant, yang menyatakan bahwa suatu tindakan dinilai benar apabila sesuai dengan kewajiban moral dan prinsip universal, tanpa bergantung pada hasil akhir.

Dalam konteks ini, kewajiban profesional dalam pengembangan sistem teknologi meliputi kejujuran, transparansi, serta tanggung jawab dalam menjaga keselamatan publik. Namun, dalam kasus ini, informasi mengenai sistem MCAS tidak disampaikan secara jelas kepada pilot.

Hal tersebut menunjukkan adanya pelanggaran terhadap kewajiban moral, sehingga tindakan ini tidak dapat dibenarkan secara deontologis.

c. Virtue Ethics (Etika Kebajikan)
Virtue ethics merupakan pendekatan etika yang berasal dari pemikiran Aristoteles, yang menilai tindakan berdasarkan karakter dan kebajikan individu, seperti tanggung jawab, integritas, dan kehati-hatian.

Dalam kasus ini, keputusan yang diambil menunjukkan kurangnya kehati-hatian serta tanggung jawab profesional dalam merancang sistem yang aman.

Dengan demikian, tindakan tersebut tidak mencerminkan kebajikan seorang profesional dan dinilai tidak etis menurut pendekatan virtue ethics.

**2. Analisis Moral**

Moral merupakan seperangkat nilai tentang benar dan salah yang berasal dari hati nurani, norma sosial, dan budaya. Moral bersifat internal dan menjadi dasar dalam pengambilan keputusan individu.

Dalam kasus Boeing 737 MAX, terdapat beberapa tindakan yang secara moral dapat dipertanyakan:

a. Tidak Mengungkap Risiko Secara Transparan
Risiko yang terdapat pada sistem MCAS tidak dikomunikasikan secara terbuka kepada pilot, serta tidak dijelaskan secara memadai dalam manual. Hal ini melanggar prinsip kejujuran dan menunjukkan kurangnya tanggung jawab terhadap keselamatan pengguna.

b. Mengabaikan Potensi Bahaya yang Sudah Diketahui
Terdapat indikasi bahwa potensi risiko telah diketahui secara internal, namun tidak ditindaklanjuti dengan perbaikan yang memadai. Tindakan ini termasuk dalam bentuk kelalaian (negligence) dan bertentangan dengan nilai tanggung jawab serta kehati-hatian.

c. Mengutamakan Profit dibanding Keselamatan
Keputusan bisnis yang memengaruhi desain sistem menunjukkan bahwa kepentingan ekonomi lebih diutamakan dibandingkan keselamatan manusia. Dalam perspektif moral, hal ini tidak dapat dibenarkan karena kehidupan manusia memiliki nilai yang lebih tinggi dibandingkan keuntungan.

**3. Analisis Etika Profesi**

Etika profesi merupakan standar perilaku yang harus dipatuhi oleh seorang profesional dalam menjalankan pekerjaannya, khususnya dalam bidang teknologi informasi dan rekayasa perangkat lunak. Standar ini mengacu pada prinsip-prinsip yang ditetapkan oleh organisasi profesional seperti ACM (Association for Computing Machinery) dan IEEE (Institute of Electrical and Electronics Engineers).

Dalam sistem yang bersifat safety-critical, seorang profesional memiliki kewajiban untuk:

Mengutamakan keselamatan publik
Mengembangkan sistem yang andal dan aman
Menjaga transparansi informasi
Bertanggung jawab atas hasil dari sistem yang dikembangkan

Namun, dalam kasus Boeing 737 MAX, terdapat beberapa pelanggaran terhadap etika profesi, yaitu:

a. Kegagalan dalam Menjamin Keselamatan
Sistem MCAS tidak dirancang dengan redundansi sensor yang memadai, sehingga meningkatkan risiko kegagalan sistem.

b. Kurangnya Transparansi
Informasi mengenai cara kerja dan risiko sistem tidak disampaikan secara jelas kepada pilot.

c. Kelalaian Profesional (Professional Negligence)
Risiko yang sebenarnya dapat diprediksi tidak ditangani dengan baik, sehingga menunjukkan adanya kelalaian dalam memenuhi standar profesional.


Berdasarkan analisis etika, moral, dan etika profesi, dapat disimpulkan bahwa kegagalan dalam kasus Boeing 737 MAX tidak hanya disebabkan oleh kesalahan teknis, tetapi juga oleh pelanggaran terhadap prinsip etika, nilai moral, dan tanggung jawab profesional.


---

# IV ANALISIS HUKUM & REGULASI
**Analisis Hukum (Perspektif Indonesia: UU ITE, HKI, dan Regulasi Terkait)**

Analisis hukum bertujuan untuk melihat bagaimana kasus kegagalan sistem seperti Boeing 737 MAX (MCAS) dapat ditinjau berdasarkan peraturan perundang-undangan di Indonesia. Meskipun kasus terjadi di luar negeri, prinsip-prinsip hukumnya tetap relevan sebagai pembelajaran dalam pengembangan teknologi di Indonesia, khususnya pada sistem safety-critical.

**1. Tinjauan Berdasarkan UU ITE (Undang-Undang Informasi dan Transaksi Elektronik)**

Undang-Undang Nomor 11 Tahun 2008 tentang Informasi dan Transaksi Elektronik sebagaimana telah diubah dengan UU No. 19 Tahun 2016 (UU ITE) mengatur tanggung jawab dalam penggunaan dan pengelolaan sistem elektronik.

a. Pasal relevan:
- Pasal 15 ayat (1):
Penyelenggara sistem elektronik wajib menyelenggarakan sistem secara andal, aman, dan bertanggung jawab.
- Pasal 15 ayat (2):
Penyelenggara bertanggung jawab terhadap beroperasinya sistem elektronik sebagaimana mestinya.

b. Analisis terhadap kasus:
Sistem MCAS dapat dikategorikan sebagai sistem elektronik.
- Kegagalan akibat:
- Tidak adanya redundansi
- Kurangnya validasi data
- Minimnya transparansi
menunjukkan bahwa sistem tidak memenuhi prinsip keandalan dan keamanan.

c. Implikasi hukum di Indonesia
Jika kasus serupa terjadi di Indonesia:
- Perusahaan dapat dianggap melanggar kewajiban hukum
- Berpotensi terkena:
    - Sanksi administratif
    - Gugatan perdata (ganti rugi)
    - Bahkan pidana jika terbukti ada kelalaian serius

---

**2. Tinjauan Berdasarkan Perlindungan Konsumen**

Mengacu pada UU No. 8 Tahun 1999 tentang Perlindungan Konsumen:

a. Hak konsumen:
- Mendapatkan keamanan dan keselamatan
- Mendapatkan informasi yang benar dan jelas

b. Kewajiban pelaku usaha:
- Memberikan informasi yang jujur
- Menjamin kualitas dan keamanan produk

c. Analisis dalam kasus MCAS:
- Pilot dan maskapai adalah “konsumen” dari sistem
- Informasi penting tentang MCAS:
    - Tidak dijelaskan secara transparan
    - Tidak dimasukkan secara memadai dalam pelatihan

d. Kesimpulan hukum:

Tindakan tersebut dapat dikategorikan sebagai:
- Cacat informasi (misleading information)
- Produk tidak aman (defective product)

Di Indonesia, hal ini dapat berujung pada:
- Gugatan ganti rugi
- Penarikan produk (recall)
- Sanksi terhadap perusahaan

---

**3. Tinjauan Berdasarkan Hukum Pidana (Kelalaian / Negligence)**

Dalam KUHP (Kitab Undang-Undang Hukum Pidana), terdapat konsep kelalaian (culpa): "Pasal 359 KUHP: Barang siapa karena kelalaiannya menyebabkan orang lain meninggal dunia dapat dipidana".

a. Analisis terkait dengan kasus:

Risiko sudah dapat diprediksi, namun tidak dicegah dan tidak ditindaklanjuti. Maka, dapat dikategorikan sebagai kelalaian berat (gross negligence)

b. Dalam konteks Indonesia:

Developer, engineer, atau manajemen bisa:
- Dimintai pertanggungjawaban pidana
- Terutama jika terbukti mengabaikan standar keselamatan

---

**4. Tinjauan Berdasarkan HKI (Hak Kekayaan Intelektual)**

Dalam konteks perangkat lunak:
- Software dilindungi oleh Hak Cipta
- Namun perlindungan HKI tidak menghapus tanggung jawab hukum

Perusahaan memiliki hak atas sistem (MCAS), namun tetap wajib memastikan sistem aman digunakan dan tidak boleh menyembunyikan informasi penting dengan alasan rahasia dagang

a. Analisis:

Jika informasi sistem disembunyikan dengan alasan proprietary system → dapat bertentangan dengan prinsip keselamatan publik

b. Kesimpulan:

HKI tidak boleh dijadikan alasan untuk:
- Mengurangi transparansi
- Menghindari tanggung jawab

---

**5. Tinjauan Regulasi Transportasi dan Keselamatan**

Di Indonesia, keselamatan penerbangan diatur oleh:
- UU No. 1 Tahun 2009 tentang Penerbangan
- Regulasi dari Direktorat Jenderal Perhubungan Udara

a. Prinsip utama:
- Keselamatan adalah prioritas tertinggi
- Semua sistem harus melalui:
   - Sertifikasi
   - Pengujian
   - Evaluasi risiko

b. Analisis:

Dalam kasus MCAS, sistem tidak diuji secara memadai dalam kondisi ekstrem dan informasi tidak lengkap kepada pengguna. 
Jika hal ini terjadi di Indonesia:
- Sertifikasi bisa:
   - Dicabut
   - Dibatalkan
- Perusahaan dapat dikenai sanksi hukum

---

**6. Analisis Konteks Sosial Indonesia**

Dalam praktik penerapan hukum dan teknologi, sering ditemukan adanya tantangan dalam hal kepatuhan terhadap regulasi (regulatory compliance), baik pada individu maupun organisasi. Tantangan ini tidak selalu berkaitan dengan niat melanggar, tetapi bisa disebabkan oleh berbagai faktor seperti:
- Kurangnya pemahaman terhadap aturan yang berlaku
- Lemahnya pengawasan dan penegakan hukum
- Tekanan efisiensi biaya dan waktu dalam pengembangan sistem
- Budaya organisasi yang belum sepenuhnya mengutamakan keselamatan

Dalam konteks pengembangan sistem teknologi, khususnya yang bersifat safety-critical, kepatuhan terhadap standar dan regulasi merupakan hal yang sangat penting. Setiap penyimpangan, sekecil apa pun, dapat berdampak besar terhadap keselamatan pengguna.

a. Relevansi dengan kasus MCAS:
- Adanya tekanan bisnis untuk mempercepat produksi
- Pengambilan keputusan yang mengurangi standar teknis (misalnya tidak adanya redundansi sensor)
- Kurangnya transparansi terhadap pengguna sistem

Hal-hal tersebut menunjukkan adanya kompromi terhadap standar keselamatan dan regulasi, yang seharusnya menjadi prioritas utama.

b. Dalam perspektif hukum:
- Kepatuhan terhadap regulasi bersifat wajib (mandatory), bukan opsional
- Pelanggaran terhadap standar keselamatan dapat menimbulkan:
   - Tanggung jawab hukum
   - Kerugian besar, baik secara material maupun korban jiwa

Kesimpulan:

Kepatuhan terhadap regulasi dan standar keselamatan merupakan fondasi utama dalam pengembangan teknologi. Oleh karena itu, baik individu maupun organisasi harus memastikan bahwa setiap proses pengembangan sistem dilakukan secara bertanggung jawab, transparan, dan sesuai dengan ketentuan hukum yang berlaku, tanpa adanya kompromi yang dapat membahayakan keselamatan.

---

**7. Kesimpulan Analisis Hukum**

Berdasarkan perspektif hukum Indonesia, kasus seperti Boeing 737 MAX berpotensi melanggar beberapa aspek hukum, yaitu:
- UU ITE → kegagalan sistem tidak andal dan tidak aman
- UU Perlindungan Konsumen → informasi tidak transparan dan produk tidak aman
- KUHP → kelalaian yang menyebabkan kematian
- HKI → tidak boleh dijadikan alasan menutup informasi penting
- Regulasi penerbangan → pelanggaran standar keselamatan

Kesimpulan utama:

Dalam konteks Indonesia, pengembangan sistem teknologi, terutama yang bersifat kritis harus mematuhi hukum secara ketat, karena:
- Keselamatan manusia memiliki nilai tertinggi
- Budaya “mengakali aturan” tidak dapat dibenarkan secara hukum
- Tanggung jawab tidak hanya bersifat teknis, tetapi juga hukum dan moral

Berdasarkan analisis hukum tersebut, dapat disimpulkan bahwa kegagalan sistem seperti pada kasus Boeing 737 MAX tidak hanya berdampak secara teknis, tetapi juga memiliki konsekuensi hukum yang serius. Hal ini menegaskan bahwa pengembangan sistem teknologi, khususnya yang bersifat safety-critical, harus memenuhi prinsip keandalan, keamanan, transparansi, serta kepatuhan terhadap regulasi yang berlaku.

--- 

# V KESIMPULAN

Secara keseluruhan, kasus Boeing 737 MAX merupakan contoh nyata kegagalan yang melibatkan aspek teknis, etika, organisasi, dan hukum dalam pengembangan sistem safety-critical. Kegagalan sistem MCAS (Maneuvering Characteristics Augmentation System) menunjukkan lemahnya desain engineering, khususnya dalam hal redundansi, validasi data, dan transparansi kepada pengguna, yang diperparah oleh tekanan bisnis dan kompetisi industri. Selain itu, lemahnya mekanisme whistleblowing serta budaya organisasi yang tidak mengutamakan keselamatan turut memperbesar risiko yang sebenarnya dapat dicegah. Dari sisi etika, baik berdasarkan prinsip Association for Computing Machinery maupun Institute of Electrical and Electronics Engineers, terjadi pelanggaran serius terkait prioritas keselamatan publik, kejujuran, dan tanggung jawab profesional. Ditinjau dari aspek hukum, kasus ini juga menunjukkan potensi pelanggaran terhadap prinsip keamanan sistem dan perlindungan konsumen. Oleh karena itu, pelajaran utama dari kasus ini adalah bahwa dalam pengembangan teknologi, khususnya sistem kritis, keselamatan manusia harus menjadi prioritas yang tidak boleh dianggap biasa oleh kepentingan bisnis, serta diperlukan integrasi kuat antara keunggulan teknis, etika profesi, dan tata kelola organisasi yang bertanggung jawab.

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