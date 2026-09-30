# **PROJECT MILESTONE 1: SYSTEM PLANNING**

**Mata Kuliah**           **:** Analisis dan Perancangan Sistem Informasi

**Semester**                 **:** Ganjil 2026/2027

**Dosen Pengampu**   **:** Hafizah Hanim, M.Kom

**Identitas Kelompok**

| **Komponen** | **Isian** |
| --- | --- |
| Nama Proyek | Sistem Informasi Prediksi Food Waste untuk Perencanaan Porsi SPPG  |
| Organisasi | SMA 3 Padang |
| Ketua Kelompok | Mikail Samyth Habibillah - 2411523016 |
| Anggota | Luthfi Harisna Mufti - 2411523019<br>Ihsan Auliya Habiburrohim - 2411523022<br>Duha Alul Bariq - 2411523036 |
| Kelas | APSI D |
| Tanggal Pengumpulan | 30 September 2026 |
| Versi Dokumen | v1.0 |

# **DAFTAR ISI**

***PROJECT MILESTONE 1: SYSTEM PLANNING***.. 1

***PETUNJUK PENGERJAAN***.. 2

***DAFTAR ISI***. 3

***DAFTAR TABEL***. 5

***1.***   ***PROFIL DAN KONTEKS ORGANISASI***. 6

*1.1.*    *Profil Organisasi* 6

*1.2.*    *Konteks Sistem*.. 7

***2.***   ***IDENTIFIKASI MASALAH DAN PELUANG***.. 8

*2.1.*    *Identifikasi Masalah*. 8

*2.2.*    *Identifikasi Peluang*. 9

*2.3.*    *Analisis Akar Masalah*. 9

***3.***   ***STAKEHOLDER ANALYSIS***. 10

*3.1.*    *Identifikasi Stakeholder*. 10

*3.2.*    *Stakeholder Map*. 10

***4.***   ***ANALISIS PROSES BISNIS***. 11

*4.1.*    *Proses Bisnis Saat Ini* 11

*4.2.*    *Business Process Model* 11

*4.3.*    *Permasalahan pada Proses Bisnis*. 12

***5.***   ***SYSTEM REQUEST***. 13

*5.1.*    *Ringkasan System Request* 13

*5.2.*    *Business Need*. 13

*5.3.*    *Business Requirements*. 13

*5.4.*    *Business Value*. 14

*5.5.*    *Scope Awal* 14

*5.6.*    *Special Issues / Constraints*. 15

***6.***   ***FEASIBILITY ANALYSIS***. 16

*6.1.*    *Technical Feasibility*. 16

*6.2.*    *Economic Feasibility*. 17

*6.3.*    *Operational / Organizational Feasibility*. 18

*6.4.*    *Feasibility Summary*. 19

***7.***   ***EFFORT ESTIMATION***.. 20

*7.1.*    *Work Breakdown Structure*. 20

*7.2.*    *Effort Estimation*. 20

***8.***   ***RENCANA PENGEMBANGAN SISTEM***.. 21

*8.1.*    *Tahapan Pengembangan*. 21

*8.2.*    *Project Schedule*. 21

***KESIMPULAN DAN REKOMENDASI***. 22

*Kesimpulan System Planning*. 22z

*Rekomendasi* 22

***TRACEABILITY MATRIX***.. 23

***DAFTAR PUSTAKA***.. 24

***LAMPIRAN***.. 25

***QUALITY CHECK – SEBELUM PENGUMPULAN***.. 26

*A.*   *Content Check*. 26

*B.*   *Traceability Check*. 26

*C.*  *Diagram Check*. 26

*D.*  *Document Quality Check*. 27

***FORMAT PENAMAAN FILE***.. 28

***STRUKTUR ID ARTEFAK PROYEK***.. 29

***OUTPUT AKHIR MILESTONE 1***. 30

# **DAFTAR TABEL**

*Tabel 1. Konteks Sistem*.. 7

*Tabel 2. Identifikasi Masalah*. 8

*Tabel 3. Identifikasi Peluang*. 9

*Tabel 4. Identifikasi Stakeholder*. 10

*Tabel 5. Informasi Proses*. 11

*Tabel 6. Hubungan Masalah dengan Proses Bisnis*. 12

*Tabel 7. Ringkasan System Request* 13

*Tabel 8. Business Requirement* 13

*Tabel 9. Business Value*. 14

*Tabel 10. In Scope*. 14

*Tabel 11. Out of Scope*. 14

*Tabel 12. Batasan Masalah*. 15

*Tabel 13. Technical Feasibility*. 16

*Tabel 14. Estimasi Biaya*. 17

*Tabel 15. Estimasi Manfaat* 17

*Tabel 16. Organizational Feasibility*. 18

*Tabel 17. Feasibility Summary*. 19

*Tabel 18. Work Breakdown Structure*. 20

*Tabel 19. Effort Estimation*. 20

*Tabel 20. Project Schedule*. 21

*Tabel 21. Traceability Matrix*. 23

*Tabel 22. Struktur Artefak Proyek*. 29

# **1.**   **PROFIL DAN KONTEKS ORGANISASI**

## **1.1.Profil Organisasi**

Objek studi dalam proyek ini adalah SMA Negeri 3 Padang, sebuah sekolah menengah atas negeri di Kota Padang, Provinsi Sumatera Barat, yang berada di bawah naungan Dinas Pendidikan Provinsi Sumatera Barat.

Secara struktural, organisasi ini dipimpin oleh seorang Kepala Sekolah yang didampingi oleh Komite Sekolah. Dalam menjalankan kegiatan operasional dan akademisnya, Kepala Sekolah dibantu oleh empat Wakil Kepala Sekolah yang masing-masing membawahi bidang Kurikulum, Kesiswaan, Sarana & Prasarana, serta Hubungan Masyarakat (Humas), beserta Kepala Urusan Tata Usaha yang mengelola administrasi sekolah.

SMA Negeri 3 Padang merupakan salah satu institusi berskala besar yang menjadi penerima manfaat program Makan Bergizi Gratis (MBG). Penerima manfaat di sekolah ini mencakup 1.184 siswa yang terbagi ke dalam 32 kelas. Selain siswa, program ini juga menyasar 60 guru serta tenaga kependidikan lainnya, termasuk staf Tata Usaha, satuan pengamanan, petugas kebersihan, dan penjaga sekolah.

Pasokan makanan disediakan oleh mitra Satuan Pelayanan Program Gizi (SPPG), yaitu R3I, yang ditetapkan melalui nota kesepahaman antara pihak sekolah dan penyedia. Pengiriman makanan dilakukan pada siang hari menjelang waktu makan siang, yang disesuaikan dengan permintaan sekolah agar kantin tetap dapat beroperasi secara normal pada jam istirahat pertama.

Fokus pengamatan dalam proyek ini adalah pada unit pelaksana MBG tingkat sekolah, yang dikoordinasikan oleh seorang *Person in Charge* (PIC) dan dibantu oleh empat orang petugas pelaksana (yang berasal dari unsur satuan pengamanan, kebersihan, dan penjaga sekolah). Mengingat pelaksanaannya melibatkan aktivitas siswa dan guru, unit ini berkoordinasi secara erat dengan jajaran pimpinan sekolah. Adapun proses bisnis utama yang relevan dengan analisis proyek ini meliputi alur penerimaan ompreng makanan dari pihak SPPG (R3I), uji cicip sebelum pembagian, pendistribusian ke ruang-ruang kelas, pengembalian ompreng kosong, serta pelaksanaan evaluasi menu mingguan bersama pihak penyedia.

## **1.2. Konteks Sistem**

Tabel 1. Konteks Sistem

| **Elemen** | **Deskripsi** |
| --- | --- |
| Nama sistem sementara | MBG Smart Food Waste Prediction System  |
| Unit/bagian terkait | Unit pelaksana MBG tingkat sekolah (PIC MBG dan petugas pelaksana)  |
| Proses utama | Penerimaan ompreng, uji cicip, distribusi makanan ke kelas, pengembalian ompreng, dan evaluasi menu mingguan bersama SPPG  |
| Pengguna utama | PIC MBG sekolah dan petugas pelaksana  |
| Permasalahan utama (asumsi) | Evaluasi penyajian dan penanganan permintaan khusus dilakukan tanpa pencatatan, sehingga bergantung pada ingatan dan inisiatif individu |
| Tujuan pengembangan | Menyediakan sistem pencatatan yang terstruktur atas penyajian harian, sisa makanan, dan permintaan khusus sebagai data dasar yang valid untuk evaluasi menu mingguan dengan pihak SPPG.    |

# **2.**   **IDENTIFIKASI MASALAH DAN PELUANG**

## **2.1. Identifikasi Masalah**

Tabel 2. Identifikasi Masalah

| **ID Masalah** | **Permasalahan** | **Penyebab** | **Dampak** | **Bukti/Sumber** |
| --- | --- | --- | --- | --- |
| M-01 | Evaluasi menu mingguan bersama SPPG dilakukan tanpa data pendukung | Belum ada instrumen pencatatan penerimaan menu dan sisa makanan | Masukan kepada SPPG bersifat kualitatif dan bergantung pada ingatan; efektivitas perbaikan tidak dapat diukur | Wawancara PIC MBG |
| M-02 | Data alergi dan pantangan siswa hanya dikumpulkan satu kali di awal program | Pengumpulan dilakukan lewat formulir daring tanpa mekanisme pembaruan dan verifikasi berkala | Data berpotensi tidak mutakhir; sekolah tidak dapat memastikan seluruh permintaan khusus terpenuhi tiap hari | Wawancara PIC MBG |
| M-03 | Kegagalan pemenuhan permintaan khusus baru diketahui setelah makanan dibagikan | Tidak ada verifikasi kesesuaian porsi khusus saat penerimaan ompreng Siswa dengan alergi tidak menerima porsi yang sesuai | penggantian baru dilakukan pada hari berikutnya | Wawancara PIC MBG |
| M-04 | Jumlah dan jenis sisa makanan tidak dicatat | Penanganan sisa diserahkan pada kebijakan masing-masing sekolah tanpa kewajiban pencatatan | Pola penolakan komponen menu tertentu tidak terdokumentasi sebagai dasar perbaikan  | Wawancara PIC MBG |
| M-05 | Penanganan porsi berlebih dilakukan secara situasional tanpa prosedur baku | Koordinasi petugas kepada PIC dilakukan lisan atau lewat pesan singkat; jumlah dihitung berdasarkan perkiraan | Keputusan penyaluran tertunda; tidak ada bukti penyaluran yang terdokumentasi | Wawancara PIC MBG |

## **2.2. Identifikasi Peluang**

