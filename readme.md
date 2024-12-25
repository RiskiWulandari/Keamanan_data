# GUI Tools Documentation

Berikut adalah panduan penggunaan untuk **chipergui**, **desgui**, **enigmagui**, dan **steganogui**. Tools ini dirancang untuk membantu pengguna dalam melakukan operasi kriptografi dan steganografi melalui antarmuka grafis.

---

## 1. Chipergui

**Chipergui** adalah aplikasi GUI untuk melakukan berbagai operasi cipher, seperti enkripsi dan dekripsi menggunakan algoritma klasik.

### Cara Menggunakan:
1. Jalankan aplikasi `chipergui`.
2. Pilih algoritma cipher yang ingin digunakan (misalnya, Caesar Cipher, Vigenere Cipher, dll.).
3. Masukkan teks yang ingin dienkripsi atau didekripsi.
4. Masukkan kunci (key) yang sesuai.
5. Klik tombol "Encrypt" atau "Decrypt".
6. Hasil akan ditampilkan di area output.

---

## 2. Desgui

**Desgui** adalah aplikasi GUI yang berfungsi untuk enkripsi dan dekripsi menggunakan algoritma DES (Data Encryption Standard).

### Cara Menggunakan:
1. Jalankan aplikasi `desgui`.
2. Masukkan teks yang ingin dienkripsi atau didekripsi.
3. Masukkan kunci (key) 64-bit.
4. Pilih mode operasi (ECB, CBC, dll.).
5. Klik tombol "Encrypt" atau "Decrypt".
6. Hasil akan ditampilkan di area output.

---

## 3. Enigmagui

**Enigmagui** adalah simulasi GUI dari mesin Enigma yang digunakan untuk enkripsi dan dekripsi pesan.

### Cara Menggunakan:
1. Jalankan aplikasi `enigmagui`.
2. Konfigurasikan rotors dan reflector sesuai kebutuhan:
   - Pilih jenis rotor.
   - Atur posisi awal rotor.
   - Pilih jenis reflector.
3. Masukkan teks yang ingin dienkripsi atau didekripsi.
4. Klik tombol "Encrypt" atau "Decrypt".
5. Hasil akan muncul di area output.

---

## 4. Steganogui

**Steganogui** adalah aplikasi GUI untuk menyembunyikan atau mengekstrak pesan dari gambar menggunakan teknik steganografi.

### Cara Menggunakan:
1. Jalankan aplikasi `steganogui`.
2. Pilih mode:
   - **Hide Message**: Untuk menyembunyikan pesan dalam gambar.
   - **Extract Message**: Untuk mengekstrak pesan dari gambar.
3. Jika memilih **Hide Message**:
   - Unggah gambar yang akan digunakan.
   - Masukkan pesan yang ingin disembunyikan.
   - Klik "Hide" untuk menyisipkan pesan ke dalam gambar.
   - Simpan gambar hasil steganografi.
4. Jika memilih **Extract Message**:
   - Unggah gambar steganografi.
   - Klik "Extract" untuk mendapatkan pesan tersembunyi.
5. Pesan akan muncul di area output.

---

## Persyaratan Sistem

- Python 3.x
- Library yang dibutuhkan:
  - Tkinter
  - Pillow
  - PyCrypto (untuk DES)
  - Library lain sesuai kebutuhan masing-masing aplikasi

## Instalasi

1. Clone repository:
   ```bash
   git clone https://github.com/username/repository.git
   cd repository
