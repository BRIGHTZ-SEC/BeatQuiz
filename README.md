<div align="center">

# 🎵 BeatQuiz!

**Ultimate Music Knowledge Battle**

Tebak artis dari judul lagu dengan sistem streak, multiplier skor, dan 3 mode permainan yang bikin nagih!

[![Live Demo](https://img.shields.io/badge/▶%20Live%20Demo-Play%20Now-f59e0b?style=for-the-badge)](https://brightz-sec.github.io/BeatQuiz)
[![GitHub Repo](https://img.shields.io/badge/GitHub-BRIGHTZ--SEC%2FBeatQuiz-181717?style=for-the-badge&logo=github)](https://github.com/BRIGHTZ-SEC/BeatQuiz)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-34d399?style=flat-square)
![Single File](https://img.shields.io/badge/Build-Single%20File-a78bfa?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-f472b6?style=flat-square)

</div>

---

## 📸 Preview

```
┌─────────────────────────────────────────────────────────┐
│  BEAT QUIZ !          Ultimate Music Knowledge Battle    │
│                                                          │
│   HighScore: 0    Played: 0    Accuracy: 0%              │
│                                                          │
│   [ 🎵 Normal ]   [ ⚡ Rush ]   [ 🌊 Chill ]            │
│                                                          │
│              [ MULAI GAME ]                              │
└─────────────────────────────────────────────────────────┘
```

---

## 🎮 Cara Main

1. Pilih mode permainan di menu utama
2. Judul lagu akan muncul beserta hint album & tahun
3. Pilih 1 dari 4 artis yang tersedia
4. Jawab secepat mungkin untuk dapat bonus poin
5. Bangun streak untuk unlock score multiplier
6. Lihat grade dan score breakdown di akhir game

---

## 🕹️ Mode Permainan

| Mode | Waktu/Soal | Nyawa | Cocok Untuk |
|---|---|---|---|
| 🎵 **Normal** | 15 detik | 3 nyawa | Pemula, santai |
| ⚡ **Rush** | 8 detik | 1 nyawa | Hardcore, adrenalin |
| 🌊 **Chill** | 30 detik | ∞ | Fokus akurasi & streak |

---

## 💯 Sistem Skor

### Perhitungan Poin
```
Base score     = 100 pts
Time bonus     = +0 hingga +50 pts (makin cepat makin gede)
Streak x2      = streak 3–4 → semua poin × 2
Streak x3      = streak 5+  → semua poin × 3
Salah/Timeout  = 0 pts + kehilangan 1 nyawa
```

### Grade Akhir
| Grade | Threshold | Keterangan |
|---|---|---|
| **S** | Akurasi ≥ 90% | 👑 GACOR! |
| **A** | Akurasi ≥ 75% | 🏆 KEREN BANGET! |
| **B** | Akurasi ≥ 60% | 🎵 LUMAYAN NIH! |
| **C** | Akurasi ≥ 40% | 😅 BELAJAR LAGI! |
| **D** | Akurasi < 40%  | 💀 WKWKWK GAS LAGI! |

---

## 🎤 Daftar Lagu (22 Lagu · 8 Artis)

<details>
<summary><b>🔵 Justin Bieber — 5 lagu</b></summary>

| Judul | Keterangan |
|---|---|
| Baby | feat. Ludacris · 2010 |
| Love Yourself | Purpose Album · 2015 |
| Sorry | Purpose Album · 2015 |
| Peaches | feat. Daniel Caesar · 2021 |
| Ghost | Justice Album · 2021 |

</details>

<details>
<summary><b>🟢 Billie Eilish — 5 lagu</b></summary>

| Judul | Keterangan |
|---|---|
| bad guy | WHEN WE ALL FALL ASLEEP · 2019 |
| Happier Than Ever | Album 2021 |
| lovely | feat. Khalid · 2018 |
| Ocean Eyes | Debut single · 2016 |
| Therefore I Am | Single · 2020 |

</details>

<details>
<summary><b>🩷 Juice WRLD — 5 lagu</b></summary>

| Judul | Keterangan |
|---|---|
| Lucid Dreams | Goodbye & Good Riddance · 2018 |
| All Girls Are the Same | Debut album · 2018 |
| Robbery | Death Race for Love · 2019 |
| Righteous | Legends Never Die · 2020 |
| Come & Go | feat. Marshmello · 2020 |

</details>

<details>
<summary><b>🟡 Artis Indonesia — 7 lagu</b></summary>

| Judul | Artis | Keterangan |
|---|---|---|
| Hati-Hati di Jalan | Tulus | Album Manusia · 2022 |
| Bunga | Tulus | Album Gajah · 2014 |
| Ruang Sendiri | Tulus | Album Monokrom · 2017 |
| Mungkin Hari Ini Esok Atau Nanti | Rizky Febian | Single · 2019 |
| Mantra Cinta | Rizky Febian | Single · 2021 |
| Tentang Rindu | Virgoun | Single · 2017 |
| Salah Apa Aku | Judika | Single · 2019 |
| Kita Biasa | Tiara Andini | Debut Single · 2020 |

</details>

> Setiap game mengambil **12 soal secara acak** dari pool 22 lagu — jadi setiap sesi selalu terasa berbeda!

---

## ✨ Fitur

- **Animated particle network** — background canvas yang hidup dan terus bergerak
- **Streak multiplier system** — combo x2 dan x3 buat yang lagi on fire
- **Timer visual** — warna berubah putih → kuning → merah berkedip saat waktu mepet
- **Score breakdown** — detail tiap soal (benar / salah / timeout) di layar hasil
- **Persistent stats** — highscore, jumlah game, dan akurasi tersimpan via `localStorage`
- **Confetti system** — meledak saat streak 3+ atau dapat grade A ke atas
- **Fully responsive** — skala otomatis via CSS `clamp()` di semua ukuran layar
- **Zero dependency** — murni HTML/CSS/JS, tidak butuh Node.js, bundler, atau framework apapun

---

## 🚀 Instalasi & Penggunaan

### Cara 1 — Clone & Buka Langsung
```bash
git clone https://github.com/BRIGHTZ-SEC/BeatQuiz.git
cd BeatQuiz

# Buka file-nya:
open BeatQuiz.html        # macOS
start BeatQuiz.html       # Windows
xdg-open BeatQuiz.html    # Linux
```

### Cara 2 — GitHub Pages
1. Fork repo ini ke akun kamu
2. Masuk **Settings → Pages**
3. Source: pilih branch `main`, folder `/ (root)`
4. Klik **Save** → tunggu sekitar 1 menit
5. Akses di `https://username.github.io/BeatQuiz`

---

## 🏗️ Struktur Proyek

```
BeatQuiz/
├── BeatQuiz.html   ← Seluruh game dalam satu file
└── README.md         ← Dokumentasi ini
```

> Semua logika game, styling, data lagu, dan animasi ter-embed dalam **satu file HTML**. Tidak ada build step, tidak ada install — download dan langsung main.

---

## 🛠️ Cara Tambah Lagu Baru

Buka `BeatQuiz.html`, cari array `SONGS`, dan tambahkan entry baru:

```javascript
const SONGS = [
  // ... lagu yang sudah ada ...

  // Tambahkan di sini:
  {
    title: "Nama Lagu",
    artist: "Nama Artis",          // harus sama persis dengan entry di ALL_ARTISTS
    hint: "Info Album • Tahun",
    color: "#hex_warna",           // warna dot badge artis
    img: "https://url-cover.jpg"   // URL gambar cover album
  }
];
```

Kalau artisnya belum ada, tambahkan juga ke `ALL_ARTISTS`:

```javascript
const ALL_ARTISTS = [
  "Justin Bieber", "Billie Eilish", "Juice WRLD",
  "Tulus", "Rizky Febian", "Virgoun", "Judika", "Tiara Andini",
  "Artis Baru Kamu"   // ← tambahkan di sini
];
```

---

## 🎨 Kustomisasi Warna

Semua warna dikelola lewat CSS variables di `:root` — tinggal ganti satu tempat:

```css
:root {
  --gold:   #f59e0b;   /* aksen utama, skor, timer */
  --purple: #a78bfa;   /* progress bar, background glow */
  --green:  #34d399;   /* jawaban benar, streak */
  --red:    #f87171;   /* jawaban salah, nyawa habis */
  --blue:   #60a5fa;   /* badge Justin Bieber & Judika */
  --pink:   #f472b6;   /* badge Juice WRLD & Tiara Andini */
  --bg:     #06060f;   /* background utama */
}
```

---

## 🗺️ Roadmap

- [ ] Tambah kategori artis baru (K-Pop, OPM, Rock Indonesia)
- [ ] Mode **Tebak Lirik** — tampilkan penggalan lirik, tebak judulnya
- [ ] Leaderboard online via Supabase atau Firebase
- [ ] Efek suara — SFX benar, salah, countdown, dan streak
- [ ] Animasi transisi slide antar soal
- [ ] Import data lagu dari file JSON eksternal
- [ ] Mode multiplayer lokal — giliran antar pemain di satu perangkat
- [ ] Filter kategori — pilih mau quiz artis mana aja sebelum mulai

---

## 🤝 Kontribusi

Pull request sangat welcome! Untuk perubahan besar, buka issue dulu ya.

```bash
# 1. Fork repo ini lewat GitHub

# 2. Clone fork kamu
git clone https://github.com/BRIGHTZ-SEC/BeatQuiz.git

# 3. Buat branch baru
git checkout -b fitur/nama-fitur-keren

# 4. Commit perubahan
git commit -m "feat: tambah fitur keren"

# 5. Push ke branch
git push origin fitur/nama-fitur-keren

# 6. Buka Pull Request ke repo utama
```

---

## 📄 Lisensi

Distributed under the **MIT License** — bebas dipakai, dimodifikasi, dan didistribusikan selama ada atribusi.

---

<div align="center">

Made for michie and erine by [BRIGHTZ-SEC](https://github.com/BRIGHTZ-SEC)

**[⭐ Star repo ini kalau suka!](https://github.com/BRIGHTZ-SEC/BeatQuiz)**

</div>