Tabel 3. Identifikasi Peluang

| **ID Peluang** | **Peluang** | **Kondisi Saat Ini** | **Kondisi yang Diharapkan** | **Nilai bagi Organisasi** |
| --- | --- | --- | --- | --- |
| O-01 | Penguatan evaluasi menu mingguan dengan data  | Evaluasi berbasis kesan lisan dari guru dan petugas  | Evaluasi didukung catatan penerimaan menu dan sisa per hari  | Masukan kepada SPPG lebih objektif dan dapat ditelusuri  |
| O-02 | Pemanfaatan mekanisme permintaan menu yang sudah berjalan | Siswa menyampaikan permintaan menu secara lisan melalui guru | Permintaan tercatat dan dapat dilihat riwayat pemenuhannya | Partisipasi penerima manfaat terdokumentasi |
| O-03 | Pengelolaan data permintaan khusus secara berkelanjutan Data alergi statis dari pengisian awal | Data alergi statis dari pengisian awal | Data dapat diperbarui dan diverifikasi saat penerimaan ompreng | Menurunkan risiko kesehatan bagi siswa dengan alergi |
| O-04 | Dokumentasi penyaluran porsi berlebih | Penyaluran dilakukan tanpa catatan | Tujuan, jumlah, dan waktu penyaluran tercatat | Akuntabilitas penanganan porsi berlebih meningkat |

## **2.3. Analisis Akar Masalah**

Analisis akar masalah dilakukan terhadap M-01 karena masalah ini mendasari keempat masalah lainnya. Ketiadaan pencatatan menyebabkan evaluasi menu, verifikasi permintaan khusus, dan penanganan porsi berlebih sama-sama berjalan tanpa dasar data. Teknik yang digunakan adalah 5 Why, dilengkapi pemetaan penyebab berdasarkan kategori.

***Masalah utama: M-01***

#### ***Root Cause Analysis***

**Masalah:** Evaluasi menu mingguan bersama SPPG dilakukan tanpa data pendukung.

**Analisis 5 Why:**

Why 1. Mengapa evaluasi dilakukan tanpa data? Karena tidak tersedia catatan mengenai penerimaan menu dan sisa makanan harian.

Why 2. Mengapa catatan tersebut tidak tersedia? Karena belum ada instrumen dan mekanisme pencatatan di tingkat sekolah. Pengecekan yang dilakukan petugas hanya mencatat kelengkapan pengembalian ompreng per kelas, bukan isinya.

Why 3. Mengapa tidak ada mekanisme pencatatan? Karena SOP yang berlaku menyerahkan penanganan sisa makanan kepada kebijakan masing-masing sekolah tanpa mewajibkan pencatatan.

Why 4. Mengapa sekolah tidak berinisiatif mencatat sendiri? Karena volume sisa dinilai kecil sehingga pencatatan dianggap belum mendesak, dan setiap kejadian dapat diselesaikan secara langsung melalui komunikasi lisan.

Why 5. Mengapa hal ini tetap menjadi masalah meskipun volume sisa kecil? Karena tanpa catatan, pola penerimaan menu tidak dapat diidentifikasi dan efektivitas perbaikan tidak dapat diukur. Kualitas evaluasi sepenuhnya bergantung pada ingatan serta kepedulian individu yang menjabat, sehingga tidak dapat dipertahankan ketika terjadi pergantian personel.

**Penyebab utama:**

| **Kategori** | **Penyebab** |
| --- | --- |
| Prosedur | SOP tidak mewajibkan pencatatan; penanganan sisa makanan diserahkan pada kebijakan masing-masing sekolah |
| Data | Tidak tersedia data historis penerimaan menu dan sisa makanan; data permintaan khusus hanya dikumpulkan sekali di awal program |
| Sarana | Belum tersedia instrumen pencatatan; koordinasi mengandalkan komunikasi lisan dan pesan singkat |
| Pelaksana | Kualitas evaluasi bergantung pada inisiatif individu; petugas berfokus pada tugas fisik penanganan ompreng |
| Kondisi | Volume sisa yang kecil membuat kebutuhan pencatatan tidak terasa mendesak |

**Akar masalah:**

Belum adanya mekanisme pencatatan baku atas penyajian dan sisa makanan di tingkat sekolah, sehingga pengetahuan mengenai pelaksanaan MBG tersimpan sebagai pengalaman individu dan tidak terdokumentasi sebagai informasi organisasi.

**Dampak terhadap organisasi:**

Pertama, evaluasi menu mingguan bersama SPPG tidak dapat menunjukkan bukti kuantitatif, sehingga masukan yang disampaikan bersifat kualitatif dan sulit ditindaklanjuti secara terukur.

Kedua, efektivitas perbaikan menu tidak dapat diukur karena tidak tersedia data pembanding antar periode.

Ketiga, praktik pengelolaan yang sudah berjalan baik berisiko hilang ketika terjadi pergantian personel pengelola, karena tidak terdokumentasi dalam bentuk yang dapat diwariskan.

# **3.**   **STAKEHOLDER ANALYSIS**

## **3.1. Identifikasi Stakeholder**

Tabel 4. Identifikasi Stakeholder

| **ID** | **Stakeholder** | **Peran** | **Kepentingan terhadap Sistem** | **Pengaruh** |
| --- | --- | --- | --- | --- |
| ST-01  | PIC MBG Sekolah | Mengoordinasi pelaksanaan MBG, berkomunikasi dengan SPPG, melakukan uji cicip, memutuskan penanganan porsi berlebih | Membutuhkan data untuk evaluasi mingguan dan penyampaian masukan kepada SPPG | Tinggi |
| ST-02  | Petugas Pelaksana MBG | Menerima dan menurunkan ompreng, mengelompokkan per kelas, mengecek pengembalian, melaporkan kondisi lapangan kepada PIC | Pengguna langsung pencatatan harian | Sedang |
| ST-03  | Kepala Sekolah | Penanggung jawab kebijakan sekolah, termasuk kerja sama dengan SPPG | Membutuhkan informasi pelaksanaan sebagai dasar kebijakan | Tinggi |
| ST-04  | Perwakilan Kelas (Piket) | Mengambil dan mengembalikan ompreng kelas | Terdampak bila ada penambahan tugas pencatatan | Rendah |
| ST-05  | Siswa | Penerima manfaat, menyampaikan permintaan menu dan keluhan | Berkepentingan atas pemenuhan permintaan khusus dan kesesuaian menu | Rendah |
| ST-06  | Guru | Mendampingi siswa saat makan, menyampaikan masukan pada evaluasi mingguan | Sumber masukan evaluasi menu | Sedang |
| ST-07 | SPPG Mitra | Menyediakan, mengirim, dan menjemput ompreng; menerima masukan evaluasi mingguan | Menerima keluaran evaluasi sebagai dasar perbaikan menu | Tinggi |

## **3.2. Stakeholder Map**

**Gambar 1. Stakeholder Map**

# **4.**   **ANALISIS PROSES BISNIS**

## **4.1. Proses Bisnis Saat Ini**

Tabel 5. Informasi Proses

| **Elemen** | **Deskripsi** |
| --- | --- |
| ID Proses | BP-01 |
| Nama Proses | Penyajian dan Pengembalian Ompreng MBG Harian  |
| Tujuan | Memastikan seluruh penerima manfaat menerima porsi MBG dan ompreng dikembalikan lengkap kepada SPPG  |
| Trigger | Kedatangan kendaraan SPPG membawa ompreng pada siang hari  |
| Input | Ompreng berisi porsi MBG, daftar jumlah siswa per kelas, daftar guru dan tenaga kependidikan, data permintaan khusus siswa  |
| Output | Porsi terdistribusi kepada penerima manfaat, ompreng kosong terkumpul, catatan kelas yang belum mengembalikan ompreng  |
| Aktor | SPPG, PIC MBG, petugas pelaksana (4 orang), perwakilan kelas, siswa, guru  |
| Frekuensi | Setiap hari sekolah aktif; tidak dilaksanakan saat siswa libur atau pembelajaran jarak jauh  |
| Permasalahan | Porsi yang tidak terambil dan sisa makanan tidak tercatat; kesesuaian porsi permintaan khusus tidak diverifikasi saat penerimaan  |

Kendaraan SPPG tiba di sekolah pada siang hari menjelang waktu makan siang. Waktu pengiriman ini ditetapkan atas permintaan sekolah agar kantin tetap dapat melayani siswa pada jam istirahat pertama.

Empat petugas pelaksana menurunkan ompreng dari kendaraan dan mengelompokkannya berdasarkan kelas. Setiap ompreng telah diberi keterangan kelas tujuan, dan jumlah per kelas disesuaikan dengan jumlah siswa, yaitu 36 ompreng untuk kelas berisi 36 siswa.

Bersamaan dengan proses penurunan, PIC melakukan uji cicip terhadap dua ompreng percobaan yang disediakan di luar jumlah penerima manfaat. Pembagian baru dilakukan setelah lima hingga sepuluh menit tanpa keluhan. Satu ompreng percobaan diuji sebelum pembagian, dan satu lagi setelah seluruh porsi dibagikan.

Setelah siswa melaksanakan salat zuhur berjamaah, empat perwakilan setiap kelas mengambil ompreng di titik pengumpulan. Pengambilan oleh empat orang disesuaikan dengan kapasitas angkut: satu renteng berisi lima ompreng, dan setiap orang membawa dua renteng.

Ompreng dibawa ke kelas dan dibagikan kepada masing-masing siswa. Setelah selesai makan, ompreng diikat kembali dan dikembalikan oleh perwakilan kelas ke titik pengumpulan semula. Petugas melakukan pengecekan berdasarkan daftar kelas untuk memastikan seluruh kelas telah mengembalikan ompreng.

Kendaraan SPPG menjemput ompreng pada pukul 14.00 hingga 15.00.

Apabila terdapat kelas yang tidak mengambil porsinya, petugas melaporkan kondisi tersebut kepada PIC melalui komunikasi lisan atau pesan singkat. PIC kemudian memperkirakan jumlah porsi dan menentukan penanganannya. Penyaluran dilakukan menggunakan kendaraan SPPG atau kendaraan sekolah.

## **4.2. Business Process Model**

## **4.3.  Permasalahan pada Proses Bisnis**

Tabel 6. Hubungan Masalah dengan Proses Bisnis

