# 🌱 Website Carbon Footprint Checker

`carbonfootprint.py` adalah skrip Python sederhana berbasis CLI untuk menganalisis jejak karbon dari sebuah website menggunakan [WebsiteCarbon.com API](https://api.websitecarbon.com/). Hasil analisis ditampilkan dalam format tabel yang menarik menggunakan pustaka `rich`.

---

## 🧰 Fitur

- Mengetahui apakah hosting website ramah lingkungan (green hosting).
- Menampilkan estimasi emisi karbon (per view) dari energi grid dan energi terbarukan.
- Menampilkan estimasi konsumsi energi per view.
- Tampilan hasil yang cantik dengan tabel berwarna di terminal.

---

## ▶️ Cara Menggunakan

### 1. Jalankan via Command Line:

```bash
python3 carbonfootprint.py https://example.com
