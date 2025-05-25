# 🔐 Implementasi AES (Advanced Encryption Standard) dalam Python

Latihan implementasi sederhana algoritma **AES (Advanced Encryption Standard)** menggunakan bahasa pemrograman **Python** dan library **PyCryptodome**.

AES adalah algoritma enkripsi simetris yang umum digunakan dalam berbagai aplikasi untuk menjaga kerahasiaan data, seperti dalam komunikasi, penyimpanan file, dan keamanan disk.

## 🧠 Penjelasan Singkat

AES bekerja dengan prinsip enkripsi simetris, yaitu menggunakan **satu kunci** yang sama untuk proses enkripsi dan dekripsi. Dalam contoh ini digunakan:
- Panjang kunci: 128-bit (16 byte)
- Mode operasi: **ECB** (Electronic Codebook)

> Catatan: MODE_ECB digunakan untuk pembelajaran. Untuk implementasi nyata, direkomendasikan menggunakan mode yang lebih aman seperti CBC atau GCM.

## 📦 Ketergantungan

Pastikan Anda telah menginstal pustaka berikut:

```bash
pip install pycryptodome