| **ID Masalah** | **Proses Terkait** | **Aktivitas yang Bermasalah** | **Dampak** |
| --- | --- | --- | --- |
| M-01 | BP-01 | Pengecekan pengembalian ompreng hanya mencatat kelengkapan, tidak mencatat isi | Evaluasi mingguan tidak memiliki data penerimaan menu |
| M-02 | BP-01 | Tidak ada aktivitas verifikasi data permintaan khusus saat penerimaan ompreng | Data alergi tidak terverifikasi kemutakhirannya |
| M-03 | BP-01 | Pembagian ompreng di kelas tidak disertai pengecekan kesesuaian porsi khusus | Ketidaksesuaian baru diketahui setelah siswa menerima porsi |
| M-04 | BP-01 | Tidak ada aktivitas pencatatan jumlah dan jenis sisa makanan | Pola penolakan komponen menu tidak terdokumentasi |
| M-05 | BP-01 | Pelaporan porsi tidak terambil dilakukan lisan tanpa pencatatan jumlah pasti | Keputusan penyaluran berdasarkan perkiraan; tidak ada bukti penyaluran |

# **5.**   **SYSTEM REQUEST**

## **5.1. Ringkasan System Request**

Tabel 7. Ringkasan System Request

| **Komponen** | **Deskripsi** |
| --- | --- |
| **Project Name** | Sistem Informasi Pencatatan dan Evaluasi Penyajian MBG  |
| **Project Sponsor** | Kepala SMA Negeri 3 Padang  |
| **Business Need** | Sekolah membutuhkan pencatatan terstruktur atas penyajian dan sisa makanan MBG sebagai dasar evaluasi menu bersama SPPG  |
| **Business Requirements** | Pencatatan penyajian harian, pencatatan porsi tidak terambil dan sisa, pengelolaan data permintaan khusus, dokumentasi penyaluran porsi berlebih, dan penyajian rekapitulasi untuk evaluasi mingguan  |
| **Business Value** | Evaluasi menu berbasis data, penurunan risiko kesalahan pemenuhan permintaan khusus, dan akuntabilitas penanganan porsi berlebih  |
| **Special Issues / Constraints** | Belum tersedia data historis; pencatatan menambah beban kerja petugas; ketergantungan pada kerja sama SPPG  |

## **5.2. Business Need**

Sekolah mengalami keterbatasan dalam melakukan evaluasi pelaksanaan MBG karena tidak tersedianya catatan mengenai penyajian, penerimaan menu, dan sisa makanan. Hal ini menyebabkan evaluasi mingguan bersama SPPG hanya berdasarkan kesan dan ingatan, sehingga efektivitas perbaikan menu tidak dapat diukur dan praktik baik yang sudah berjalan berisiko hilang saat terjadi pergantian personel.

Oleh karena itu, diperlukan sistem informasi yang mencatat penyajian dan sisa makanan harian serta menyajikan rekapitulasinya, untuk membantu sekolah menyampaikan masukan yang objektif kepada SPPG dan menjaga kualitas layanan secara berkelanjutan.

## **5.3. Business Requirements**

Tabel 8. Business Requirement

| **ID** | **Business Requirement** | **Sumber** |
| --- | --- | --- |
| BR-01 | Sistem harus dapat mencatat data penyajian harian meliputi tanggal, menu, jumlah porsi diterima, dan jumlah porsi terdistribusi per kelas | M-01 / ST-01 |
| BR-02 | Sistem harus dapat mencatat jumlah porsi tidak terambil beserta kelas asal dan komponen makanan yang tersisa | M-04 / ST-02 |
| BR-03 | Sistem harus dapat mengelola data permintaan khusus siswa yang dapat diperbarui dan diverifikasi | M-02 / ST-05 |
| BR-04 | Sistem harus dapat mencatat verifikasi pemenuhan porsi permintaan khusus pada saat penerimaan ompreng | M-03 / ST-01 |
| BR-05 | Sistem harus dapat mendokumentasikan penyaluran porsi berlebih meliputi jumlah, tujuan, dan waktu penyaluran | M-05 / ST-01 |
| BR-06 | Sistem harus dapat menyajikan rekapitulasi mingguan sebagai bahan evaluasi bersama SPPG | O-01 / ST-01 |
| BR-07 | Sistem harus dapat mencatat permintaan menu dari penerima manfaat beserta riwayat pemenuhannya | O-02 / ST-05 |
| BR-08 | Sistem harus dapat memperkirakan tingkat risiko penolakan menu berdasarkan riwayat penerimaan menu sebelumnya | O-01 / ST-01 |

## **5.4. Business Value**

Tabel 9. Business Value

| **Business Requirement** | **Expected Value** | **Indikator Keberhasilan** |
| --- | --- | --- |
| BR-01 | Tersedianya catatan penyajian yang dapat ditelusuri | Seluruh hari penyajian tercatat dalam satu periode evaluasi |
| BR-02 | Pola penerimaan menu dapat diidentifikasi | Tersedia data porsi tidak terambil per menu |
| BR-03 | Data permintaan khusus selalu mutakhir | Data diperbarui minimal setiap awal semester |
| BR-04 | Menurunnya kesalahan pemenuhan porsi khusus | Tidak terdapat laporan porsi khusus tidak terpenuhi |
| BR-05 | Penyaluran porsi berlebih dapat dipertanggungjawabkan | Setiap penyaluran memiliki catatan tujuan dan jumlah |
| BR-06 | Evaluasi mingguan berbasis data | Rekapitulasi tersedia sebelum pelaksanaan evaluasi |
| BR-07 | Partisipasi penerima manfaat terdokumentasi | Permintaan menu tercatat beserta status pemenuhan |
| BR-08 | Perencanaan menu mempertimbangkan risiko penolakan | Estimasi risiko tersedia sebelum menu ditetapkan |

## **5.5. Scope Awal**

Tabel 10. In Scope

| ***ID*** | ***Scope*** |
| --- | --- |
| *SC-IN-01* | Pencatatan penyajian harian MBG di tingkat sekolah |
| *SC-IN-02* | Pencatatan porsi tidak terambil dan komponen makanan tersisa |
| *SC-IN-03* | Pengelolaan data permintaan khusus siswa |
| *SC-IN-04* | Dokumentasi penyaluran porsi berlebih |
| *SC-IN-05* | Rekapitulasi mingguan untuk evaluasi bersama SPPG |
| *SC-IN-06* | Estimasi risiko penolakan menu berdasarkan riwayat |
| *SC-IN-07* | Pengelolaan pengguna dan hak akses |

Tabel 11. Out of Scope

| **ID** | **Scope** |
| --- | --- |
| SC-OUT-01 | Proses pengadaan bahan dan produksi makanan di SPPG |
| SC-OUT-02 | Penyusunan menu dan perhitungan kandungan gizi |
| SC-OUT-03 | Penentuan rute dan penjadwalan pengiriman |
| SC-OUT-04 | Pencatatan data kesehatan individual siswa di luar informasi permintaan khusus |
| SC-OUT-05 | Pengelolaan honor petugas dan administrasi keuangan program |
| SC-OUT-06 | Implementasi dan deployment sistem |

## **5.6. Special Issues / Constraints**

Tabel 12. Batasan Masalah

| **ID** | **Constraint / Issue** | **Dampak** | **Mitigasi Awal** |
| --- | --- | --- | --- |
| C-01 | Belum tersedia data historis penyajian dan sisa makanan | Komponen estimasi risiko penolakan menu tidak dapat langsung difungsikan | Rancangan menempatkan pencatatan sebagai prasyarat; estimasi berjalan setelah data mencukupi |
| C-02 | Penambahan tugas pencatatan harian bagi petugas pelaksana | Potensi resistensi dan pencatatan tidak konsisten | Rancangan input dibuat sederhana dan terbatas pada data yang sudah diamati petugas |
| C-03 | Keluaran sistem bergantung pada kesediaan SPPG menindaklanjuti | Manfaat sistem tidak optimal bila tidak ditindaklanjuti | Keluaran diarahkan pada forum evaluasi mingguan yang sudah berjalan |
| C-04 | Data mencakup informasi permintaan khusus siswa | Risiko terhadap privasi | Sistem tidak menyimpan data kesehatan; hanya mencatat jenis pantangan dan kelas |
| C-05 | Keterbatasan waktu pengerjaan satu semester | Cakupan harus dibatasi | Proyek berhenti pada tahap rancangan |
| C-06 | Akses ke SPPG terbatas | Perspektif penyedia tidak tergali langsung | Analisis difokuskan pada proses di tingkat sekolah |

**6.**   **FEASIBILITY ANALYSIS**

Bagian ini menyajikan analisis kelayakan pengembangan sistem dari tiga sudut pandang, yaitu kelayakan teknis, ekonomis, dan operasional, sebagai dasar pengambilan keputusan pada tahap perencanaan sistem.

## **6.1. Technical Feasibility**

Analisis kelayakan teknis mengevaluasi ketersediaan perangkat keras (*hardware*), perangkat lunak (*software*), infrastruktur jaringan, serta kesiapan keterampilan teknis para petugas pelaksana di SMA Negeri 3 Padang.

Tabel 13. Technical Feasibility

| Aspek | Kondisi | Kebutuhan | Gap | Tingkat Kelayakan |
| --- | --- | --- | --- | --- |
| Teknologi | Komunikasi dan pendataan MBG saat ini mengandalkan aplikasi WhatsApp serta Google Form statis yang diisi satu kali di awal program. Belum ada aplikasi pencatatan terstruktur | Aplikasi web (*responsive web app*) berbasis input cepat untuk mengelola data penyajian, sisa makanan, dan kebutuhan porsi khusus.  | Diperlukan pengembangan antarmuka web baru yang ringan dan ramah pengguna (user-friendly). | Tinggi |
| Infrastruktur | Sekolah memiliki laptop dan PC administrasi di ruang Tata Usaha dan ruang PIC MBG. Petugas lapangan (Satpam dan Kebersihan) memiliki smartphone pribadi. Jaringan Wi-Fi dan seluler tersedia di area sekolah. | Perangkat seluler atau laptop yang mampu mengakses formulir pencatatan harian secara stabil di lokasi pengumpulan ompreng (Aula / depan ruang guru).Perangkat seluler atau laptop yang mampu mengakses formulir pencatatan harian secara stabil di lokasi pengumpulan ompreng (Aula / depan ruang guru). | Sinyal internet di area luar ruangan terkadang fluktuatif. Gap ini dimitigasi dengan merancang formulir web hemat data (lightweight). | Sedang |
| SDM | Pelaksana lapangan terdiri dari 1 orang PIC MBG dan 4 orang petugas operasional (Pak Doris, Pak Dedi, Pak Ezi, dan Bu Eli). Seluruh petugas sudah terbiasa menggunakan smartphone. | Keterampilan menginput data sisa makanan dan memverifikasi porsi khusus secara digital. | Petugas membutuhkan sosialisasi dan pelatihan singkat (15–30 menit) mengenai alur pengisian formulir digital. | Tinggi |
| Fitur Prediksi (Estimasi Risiko Penolakan Menu)  | Belum tersedia data historis penerimaan menu dan sisa makanan  | Data historis penyajian minimal beberapa minggu/bulan untuk membangun model estimasi yang valid  | Fitur estimasi risiko (BR-08) tidak dapat langsung berfungsi di awal peluncuran karena bergantung pada data yang baru mulai dikumpulkan sistem ini sendiri  | Sedang  |

