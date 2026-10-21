# 🌌 Group Modulo Visualizer (ℤₙ)

> A high-tech, interactive mathematical dashboard and 3D spherical orbit visualizer for finite cyclic groups and abstract algebra structures.

---

## 🚀 Overview
**Group Modulo Visualizer** adalah aplikasi web interaktif berbasis *single-file* (HTML5/Tailwind CSS/JavaScript murni) yang dirancang untuk memvisualisasikan struktur aljabar abstrak dari grup aditif bilangan bulat modulo $n$ ($\mathbb{Z}_n$). 

Proyek ini menjembatani konsep teoretis aljabar murni—seperti Teorema Lagrange, tabel Cayley, generator, dan koset—ke dalam representasi visual digital yang imersif dan futuristik.

---

## ✨ Key Features

* **🔄 Dynamic Modulo Switcher ($n = 2$ hingga $100$):** Ubah semesta grup secara *real-time* untuk menganalisis karakteristik sebarang grup siklik berhingga $\mathbb{Z}_n$.
* **🌐 3D Spherical Orbit Visualizer:** Proyeksi bola 3D interaktif lengkap dengan orbit multi-planar, animasi pulsa lintasan generator, fitur *drag-to-rotate*, dan *zoom control*.
* **📊 Interactive Cayley Table:** Tabel operasi penjumlahan modulo yang dilengkapi dengan pelacakan baris-kolom otomatis serta *tooltip* persamaan aljabar.
* **🌳 Subgroup Lattice (Lagrange's Theorem):** Panel interaktif untuk menguji subgrup unik yang dihasilkan dari pembagi positif (*divisors*) dari orde grup $n$.
* **🔍 Element Inspector:** Analisis mendalam untuk setiap elemen $a \in \mathbb{Z}_n$ meliputi:
  * Orde elemen ($\vert{}a\vert{}$)
  * Invers aditif ($-a \pmod n$)
  * Subgrup yang dihasilkan ($\langle a \rangle$)
  * Status generator utama ($\gcd(a, n) = 1$)
* **⛶ Fullscreen Mode:** Dukungan mode layar penuh untuk pengalaman visualisasi yang lebih luas dan sinematik.

---

## 🛠️ Tech Stack
* **HTML5 Canvas & 2D/3D Projection Engine:** Render grafis orbit dan node secara *real-time* tanpa pustaka eksternal yang berat.
* **Tailwind CSS (CDN):** Desain antarmuka modern dengan gaya *Glassmorphism* dan palet warna *cyber-tech*.
* **Google Fonts (Orbitron & Rajdhani):** Tipografi bernuansa futuristik dan sains-fiksi.
* **Vanilla JavaScript:** Logika komputasi aljabar abstrak, aritmetika modular, dan penanganan event interaktif.

---

## 🌐 Live Demo
Aplikasi ini di-hosting secara publik menggunakan **GitHub Pages**. Kamu dapat langsung mencobanya melalui tautan berikut:

👉 **[https://alirizqanmuhammad-design.github.io/group-modulo-visualizer/](https://alirizqanmuhammad-design.github.io/group-modulo-visualizer/)**

---

## 💻 Local Installation & Usage
Karena dibangun dalam satu berkas portabel (`index.html`), kamu dapat menjalankannya secara lokal tanpa instalasi *dependency* Node.js yang rumit:

1. Clone repository ini:
   ```bash
   git clone [https://github.com/alirizqanmuhammad-design/group-modulo-visualizer.git](https://github.com/alirizqanmuhammad-design/group-modulo-visualizer.git)
