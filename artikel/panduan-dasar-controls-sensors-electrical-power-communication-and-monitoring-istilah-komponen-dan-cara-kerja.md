---
article_id: ELV-08-01
title: "Panduan Dasar Controls, sensors, electrical power, communication, and monitoring: Istilah, Komponen, dan Cara Kerja"
slug: "panduan-dasar-controls-sensors-electrical-power-communication-and-monitoring-istilah-komponen-dan-cara-kerja"
description: "Panduan pemula untuk mengenali istilah, komponen, hubungan, dan batas sistem kendali, sensor, daya listrik, komunikasi, dan pemantauan pada elevator."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-10-06"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: ELV-08
primary_intent: "Memahami definisi, komponen, mekanisme, dan batas sistem Controls, sensors, electrical power, communication, and monitoring."
reader_community: "Elevator.co.id"
reader_address: "Teman Elevator.co.id"
final_route: "/artikel/panduan-dasar-controls-sensors-electrical-power-communication-and-monitoring-istilah-komponen-dan-cara-kerja.html"
technical_review: required
sources:
  - "https://www.ilo.org/topics-and-sectors/occupational-safety-and-health-guide-labour-inspectors-and-other/how-can-occupational-safety-and-health-be-managed/controlling-risks"
  - "https://www.ilo.org/publications/5-step-guide-employers-workers-and-their-representatives-conducting"
  - "https://bnsp.go.id/"
  - "https://www.iso.org/files/live/sites/isoorg/files/archive/pdf/en/iso_45001_-briefing_note.pdf"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
---

# Panduan Dasar Controls, sensors, electrical power, communication, and monitoring: Istilah, Komponen, dan Cara Kerja

Halo, Teman Elevator.co.id! Saat melihat panel, kabel, layar pemantauan, atau sensor di sekitar elevator, pembaca baru sering mengira semuanya adalah satu “sistem kontrol”. Padahal, tiap bagian punya tugas berbeda. Salah mengenali tugasnya dapat membuat kebutuhan proyek dirumuskan terlalu cepat, sementara data penting belum diketahui.

Jawaban singkatnya: controls (kendali) membuat keputusan operasi, sensors (sensor) menangkap keadaan, electrical power (daya listrik) memasok energi, communication (komunikasi) mengirim pesan, dan monitoring (pemantauan) menyajikan status serta kejadian. Kelimanya bekerja sebagai rantai: sensor memberi masukan, kendali mengolahnya, daya menggerakkan peralatan, komunikasi menghubungkan perangkat, lalu pemantauan membantu orang memahami hasilnya. Artikel ini membangun model mental tersebut; ia tidak membandingkan merek, memilih spesifikasi, atau menyatakan suatu instalasi sudah aman.

![Ilustrasi jasa maintenance elevator](/wp-content/uploads/2020/07/jasa-maintenance-elevator.png)

Ilustrasi umum dari aset lokal Elevator.co.id; bukan dokumentasi proyek tertentu.

## Apa hasil yang ingin dicapai dan prasyaratnya?

Bagian ini menjelaskan arti “berhasil” supaya Anda tidak mengukur sistem hanya dari lampu indikator yang menyala. Hasil yang berguna ialah peta sederhana: keadaan apa yang diukur, keputusan apa yang dibuat, perangkat mana yang menjalankan keputusan, pesan apa yang dikirim, dan siapa yang membaca rekamannya.