**Kesimpulan Technical Feasibility:**

Pengembangan sistem dinyatakan layak dari segi teknis. Perangkat pendukung seperti PC administrasi sekolah dan smartphone milik 4 orang petugas lapangan sudah memadai. Kendala fluktuasi sinyal di titik penerimaan ompreng dapat diatasi dengan merancang antarmuka aplikasi web yang ringan dan hemat konsumsi data.Namun demikian, komponen prediksi/estimasi risiko penolakan menu (BR-08) sangat bergantung pada ketersediaan data historis dan baru dapat berfungsi secara optimal setelah periode pengumpulan data awal berjalan, sejalan dengan batasan C-01.

## **6.2. Economic Feasibility**

Analisis kelayakan ekonomis menilai estimasi biaya yang dibutuhkan dalam pengembangan serta potensi manfaat yang akan diperoleh sekolah dan pihak SPPG R3I.

**Estimasi Biaya**

Tabel 14. Estimasi Biaya

| Komponen | Estimasi Biaya |
| --- | --- |
| Pengembangan | Rp 0 |
| Infrastruktur | Rp 0 |
| Software | Rp 0 |
| Maintenance | Rp 150.000 |
| Lainnya | Rp 0 |
| **Total** | **Rp 150.000** |

Mengingat proyek ini berhenti pada tahap rancangan (C-05) dan implementasi berada di luar cakupan (SC-OUT-06), estimasi biaya berikut merupakan proyeksi untuk tahap implementasi pascarancangan, bukan biaya Milestone ini. Komponen Pengembangan, Infrastruktur, dan Software diproyeksikan Rp0 dengan asumsi implementasi kelak dilakukan swakelola menggunakan perangkat sekolah yang sudah ada dan hosting gratis. Biaya Maintenance Rp150.000/tahun untuk sewa domain tahunan

**Estimasi Manfaat**

Tabel 15. Estimasi Manfaat

| Manfaat | Estimasi Nilai |
| --- | --- |
| Penghematan waktu | Rp 625.000  |
| Pengurangan biaya | Rp1.920.000  |

Penghematan waktu dihitung dari estimasi 15 menit/hari waktu rekap manual yang dihilangkan, dikalikan nilai waktu kerja PIC (±Rp12.500/jam, dari gaji Rp100.000/8 jam) selama 200 hari sekolah efektif/tahun. Pengurangan biaya dihitung dari estimasi penurunan kehilangan ompreng 2 unit/bulan setelah pencatatan digital diterapkan, dikalikan denda Rp80.000/ompreng yang berlaku saat ini.

**Metode analisis yang digunakan:**

*Cost-Benefit Analysis* dan estimasi *Payback Period* sederhana. Mengingat investasi awal pengembangan sistem adalah Rp0 dan biaya pemeliharaan tahunan sangat kecil (Rp150.000/tahun), manfaat berupa penghematan waktu dan akuntabilitas data membuat sistem ini mencapai masa balik modal (Payback Period) sekitar 21 hari, berdasarkan total manfaat Rp2.545.000/tahun.

**Kesimpulan Economic Feasibility:**

Proyek pengembangan ini layak secara ekonomis karena tidak membutuhkan penambahan honor petugas baru dan memberikan manfaat efisiensi bagi pengelolaan MBG di sekolah. Analisis ini bersifat proyeksi kelayakan ekonomis apabila sistem diimplementasikan pada tahap selanjutnya, mengingat cakupan Milestone 1 berhenti pada tahap rancangan (C-05).

## **6.3. Operational / Organizational Feasibility**

Analisis kelayakan operasional menilai tingkat kesiapan organisasi, penerimaan pengguna di lapangan, dampak perubahan proses bisnis, serta mitigasi terhadap potensi kendala kerja.

Tabel 16. Organizational Feasibility

| Aspek | Kondisi Saat Ini | Risiko | Mitigasi |
| --- | --- | --- | --- |
| Pengguna | 4 orang petugas lapangan fokus pada aktivitas fisik (menurunkan, mengelompokkan, dan mengecek pengembalian ompreng). | Petugas merasa terbebani (user fatigue) atau lupa menginput data jika formulir terlalu rumit. | Menyelaraskan antarmuka aplikasi dengan bentuk checklist sederhana (durasi pengisian maksimal 3–5 menit/hari). |
| Organisasi | Evaluasi menu dilakukan via telepon/WhatsApp antara PIC dan SPPG R3I, namun belum didukung data kuantitatif yang rapi. | Masukan mengenai kualitas menu bersifat subjektif sehingga perbaikan dari SPPG lambat terealisasi. | Menyediakan rekapitulasi data harian/mingguan yang valid sebagai dasar evaluasi bersama pihak SPPG R3I. |
| Proses kerja | Penyaluran porsi berlebih (1–3 kelas) dilakukan secara situasional tanpa pencatatan resmi. | Potensi kendala transparansi dan pertanggungjawaban pengelolaan porsi berlebih. | Menambahkan field pencatatan porsi berlebih pada formulir harian dengan logika ambang batas otomatis: &lt;30 porsi → tujuan 'Asrama/ADM', 30–50 porsi → tujuan 'Panti Asuhan'. Petugas cukup memilih dari dropdown, tanpa input manual tambahan, sehingga tidak menambah durasi pengisian formulir (tetap 3–5 menit). |

**Kesimpulan Operational Feasibility:**

Secara operasional sistem layak untuk diterapkan di SMA Negeri 3 Padang. Pengadopsian aplikasi dapat berjalan selaras dengan prosedur harian sekolah, dengan catatan tampilan pencatatan harus dirancang seringkas mungkin agar tidak mengganggu tugas fisik para petugas di lapangan.

## **6.4. Feasibility Summary**

Tabel 17. Feasibility Summary

| Aspek | Hasil Analisis | Kesimpulan |
| --- | --- | --- |
| Technical | Perangkat komputer dan smartphone petugas sudah memadai. Fitur prediksi bergantung pada data historis yang baru terkumpul. | Layak dengan catatan |
| Economic | Tanpa biaya lisensi dan tidak menambah honor SDM baru. Memberikan efisiensi dan transparansi data. | Layak |
| Operational | Mudah diintegrasikan ke dalam alur kerja yang berjalan (BP-01). Didukung oleh PIC dan Kepala Sekolah. | Layak dengan catatan |

Kolom Technical dan Operational ditetapkan 'Layak dengan Catatan'. Pada aspek teknis, fitur prediksi risiko penolakan menu baru dapat berfungsi secara optimal setelah tersedia data historis yang memadai (lihat 6.1). Pada aspek operasional, keberhasilan implementasi bergantung pada kesederhanaan antarmuka pencatatan harian agar tidak menimbulkan beban tambahan bagi petugas lapangan (lihat 6.3). Estimasi manfaat ekonomis pada 6.2 juga masih bersifat proyeksi awal dan akan divalidasi lebih lanjut pada tahap User Acceptance Testing (UAT).

**Keputusan**

**[ ] Layak dikembangkan**

**[**✓ **] Layak dengan catatan**

**[ ] Tidak layak dikembangkan**

**Argumentasi**

Pengembangan MBG Smart Food Waste Prediction System di SMA Negeri 3 Padang dinyatakan Layak dengan Catatan. Proyek ini layak secara teknis dan ekonomis, dengan estimasi manfaat yang masih bersifat proyeksi awal karena memanfaatkan sarana yang sudah ada tanpa menambah beban biaya operasional sekolah. Catatan utama terletak pada dua aspek. Pertama, dari sisi teknis, fitur prediksi risiko penolakan menu memerlukan periode pengumpulan data historis terlebih dahulu sebelum dapat berfungsi secara akurat. Kedua, dari sisi operasional, tim pengembang wajib memastikan antarmuka pencatatan harian dibuat sangat cepat dan mudah (durasi input maksimal 3–5 menit per hari) agar petugas lapangan tidak mengalami kelelahan mencatat (user fatigue) di tengah rutinitas fisik penanganan ompreng.

#

# **7.**   **EFFORT ESTIMATION**

## **7.1. Work Breakdown Structure**

Work Breakdown Structure (WBS) disusun untuk memecah pekerjaan proyek menjadi aktivitas yang lebih kecil, terukur, dan memiliki penanggung jawab yang jelas. Pekerjaan dibagi mengikuti tiga milestone mata kuliah APSI, yaitu System Planning, System Analysis, dan System Design. Implementasi dan deployment sistem tidak dimasukkan ke dalam WBS karena berada di luar cakupan proyek (SC-OUT-06). Estimasi dinyatakan dalam satuan jam-orang (*person-hour*), yaitu total jam kerja yang dibutuhkan satu orang untuk menyelesaikan suatu aktivitas.

Tabel 18. Work Breakdown Structure

