---
article_id: ELV-03-05
title: "Tahapan Pekerjaan Traffic analysis, capacity, speed, quantity, and service performance: Persiapan, Pelaksanaan, dan Kontrol Mutu"
slug: "tahapan-pekerjaan-traffic-analysis-capacity-speed-quantity-and-service-performance-persiapan-pelaksanaan-dan-kontrol-mutu"
description: "Panduan memeriksa kesiapan data, mengikuti tahapan analisis lalu lintas lift, mengenali titik kritis, dan menghentikan pekerjaan yang belum memenuhi prasyarat."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-05-16"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: ELV-03
primary_intent: "Memahami urutan kerja, dependensi, hold point, dan pemeriksaan mutu Traffic analysis, capacity, speed, quantity, and service performance."
reader_community: "Elevator.co.id"
reader_address: "Teman Elevator.co.id"
final_route: "/artikel/tahapan-pekerjaan-traffic-analysis-capacity-speed-quantity-and-service-performance-persiapan-pelaksanaan-dan-kontrol-mutu.html"
technical_review: required
sources:
  - "https://www.ilo.org/topics-and-sectors/occupational-safety-and-health-guide-labour-inspectors-and-other/how-can-occupational-safety-and-health-be-managed/controlling-risks"
  - "https://www.ilo.org/publications/5-step-guide-employers-workers-and-their-representatives-conducting"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.pu.go.id/detail-dokumen/PermenPUPR-nomor-10-tahun-2021-Pedoman-Sistem-Manajemen-Keselamatan-Konstruksi"
  - "https://peraturan.bpk.go.id/Details/161846/pp-no-16"
writer_execution:
  role: "portfolio_article_writer"
  requested_model: "gpt-5.6-luna"
  requested_effort: "medium"
  requested_tier: "default"
  verified_model: "unverified"
  verified_effort: "unverified"
  effective_tier: "unverified"
  host: "windows"
  account: "unverified"
  escalation_reason: "none"
  skills:
    - name: "delegate-with-skills"
      source: "C:\Users\THINKPAD\.codex\skills\delegate-with-skills\SKILL.md"
      sha256: "5e8f8417911616d8fcb478ed9defe0c74f08bd48542012c161f7bfe7e26dc039"
    - name: "write-portfolio-articles"
      source: "C:\Users\THINKPAD\OneDrive\MD\skills\write-portfolio-articles\SKILL.md"
      sha256: "307847bf32194acf20c1abd251a868d162a4c741077a7f7be6cc8e7a82b709f7"
    - name: "native-article-leaf-receipts"
      source: "C:\Users\THINKPAD\.codex\skills\native-article-leaf-receipts\SKILL.md"
      sha256: "b698b23146daee880c996e629349e12c2d69fe7a3f7426779139ca1b9adf05ca"
---

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

# Tahapan Pekerjaan Traffic analysis, capacity, speed, quantity, and service performance: Persiapan, Pelaksanaan, dan Kontrol Mutu

Halo, Teman Elevator.co.id! Saat pemilik gedung meminta analisis lalu lintas lift, pertanyaan “berapa unit dan seberapa cepat?” sering muncul lebih dulu. Padahal keputusan pentingnya adalah apakah data pemakaian, kondisi bangunan, tujuan layanan, dan cara pengujiannya sudah disepakati. Jika belum, angka yang terlihat rapi dapat mengarahkan pengadaan dan penerimaan ke masalah yang sama.

Jawaban singkatnya: tetapkan tujuan dan batas, kumpulkan data yang dapat ditelusuri, jalankan metode yang disetujui, lalu uji dan serahkan hasil dengan rekaman mutu. Perubahan fungsi gedung, denah, konfigurasi, atau kriteria penerimaan dapat mengubah kesimpulan. Panduan ini membantu pemilik, pengawas, dan pelaksana menyelaraskan pekerjaan; bukan pengganti metode kerja proyek atau tenaga kompeten.

![Ilustrasi jasa maintenance elevator](/wp-content/uploads/2020/07/jasa-maintenance-elevator.png)

Ilustrasi umum dari aset lokal proyek; bukan dokumentasi proyek tertentu.

## Hasil dan prasyarat yang harus disepakati

