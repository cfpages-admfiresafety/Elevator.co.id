---
article_id: ELV-02-02
title: "Cara Menentukan Kebutuhan Tipe elevator dan use-case selection Sebelum Memilih Solusi"
slug: "cara-menentukan-kebutuhan-tipe-elevator-dan-use-case-selection-sebelum-memilih-solusi"
description: "Pembaca dapat mengumpulkan data lapangan, menetapkan requirement, dan menyaring solusi yang tidak cocok."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-04-01"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: ELV-02
primary_intent: "Menerjemahkan fungsi, lokasi, pengguna, risiko, dan target mutu menjadi persyaratan Tipe elevator dan use-case selection."
reader_community: "Elevator.co.id"
reader_address: "Kawan Elevator.co.id"
final_route: "/artikel/cara-menentukan-kebutuhan-tipe-elevator-dan-use-case-selection-sebelum-memilih-solusi.html"
technical_review: required
sources:
  - "https://www.ilo.org/topics-and-sectors/occupational-safety-and-health-guide-labour-inspectors-and-other/how-can-occupational-safety-and-health-be-managed/controlling-risks"
  - "https://www.ilo.org/publications/5-step-guide-employers-workers-and-their-representatives-conducting"
  - "https://www.iso.org/standard/70017.html"
  - "https://peraturan.bpk.go.id/Details/5263/pp-no-50-tahun-2012"
  - "https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://www.iso.org/standard/80553.html"
  - "https://peraturan.bpk.go.id/Home/Download/251564/Kemnaker%20No.%206%20Tahun%202017.pdf"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
  - "https://peraturan.bpk.go.id/Details/161846/pp-no-16"
  - "https://www.iso.org/standard/73072.html"
---

# Cara Menentukan Kebutuhan Tipe elevator dan use-case selection Sebelum Memilih Solusi

Halo, Kawan Elevator.co.id! Kesalahan paling mahal biasanya terjadi sebelum ada merek atau penawaran: fungsi elevator belum diterjemahkan menjadi requirement yang bisa diuji. Cara yang lebih aman adalah memulai dari siapa yang diangkut, apa yang dipindahkan, di mana unit bekerja, seberapa sering digunakan, dan risiko apa yang tidak boleh diterima. Dari data itu, Anda menyusun *use case* (skenario penggunaan), lalu menyaring tipe elevator yang tidak mampu memenuhi fungsi tersebut.

Jawaban singkatnya: jangan memilih “tipe penumpang” atau “tipe barang” hanya dari nama bangunan. Buat lembar kebutuhan yang memuat pengguna dan beban, pola perjalanan, kondisi sumur luncur (shaft) dan lingkungan, antarmuka bangunan, target aksesibilitas serta keadaan darurat, kemudian minta verifikasi kompeten sebelum solusi dipilih. Kesimpulan dapat berubah jika fungsi berubah—misalnya elevator yang semula untuk penghuni ternyata juga membawa troli, pasien, atau material selama renovasi.

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

Hasil yang dicari bukan sekadar satu nama produk, melainkan *ringkasan kebutuhan (requirement brief)* yang dapat dibandingkan antar-solusi. Dokumen itu sebaiknya menyebut tujuan layanan, batas ruang lingkup, asumsi yang masih terbuka, bukti yang sudah tersedia, dan orang yang berwenang menyetujui perubahan. Pemilik menetapkan tujuan dan anggaran tingkat program; perencana atau insinyur yang berkompeten menerjemahkannya menjadi persyaratan desain; operator memberi data operasi; dan pihak keselamatan dan kesehatan kerja (K3), bangunan, serta pemeliharaan menilai antarmuka masing-masing.

Prasyarat minimumnya adalah denah dan potongan bangunan yang terukur, fungsi setiap lantai, daftar calon pengguna, pola jam sibuk, jenis barang atau alat bantu yang ikut masuk, kondisi lingkungan, sumber listrik, jalur komunikasi, serta rencana penggunaan saat gangguan atau keadaan darurat. Jangan mengisi kolom yang belum diketahui dengan angka contoh. Tulis “belum tersedia” dan tetapkan siapa yang harus mengukurnya.

Kawan Elevator.co.id, bedakan tiga hal sejak awal: kebutuhan pengguna, persyaratan kinerja, dan bukti penerimaan. “Mudah diakses” adalah kebutuhan; lebar bukaan atau ruang manuver adalah persyaratan yang harus ditentukan oleh desain dan aturan yang berlaku; gambar terkoordinasi dan hasil pemeriksaan adalah bukti. Ketiganya tidak boleh diperlakukan sebagai sinonim.

## Langkah 1 — tetapkan ruang lingkup

Mulailah dengan kalimat fungsi: elevator ini menghubungkan lantai apa, untuk aktivitas apa, dan pada fase apa. Tandai apakah proyek berupa instalasi baru, penggantian, modernisasi, atau penggunaan sementara. Catat pula apa yang tidak termasuk, seperti desain struktur, perhitungan lalu lintas, detail kelistrikan, proteksi kebakaran, atau prosedur penyelamatan. Batas ini mencegah lembar kebutuhan berubah menjadi instruksi teknis tanpa data.