| **WBS ID** | **Aktivitas** | **Deliverable** | **PIC** | **Estimasi** |
| --- | --- | --- | --- | --- |
| 1.0 | System Planning (Milestone 1) | Dokumen System Planning | Mikail | 48 jam |
| 1.1 | Discovery: wawancara daring dengan PIC MBG  | Daftar pertanyaan, transkrip/ringkasan wawancara   | Seluruh anggota | 8 jam |
| 1.2 | Penyusunan profil dan konteks organisasi | Profil organisasi, Tabel Konteks Sistem | Duha | 3 jam |
| 1.3 | Identifikasi masalah, peluang, dan akar masalah | Tabel M-xx, Tabel O-xx, analisis 5 Why | Mikail | 5 jam |
| 1.4 | Analisis stakeholder | Tabel ST-xx, Stakeholder Map | Luthfi | 3 jam |
| 1.5 | Pemodelan proses bisnis as-is | Uraian dan BPMN BP-01 | Ihsan | 6 jam |
| 1.6 | Penyusunan System Request | BR-xx, Business Value, Scope, Constraint | Mikail | 4 jam |
| 1.7 | Analisis kelayakan | Technical, Economic, dan Operational Feasibility | Luthfi | 5 jam |
| 1.8 | Estimasi effort dan rencana proyek | WBS, Effort Estimation, Project Schedule | Duha | 4 jam |
| 1.9 | Traceability matrix, kompilasi, dan quality check | Traceability Matrix, dokumen M1 (PDF) | Mikail | 4 jam |
| 1.10 | Revisi dan presentasi Milestone 1 | Dokumen revisi, slide presentasi M1 | Seluruh anggota | 6 jam |
| 2.0 | System Analysis (Milestone 2) | Dokumen System Analysis | Mikail | 64 jam |
| 2.1 | Validasi kebutuhan lanjutan dengan PIC dan petugas | Hasil wawancara lanjutan, kebutuhan tervalidasi | Ihsan, Duha | 6 jam |
| 2.2 | Spesifikasi kebutuhan fungsional dan non-fungsional (termasuk FR-AI dan NFR-AI) | Dokumen Requirement Specification | Luthfi | 10 jam |
| 2.3 | Pemodelan proses bisnis to-be | BPMN to-be | Ihsan | 6 jam |
| 2.4 | Pemodelan use case | Use Case Diagram dan skenario use case | Duha | 10 jam |
| 2.5 | Pemodelan activity diagram | Activity Diagram per use case utama | Ihsan | 8 jam |
| 2.6 | Analisis data dan kebutuhan komponen prediksi | Daftar variabel, sumber data, rencana metrik evaluasi | Mikail, Luthfi | 8 jam |
| 2.7 | Traceability BR → FR → UC, kompilasi, dan quality check | Traceability Matrix M2, dokumen M2 | Mikail | 4 jam |
| 2.8 | Revisi dan presentasi Milestone 2 | Dokumen revisi, slide presentasi M2 | Seluruh anggota | 12 jam |
| 3.0 | System Design (Milestone 3) | Dokumen System Design | Mikail | 112 jam |
| 3.1 | Perancangan arsitektur sistem dan posisi layanan prediksi | Diagram arsitektur sistem | Mikail | 10 jam |
| 3.2 | Perancangan class diagram | Class Diagram | Luthfi | 12 jam |
| 3.3 | Perancangan sequence diagram (termasuk alur prediksi) | Sequence Diagram | Duha | 16 jam |
| 3.4 | Perancangan basis data | ERD dan skema tabel | Luthfi | 14 jam |
| 3.5 | Perancangan model prediksi | Rancangan fitur, algoritma, dan skema evaluasi model | Mikail, Ihsan | 18 jam |
| 3.6 | Perancangan antarmuka pengguna | Wireframe/mockup formulir harian, rekapitulasi, dan hasil prediksi | Ihsan | 18 jam |
| 3.7 | Perancangan deployment | Deployment Diagram | Duha | 4 jam |
| 3.8 | Traceability, kompilasi, dan quality check | Traceability Matrix M3, dokumen M3 | Duha | 6 jam |
| 3.9 | Revisi dan presentasi Milestone 3 | Dokumen revisi, slide presentasi M3 | Seluruh anggota | 14 jam |
|   | Total |   |   | 224 jam |

| **Anggota** | **Planning** | **Analysis** | **Design** | **Total** |
| --- | --- | --- | --- | --- |
| Mikail Samyth Habibillah | 16,5 jam | 11 jam | 22,5 jam | 50 jam |
| Luthfi Harisna Mufti | 11,5 jam | 17 jam | 29,5 jam | 58 jam |
| Ihsan Auliya Habiburrohim | 9,5 jam | 20 jam | 30,5 jam | 60 jam |
| Duha Alul Bariq | 10,5 jam | 16 jam | 29,5 jam | 56 jam |
| **Total** | **48 jam** | **64 jam** | **112 jam** | **224 jam** |

## **7.2. Effort Estimation**

Jelaskan metode estimasi yang digunakan.

**Metode:** Simply Method

Simply Method dipilih karena proyek masih berada pada tahap System Planning. Pada tahap ini kebutuhan sistem baru teridentifikasi pada tingkat Business Requirement dan belum dirinci menjadi fungsi maupun use case. Metode Function Point belum dapat digunakan karena membutuhkan analisis fungsi yang cukup detail. Metode Use Case Point juga belum dapat digunakan karena Use Case Diagram baru akan disusun pada Milestone 2 (aktivitas 2.4). Simply Method memungkinkan estimasi awal yang cepat tanpa spesifikasi detail, dengan menghitung total effort proyek dari effort salah satu fase yang sudah diketahui berdasarkan distribusi persentase berikut.

| **Tahap** | **Persentase** |
| --- | --- |
| Planning | 15% |
| Analysis | 20% |
| Design | 35% |
| Implementation | 30% |

**Asumsi:**

1.  Effort fase Planning diketahui sebesar 48 jam-orang, berdasarkan rincian aktivitas System Planning pada WBS (Tabel 18, WBS 1.0) yang telah dijalankan kelompok.
2.  Tim terdiri atas 4 orang anggota kelompok. Setiap anggota mengalokasikan rata-rata 2 jam efektif per hari untuk proyek ini, di samping mata kuliah lain, sehingga kapasitas tim adalah 4 × 2 = 8 jam-orang per hari kerja.
3.  Satu minggu terdiri atas 5 hari kerja efektif.
4.  Fase Implementation dihitung sebagai proyeksi untuk kelengkapan metode. Fase ini tidak dikerjakan dalam proyek karena berada di luar cakupan (SC-OUT-06) dan proyek berhenti pada tahap rancangan (C-05).

**Perhitungan:**

Total effort proyek:

Total Effort = Effort Planning / 15%
 = 48 / 0,15
 = 320 jam-orang

Distribusi effort per fase:

  - Planning = 15% × 320 = 48 jam-orang
  - Analysis = 20% × 320 = 64 jam-orang
  - Design = 35% × 320 = 112 jam-orang
  - Implementation = 30% × 320 = 96 jam-orang

Durasi setiap fase dihitung dengan rumus Durasi = Effort / kapasitas tim (8 jam-orang per hari).

**Estimasi**

Tabel 19. Effort Estimation

| **Aktivitas** | **Effort** | **Durasi** | **Sumber Daya** |
| --- | --- | --- | --- |
| Planning | 48 jam | 6 hari | 4 orang anggota kelompok |
| Analysis | 64 jam | 8 hari | 4 orang anggota kelompok |
| Design | 112 jam | 14 hari | 4 orang anggota kelompok |
| Implementation *(proyeksi, di luar cakupan)* | 96 jam | 12 hari | 4 orang anggota kelompok |

**Total Effort:** 224 jam-orang untuk cakupan proyek (Planning, Analysis, dan Design), atau 320 jam-orang apabila sistem dilanjutkan hingga tahap implementasi.

Dengan kapasitas tim 8 jam-orang per hari, cakupan proyek membutuhkan 28 hari kerja efektif, atau sekitar 6 minggu. Estimasi ini realistis untuk diselesaikan dalam satu semester. Jika dikonversi ke satuan Person Month (1 PM = 8 jam × 22 hari = 176 jam), effort cakupan proyek setara dengan 224 / 176 ≈ 1,27 PM.

Perlu dicatat bahwa Simply Method memiliki akurasi yang rendah dan sangat bergantung pada asumsi distribusi persentase. Karena itu, estimasi ini diperlakukan sebagai estimasi awal. Estimasi akan diperbarui menggunakan metode Use Case Point pada Milestone 2, setelah Use Case Diagram tersedia.

# **8.**   **RENCANA PENGEMBANGAN SISTEM**

## **8.1. Tahapan Pengembangan**

Pengembangan sistem menggunakan pendekatan System Development Life Cycle (SDLC) model Waterfall dengan umpan balik (feedback). Setiap tahap dikerjakan secara berurutan, dan hasil satu tahap menjadi masukan bagi tahap berikutnya. Model ini dipilih karena tiga alasan. Pertama, struktur proyek mengikuti milestone mata kuliah yang berurutan, yaitu System Planning, System Analysis, dan System Design. Kedua, kebutuhan bisnis telah teridentifikasi dengan cukup jelas melalui wawancara dengan PIC MBG. Ketiga, setiap tahap menghasilkan dokumen yang harus dinilai sebelum tahap berikutnya dimulai. Umpan balik ditambahkan pada setiap tahap untuk mengakomodasi revisi berdasarkan masukan dosen, sehingga kesalahan dapat diperbaiki sebelum berlanjut ke tahap selanjutnya.

**Gambar 3. Tahapan Pengembangan Sistem**

Gambar 3 menunjukkan bahwa tahapan pengembangan terbagi menjadi dua bagian, yaitu tahapan yang termasuk dalam cakupan proyek APSI dan tahapan lanjutan yang bersifat proyeksi.

Tahapan dalam cakupan proyek:

1.  **Planning (Milestone 1)** bertujuan menentukan mengapa sistem perlu dikembangkan. Tahap ini menghasilkan identifikasi masalah dan akar masalah, analisis stakeholder, model proses bisnis as-is, System Request, analisis kelayakan, serta estimasi effort (WBS 1.0; 48 jam-orang).
2.  **Analysis (Milestone 2)** bertujuan menentukan apa yang harus dilakukan sistem. Business Requirement (BR-01 s.d. BR-08) diturunkan menjadi kebutuhan fungsional dan non-fungsional, termasuk kebutuhan komponen prediksi (FR-AI). Tahap ini juga memodelkan proses bisnis to-be, use case, dan activity diagram, serta mengidentifikasi data yang dibutuhkan model prediksi (WBS 2.0; 64 jam-orang).
3.  **Design (Milestone 3)** bertujuan menentukan bagaimana sistem dibangun. Tahap ini menghasilkan rancangan arsitektur, class diagram, sequence diagram, basis data, rancangan model prediksi, antarmuka pengguna, dan deployment diagram (WBS 3.0; 112 jam-orang).

**Tahapan lanjutan (proyeksi, di luar cakupan SC-OUT-06):**

1.  **Implementation** berupa pembangunan aplikasi berdasarkan dokumen rancangan. Tahap ini juga menandai dimulainya pengumpulan data historis penyajian dan sisa makanan sebagai prasyarat komponen prediksi (C-01).
2.  **Testing** berupa pengujian fungsional, evaluasi kinerja model prediksi, dan *User Acceptance Testing* (UAT) bersama PIC MBG untuk memvalidasi estimasi manfaat pada bagian 6.2.
3.  **Deployment** berupa instalasi sistem di lingkungan sekolah, pelatihan singkat bagi petugas pelaksana (15–30 menit, sesuai Tabel 13), dan pemeliharaan.

Ketiga tahapan lanjutan tersebut diproyeksikan membutuhkan 96 jam-orang (30% dari total effort pada bagian 7.2). Tahapan ini tidak dikerjakan dalam proyek, tetapi dicantumkan agar arah pengembangan sistem setelah tahap rancangan tetap jelas.