Bagian ini menjelaskan keluaran agar analisis tidak berhenti sebagai lembar angka. Traffic analysis adalah kajian pola kedatangan, waktu tunggu, kapasitas angkut, kecepatan perjalanan, jumlah unit, dan mutu layanan berdasarkan ukuran yang disetujui. Tulis ringkasan asumsi, model, batas penggunaan, serta pemilik keputusan. ILO menganjurkan siklus mengenali risiko, menilai, memilih pengendalian, dan meninjau ulang ([pengendalian risiko](https://www.ilo.org/topics-and-sectors/occupational-safety-and-health-guide-labour-inspectors-and-other/how-can-occupational-safety-and-health-be-managed/controlling-risks); [panduan lima langkah](https://www.ilo.org/publications/5-step-guide-employers-workers-and-their-representatives-conducting)). Itu bukan penilaian risiko lengkap untuk proyek tertentu.

Data awal sekurang-kurangnya memuat fungsi bangunan, jam sibuk yang diuji, jumlah lantai, pola pengguna, aksesibilitas, konfigurasi lift, denah, potongan, daya, dan ruang tersedia. Tandai mana yang diukur, berasal dari gambar, atau masih asumsi. Kriteria penerimaan harus menyebut pengamat, sumber data, periode, toleransi, dan tindakan bila hasil tidak memenuhi. [NEEDS REVIEW: data lalu lintas aktual dan kriteria penerimaan proyek belum tersedia di packet ini.]

## Langkah 1 — tetapkan batas kajian dan antarmuka

Sebelum menghitung, tetapkan objek, lantai yang dilayani, pola operasi, kondisi normal, serta pengecualian. Capacity berarti kemampuan angkut dalam kondisi tertentu; speed memengaruhi perjalanan tetapi tidak sendirian menentukan waktu tunggu; quantity adalah jumlah unit; service performance adalah mutu layanan menurut ukuran yang disepakati. Istilah tersebut harus dibaca bersama, bukan dipilih dari brosur secara terpisah.

Catat siapa menyediakan denah, mengonfirmasi penggunaan, merekam operasi, dan menyetujui perubahan. Angka kapasitas tidak otomatis membuktikan struktur, keselamatan kebakaran, aksesibilitas, atau kepatuhan. PP 16/2021 menjadi salah satu rujukan penyelenggaraan bangunan, tetapi penerapan tetap bergantung pada proyek dan aturan yang berlaku ([PP 16/2021](https://peraturan.bpk.go.id/Details/161846/pp-no-16)). Pedoman keselamatan konstruksi juga menekankan antarmuka pemilik, perancang, kontraktor, dan pengawas ([pedoman SMKK](https://jdih.pu.go.id/detail-dokumen/PermenPUPR-nomor-10-tahun-2021-Pedoman-Sistem-Manajemen-Keselamatan-Konstruksi)).

## Langkah 2 — cocokkan dokumen, lapangan, dan data operasi

Lapis pertama bukti adalah denah, spesifikasi, daftar unit, dan catatan perubahan. Lapis kedua adalah kondisi lapangan: akses lantai, pintu, ruang tunggu, jam penggunaan, dan hambatan. Lapis ketiga adalah data operasi seperti panggilan, perjalanan, waktu pintu, muatan, atau observasi dengan metode yang dicatat. Ketiganya harus menunjuk objek dan versi yang sama. Jika gambar menyebut dua unit tetapi satu yang aktif, hentikan penggabungan angka dan minta klarifikasi.

Simpan sumber, tanggal, pemilik, dan keputusan akses. Gunakan identitas agregat bila nama atau rekaman pribadi tidak diperlukan. Jangan menganggap tangkapan layar sertifikat atau klaim pemasok sebagai bukti lengkap untuk model terpasang. [NEEDS REVIEW: klasifikasi data, masa simpan, dan persetujuan akses mengikuti kebijakan proyek serta tinjauan hukum/privasi.]

## Langkah 3 — jalankan model, pengamatan, dan pemeriksaan mutu

Masukkan data dasar, pilih metode perhitungan atau simulasi yang disetujui, lalu tulis satuan, periode, pembulatan, dan batas berlaku. Uji skenario yang relevan, misalnya perubahan jam sibuk atau penutupan satu lantai. Jangan mengarang nilai performa atau toleransi; tandai hasil yang masih perkiraan dan simpan versi model.

Lakukan pengamatan dengan prosedur yang sama, catat kondisi saat pengukuran, dan cocokkan catatan dengan data sistem bila tersedia. Pemeriksa harus dapat menelusuri angka kembali ke sumbernya. Temuan berbeda dicatat sebagai pertanyaan terbuka, bukan dirata-ratakan untuk menghilangkan perbedaan.

Setiap versi model, data, hasil, catatan observasi, komentar pemeriksa, dan keputusan perubahan diberi nama serta tanggal. UU No. 1 Tahun 1970 menempatkan penerapan keselamatan pada kondisi tempat kerja dan kegiatannya, sehingga satu templat tidak otomatis membuktikan kecukupan semua proyek ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970)).

## Titik berhenti sebelum pekerjaan diteruskan

Teman Elevator.co.id, hentikan tahap berikutnya bila objek yang dihitung tidak cocok dengan lapangan, data penting hilang, asumsi berubah tanpa persetujuan, metode pengukuran tidak diketahui, atau hasil hendak dipakai di luar batas kajian. Tanyakan: apakah denah dan konfigurasi sudah disetujui, periode pengamatan tercatat, perubahan fungsi masuk model, dan kriteria penerimaan memiliki pemilik? Kondisi berkonsekuensi tinggi memerlukan tinjauan tenaga kompeten dan dokumen proyek lengkap.

## Verifikasi hasil dan serah-terima

Paket penerimaan berisi tujuan dan batas kajian, daftar input beserta sumber, versi model, asumsi disetujui, hasil per skenario, penyimpangan, kriteria penerimaan, daftar terbuka, dan pihak yang menyetujui. Pembaca dapat melihat [layanan pemeriksaan lift](/jasa-service-lift-4/) sebagai jalur menghubungi penyedia yang relevan, bukan bukti bahwa pekerjaan tertentu sudah sesuai. Tetapkan pemicu tinjauan ulang ketika fungsi, lantai, konfigurasi, atau kriteria berubah.

Serah-terima yang rapi juga menjelaskan apa yang belum bisa disimpulkan. Hasil simulasi bukan catatan operasi aktual; observasi satu periode bukan gambaran semua musim; dan angka dari pemasok bukan verifikasi pemasangan. Minta pihak penerima menandatangani daftar asumsi, bukan hanya halaman kesimpulan. Jika ada catatan terbuka, beri pemilik dan tenggat yang realistis, lalu simpan bukti penutupnya pada versi berikutnya. Cara ini membuat perubahan dapat dilacak tanpa menghapus riwayat dan membantu tim baru memahami alasan keputusan lama.

Untuk pekerjaan lanjutan, pisahkan permintaan pemeriksaan dari kajian layanan. [Jadwal layanan lift](/jasa-service-lift-3/) dapat menjadi percakapan berikutnya tentang kondisi aset, tetapi pembaca tetap perlu memberikan identitas unit, riwayat perubahan, dan tujuan pemeriksaan. Jangan menjadikan tautan layanan sebagai pengganti kriteria teknis atau persetujuan proyek.

## Jalan pintas yang sering menyesatkan

Menyalin angka gedung lain terasa cepat, tetapi jumlah pengguna, pola kedatangan, jarak perjalanan, tata letak, dan aturan operasi bisa berbeda. Struktur dokumen boleh dipinjam; data, asumsi, dan kriteria harus diisi ulang untuk gedung yang sedang dikaji. Tandai bagian yang belum terukur dan buat keputusan bersyarat agar pengawas dapat menghentikan tahap yang belum siap.

## Kesimpulan

Tahapan pekerjaan analisis lalu lintas lift dimulai dari tujuan dan batas, dilanjutkan bukti yang cocok dengan lapangan, model dengan asumsi terlihat, pengujian yang dapat diulang, lalu kontrol mutu dan serah-terima. Kriteria penerimaan dan data aktual tetap menjadi penentu. Kawan Elevator.co.id, minta paket data awal, pemilik keputusan, dan kriteria tertulis sebelum menyetujui perhitungan. Aturan operasinya: jangan menerima angka yang tidak dapat ditelusuri ke kondisi, metode, dan keputusan yang menyetujuinya.
