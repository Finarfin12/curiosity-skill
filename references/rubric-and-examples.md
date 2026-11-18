# Rubrik dan contoh

Baca file ini saat menyusun ringkasan, menilai sumbu yang meragukan, atau butuh contoh pola metode.

## Definisi skor (0–3, terbatas pada topik/tugas)

| Sumbu | 0 | 1 | 2 | 3 |
| --- | --- | --- | --- | --- |
| Recall (R) | Salah pada soal yang dicoba | Ingat sebagian dengan bantuan | Ingat akurat secara mandiri | Ingat akurat dalam berbagai bentuk |
| Explanation (E) | Tidak ada mekanisme/alasan | Penjelasan terpotong | Penjelasan runtut atas alasan kunci | Menjelaskan batas dan contoh penyangkal |
| Procedure (P) | Tidak bisa mengerjakan | Mengerjakan sebagian/dengan bantuan | Mengerjakan benar secara mandiri | Memilih dan mengecek metode dengan luwes |
| Transfer (T) | Belum tampak | Butuh banyak petunjuk | Benar di konteks baru secara mandiri | Menjelaskan adaptasi dan batasnya |
| Retention (D) | Salah pada soal setelah jeda | Ingat setelah jeda dengan bantuan | Ingat mandiri setelah jeda | Berulang kali ingat di konteks berbeda |

`not_tested` bukan 0. Kekuatan bukti naik bila soal baru (bukan salinan contoh), dikerjakan mandiri, cakupannya luas. Keyakinan diri pengguna dicatat terpisah dari penilaian kinerja.

## Format ringkasan (`ringkas`)

```
Tujuan: menjumlahkan pecahan beda penyebut dan menjelaskan alasannya.

Sudah terbukti
- Explanation 2: kamu menjelaskan bahwa penyebut harus sama karena potongannya harus seukuran.
- Procedure 2: 1/4 + 2/3 = 11/12 dikerjakan tanpa petunjuk.
- Transfer 1: soal resep (3/4 gelas + 1/3 gelas) benar setelah satu petunjuk.

Belum diuji
- Retention: perlu dicek setelah jeda.

Yang diperbaiki
- Awalnya 1/2 + 1/3 = 2/5 (dugaan: salah konsep tentang penyebut), sudah diperbaiki lewat gambar pizza.

Ulangan yang disarankan: coba 2 soal lagi besok tanpa melihat catatan.
Penasaran berikutnya: kenapa membagi pecahan sama dengan mengalikan kebalikannya?
```

Contoh di atas ilustrasi, bukan data nyata.

## Contoh pola dialog

**1. Pemula bingung → ajari dulu**
User: "aku nggak ngerti pecahan sama sekali"
Baik: penjelasan pendek (pizza dipotong 4, ambil 1 = 1/4), satu gambar sederhana, lalu satu cek: "Kalau dipotong 8 dan kamu ambil 3, pecahannya berapa?"
Buruk: "Menurutmu apa itu pecahan?" lalu Devil's Advocate.

**2. Teach-back fasih tapi salah → Feynman**
User: "1/2 sama dengan 3/6 karena 3 itu setengah dari 6, jadi semua angka setengah sama."
Baik: akui bagian yang benar, tunjuk celah ("semua angka setengah" tidak tepat; yang penting perbandingannya), beri 1/2 vs 2/3 sebagai cek, minta versi revisi.
Buruk: "Bagus, kamu sudah paham!"

**3. Teach-back akurat → penerapan**
Lanjut ke soal baru mandiri. Jangan tandai Transfer atau Retention sebagai terbukti.

**4. Asumsi keliru → Socratic satu pertanyaan**
"Kalau 1/2 pizza ditambah 1/3 pizza, apakah potongannya seukuran?"

**5. Dasar kuat → Devil's Advocate**
"Temanmu bilang 1/2 + 1/3 = 2/5. Bagaimana kamu membuktikan dia salah tanpa rumus?"

**6. User minta jawaban → langsung jelaskan**
"jelaskan" berarti solusi lengkap langkah demi langkah, lalu tawarkan (tidak wajib) satu soal serupa.

**7. Klaim empiris → evaluasi bukti**
"Latihan mengingat lebih efektif daripada membaca ulang." Cari sumber bila alat tersedia (misalnya Roediger & Karpicke 2006; Dunlosky dkk. 2013). Tanya: apa yang diukur, dibandingkan dengan apa, berlaku untuk siapa.

**8. Minta sitasi yang tidak bisa diverifikasi**
Katakan terus terang bahwa sumber belum bisa diverifikasi. Jangan mengarang judul, penulis, atau tautan.

**9. Klaim matematika**
Minta derivasi atau contoh penyangkal, bukan kutipan jurnal.

**10. Stop/lewati/simpan**
Patuhi seketika. Untuk `simpan`, tanyakan tujuan dan tunggu izin sebelum menulis ke mana pun.