## **8.2. Project Schedule**

Jadwal proyek disusun berdasarkan hasil Effort Estimation pada bagian 7.2, dengan kapasitas tim 8 jam-orang per hari dan 5 hari kerja efektif per minggu. Kolom M1 sampai M8 menyatakan minggu kerja efektif ke-1 sampai ke-8. Total durasi sebesar 40 hari kerja (320 jam-orang ÷ 8 jam-orang per hari) tepat setara dengan 8 minggu.

Tabel 20. Project Schedule

| **Aktivitas** | **M1** | **M2** | **M3** | **M4** | **M5** | **M6** | **M7** | **M8** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Planning (hari ke-1–6) | ✓ | ✓ |   |   |   |   |   |   |
| Analysis (hari ke-7–14) |   | ✓ | ✓ |   |   |   |   |   |
| Design (hari ke-15–28) |   |   | ✓ | ✓ | ✓ | ✓ |   |   |
| Implementation, Testing & Deployment *(proyeksi)* (hari ke-29–40) |   |   |   |   |   | ✓ | ✓ | ✓ |

Titik penyelesaian setiap milestone ditunjukkan pada tabel berikut.

| **Milestone** | **Deliverable** | **Selesai pada** |
| --- | --- | --- |
| Milestone 1 | Dokumen System Planning | Akhir hari ke-6 (Minggu 2) |
| Milestone 2 | Dokumen System Analysis | Akhir hari ke-14 (Minggu 3) |
| Milestone 3 | Dokumen System Design | Akhir hari ke-28 (Minggu 6) |

Jadwal di atas menggunakan hari kerja efektif. Dalam pelaksanaannya, jarak antar milestone akan menyesuaikan dengan tenggat pengumpulan yang ditetapkan dosen, sehingga durasi kalender dapat lebih panjang daripada durasi efektif.

# **KESIMPULAN DAN REKOMENDASI**

## **Kesimpulan System Planning**

*Jawab pertanyaan berikut:*

*1.*     *Apa masalah utama organisasi?*

*2.*     *Mengapa masalah tersebut penting untuk diselesaikan?*

*3.*     *Siapa stakeholder utama?*

*4.*     *Bagaimana proses bisnis saat ini?*

*5.*     *Sistem seperti apa yang secara umum dibutuhkan?*

*6.*     *Apakah solusi layak dikembangkan?*

*7.*     *Apakah effort pengembangan realistis?*

**Kesimpulan:**

[…]

 Berdasarkan hasil System Planning yang dilakukan melalui wawancara daring dengan PIC MBG SMA Negeri 3 Padang, diperoleh kesimpulan sebagai berikut. .

Masalah utama yang dihadapi sekolah adalah evaluasi menu mingguan bersama SPPG R3I yang dilakukan tanpa data pendukung (M-01). Akar masalahnya adalah belum adanya mekanisme pencatatan baku atas penyajian dan sisa makanan di tingkat sekolah. Akibatnya, pengetahuan mengenai pelaksanaan MBG hanya tersimpan sebagai pengalaman individu dan tidak terdokumentasi sebagai informasi organisasi. Akar masalah ini juga mendasari empat masalah lain, yaitu:

  - data alergi dan pantangan yang hanya dikumpulkan sekali di awal program (M-02);
  - ketidaksesuaian porsi permintaan khusus yang baru diketahui setelah makanan dibagikan (M-03);
  - jumlah dan jenis sisa makanan yang tidak dicatat (M-04);
  - penanganan porsi berlebih yang dilakukan secara situasional tanpa prosedur baku (M-05).

Masalah ini penting untuk diselesaikan karena program MBG di sekolah melayani 1.184 siswa di 32 kelas, ditambah guru dan tenaga kependidikan, setiap hari sekolah aktif. Tanpa data, masukan sekolah kepada SPPG hanya bersifat kualitatif, efektivitas perbaikan menu tidak dapat diukur, dan pola penerimaan menu maupun sisa makanan tidak dapat dikenali. Kesalahan pemenuhan permintaan khusus juga berisiko terhadap kesehatan siswa yang memiliki alergi. Selain itu, praktik pengelolaan yang sudah berjalan baik berisiko hilang ketika terjadi pergantian personel.

Stakeholder utama sistem adalah PIC MBG Sekolah (ST-01) sebagai pengguna sekaligus pengambil keputusan operasional, serta SPPG Mitra R3I (ST-07) sebagai penerima keluaran evaluasi. Keduanya berada pada kuadran *Manage Closely*. Kepala Sekolah (ST-03) berperan sebagai project sponsor, sedangkan petugas pelaksana (ST-02) merupakan pengguna langsung pencatatan harian.

Proses bisnis yang dianalisis adalah Penyajian dan Pengembalian Ompreng MBG Harian (BP-01). Proses ini mencakup penerimaan ompreng dari SPPG, uji cicip, pengelompokan dan distribusi per kelas, pengembalian ompreng, serta penanganan porsi yang tidak terambil. Proses tersebut berjalan cukup tertib secara fisik. Namun, pengecekan yang dilakukan hanya mencatat kelengkapan pengembalian ompreng, bukan isinya, dan seluruh koordinasi dilakukan secara lisan atau melalui pesan singkat.

Secara umum, sekolah membutuhkan sistem informasi berbasis web yang ringan untuk:

  - mencatat penyajian harian, porsi tidak terambil, dan komponen makanan yang tersisa;
  - mengelola dan memverifikasi data permintaan khusus siswa;
  - mendokumentasikan penyaluran porsi berlebih;
  - menyajikan rekapitulasi mingguan sebagai bahan evaluasi bersama SPPG.

Data yang terkumpul kemudian dimanfaatkan untuk memperkirakan risiko penolakan menu, sehingga perencanaan menu dapat mempertimbangkan potensi sisa makanan. Kebutuhan tersebut dirumuskan dalam delapan Business Requirement (BR-01 s.d. BR-08).

Hasil analisis kelayakan menyatakan bahwa sistem **layak dikembangkan dengan catatan**:

  - Secara teknis, perangkat dan keterampilan pengguna sudah memadai, tetapi komponen prediksi baru dapat berfungsi optimal setelah data historis terkumpul (C-01).
  - Secara ekonomis, sistem tidak membutuhkan biaya lisensi maupun tambahan tenaga kerja. Biaya pemeliharaannya Rp150.000/tahun, sedangkan proyeksi manfaatnya Rp2.545.000/tahun.
  - Secara operasional, sistem dapat diintegrasikan ke dalam BP-01 dengan syarat antarmuka pencatatan dibuat sangat ringkas.

Effort pengembangan dinilai realistis. Berdasarkan Simply Method, cakupan proyek (Planning, Analysis, dan Design) membutuhkan 224 jam-orang, atau sekitar 1,27 Person Month. Dengan kapasitas tim 8 jam-orang per hari, effort tersebut setara dengan 28 hari kerja efektif, sekitar 6 minggu, sehingga dapat diselesaikan dalam satu semester oleh empat anggota kelompok.

Dengan demikian, hasil System Planning ini dinyatakan siap untuk dilanjutkan ke tahap System Analysis pada Milestone 2.

## **Rekomendasi**

*Berikan rekomendasi berdasarkan hasil System Planning.*

Berdasarkan hasil System Planning, kelompok memberikan rekomendasi sebagai berikut.

1.  **Melanjutkan proyek ke tahap System Analysis dengan validasi yang lebih luas.** Seluruh ID artefak (M-xx, ST-xx, BP-xx, BR-xx) dipertahankan sebagai dasar traceability. Validasi kebutuhan yang saat ini bersumber dari PIC MBG perlu diperluas kepada petugas pelaksana, Kepala Sekolah, dan, apabila memungkinkan, SPPG R3I (C-06).
2.  **Memulai pencatatan penyajian dan sisa makanan sedini mungkin.** Sekolah dapat menggunakan formulir terstruktur sederhana walaupun sistem belum dibangun. Komponen prediksi bergantung pada data historis (C-01), sehingga semakin awal data dikumpulkan, semakin cepat komponen tersebut dapat difungsikan.
3.  **Merancang pencatatan yang ringkas dan selaras dengan forum evaluasi yang sudah berjalan.** Formulir harian dibuat dalam bentuk *checklist* dan *dropdown* dengan waktu pengisian maksimal 3–5 menit (C-02). Format rekapitulasi mingguan juga perlu disepakati bersama SPPG R3I agar masukan sekolah dapat ditindaklanjuti (C-03).
4.  **Menggunakan data dan hasil prediksi secara bertanggung jawab.** Sistem hanya mencatat jenis pantangan dan kelas tanpa data kesehatan individual (C-04). Hasil prediksi diposisikan sebagai pendukung keputusan, sehingga keputusan akhir mengenai menu tetap berada pada PIC MBG dan SPPG.

# **TRACEABILITY MATRIX**

*Bagian ini* ***wajib diisi*** *dan menjadi dasar untuk Milestone 2.*

*Tujuannya memastikan setiap keputusan pada System Planning dapat ditelusuri.*

Traceability matrix disusun untuk memastikan setiap Business Requirement memiliki dasar yang jelas, baik dari masalah (M-xx) maupun peluang (O-xx) yang ditemukan pada tahap System Planning. Setiap requirement ditelusuri mulai dari sumbernya, stakeholder yang berkepentingan, proses bisnis tempat masalah terjadi, hingga nilai bisnis yang diharapkan. Seluruh masalah dan peluang berada pada satu proses bisnis, yaitu BP-01 (Penyajian dan Pengembalian Ompreng MBG Harian). Matriks ini akan menjadi dasar penurunan kebutuhan fungsional dan non-fungsional pada Milestone 2.

Tabel 21. Traceability Matrix

| **Masalah/Peluang** | **Stakeholder** | **Proses** | **Business Requirement** | **Business Value** |
| --- | --- | --- | --- | --- |
| M-01 | ST-01 | BP-01 | BR-01 | Tersedianya catatan penyajian yang dapat ditelusuri |
| M-04 | ST-02 | BP-01 | BR-02 | Pola penerimaan menu dapat diidentifikasi |
| M-02 | ST-05 | BP-01 | BR-03 | Data permintaan khusus selalu mutakhir |
| M-03 | ST-01 | BP-01 | BR-04 | Menurunnya kesalahan pemenuhan porsi khusus |
| M-05 | ST-01 | BP-01 | BR-05 | Penyaluran porsi berlebih dapat dipertanggungjawabkan |
| O-01 | ST-01 | BP-01 | BR-06 | Evaluasi mingguan berbasis data |
| O-02 | ST-05 | BP-01 | BR-07 | Partisipasi penerima manfaat terdokumentasi |
| O-01 | ST-01 | BP-01 | BR-08 | Perencanaan menu mempertimbangkan risiko penolakan |