Prasyaratnya bukan daftar merek, melainkan gambaran aset, tujuan operasi, antarmuka dengan sistem lain, riwayat perubahan, serta dokumen yang tersedia. Bila data itu belum ada, tandai sebagai kekosongan informasi, bukan diisi dengan asumsi. Panduan ILO menekankan penilaian bahaya dan pengendalian yang disesuaikan dengan konteks, bukan matriks generik yang otomatis berlaku untuk semua lokasi ([ILO tentang pengendalian risiko](https://www.ilo.org/topics-and-sectors/occupational-safety-and-health-guide-labour-inspectors-and-other/how-can-occupational-safety-and-health-be-managed/controlling-risks)). Penetapan kewajiban, desain, dan penerimaan tetap memerlukan pihak berwenang serta bukti proyek.

## Mengenali lima lapisan sistem

Sebelum masuk ke komponen, kita perlu memisahkan istilah yang sering tercampur. Pemisahan ini mencegah anggapan bahwa sensor dapat “memutuskan” sendiri atau layar pemantauan dapat menggantikan pengaman.

### Kendali: bagian yang mengolah keputusan

Controls atau kendali menerima masukan, memeriksa syarat, lalu mengeluarkan perintah. Bentuknya dapat berupa pengendali terprogram, modul masukan-keluaran, atau logika pada penggerak. Mekanismenya seperti aturan “jika keadaan A dan B terpenuhi, izinkan langkah C”. Kendali hanya sebaik masukan, aturan, dan batas yang benar-benar didefinisikan.

Bila pintu belum terdeteksi tertutup, kendali dapat menahan perintah gerak. Contoh itu bukan bukti bahwa seluruh rantai keselamatan elevator sudah memenuhi persyaratan. Periksa masukan yang dipakai, keluaran yang dipengaruhi, kondisi gagal yang dikenali, dan versi dokumen acuannya.

### Sensor: bagian yang mengubah keadaan menjadi sinyal

Sensors atau sensor mendeteksi keadaan fisik—misalnya posisi, suhu, arus, getaran, atau status pintu—lalu mengubahnya menjadi sinyal. Sensor tidak otomatis memahami konteks dan tidak menjamin keputusan akhir. Sinyal dapat salah karena pemasangan, lingkungan, kabel, kalibrasi, atau batas alat.

Jangan hanya mencatat nama sensor. Catat apa yang diukur, jenis sinyal, lokasi, kondisi rujukan, dan cara memeriksa hasilnya. Jika nilai tampak tidak wajar, pemeriksaan harus membedakan kerusakan sensor dari perubahan keadaan yang memang terjadi.

### Daya listrik: prasyarat perangkat bekerja

Electrical power atau daya listrik menyediakan energi bagi pengendali, sensor, penggerak, penerangan, dan komunikasi. Daya bukan sekadar “ada listrik”; sumber, pemisahan rangkaian, perlindungan, pembumian, dan kondisi lingkungan memengaruhi perilaku perangkat.

Karena itu, gambar satu garis, identitas sumber, status isolasi, dan rekaman pemeriksaan menjadi bagian dari pemahaman sistem. Undang-Undang Nomor 1 Tahun 1970 memberi dasar umum keselamatan kerja, tetapi penerapannya bergantung pada tempat kerja, aktivitas, peralatan, dan aturan pelaksana yang relevan ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970)). Artikel ini tidak menetapkan ukuran pengaman, setelan proteksi, atau prosedur bekerja bertegangan.

### Komunikasi: jalan pertukaran pesan

Communication atau komunikasi menghubungkan pengendali, sensor cerdas, panel, sistem gedung, dan perangkat pemantauan. Pesannya dapat berisi nilai, status, perintah, atau alarm. Media, alamat, format pesan, waktu pembaruan, dan perilaku saat jaringan terputus menentukan mekanismenya.

“Terhubung” belum berarti pesannya dapat dipercaya. Periksa siapa pengirim dan penerima, pesan wajib, tanda kehilangan pesan, serta siapa yang boleh mengubah konfigurasi. Jangan menyimpulkan keamanan siber, keandalan waktu, atau kecocokan antarproduk hanya dari nama protokol.

### Pemantauan: jendela untuk melihat keadaan

Monitoring atau pemantauan menyajikan nilai dan peristiwa agar operator dapat mengamati dan menindaklanjuti. Layar, tren, laporan, dan notifikasi berada di lapisan ini. Pemantauan membantu manusia mengambil keputusan, tetapi bukan pengganti pengaman otomatis atau inspeksi lapangan.

Layar dapat menunjukkan status “normal” karena pesan terakhir masih tersimpan, padahal komunikasi sudah terputus. Setiap tampilan penting perlu penanda kesegaran data, waktu kejadian, sumber, dan kondisi ketika data tidak tersedia. Tanyakan pula siapa pemilik tindak lanjut ketika alarm muncul.

## Bagaimana hubungan antarkomponen dibaca?

Setelah lima lapisan terpisah, bagian ini menyusun urutannya. Mulailah dari keadaan nyata: pintu, posisi kabin, suhu ruang, atau status daya. Sensor mengubah keadaan menjadi sinyal. Pengendali memeriksa sinyal terhadap aturan dan mengeluarkan perintah. Perangkat pelaksana menjalankan perintah menggunakan daya. Komunikasi membawa status ke perangkat lain, sedangkan pemantauan menampilkan apa yang terjadi dan menyimpan jejak waktunya.

Satu keadaan dapat melewati beberapa lapisan. Jika sensor posisi mengirim nilai keliru, kendali dapat mengambil keputusan keliru; bila daya modul turun, nilai dapat hilang; bila jaringan putus, layar mungkin menampilkan data lama. Sebaliknya, layar yang mati belum membuktikan kendali berhenti. Sobat Elevator.co.id, tanyakan di lapisan mana bukti terakhir masih benar, bukan komponen mana yang harus langsung diganti.

Gunakan tabel sederhana: keadaan, sinyal, aturan, aksi, pesan, dan rekaman. Isi berdasarkan gambar, manual, daftar titik, atau catatan pengujian yang tersedia. Jika satu kolom kosong, tulis “belum terbukti” dan minta sumbernya.

## Menetapkan batas pekerjaan tanpa menjadikannya spesifikasi

Bagian ini mencegah model mental melebar menjadi keputusan pembelian atau rancangan yang belum memiliki data. Tentukan objek dan antarmukanya: pengendali elevator, pemantauan gedung, catu daya, atau koneksi antarperangkat. Tentukan pula fasenya—perancangan, pemasangan, pemeliharaan, atau perubahan—karena bukti dan pemilik keputusan dapat berbeda.

