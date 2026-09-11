# ⚖️ Indonesian Legal Text Simplifier

Alat bantu berbasis Claude API untuk menerjemahkan pasal, putusan, dan dokumen hukum Indonesia yang padat menjadi bahasa awam yang mudah dipahami — dibangun sebagai proyek portofolio untuk **Claude Campus Ambassador (Builder Club track)**.

## Kenapa proyek ini dibuat

Sebagai mahasiswa Hukum Bisnis, saya sering menghabiskan waktu lama untuk memahami pasal dan putusan yang ditulis dalam bahasa hukum yang padat. Saya mulai menggunakan Claude untuk membantu membedah teks-teks itu ke bahasa sehari-hari — dan proyek ini adalah otomatisasi dari kebiasaan itu, supaya mahasiswa lain (khususnya di luar jurusan hukum) juga bisa memahami teks hukum tanpa perlu bertanya ke siapa pun.

## Fitur

* **Analisis Live** — tempelkan pasal/putusan apa pun, dapatkan hasil dari Claude API secara real-time.
* **Pilihan Model** — bisa memilih antara Sonnet 5 atau Haiku 4.5, sesuai kebutuhan kecepatan/kedalaman analisis.
* **Mode Demo (tanpa API Key)** — untuk yang ingin mencoba cepat tanpa memasukkan API key, tersedia contoh hasil analisis nyata (bukan ditulis manual) dari Pasal 1365 KUHPerdata.
* **Output 3 Tab** — Inti Sederhana, Glosarium Istilah, dan Dampak \& Implikasi.
* **Ekspor Hasil** — unduh hasil analisis dalam format `.txt`.

## Cara Menjalankan

```bash
pip install -r requirements.txt
streamlit run app.py
```

Masukkan Claude API key kamu sendiri di sidebar (dapatkan di [console.anthropic.com](https://console.anthropic.com)), atau klik **"Jalankan Mode Demo"** untuk melihat contoh hasil tanpa perlu API key.

## Dibangun dengan

* [Streamlit](https://streamlit.io) — antarmuka web
* [Claude API](https://www.anthropic.com) (Anthropic) — analisis teks hukum

## Catatan

Proyek ini dibuat dalam waktu terbatas sebagai bukti eksplorasi teknis untuk aplikasi Claude Campus Ambassador, oleh mahasiswa Hukum Bisnis (Universitas Negeri Makassar) yang sedang mempertimbangkan transisi ke bidang AI/engineering. Rencana pengembangan lanjutan: dukungan upload PDF untuk dokumen hukum lengkap, bukan hanya teks yang ditempel manual.

