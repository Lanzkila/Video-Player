# 🎬 Kirin Video Player V6 (Multi-Screen)

**Kirin Video Player** adalah aplikasi pemain video berasaskan web yang menyokong fungsi **Multi-Screen**. Ia direka untuk pengguna yang ingin menonton pelbagai sumber video (YouTube, Twitch, Bilibili, Kick, dll) secara serentak dalam satu paparan.

## ✨ Ciri-Ciri Utama
* **Multi-Layout Support:** Pilih antara mod 1 Skrin, 2 Skrin (Dual), atau 4 Skrin (Quad).
* **Cross-Platform Compatibility:** Sokongan penuh untuk:
  - **YouTube** (Embed Player)
  - **Twitch** (Live Stream dengan fix Parent Domain)
  - **Bilibili** (High Quality Support)
  - **Kick** (Live Streaming)
  - **Direct MP4** (Menggunakan engine Video.js)
* **Smart Input:** Logik automatik yang mengesan jenis link dan menukarnya kepada format iframe yang betul.
* **Responsive Grid:** Paparan grid yang kemas dan berubah mengikut saiz skrin (PC/Tablet/HP).
* **Hotkeys:** Sokongan kunci `Enter` untuk proses link dan `Space` untuk play/pause (pada mod MP4).

## 🛠️ Cara Penggunaan
1.  Buka aplikasi melalui GitHub Pages.
2.  Pilih mod skrin yang kau mahu (1, 2, atau 4).
3.  *Paste* link video ke dalam kotak input dan tekan **Enter** atau butang Play.
4.  Video akan dimuatkan ke dalam slot yang aktif secara bergilir-gilir.
5.  Tekan butang **"×"** untuk mengosongkan kotak input dengan cepat.

## 💻 Pemasangan
1.  *Fork* repo ini.
2.  Pastikan fail `index.html` berada di root folder.
3.  Aktifkan **GitHub Pages** di bahagian Settings.
4.  Aplikasi anda sedia digunakan di `https://username.github.io/Video-Player/`.

## 📦 Tech Stack
* **HTML5 / CSS3** (Custom Grid System)
* **JavaScript** (Dynamic Iframe Logic)
* **Video.js** (Untuk pemain video tempatan/MP4)

---

> **Nota:** Untuk video Twitch, sistem akan secara automatik mengesan domain GitHub Pages anda untuk melepasi sekatan *Parent Domain*.

Dibuat dengan 🔥 oleh **Lanz**.