Hasil penelusuran menunjukkan bahwa seluruh masalah (M-01 s.d. M-05) telah memiliki Business Requirement yang menanganinya. Tidak ada pula Business Requirement yang muncul tanpa dasar masalah atau peluang. BR-06 dan BR-08 bersumber dari peluang O-01, yang merupakan kelanjutan dari masalah M-01. Ketersediaan data pencatatan harian (BR-01 dan BR-02) memungkinkan evaluasi mingguan dilakukan berbasis data (BR-06) dan menjadi masukan bagi estimasi risiko penolakan menu (BR-08). Dengan demikian, hubungan **M-xx/O-xx → ST-xx → BP-01 → BR-xx** telah dapat ditelusuri secara logis.

**Traceability Rule**

*Setiap:*

***M-xx → ST-xx → BP-xx → BR-xx***

*harus memiliki hubungan yang logis.*

*Jika sebuah Business Requirement tidak memiliki sumber masalah/kebutuhan yang jelas, lakukan pemeriksaan kembali.*

# **DAFTAR PUSTAKA**

Albrecht, A. J. (1979). Measuring application development productivity. Dalam *Proceedings of the Joint SHARE/GUIDE/IBM Application Development Symposium* (hlm. 83–92). IBM.

Dennis, A., Wixom, B. H., & Roth, R. M. (2012). *Systems analysis and design* (5th ed.). John Wiley & Sons.

Dennis, A., Wixom, B. H., & Tegarden, D. (2015). *Systems analysis and design: An object-oriented approach with UML* (5th ed.). John Wiley & Sons.

Dumas, M., La Rosa, M., Mendling, J., & Reijers, H. A. (2018). *Fundamentals of business process management* (2nd ed.). Springer. https://doi.org/10.1007/978-3-662-56509-4

Karner, G. (1993). *Resource estimation for Objectory projects*. Objective Systems SF AB.

Object Management Group. (2013). *Business Process Model and Notation (BPMN) version 2.0.2* (OMG Document No. formal/13-12-09). https://www.omg.org/spec/BPMN/2.0.2/

Ohno, T. (1988). *Toyota production system: Beyond large-scale production*. Productivity Press.

Peraturan Presiden Republik Indonesia Nomor 83 Tahun 2024 tentang Badan Gizi Nasional. (2024). https://peraturan.bpk.go.id/Details/295857/perpres-no-83-tahun-2024

Peraturan Presiden Republik Indonesia Nomor 115 Tahun 2025 tentang Tata Kelola Penyelenggaraan Program Makan Bergizi Gratis. (2025). https://www.peraturan.go.id/files/perpres-no-115-tahun-2025.pdf

Project Management Institute. (2017). *A guide to the project management body of knowledge (PMBOK guide)* (6th ed.). Project Management Institute.

Sommerville, I. (2016). *Software engineering* (10th ed.). Pearson.

# **LAMPIRAN**

## **Lampiran A. Daftar Pertanyaan Wawancara**

Tabel A.1. Daftar Pertanyaan Wawancara dengan PIC MBG SMA Negeri 3 Padang

| **No** | **Kategori** | **Pertanyaan** | **Tujuan** |
| --- | --- | --- | --- |
| 1 | Pembuka | Peran Bapak/Ibu di sekolah ini apa ya? | Memastikan posisi dan kewenangan narasumber dalam pelaksanaan MBG, sebagai dasar identifikasi stakeholder (ST-01) |
| 2 | Alur proses | Coba ceritakan dari awal Bu/Pak: makanan datang jam berapa, diterima siapa, terus apa yang terjadi sampai siswa selesai makan? | Memperoleh gambaran utuh proses bisnis as-is dari awal sampai akhir sebagai bahan uraian dan BPMN BP-01 |
| 3 | Alur proses | Waktu makanan datang, ada yang dicek dulu? Ada form serah terima? | Mengetahui ada tidaknya aktivitas verifikasi dan pencatatan saat penerimaan ompreng |
| 4 | Alur proses | Jeda antara makanan datang sampai siswa makan berapa lama? Disimpan di mana? | Mengidentifikasi titik pengumpulan dan waktu tunggu dalam proses distribusi |
| 5 | Alur proses | Berapa lama waktu makan siswa? Siapa yang mengawasi? | Mengidentifikasi aktor yang terlibat saat siswa makan (siswa, guru, perwakilan kelas) |
| 6 | Alur proses | Setelah selesai, wadah dan sisa diapakan? Siapa yang menangani? | Memetakan aktivitas pengembalian ompreng dan penanganan sisa makanan beserta penanggung jawabnya |
| 7 | Alur proses | Kalau ada masalah — terlambat, jumlah kurang, makanan rusak — lapor ke siapa, lewat apa? | Mengetahui jalur pelaporan dan koordinasi dengan SPPG, termasuk media komunikasi yang digunakan |
| 8 | Sisa makanan | Biasanya ada makanan yang tidak habis? Kira-kira berapa banyak — berapa porsi atau berapa persen? | Mengukur skala sisa makanan untuk menilai urgensi masalah |
| 9 | Sisa makanan | Beda-beda tiap hari? Hari apa paling banyak? | Mengetahui adanya pola sisa makanan menurut waktu sebagai dasar kebutuhan rekapitulasi dan estimasi |
| 10 | Sisa makanan | Bagian mana paling sering tersisa — nasi, sayur, lauk, atau buah? | Mengidentifikasi komponen makanan yang perlu dicatat dalam pencatatan sisa (BR-02) |
| 11 | Sisa makanan | Menu apa yang paling sering tidak habis? Yang selalu habis apa? | Mengetahui hubungan jenis menu dengan tingkat penerimaan sebagai dasar estimasi risiko penolakan menu (BR-08) |
| 12 | Sisa makanan | Menurut Bapak/Ibu kenapa siswa tidak menghabiskan? (kejar: porsi kebanyakan? rasa? waktu kurang? sudah sarapan? sudah dingin?) | Menggali penyebab sisa makanan untuk analisis akar masalah |
| 13 | Sisa makanan | Apa dampaknya kalau terus tersisa? | Mengidentifikasi dampak masalah bagi sekolah dan penerima manfaat |
| 14 | Pencatatan | Ada pencatatan porsi yang diterima dan jumlah siswa yang makan tiap hari? Di mana? | Mengetahui kondisi pencatatan penyajian harian saat ini (M-01, BR-01) |
| 15 | Pencatatan | Jumlah yang tersisa pernah dicatat, walaupun cuma perkiraan? Kalau ada, sejak kapan, boleh saya lihat? | Memastikan ada tidaknya data historis sisa makanan (M-04, C-01) |
| 16 | Pencatatan | Data MBG disimpan dalam bentuk apa — buku tulis, Excel, foto di WA, atau aplikasi? | Mengetahui teknologi dan media yang sudah digunakan sebagai dasar technical feasibility |
| 17 | Pencatatan | Kalau nanti ada pencatatan sisa makanan harian, siapa yang paling mungkin mengerjakan? Berapa lama waktu yang wajar? | Menentukan calon pengguna pencatatan harian dan batas waktu pengisian yang dapat diterima (C-02, operational feasibility) |
| 18 | Orang dan keputusan | Kalau ada keputusan soal MBG di sekolah, siapa yang menentukan akhirnya? | Mengidentifikasi pengambil keputusan dan tingkat pengaruh stakeholder (ST-01, ST-03, ST-07) |
| 19 | Orang dan keputusan | Siapa yang paling berkepentingan tahu data sisa makanan ini? | Mengidentifikasi pengguna keluaran sistem dan tingkat kepentingan stakeholder |
| 20 | Kebutuhan | Apa yang menurut Bapak/Ibu tanda kalau pengelolaan sisa makanan sudah membaik? | Merumuskan indikator keberhasilan sebagai dasar business value |
| 21 | Penutup | Ada hal lain soal MBG yang penting saya tahu tapi belum saya tanyakan? | Menangkap informasi penting di luar daftar pertanyaan |
| 22 | Penutup | Boleh saya minta izin mengamati langsung waktu jam makan? | Meminta izin observasi lapangan untuk memvalidasi hasil wawancara |

## **Lampiran B. Ringkasan Hasil Wawancara**

Tabel B.1. Informasi Pelaksanaan Wawancara

| **Elemen** | **Keterangan** |
| --- | --- |
| Narasumber | PIC MBG SMA Negeri 3 Padang |
| Pewawancara | [isi nama anggota yang bertanya] |
| Tanggal | [isi tanggal wawancara] |
| Media | Wawancara daring, direkam dengan izin narasumber |
| Durasi | ± 45 menit |
| Pedoman | Daftar pertanyaan pada Lampiran A |

Ringkasan berikut disusun dari rekaman wawancara. Isinya adalah parafrase jawaban narasumber, bukan kutipan kata per kata. Kolom "Menit" menunjukkan posisi jawaban dalam rekaman. Bagian akhir rekaman yang berisi percakapan pribadi tidak digunakan atas permintaan narasumber.

Tabel B.2. Ringkasan Jawaban Narasumber per Topik