Petakan antarmuka: lubang dan sumur luncur (shaft), ruang bawah (pit) serta ruang atas, pintu lantai, struktur penyangga, ventilasi, listrik, jaringan komunikasi, sistem alarm, akses penyandang disabilitas, dan jalur evakuasi. Peraturan bangunan dan standar elevator harus diverifikasi terhadap edisi serta penerapan Indonesia yang relevan; catatan umum tentang elevator tidak cukup untuk menyimpulkan kepatuhan. ISO 8100-1:2026 sendiri perlu dibaca sesuai ruang lingkup lift dan tanggal instalasi yang nyata, bukan sekadar dijadikan label produk ([ISO 8100-1:2026](https://www.iso.org/standard/80553.html)).

Lakukan penyaringan risiko secara berulang: identifikasi bahaya, siapa yang terpapar, pengendalian yang sudah ada, tindakan tambahan, penanggung jawab, dan tanggal tinjau. ILO menekankan siklus penilaian dan pengendalian risiko yang disesuaikan dengan konteks, bukan matriks generik yang otomatis menentukan tingkat risiko ([panduan ILO pengendalian risiko](https://www.ilo.org/topics-and-sectors/occupational-safety-and-health-guide-labour-inspectors-and-other/how-can-occupational-safety-and-health-be-managed/controlling-risks); [panduan lima langkah ILO](https://www.ilo.org/publications/5-step-guide-employers-workers-and-their-representatives-conducting)).

## Langkah 2 — kumpulkan dan cocokkan bukti

Buat tabel sederhana dengan kolom “kebutuhan”, “sumber data”, “status verifikasi”, dan “konsekuensi jika tidak terpenuhi”. Untuk pengguna, tanyakan jumlah orang per perjalanan, kursi roda atau tandu, troli, kebiasaan membawa barang, dan kebutuhan pendamping. Untuk operasi, tanyakan jam sibuk, perjalanan berulang, akses publik, dan siapa yang boleh mengoperasikan atau memanggil unit. Untuk lingkungan, catat debu, kelembapan, suhu, lokasi luar ruang, risiko vandalisme, serta pekerjaan konstruksi yang berjalan bersamaan.

Selanjutnya cocokkan data bangunan dengan solusi: dimensi sumur luncur dan ruang bawah, ruang atas, titik berhenti, struktur, daya listrik, jalur kabel, pintu, dan akses perawatan. Gambar arsitektur atau brosur vendor hanya menjadi bahan awal sampai diukur dan dikoordinasikan. Beban nominal (rated load), ukuran kabin, atau hasil kalkulator lalu lintas tidak dengan sendirinya membuktikan kualitas layanan, kecukupan struktur, operasi kebakaran, aksesibilitas, atau penerimaan akhir; semua antarmuka itu memerlukan desain dan pengujian tersendiri ([PP No. 16 Tahun 2021](https://peraturan.bpk.go.id/Details/161846/pp-no-16); [katalog standar elevator ISO](https://www.iso.org/standard/73072.html)).

Periksa juga jejak bukti pemasok. Logo, foto sertifikat, klaim “sesuai standar”, atau ulasan marketplace tidak membuktikan model yang dikirim dan sistem yang terpasang benar-benar sesuai. Minta identitas model, ruang lingkup dokumen, tanggal, penerbit, batasan, serta cara menelusuri dokumen asli. Prinsip perlindungan konsumen menuntut informasi yang dapat dibandingkan dan tidak menyesatkan; jangan menjadikan satu lembar promosi sebagai keputusan teknis ([UU No. 8 Tahun 1999](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999)).

Untuk kompetensi, simpan peran, kewenangan, pelatihan, dan bukti pemeriksaan secara terpisah. Dokumen inspeksi lama atau stiker pemeliharaan bukan bukti lengkap bahwa unit saat ini layak digunakan. Status aturan dan rekaman pemeriksaan elevator harus diverifikasi pada teks yang berlaku, riwayat aset, personel berwenang, temuan, dan tindakan korektif ([Permenaker No. 6 Tahun 2017](https://peraturan.bpk.go.id/Home/Download/251564/Kemnaker%20No.%206%20Tahun%202017.pdf); [status Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026)).

## Langkah 3 — jalankan urutan kerja

Urutannya dapat dibuat seperti ini. Pertama, tulis skenario normal dan skenario terganggu: siapa naik, dengan beban apa, pada waktu kapan, serta apa yang terjadi ketika listrik atau komunikasi terganggu. Kedua, ubah skenario menjadi kriteria “wajib”, “diinginkan”, dan “tidak boleh”. Ketiga, eliminasi tipe yang gagal pada satu kriteria wajib sebelum membandingkan harga atau fitur tambahan.

Keempat, koordinasikan pilihan awal dengan arsitektur, struktur, listrik, kebakaran, aksesibilitas, operasi, dan pemeliharaan. Kelima, minta pemasok menjawab setiap kriteria dengan referensi dokumen, bukan jawaban ya/tidak tanpa batasan. Keenam, susun daftar asumsi dan buat *titik tahan keputusan (hold point)* untuk data yang belum terukur. Tautan katalog ISO 8100-20:2018 di sini hanya membantu mengenali dokumen yang perlu dibaca; artikel ini tidak merangkum klausul atau menyatakan kepatuhan berdasarkan halaman katalog tersebut ([ISO 8100-20:2018](https://www.iso.org/standard/73072.html)).

Jika fungsi berubah menjadi membawa pasien, material berbahaya, atau penggunaan publik intensif, hentikan pemilihan otomatis dan minta telaah disiplin yang sesuai. Jangan menyimpulkan bahwa tipe tertentu aman untuk evakuasi, paparan cuaca, gempa, atau penggunaan khusus hanya dari nama kategorinya.

## Titik berhenti dan kondisi berhenti

Pekerjaan harus berhenti pada tahap seleksi bila fungsi utama belum disepakati, ukuran dan kondisi bangunan belum terukur, jalur evakuasi atau operasi kebakaran belum dikoordinasikan, atau tidak ada pihak kompeten yang menerima persyaratan. Berhenti juga bila pemasok tidak dapat menunjukkan identitas model dan batas penggunaan, bila dokumen saling bertentangan, atau bila perubahan desain menghapus asumsi awal.

Teman Elevator.co.id, anggap “belum ada bukti” sebagai status nyata, bukan izin untuk meneruskan. Untuk risiko dengan konsekuensi tinggi, penilaian generik harus diganti metode dan persetujuan disiplin yang memadai. Rujukan keselamatan kerja nasional memberi dasar penting, tetapi kewajiban akhirnya bergantung pada tempat kerja, aktivitas, peralatan, dan aturan pelaksana yang berlaku ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970)).

## Verifikasi hasil dan serah terima

Sebelum ringkasan kebutuhan disahkan, lakukan pemeriksaan silang: setiap kebutuhan punya pemilik; setiap angka punya sumber pengukuran; setiap asumsi punya tanggal kedaluwarsa; setiap kriteria wajib punya cara uji atau inspeksi; dan setiap penyimpangan punya keputusan tertulis. Gunakan versi dokumen, daftar distribusi, serta rekaman perubahan agar tim bekerja dari basis yang sama. Tautan ISO 19011:2018 dan PP No. 50 Tahun 2012 di sini hanya menandai dokumen rujukan; penilaian audit, tinjauan, atau kepatuhan harus mengikuti teks dan kewenangan yang berlaku untuk proyek, bukan disimpulkan dari halaman katalog atau ringkasan ini ([ISO 19011:2018](https://www.iso.org/standard/70017.html); [PP No. 50 Tahun 2012](https://peraturan.bpk.go.id/Details/5263/pp-no-50-tahun-2012)).

Paket serah-terima minimum berisi ringkasan kebutuhan yang disetujui, gambar terkoordinasi, daftar model dan batas penggunaan, catatan pemeriksaan dan pengujian, manual operasi serta pemeliharaan, daftar temuan terbuka, kontak penanggung jawab, dan pemicu peninjauan ulang. Serahkan hanya dokumen yang memang boleh diakses; rekaman kesehatan, identitas, atau data pribadi perlu pengaturan akses dan dasar pemrosesan tersendiri. Setelah kebutuhan operasi jelas, Anda dapat menyiapkan percakapan lanjutan dengan penyedia [maintenance elevator di Yogyakarta](/maintenance-elevator-yogyakarta) atau [maintenance elevator di Tuban](/maintenance-elevator-tuban), dengan membawa ringkasan kebutuhan dan daftar bukti yang sama.

## Jalan pintas yang sering menyesatkan

Jalan pintasnya adalah memilih unit berdasarkan kapasitas dan harga terendah, lalu berharap detail lain dapat disesuaikan belakangan. Cara ini gagal ketika sumur luncur tidak cukup, pola pengguna berbeda dari asumsi vendor, aksesibilitas terlewat, atau pemeliharaan dan penyelamatan tidak memiliki antarmuka. Alternatif yang lebih andal adalah memakai kriteria wajib sebagai saringan pertama, meminta bukti yang dapat ditelusuri, dan menyimpan keputusan serta batasannya sebelum membandingkan biaya.

## Kesimpulan

Cara menentukan kebutuhan tipe elevator dan *use-case selection* adalah memulai dari fungsi dan risiko nyata, mengukurnya dalam persyaratan yang dapat diverifikasi, lalu menolak solusi yang gagal pada kriteria wajib. Langkah Anda berikutnya: jadwalkan lokakarya singkat lintas fungsi, bawa denah terukur dan skenario pengguna, isi daftar bukti serta asumsi, kemudian minta tinjauan teknis dan K3 sebelum meminta penawaran final.

Aturan operasinya sederhana: tidak ada model yang “pasti cocok” sebelum ruang lingkup, antarmuka, bukti, dan kewenangan persetujuan jelas. Jika salah satu masih kosong atau berubah, tandai `[NEEDS TECHNICAL REVIEW: verifikasi scope, standar yang berlaku, dan bukti penerimaan]` dan jangan mengubahnya menjadi kepastian.
