# E-SMART

Aplikasi web statis untuk GitHub Pages yang melakukan scan Lembar Jawaban Komputer (LJK) Evalbee.

## Fitur utama
- Scan dari upload file gambar.
- Scan langsung dari kamera sebagai simulasi paper feeder.
- Upload template untuk kalibrasi (sensor kotak di tiap pojok) agar alignment lebih akurat.
- Sensor orientasi atas-bawah untuk auto-rotate jika lembar terbalik.
- Output hasil scan ternormalisasi bisa diunduh ke PNG.

## Menjalankan lokal
Buka `index.html` langsung di browser modern (Chrome/Edge/Firefox). Untuk akses kamera, lebih stabil jika dijalankan lewat server lokal sederhana:

```bash
python3 -m http.server 8080
```

Lalu akses `http://localhost:8080`.
