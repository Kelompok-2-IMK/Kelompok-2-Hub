# 📚 Kelompok 2 - Project IMK 2026
> **Focus:** SDG 4 - Quality Education (Indicator 4.6)  
> **Mission:** Enhancing Literacy through Immersive Technology.

---

## 📌 Project Overview
Repository ini merupakan **Central Hub** untuk manajemen proyek, dokumentasi, dan pemantauan progres aplikasi Interaksi Manusia Komputer (IMK) Kelompok 2. Kami berfokus pada pengembangan literasi (membaca dan menulis) dengan memanfaatkan teknologi **Augmented Reality (AR)**.

### 🎯 SDG Target: Quality Education (4.6)
*"By 2030, ensure that all youth and a substantial proportion of adults, both men and women, achieve literacy and numeracy."*
<img width="1161" height="332" alt="image" src="https://github.com/user-attachments/assets/56d2903a-a2ae-4b47-80a6-38b09729958d" />

Aplikasi ini dirancang untuk mengatasi hambatan belajar konvensional dengan menyediakan pengalaman visual yang interaktif dalam mempelajari mekanika penulisan karakter.

---

## 👥 The Team

| Name | Student ID | Primary Role |
| :--- | :---: | :--- |
| **Ammara Azwadiena** | 140810230073 | Scrum Master / QA |
| **Senia Nur Hasanah** | 140810230021 | 3D Design & Animator |
| **Siti Nailah Putri Eko A.** | 140810230058 | 3D Design & Animator |
| **Martha Meslina Florencia** | 140810230037 | Unity Developer |
| **Aidan Ismail** | 140810230075 | Unity Developer |

---

## 💡 Concept Evolution

### **The Initial Idea**
Membuat kartu fisik alfabet yang saat di-scan menggunakan AR akan memunculkan objek 3D beserta animasi *stroke-by-stroke* (urutan goresan) cara menulis karakter tersebut.

### **The Current Pivot (Post-Consultation)**
Menanggapi masukan bahwa ide awal terlalu sederhana untuk proyek berdurasi 6 bulan dengan tim 5 orang, kami sedang mengevaluasi peningkatan kompleksitas pada aspek:
* **Interactive Feedback:** Sistem yang dapat mendeteksi apakah pengguna mengikuti goresan dengan benar secara *real-time*.
* **Card Combination System (Word Synthesis):** Fitur utama di mana aplikasi dapat mendeteksi dua atau lebih marker kartu sekaligus. 
    * *Contoh:* Jika kartu **"Ku"** dan kartu **"da"** diletakkan berdampingan, AR akan memunculkan objek visual **"Kuda"** beserta suara/pelafalannya.
* **Multi-Language/Script Support:** Penjajakan ke karakter yang lebih kompleks (seperti Aksara atau Hanzi).

---

## 🚀 Key Features 
Aplikasi ini mengintegrasikan lima fitur utama yang dirancang untuk memaksimalkan retensi memori pengguna melalui keterlibatan visual, auditori, dan kinestetik:

### 1. Smart Stroke Visualization (AR Animation)
Fitur ini mengatasi kesulitan utama dalam mempelajari aksara non-latin (seperti Hanzi).
* **Step-by-Step Guide:** Animasi 3D yang menunjukkan urutan goresan yang benar secara perlahan di atas kartu fisik.
* **Directional Arrows:** Indikator panah transparan yang menunjukkan arah tarikan garis (atas ke bawah, kiri ke kanan).

### 2. Contextual 3D Visualizer
Meningkatkan pemahaman semantik dengan menghubungkan simbol abstrak dengan objek nyata.
* **Dynamic Spawning:** Saat kartu "Māo" (Kucing) terdeteksi, model 3D kucing akan muncul dengan animasi *idle* (seperti bernapas atau mengeong).
* **Pinyin & Tone Support:** Teks melayang (Floating UI) yang menampilkan cara baca beserta tanda nadanya.

### 3. Native Audio Phonics
Melatih pelafalan yang akurat melalui *Audio Feedback*.
* **Pronunciation Button:** Tombol virtual AR yang jika ditekan akan memutar suara penutur asli (*Native Speaker*).
* **Repetition Mode:** Pengguna dapat mendengarkan berkali-kali untuk menyinkronkan antara visual karakter dan bunyinya.

### 4. Card Synthesis (Combinational Logic)
Fitur tercanggih yang mendeteksi hubungan antar-kartu (Multi-Marker Tracking).
* **Word Building:** Jika kartu **"Huǒ" (Api)** didekatkan dengan kartu **"Shān" (Gunung)**, AR akan mendeteksi kombinasi tersebut dan memunculkan objek **Gunung Berapi (Huǒshān)**.
* **Proximity Sensing:** Objek hanya akan berubah jika jarak antar kartu fisik berada dalam radius tertentu (< 5cm).

### 5. Gamified Interactive Quiz
Mode evaluasi untuk mengukur progres belajar.
* **"Find the Card" Challenge:** Aplikasi memberikan instruksi suara (misal: "Di mana kartu Air?"), dan pengguna harus mengarahkan kamera ke kartu yang benar untuk mendapatkan poin.
* **Visual Validation:** Efek partikel hijau (centang) jika benar, dan merah (silang) jika salah, memberikan umpan balik instan kepada pengguna.
---

## 🛠️ Management & Workflow
Kami menggunakan **Trello** sebagai pusat manajemen tugas (*Backlog, To-Do, In Progress, Done*).

* **Trello Board:** [Kelompok 2 IMK - Project Tracking](https://trello.com/b/COzb5783/kelompok-2-imk)
* **Duration:** 6 Months (Semester Project)
* **Team Size:** 5 Members

---
*© 2026 - Kelompok 2 IMK Universitas Padjadjaran.*
