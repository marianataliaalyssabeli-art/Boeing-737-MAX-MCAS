# BAB II
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