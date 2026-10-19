# 🏝️ Survival Pulau Akhlak KRN

Game **survival 3D** bergaya kotak-kotak untuk **Pendidikan Agama Islam & Budi Pekerti Kelas 3**
di **Kuttab Raudhah Nabawiyah (KRN)**. Materinya diambil dari RPP PAI Kelas 3 Tahun Pelajaran 2025/2026 (Pertemuan 1–21).

**Kuttab Raudhah Nabawiyah** · PKBM Raudhah Parenting Nabawiyah Bogor
Jl. Bima Raya Ujung No. 31, Cibuluh, Bogor Utara, Kota Bogor, Jawa Barat
Telp +62 812-7272-7938 · www.raudhahnabawiyah.id

## Cara bermain

Santri terdampar di **Pulau Akhlak** dan harus bertahan hidup sambil mengumpulkan **21 Gulungan Ayat**.

| Bilah | Artinya |
|---|---|
| ❤️ Hati | Berkurang jika disentuh bayangan sifat buruk. Pulih di dekat api unggun Kuttab. |
| 🍎 Kenyang | Berkurang seiring waktu. Makan apel, kurma, jeruk, atau pisang (muncul doa *Bismillah… Alhamdulillah*). |
| ✨ Cahaya | Dipakai untuk mengusir bayangan. Bertambah dengan menjawab soal gulungan dengan benar. |

- **Siang dan malam** berganti setiap 4 menit. Saat malam, muncul **bayangan sifat buruk**: Sombong, Suka Mengejek, Tamak Harta, Malas, Dengki, Menunda-nunda, Zalim, dan Kufur Nikmat. Setiap bayangan yang diusir menampilkan pelajaran dari ayatnya.
- Area **api unggun Kuttab** dan **Ka'bah** aman, karena bayangan tidak bisa masuk (sesuai Quraisy ayat 4: *"mengamankan mereka dari ketakutan"*).
- Setiap gulungan berisi ayat (Rasm Utsmani), murottal, arti, makna penting, nilai akhlak, tantangan di rumah, dan satu soal.
- Setelah semua ayat satu surat terkumpul, santri **menyusun hafalan** (mengurutkan ayat) di **Tugu Hafalan** untuk menyalakan apinya.
- Nyalakan **4 tugu** untuk menang dan mendapat **sertifikat** berlogo KRN.
- Pingsan tidak membuat progres hilang. Santri dibawa kembali ke Kuttab.

## Empat wilayah

| Wilayah | Surat | Pertemuan |
|---|---|---|
| 🐫 Jalur Kafilah Quraisy (tenda, pasar, kafilah unta) | Quraisy | 1–4 |
| 🐘 Lembah Pasukan Gajah (pasukan gajah, burung Ababil) | Al-Fil | 5–9 |
| 💰 Lembah Harta (tumpukan emas, tiang-tiang panjang, gunung api) | Al-Humazah | 10–18 |
| ⏳ Menara Waktu (menara jam, jam pasir raksasa, jam matahari) | Al-'Ashr | 19–21 |

## Kontrol

| Aksi | Laptop | HP / Tablet |
|---|---|---|
| Berjalan | W A S D / panah | Geser jempol di sisi kiri layar |
| Kamera | Seret mouse, scroll untuk zoom | Geser di sisi kanan layar |
| Lompat | Spasi | Tombol ⤒ |
| Cahaya kebaikan | F | Tombol ✨ |
| Baca gulungan / susun hafalan | E | Tombol kuning |
| Buku ayat / peta | B / M | 📖 / 🗺️ |

Disarankan memegang HP dalam posisi mendatar. Progres tersimpan otomatis di perangkat.

## Cara upload ke GitHub Pages

1. Buka [github.com](https://github.com) → **New repository** → beri nama, misalnya `krn-survival` → **Public** → **Create repository**.
2. Klik **uploading an existing file**, seret `index.html` dan `README.md`, lalu **Commit changes**.
3. Buka **Settings → Pages** → *Source*: **Deploy from a branch** → branch **main**, folder **/ (root)** → **Save**.
4. Setelah 1–2 menit, game bisa dibuka di `https://NAMA-AKUN.github.io/krn-survival/`.

Game membutuhkan internet saat pertama dibuka (untuk mesin 3D three.js). Logo dan font Al-Qur'an sudah tertanam di dalam file.

## Mengubah isi

- Materi ada di `const SCROLLS=[` di dalam `index.html` (arti, makna, nilai, tugas, dan soal per pertemuan).
- Daftar sifat buruk dan pesannya ada di `const VICES=[`.
- Alamat sekolah tertulis di menu, papan nama Kuttab (fungsi `signTexture`), dan sertifikat. Cari teks `Jl. Bima Raya` untuk mengubahnya.

## Kredit

- Materi: RPP PAI Kelas III KRN 2025/2026 (Muhammad Dony Purnama, S.Pd.).
- Teks Al-Qur'an: data Tanzil (paket `quran-json`). Font: Amiri Quran (SIL OFL), Fredoka.
- Mesin 3D: three.js. Murottal: Syaikh Mishary Alafasy (everyayah.com).
- Game bergaya kotak-kotak buatan sendiri, tidak berafiliasi dengan Roblox.