| **No** | **Topik** | **Ringkasan Jawaban** | **Menit** | **Digunakan pada** |
| --- | --- | --- | --- | --- |
| 1 | Penerima manfaat | MBG diberikan kepada seluruh siswa, guru, dan tenaga kependidikan (Tata Usaha, satpam, petugas kebersihan, penjaga sekolah). | 00:00–00:43 | 1.1 |
| 2 | Mitra SPPG | Sekolah memilih SPPG, lalu memperoleh R3I sebagai mitra dan membuat MoU. Isi MoU yang ditekankan adalah makanan bergizi; sekolah dapat mengajukan permintaan atau keberatan kepada SPPG. | 08:13–08:41 | 1.1, ST-07 |
| 3 | Waktu pengantaran | Pengantaran seharusnya pukul 10.00, tetapi sekolah meminta diantar siang menjelang makan siang agar kantin tetap berjualan dan siswa dapat jajan pada istirahat pertama. | 09:21–09:50 | 1.1, 4.1 |
| 4 | Penerimaan ompreng | Setelah kendaraan SPPG datang, empat petugas menurunkan ompreng dan mengaturnya per kelas. Setiap ompreng sudah bertuliskan kelas tujuan; jumlah per kelas sesuai jumlah siswa (misalnya 36). | 09:52–10:20 | 4.1, BP-01 |
| 5 | Pengambilan oleh kelas | Setelah salat zuhur berjamaah, empat perwakilan setiap kelas mengambil ompreng. Satu renteng berisi 5 ompreng dan setiap orang membawa 2 renteng. Ompreng dibawa ke kelas dan dibagikan kepada setiap siswa. | 10:20–11:08; 11:49–11:59 | 4.1, BP-01 |
| 6 | Pengembalian ompreng | Setelah makan, piket kelas mengikat kembali ompreng dan mengantarkannya ke titik pengumpulan di aula. Petugas mengecek berdasarkan absen per kelas untuk mengetahui kelas yang belum mengembalikan. SPPG menjemput ompreng sekitar pukul 14.00–15.00. | 11:08–11:47; 11:59–12:15 | 4.1, M-01 |
| 7 | Jumlah porsi | Jumlah porsi sama setiap hari, berdasarkan data siswa per kelas dan data guru yang diserahkan sekolah kepada SPPG. Sekolah meminta tambahan 2 porsi untuk tamu dari dinas. | 20:41–21:09 | 4.1 |
| 8 | Komunikasi dengan SPPG | Komunikasi antara SPPG dan sekolah dilakukan melalui PIC, misalnya pemberitahuan bahwa kelas 12 sudah tidak masuk sehingga jumlah porsi berubah. | 23:45–24:27 | ST-01, ST-07 |
| 9 | Kebijakan dari pusat | Ketentuan menu kering atau basah ditetapkan pusat; sejak setelah Lebaran menu kering tidak lagi diperbolehkan. MBG hanya diberikan bila ada siswa: saat siswa libur atau PJJ, MBG tidak ada dan tidak boleh diberikan hanya untuk guru. MBG juga pernah tidak ada beberapa hari karena dana pusat belum turun. | 21:58–24:10 | 4.1 (Frekuensi) |
| 10 | Masalah kualitas makanan | Pernah ada jeruk busuk. Guru mengomentari, PIC memotret dan mengirimkannya ke SPPG melalui telepon/pesan, lalu SPPG mengganti. | 08:41–09:15; 12:30–12:42 | M-01 |
| 11 | Keterlambatan SPPG | SPPG pernah terlambat pada hari Jumat saat ujian kelas 12 sehingga siswa sudah pulang. Porsi (±396) diantar ke panti asuhan; ompreng dijemput keesokan harinya. Menurut narasumber, keterlambatan adalah risiko SPPG sesuai perjanjian. | 12:46–15:11 | M-05 |
| 12 | Ompreng hilang | Bila ompreng hilang karena kesalahan pihak sekolah, sekolah mengganti Rp80.000 per ompreng, yang dipotong dari upah pekerja. | 07:27–07:40; 14:18–14:24 | 6.2 |
| 13 | Petugas pelaksana | Pekerja pelaksana MBG ada 4 orang (1 satpam dan 3 petugas kebersihan). Yang menerima upah adalah pekerja, bukan PIC. Upah Rp100.000 per hari untuk berempat bila penerima manfaat lebih dari 1.000 orang (Rp50.000 bila kurang), dibayarkan per ± 15 hari. | 03:28–05:09 | ST-02, 6.1, 6.2 |
| 14 | Penerimaan menu | Secara umum menu cocok dengan selera siswa. Menu yang tidak dimakan atau banyak bersisa: sambal telur, lele, dan ikan kolam (nila). Dendeng selalu habis. Variasi menu antara lain ayam kecap, ayam saus, ayam tepung, telur dadar, dan telur mata sapi. | 01:14–02:36 | M-04, BR-02, BR-08 |
| 15 | Komponen yang tersisa | Sisa umumnya tidak banyak; yang sering tersisa adalah sayur (misalnya lobak). Nasi tersisa bila lauk kurang cabai. | 16:11–16:17; 25:15–25:23; 27:03–27:15 | M-04, BR-02 |
| 16 | Kelas tidak mengambil porsi | Bila lauknya telur atau lele, pernah satu sampai tiga kelas tidak mengambil porsinya. | 16:25–16:39; 27:16–27:36 | M-05 |
| 17 | Penanganan sisa makanan | Sisa kadang diminta guru untuk pakan ternak atau dibawa pulang untuk diberikan kepada orang lain, tetapi jarang; selebihnya dibawa kembali oleh SPPG. Belum ada pengolahan sisa menjadi kompos. | 15:43–17:05; 25:12–26:55 | M-04 |
| 18 | Pencatatan sisa | Tidak ada dokumentasi atau pencatatan sisa makanan, baik oleh sekolah maupun SPPG. | 17:06–17:13 | M-01, M-04, C-01 |
| 19 | SOP sisa makanan | Menurut SOP, penanganan sisa makanan diserahkan pada kebijakan masing-masing sekolah. SPPG menyatakan sisa boleh diberikan, misalnya ke panti asuhan. | 29:23–30:15 | Akar masalah (Why 3) |
| 20 | Porsi berlebih | Petugas melaporkan kepada PIC bila ada kelas yang tidak mengambil porsi (misalnya 3 kelas ≈ 90-an porsi). Kelebihan sekitar 30 porsi diberikan kepada "anak ADM" [kurang jelas dalam rekaman], sedangkan 30–50 porsi atau lebih diantar ke panti asuhan menggunakan mobil SPPG atau mobil sekolah. Ompreng ditinggal dan dijemput kemudian. | 30:39–32:34 | M-05, BR-05, Tabel 16 |
| 21 | Data alergi | Sebelum MBG berjalan, seluruh siswa mengisi Google Form berisi alergi atau pantangan per nama dan kelas, dan boleh mengajukan menu pengganti. | 33:34–34:44 | M-02, BR-03 |
| 22 | Kegagalan porsi khusus | Pernah siswa alergi (telur/ayam) tidak menerima porsi khusus. Siswa melapor kepada petugas, petugas kepada PIC, dan PIC menelepon SPPG. SPPG meminta maaf dan mengganti pada hari berikutnya dengan menu kering. | 34:44–35:58 | M-03, BR-04 |
| 23 | Penggantian menu | Bila ada menu yang tidak disukai siswa (misalnya lele), sekolah meminta SPPG agar tidak memberikannya lagi. | 32:52–33:32 | O-01 |
| 24 | Dokumentasi | PIC mendokumentasikan pelaksanaan MBG dalam bentuk foto yang diunggah ke Instagram resmi SMA Negeri 3 Padang, dan pihak kelompok diizinkan menggunakannya. | 28:00–28:14 | Lampiran H |

# **QUALITY CHECK – SEBELUM PENGUMPULAN**

*Gunakan checklist berikut sebelum dokumen dikumpulkan.*

## **A.**    **Content Check**

☐     Organisasi dan konteks sistem dijelaskan dengan jelas.

☐     Masalah dibedakan dari penyebab dan solusi.

☐     Setiap masalah memiliki dampak.

☐     Stakeholder telah diidentifikasi.

☐     Proses bisnis utama telah dimodelkan.

☐     System Request lengkap.

☐     Feasibility Analysis mencakup aspek teknis, ekonomi, dan operasional.

☐     Effort Estimation memiliki dasar/asumsi.

☐     Scope sistem realistis.

## **B.**    **Traceability Check**

☐     Setiap masalah memiliki ID M-xx.

☐     Setiap stakeholder memiliki ID ST-xx.

☐     Setiap proses memiliki ID BP-xx.

☐     Setiap Business Requirement memiliki ID BR-xx.

☐     M-xx dapat ditelusuri ke BP-xx.

☐     M-xx dapat ditelusuri ke BR-xx.

☐     BR-xx memiliki stakeholder/sumber yang jelas.

☐     Tidak terdapat Business Requirement yang muncul tanpa dasar.

☐     Informasi pada System Request konsisten dengan analisis masalah.

☐     Kesimpulan feasibility sesuai dengan hasil analisis.

## **C.**    **Diagram Check**

☐     Semua diagram memiliki nomor dan judul.

☐     Semua diagram memiliki sumber/keterangan jika diperlukan.

☐     Notasi diagram digunakan dengan benar.

☐     Nama aktivitas/elemen konsisten.

☐     Diagram dapat dibaca dengan jelas.

☐     Tidak ada diagram yang terlalu kecil.

☐     Diagram dijelaskan dalam narasi.

☐     Setiap diagram relevan dengan pembahasan.

## **D.**    **Document Quality Check**

☐     Struktur heading konsisten.

☐     Penomoran tabel konsisten.

☐     Penomoran gambar konsisten.

☐     Tidak ada typo yang mengganggu.

☐     Semua tabel memiliki judul.

☐     Semua gambar memiliki caption.

☐     Semua referensi yang dikutip tercantum dalam daftar pustaka.

☐     Tidak ada referensi yang tidak pernah digunakan.

☐     Format halaman konsisten.

☐     Dokumen dapat dibaca dengan baik saat dicetak maupun PDF.

# **FORMAT PENAMAAN FILE**

Gunakan format:

**APSI_M1_[NamaKelompok]_[NamaSistem]_v1.pdf**

Contoh:

**APSI_M1_Kelompok03_SistemInformasiKlinik_v1.pdf**

Jika terdapat revisi:

**APSI_M1_Kelompok03_SistemInformasiKlinik_v2.pdf**

# **STRUKTUR ID ARTEFAK PROYEK**

Gunakan ID berikut secara konsisten selama seluruh proyek APSI.

Tabel 22. Struktur Artefak Proyek

| Artefak | Format ID | Contoh |
| --- | --- | --- |
| Masalah | M-xx | M-01 |
| Opportunity | O-xx | O-01 |
| Stakeholder | ST-xx | ST-01 |
| Business Process | BP-xx | BP-01 |
| Business Requirement | BR-xx | BR-01 |
| Scope In | SC-IN-xx | SC-IN-01 |
| Scope Out | SC-OUT-xx | SC-OUT-01 |
| Constraint | C-xx | C-01 |

**Catatan penting:** ID yang sudah dibuat pada Milestone 1 **tidak boleh diubah sembarangan pada Milestone 2 dan Milestone 3**. ID inilah yang akan menjadi dasar *traceability* proyek secara keseluruhan.

# **OUTPUT AKHIR MILESTONE 1**

Mahasiswa wajib mengumpulkan:

1\.     **System Planning Document – PDF**

2\.     **Business Process Model**

3\.     **System Request**

4\.     **Feasibility Analysis**

5\.     **Effort Estimation / Project Plan**

6\.     **Traceability Matrix**

7\.     File sumber model jika diminta dosen

Dokumen harus menunjukkan hubungan:

**Problem → Stakeholder → Business Process → System Request → Feasibility → Effort → Project Plan**

Milestone 1 dinyatakan **siap dilanjutkan ke System Analysis** apabila seluruh hubungan tersebut dapat dijelaskan dan ditelusuri dengan jelas.