Cocokkan bukti dengan pertanyaannya. Dokumen identitas komponen menjawab “apa bendanya”, bukan “apakah seluruh sistem telah diterima”. Rekaman pengujian menjawab kondisi pada waktu tertentu, bukan jaminan selamanya. Bukti kompetensi membantu menilai siapa yang boleh mengerjakan tugas, tetapi tidak mengesahkan semua keputusan orang tersebut. BNSP dan catatan ISO 45001 menekankan pentingnya ruang lingkup, kompetensi, identitas, serta konteks penugasan ketika bukti kredensial dinilai ([BNSP](https://bnsp.go.id/); [ISO 45001 briefing note](https://www.iso.org/files/live/sites/isoorg/files/archive/pdf/en/iso_45001_-briefing_note.pdf)).

Jika tujuan Anda berubah menjadi memilih perangkat terbaik atau menentukan kapasitas, berhenti. Pertanyaan itu membutuhkan data proyek dan kajian tersendiri, bukan kesimpulan dari panduan istilah.

## Urutan pemeriksaan konseptual dan titik berhenti

Urutan ini memberi cara kerja yang dapat diikuti tanpa menyentuh bagian berbahaya. Gambarkan aliran dari keadaan ke rekaman, cocokkan setiap masukan dengan sumber dan kondisi normalnya, lalu cocokkan keluaran dengan perangkat yang dikendalikan. Berikutnya periksa tanda gagal pada daya dan komunikasi, kemudian pastikan pemantauan menampilkan waktu, asal data, dan status kehilangan data.

Berhenti dan minta review kompeten bila sumber listrik tidak jelas, diagram berbeda dari kondisi lapangan, fungsi keselamatan tidak memiliki bukti pengujian, alarm tidak memiliki pemilik tindak lanjut, atau perubahan konfigurasi tidak terlacak. Penilaian risiko yang serius memerlukan metode, bukti, kompetensi, dan persetujuan sesuai konteks; panduan lima langkah ILO bukan izin melakukan pekerjaan berbahaya tanpa pengawasan ([panduan penilaian risiko ILO](https://www.ilo.org/publications/5-step-guide-employers-workers-and-their-representatives-conducting)).

Jangan melakukan pengukuran pada bagian bertegangan, mengubah parameter, atau menjumper pengaman demi membuktikan hipotesis dari artikel ini. Pekerjaan demikian berada di luar batas tulisan dan harus mengikuti prosedur, kewenangan, serta pemeriksaan yang berlaku di lokasi.

## Verifikasi hasil dan serah-terima informasi

Bagian akhir ini mengubah model mental menjadi daftar tanya untuk rapat atau pemeriksaan. Periksa identitas perangkat; fungsi dan titik masukan-keluaran; sumber daya dan kondisi gagal; jalur komunikasi dan tanda kehilangan pesan; tampilan serta umur data; serta riwayat perubahan, pengujian, atau persetujuan. Untuk tiap hal, simpan sumber, tanggal, versi, batas penggunaan, dan orang yang bertanggung jawab.

Kawan Elevator.co.id, lakukan satu uji pemahaman: minta orang lain menunjuk dari satu keadaan nyata sampai tindakan dan rekamannya tanpa melihat jawaban Anda. Bila ia berhenti karena istilah tidak jelas atau bukti hilang, itulah pekerjaan berikutnya—memperbaiki dokumentasi atau meminta review—bukan alasan untuk menebak.

### Jalan pintas yang menyesatkan

Jalan pintas paling umum ialah memilih berdasarkan foto panel, logo, atau klaim “sudah terintegrasi”. Foto hanya menunjukkan bentuk, sedangkan integrasi bergantung pada titik, aturan, daya, komunikasi, pengujian, dan perubahan versi. Alternatif yang lebih andal adalah mencocokkan klaim dengan dokumen asli dan kondisi aset yang dinyatakan jelas; logo atau salinan sertifikat tidak otomatis membuktikan sistem terpasang sesuai kebutuhan.

## Kesimpulan: keputusan kecil yang perlu dibuat sekarang

Controls membuat keputusan, sensors membaca keadaan, electrical power memberi energi, communication mengirim pesan, dan monitoring membantu orang melihat serta menindaklanjuti status. Hubungan itu dapat diringkas sebagai keadaan → sinyal → aturan → aksi → pesan → rekaman, dengan bukti dan pemilik pada setiap tahap.

Mulailah dengan satu diagram aliran dan enam pertanyaan verifikasi di atas. Baca juga konteks layanan di [beranda Elevator.co.id](/) bila Anda perlu menempatkan istilah ini dalam alur pekerjaan, lalu bawa hasilnya kepada pihak kompeten bila menyentuh desain, daya, fungsi keselamatan, perubahan konfigurasi, atau kewajiban hukum. Jangan membandingkan opsi atau menetapkan spesifikasi dari artikel ini; bila bukti tidak lengkap, tahan langkah dan minta data yang dapat ditelusuri.

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-001`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi jasa maintenance elevator](/wp-content/uploads/2020/07/jasa-maintenance-elevator.png)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `jasa maintenance elevator` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-001]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->
