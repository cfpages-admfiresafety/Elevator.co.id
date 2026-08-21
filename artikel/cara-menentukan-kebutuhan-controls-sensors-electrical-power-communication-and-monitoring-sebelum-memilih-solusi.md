---
article_id: ELV-08-02
title: "Cara Menentukan Kebutuhan Controls, sensors, electrical power, communication, and monitoring Sebelum Memilih Solusi"
slug: "cara-menentukan-kebutuhan-controls-sensors-electrical-power-communication-and-monitoring-sebelum-memilih-solusi"
description: "Pembaca dapat mengumpulkan data lapangan, menetapkan requirement, dan menyaring solusi yang tidak cocok."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-10-11"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: ELV-08
primary_intent: "Menerjemahkan fungsi, lokasi, pengguna, risiko, dan target mutu menjadi persyaratan Controls, sensors, electrical power, communication, and monitoring."
reader_community: "Elevator.co.id"
reader_address: "Sobat Elevator.co.id"
final_route: "/artikel/cara-menentukan-kebutuhan-controls-sensors-electrical-power-communication-and-monitoring-sebelum-memilih-solusi.html"
technical_review: required
sources:
  - "https://www.ilo.org/topics-and-sectors/occupational-safety-and-health-guide-labour-inspectors-and-other/how-can-occupational-safety-and-health-be-managed/controlling-risks"
  - "https://www.ilo.org/publications/5-step-guide-employers-workers-and-their-representatives-conducting"
  - "https://bnsp.go.id/"
  - "https://www.iso.org/files/live/sites/isoorg/files/archive/pdf/en/iso_45001_-briefing_note.pdf"
  - "https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999"
  - "https://jdih.kemendag.go.id/pdf/Regulasi/2019/PP%20Nomor%2080%20Tahun%202019.pdf"
  - "https://peraturan.bpk.go.id/Details/229798/uu-no-27-tahun-2022"
  - "https://www.iso.org/standard/62542.html"
  - "https://www.iso.org/standard/80553.html"
  - "https://peraturan.bpk.go.id/Home/Download/251564/Kemnaker%20No.%206%20Tahun%202017.pdf"
  - "https://peraturan.bpk.go.id/Details/161846/pp-no-16"
---

# Cara Menentukan Kebutuhan Controls, sensors, electrical power, communication, and monitoring Sebelum Memilih Solusi

Halo, Sobat Elevator.co.id! Kesalahan paling mahal biasanya terjadi sebelum memilih merek: kebutuhan belum diterjemahkan menjadi fungsi, kondisi lokasi, bukti penerimaan, dan batas tanggung jawab. Cara yang lebih aman ialah membuat ringkasan persyaratan (requirement brief) dari fakta lapangan, lalu menguji setiap tawaran terhadap ringkasan itu. Jangan mulai dari daftar fitur penjual.

Jawaban singkatnya: tetapkan dulu apa yang harus dikendalikan, apa yang harus diukur, bagaimana daya tersedia dan dilindungi, bagaimana data dikirim, siapa yang memantau dan merespons, serta bukti apa yang harus diserahkan. Hasilnya harus cukup jelas untuk dibandingkan, tetapi tidak berpura-pura menggantikan desain atau persetujuan ahli. Kondisi bangunan, jenis lift, pengguna, aturan yang berlaku, dan riwayat aset dapat mengubah persyaratan; karena itu data yang belum terukur harus ditandai, bukan ditebak. Untuk konteks umum pengelolaan lift, Anda dapat mulai dari beranda Elevator.co.id sebelum menyusun ringkasan persyaratan.

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

![Ilustrasi jasa maintenance elevator](/wp-content/uploads/2020/07/jasa-maintenance-elevator.png)

Aset lokal ini adalah ilustrasi umum, bukan dokumentasi proyek tertentu.

## Hasil akhir dan prasyarat

Target akhirnya adalah satu ringkasan persyaratan yang bisa dibaca pemilik, operator, perencana, integrator, dan penguji dengan arti yang sama. Isi minimalnya mencakup:

- tujuan operasi dan pengguna yang dilayani;
- lokasi, lingkungan, ruang tersedia, serta antarmuka dengan struktur, pintu, sistem kebakaran, dan jaringan;
- fungsi pengendalian (controls), pendeteksian (sensors), catu dan proteksi daya (electrical power), komunikasi (communication), dan pemantauan (monitoring);
- kondisi normal, gangguan, kehilangan daya atau jaringan, serta siapa yang mengambil keputusan;
- kriteria penerimaan, rekaman yang diserahkan, dan pemicu perubahan.

Sebelum mengisi, tunjuk seorang pemilik requirement yang berwenang menyetujui fungsi dan risiko. Siapkan gambar dan data aset yang tersedia, wawancara operator, catatan gangguan, inspeksi visual yang aman, daftar antarmuka, serta versi dokumen yang jelas. Penilaian risiko sebaiknya mengikuti siklus identifikasi, penilaian, pengendalian, dan peninjauan; panduan lima langkah ILO menekankan keterlibatan pekerja dan pengendalian risiko yang nyata, bukan sekadar formulir ([ILO controlling risks](https://www.ilo.org/topics-and-sectors/occupational-safety-and-health-guide-labour-inspectors-and-other/how-can-occupational-safety-and-health-be-managed/controlling-risks), [ILO five-step guide](https://www.ilo.org/publications/5-step-guide-employers-workers-and-their-representatives-conducting)).

## Langkah 1 — tetapkan ruang lingkup

Tulis kalimat batas: apakah ringkasan persyaratan untuk lift baru, modernisasi, pemantauan kondisi, atau gabungan? Sebut aset dan area yang termasuk, lalu sebut yang tidak termasuk. Misalnya, panel pengendali dan sinyal status dapat masuk, sedangkan perubahan struktur gedung, perhitungan lalu lintas, dan prosedur penyelamatan rinci memerlukan disiplin serta persetujuan tersendiri.

Buat peta antarmuka. Untuk setiap titik, catat pemilik dan arah informasinya: sensor pintu ke kontroler, status kontroler ke sistem monitoring, alarm ke petugas, suplai utama ke panel, atau jaringan gedung ke gateway. Nyatakan apakah kebutuhan berlaku saat operasi normal, inspeksi, pemadaman, kebakaran, atau pekerjaan pemeliharaan. Standar lift dan aturan bangunan harus diverifikasi terhadap tipe, tahun pemasangan, penggunaan, dan yurisdiksi yang sebenarnya; rujukan umum tidak otomatis membuktikan kesesuaian aset ([ISO 8100-1:2026](https://www.iso.org/standard/80553.html), [PP No. 16 Tahun 2021](https://peraturan.bpk.go.id/Details/161846/pp-no-16)).

Kawan Elevator.co.id, anggap setiap kata “aman”, “real-time”, atau “siap integrasi” sebagai pertanyaan yang harus dijawab: aman terhadap bahaya apa, real-time menurut batas waktu berapa, dan integrasi melalui antarmuka mana? Jika jawabannya belum ada, ubah kata promosi itu menjadi kolom yang harus diisi.

## Langkah 2 — kumpulkan dan cocokkan bukti

Mulailah dari observasi dan dokumen yang dapat ditelusuri, bukan asumsi. Cocokkan lima kelompok kebutuhan berikut.

**Pengendalian (controls).** Tulis tindakan yang harus terjadi: menerima perintah, memilih mode, mengunci kondisi, mengeluarkan perintah berhenti, atau mengeskalasi gangguan. Bedakan perintah operator, interlock keselamatan, dan logika diagnostik. Jangan menulis “kontrol otomatis” tanpa kondisi pemicu, keadaan aman, dan kewenangan perubahan.

**Pendeteksian (sensors).** Untuk tiap besaran, catat apa yang diukur, lokasi, keadaan normal, tanda gagal, dan tindakan ketika data hilang atau tidak masuk akal. Identitas sensor, rentang, metode pemasangan, dan kebutuhan kalibrasi harus berasal dari desain atau lembar data yang disetujui; artikel ini tidak menetapkan angka atau tipe komponen.

**Catu dan proteksi daya (electrical power).** Kumpulkan sumber, pemisahan beban, proteksi, kualitas daya yang dipersyaratkan, kebutuhan saat listrik padam, dan titik isolasi. Diagram satu garis (one-line diagram), inspeksi kondisi aktual, serta verifikasi oleh personel berkompeten diperlukan sebelum memilih proteksi atau melakukan pekerjaan listrik. Ringkasan persyaratan hanya menyatakan kebutuhan dan bukti, bukan memberi prosedur kerja bertegangan.

**Komunikasi (communication).** Tentukan pesan yang dikirim, tujuan, media, ketersediaan, autentikasi, dan perilaku saat jaringan putus. “Terhubung ke BMS” belum cukup: sebutkan data minimum, arah perintah, pemilik jaringan, serta siapa yang menerima alarm.

**Pemantauan (monitoring).** Pisahkan tampilan, pencatatan, alarm, dan tindakan. Tetapkan sumber waktu, identitas aset, urutan kejadian, hak akses, dan lama penyimpanan sesuai kebijakan organisasi. Catatan pemeliharaan, inspeksi, dan kejadian harus memiliki pemilik serta versi; katalog ISO mencantumkan ISO 15489-1:2016 sebagai standar pengelolaan rekaman dan halaman publiknya dipakai di sini hanya untuk identitas, status, serta lingkup publik, bukan untuk menafsirkan klausul teknis, sementara kewajiban perlindungan data perlu ditinjau berdasarkan konteks Indonesia ([ISO 15489-1:2016](https://www.iso.org/standard/62542.html), [UU No. 27 Tahun 2022](https://peraturan.bpk.go.id/Details/229798/uu-no-27-tahun-2022)).

Untuk setiap butir, simpan sumber, tanggal, asumsi, dan status: terverifikasi, perlu ukur, atau menunggu keputusan. Bukti kompetensi orang yang menyetujui pekerjaan juga harus diperiksa sesuai lingkup tugas. Untuk mencocokkan identitas lembaga atau lingkup dokumen publik, lihat halaman BNSP dan catatan pengantar ISO 45001; keduanya bukan bukti kompetensi, sertifikasi, atau otorisasi pekerjaan tertentu ([BNSP](https://bnsp.go.id/), [ISO 45001 briefing note](https://www.iso.org/files/live/sites/isoorg/files/archive/pdf/en/iso_45001_-briefing_note.pdf)).

## Langkah 3 — jalankan urutan kerja

Gunakan urutan konseptual yang dapat diaudit:

1. **Nyatakan hasil operasi.** Contoh: operator harus mengetahui lift berhenti karena kondisi apa dan tindakan awal yang diizinkan. Hindari target yang tidak dapat diamati.
2. **Petakan kondisi dan bahaya.** Tinjau operasi normal, akses pemeliharaan, kehilangan daya, kehilangan komunikasi, banjir, kebakaran, dan perubahan penggunaan. Tandai skenario yang memerlukan ahli K3, listrik, lift, kebakaran, struktur, atau perlindungan data.
3. **Turunkan kebutuhan terukur.** Untuk tiap fungsi, tulis pemicu, masukan, keluaran, prioritas, batas waktu yang memang disetujui, dan bukti penerimaan. Jika belum ada dasar untuk angka, gunakan “ditentukan melalui desain dan pengujian”, bukan angka rekaan.
4. **Cocokkan antarmuka.** Buat matriks siapa memasok sinyal, daya, jaringan, ruang, dan dokumen. Konflik antara kontrol lokal dan perintah jarak jauh harus diselesaikan sebelum pengadaan.
5. **Saring solusi.** Tolak tawaran yang tidak menyebut model, revisi, batas lingkungan, dukungan, rekaman, atau cara pengujian. Klaim “sesuai standar” atau gambar sertifikat tidak membuktikan model dan sistem terpasang benar-benar sesuai; konsumen berhak memperoleh informasi yang benar dan dapat dibandingkan, tetapi verifikasi dokumen tetap diperlukan ([UU No. 8 Tahun 1999](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999), [PP No. 80 Tahun 2019](https://jdih.kemendag.go.id/pdf/Regulasi/2019/PP%20Nomor%2080%20Tahun%202019.pdf)).
6. **Tetapkan versi acuan.** Beri nomor versi, daftar pengecualian, dan persetujuan. Perubahan fungsi, tata letak, jaringan, atau pengguna memicu peninjauan ulang risiko dan persyaratan.

## Titik henti dan kondisi berhenti

Hentikan pemilihan solusi bila data utama bertentangan: kapasitas dan penggunaan belum dipastikan, jalur daya atau jaringan tidak diketahui, ruang panel belum diukur, atau pihak yang berwenang belum jelas. Jangan menutup selisih dengan asumsi penyedia. Hentikan juga bila solusi mengubah rangkaian keselamatan, mode kebakaran, akses penyelamatan, atau sistem listrik tanpa desain dan peninjauan oleh tenaga kompeten.

Teman Elevator.co.id, jadikan titik keputusan sebagai keputusan tertulis: “lanjut”, “ukur ulang”, atau “tunggu persetujuan”. Untuk aset lift yang sudah beroperasi, pemeriksaan dan pengujian sesuai aturan yang berlaku serta riwayat instalasi tetap diperlukan; dokumen lama atau stiker pemeliharaan saja bukan bukti lengkap kelayakan ([Permenaker No. 6 Tahun 2017](https://peraturan.bpk.go.id/Home/Download/251564/Kemnaker%20No.%206%20Tahun%202017.pdf)). [NEEDS TECHNICAL REVIEW: verifikasi adopsi Indonesia, persyaratan lokal, dan penerimaan otoritas untuk aset serta perubahan yang dimaksud.]

## Verifikasi hasil dan serah terima

Sebelum ringkasan persyaratan dipakai untuk membandingkan penawaran, lakukan pemeriksaan silang:

- setiap fungsi memiliki pemilik, kondisi pemicu, dan bukti penerimaan;
- setiap sensor dan sinyal memiliki identitas, lokasi, status gagal, serta jalur rekaman;
- setiap beban daya memiliki sumber dan batas antarmuka yang disetujui;
- setiap pesan komunikasi memiliki tujuan, hak akses, dan respons saat terputus;
- alarm dapat ditelusuri dari kejadian ke tindakan, tanpa menganggap tampilan sebagai bukti sensor benar;
- dokumen konfigurasi, daftar perubahan, hasil uji, manual, pelatihan, dan kontak eskalasi diserahkan dengan nomor versi.

Minta peninjauan independen yang sesuai kompetensi untuk bagian keselamatan, listrik, kebakaran, struktur, jaringan, dan data pribadi. Rekam temuan, tindakan koreksi, penanggung jawab, tenggat, dan bukti efektivitas. Setelah serah terima, tetapkan pemicu peninjauan: perubahan perangkat lunak atau jaringan, penggantian sensor, perubahan penggunaan gedung, insiden, temuan inspeksi, atau perubahan aturan.

## Jalan pintas yang sering gagal

Jalan pintas yang tampak menarik adalah menyalin spesifikasi proyek lain atau memilih paket “all-in-one” berdasarkan harga dan jumlah fitur. Cara ini dapat gagal karena kondisi daya, ruang, jaringan, profil pengguna, dan tanggung jawab respons berbeda. Paket yang banyak fiturnya pun belum tentu menyediakan bukti, antarmuka, atau perilaku gagal yang dibutuhkan.

Alternatifnya, berikan penyedia ringkasan persyaratan yang sama, minta matriks kepatuhan per butir, daftar pengecualian, asumsi, versi produk, rencana uji, dan rekaman yang akan diserahkan. Bandingkan jawaban terhadap kebutuhan yang telah disetujui, bukan terhadap brosur.

## Kesimpulan

Cara menentukan kebutuhan Controls, sensors, electrical power, communication, and monitoring adalah mengubah tujuan operasi dan kondisi nyata menjadi ringkasan persyaratan yang memiliki cakupan, bukti, antarmuka, perilaku gagal, kriteria penerimaan, dan pemilik keputusan. Mulailah dengan kunjungan serta dokumen aset, tandai data yang belum terverifikasi, lalu minta tinjauan profesional sebelum menyentuh desain keselamatan, daya, kebakaran, atau perubahan lift.

Langkah berikutnya: buat matriks lima fungsi tersebut, isi sumber dan status tiap butir, lalu kirimkan versi bernomor kepada pihak berwenang untuk disetujui. Untuk pertanyaan lanjutan, gunakan [beranda Elevator.co.id](/) dan bawa ringkasan persyaratan versi terbaru agar tim merujuk dokumen yang sama. Aturan operasinya sederhana: bila fungsi, bukti, atau tanggung jawab respons belum jelas, persyaratan belum siap menjadi dasar pemilihan solusi.
