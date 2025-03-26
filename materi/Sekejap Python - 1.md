# Dasar Pemrograman 
## Apa Itu Python?
---
Python adalah bahasa pemrograman yang mudah dipelajari dan digunakan untuk berbagai keperluan, seperti:
 - Membuat aplikasi web terutama Backend dengan dukungan berbagai macam Framework siap pakai seperti [FastAPI](https://fastapi.tiangolo.com/),[Welcome to Flask — Flask Documentation (3.1.x)](https://flask.palletsprojects.com/en/stable/) dan  [The web framework for perfectionists with deadlines | Django](https://www.djangoproject.com/)
 - Pengembangan aplikasi berbasis  Kecerdasan Buatan atau _AI - Artificial Intelligent_ 
 - Pemrograman sederhana untuk otomatisasi seperti _Web Scrapping_ 
 - Pembuatan _script_ untuk cyber security 

## Variabel dan Tipe Data
---
 Variabel adalah tempat untuk menyimpan data yang dibutuhkan dalam proses komputasi. Python memiliki beberapa tipe data dasar:

1. Tipe Data Dasar
 - Integer (Angka Bulat): Contoh: 5, -10, 100
 - Float (Angka Desimal): Contoh: 3.14, -2.5
 - String (Teks): Contoh: "Halo", 'Python'
 - Boolean (True/False): Contoh: True, False

 2. Contoh Penggunaan Variabel
 - Mendeklarasikan variabel:
```python
angka_bulat = 10
angka_desimal = 3.14
teks = "Belajar Python"
kondisi = True
```
- Menampilkan isi variabel
```python
print("Angka Bulat:", angka_bulat)
print("Angka Desimal:", angka_desimal)
print("Teks:", teks)
print("Kondisi:", kondisi)
```

## Operasi Dasar pada Python
---
Python mendukung berbagai operasi matematika:
- Penjumlahan
```python
hasil_penjumlahan = 5 + 3
print("Hasil Penjumlahan:", hasil_penjumlahan)
```
 - Pengurangan
```python
hasil_pengurangan = 10 - 4
print("Hasil Pengurangan:", hasil_pengurangan)
```
- Perkalian
 ```python
hasil_perkalian = 7 * 6
print("Hasil Perkalian:", hasil_perkalian)
```
- Pembagian
```python 
hasil_pembagian = 8 / 2
print("Hasil Pembagian:", hasil_pembagian)
```
- Sisa Bagi (Modulus)
```python 
hasil_modulus = 10 % 3
print("Hasil Modulus:", hasil_modulus)
```

## Struktur Kontrol 
 Percabangan digunakan untuk membuat keputusan dalam program.
 - Contoh Percabangan
```python
umur = 17
if umur >= 18:
    print("Kamu sudah dewasa.")
else:
    print("Kamu masih di bawah umur.")

```
Tips :
- Gunakan nama variabel yang jelas dan deskriptif.
- Hindari logika kompleks dalam satu baris. Pecah menjadi bagian yang lebih kecil. 
   Contoh:
```python
def cek_usia(umur):
    if umur >= 18:
        return "Dewasa"
    return "Di bawah umur"
    
status = cek_usia(umur)
print("Status usia:", status)
```

# Bagian 6: Loop (Perulangan)
# Ada dua jenis perulangan utama di Python:

# 1. Perulangan "for"
for i in range(5):  # Mengulang sebanyak 5 kali
    print("Perulangan ke:", i)

# 2. Perulangan "while"
hitung = 0
while hitung < 5:
    print("Perulangan while ke:", hitung)
    hitung += 1

# Praktik Terbaik:
# - Hindari perulangan yang tidak berakhir. Pastikan ada kondisi berhenti.
# - Gunakan komentar untuk menjelaskan tujuan perulangan jika kompleks.

# Bagian 7: Fungsi
# Fungsi adalah blok kode yang bisa digunakan ulang.

# Contoh Fungsi Sederhana

def sapa_nama(nama):
    print(f"Halo, {nama}! Selamat belajar Python.")

# Memanggil fungsi
sapa_nama("Ani")
sapa_nama("Budi")

# Contoh Fungsi dengan Parameter dan Return

def hitung_luas_persegi(sisi):
    return sisi * sisi

# Memanggil Fungsi
luas = hitung_luas_persegi(4)
print("Luas Persegi:", luas)

# Bagian 8: Prinsip Clean Code dalam Flow Control
# - **KISS (Keep It Simple, Stupid):** Buat kode sesederhana mungkin tanpa logika yang rumit.
# - **DRY (Don't Repeat Yourself):** Hindari pengulangan kode. Gunakan fungsi jika diperlukan.
# - **SOLID:** Strukturkan kode dengan baik agar mudah diperbaiki dan diperluas.

# Contoh Gabungan:
def cek_status_pelanggan(umur, status_akun):
    if umur < 18:
        return "Pelanggan di bawah umur."
    if not status_akun:
        return "Akun belum aktif."
    return "Pelanggan aktif."

status_pelanggan = cek_status_pelanggan(17, True)
print("Status Pelanggan:", status_pelanggan)

Bagian 9: Penutup
Kamu telah mempelajari dasar-dasar Python, seperti variabel, operasi dasar, percabangan, perulangan, fungsi, dan prinsip clean code.
Silakan bereksperimen lebih lanjut dengan membuat program sederhana! 
Jangan lupa untuk selalu mencoba menyelesaikan masalah dengan kode Python yang bersih dan efisien.
