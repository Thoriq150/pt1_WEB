# Praktikum1 HTML Dasar
## Latihan
### Modul Praktikum web
#### Buatlah kerangka pengantar HTML 
![Screenshot (89)](https://github.com/Thoriq150/pt1_WEB/assets/115950790/f0cb6ed0-2e74-490a-b2f6-bd4623d1720d)
#### Kemudian Buka file browser
![Screenshot (90)](https://github.com/Thoriq150/pt1_WEB/assets/115950790/72187b68-3a9b-45c9-94ea-de741575570f)

### 1. Membuat Paragraf
#### Buatlah 2 buah paragraf menggunakan`<p></p>`
![Screenshot (108)](https://github.com/Thoriq150/pt1_WEB/assets/115950790/3a39933e-e683-4300-b44b-c0c95cb804a2)
#### tampilan browser
![Screenshot (90)](https://github.com/Thoriq150/pt1_WEB/assets/115950790/7b24f4be-6067-4b9c-98a5-0395cc6157c3)
### 2. Buat Judul
#### Tambahkan judul di masing-masing paragraf pakai`<h1>` dan `<h2>`
![Screenshot (94)](https://github.com/Thoriq150/pt1_WEB/assets/115950790/3b5074b0-cda0-43b3-8059-336f7011d6cd)
#### tampilan browser
![Screenshot (92)](https://github.com/Thoriq150/pt1_WEB/assets/115950790/e9d7f6ac-5111-429a-8fde-a911d17a9712)
### 3. Memformat Text
#### format text dan tambahkan fariasi seperti kata miring ,tebal ,garis bawah dll
![Screenshot (97)](https://github.com/Thoriq150/pt1_WEB/assets/115950790/137f4172-f7b7-4efe-b24b-b6feb5e2b530)
#### tampilan browser
![Screenshot (98)](https://github.com/Thoriq150/pt1_WEB/assets/115950790/466b89cc-fb17-438e-bc30-65730d414426)
### 4. menyispkan gambar
#### letakan gambar di satu folder yang sama dengan file html ,lalu gunakan src
![Screenshot (107)](https://github.com/Thoriq150/pt1_WEB/assets/115950790/b8763bbf-b7df-4beb-8558-d1474ddbca5f)
![Screenshot (101)](https://github.com/Thoriq150/pt1_WEB/assets/115950790/9278f210-ea8b-4d7c-aece-8dd318b27f30)
#### tampilan browser
![Screenshot (100)](https://github.com/Thoriq150/pt1_WEB/assets/115950790/428f2084-7678-4e02-8316-499a8280530e)
### 5. Tambahkan Hyperlink
#### buatlah navigasi diatas ,lalu buatkan satu file html lagi untuk link kedua dan satunya gunakan google
![Screenshot (105)](https://github.com/Thoriq150/pt1_WEB/assets/115950790/f19b000a-5712-44a4-8287-19d706191ed2)
#### tampilan browser
![Screenshot (106)](https://github.com/Thoriq150/pt1_WEB/assets/115950790/2c2c0a23-0170-4749-91dd-aa0eb900dd34)

#### Jawab Pertanyaan Berikut
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
2. Apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya!
3. Apa perbedaan atribut title dan alt pada tag `<img>`, berikan penjelasannya!
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

### Jawaban ----
#### 1. tidak ada eror, karena tag nya telah dibuat dengan nama file pertemuan 1
![Screenshot (109)](https://github.com/Thoriq150/pt1_WEB/assets/115950790/dd959218-79c1-4267-9d20-7601b57d6574)

#### 2. `<p>` (paragraph) adalah elemen untuk membuat paragraf baru. Ini menambahkan jarak atas dan bawah elemen,
menciptakan batas paragraf. Sebuah paragraf baru dimulai setelah elemen `<p>`.
`<br>` (break) adalah elemen untuk melakukan pemisahan baris (line break). Ini hanya memindahkan teks ke baris 
baru dalam elemen yang sama, tanpa menciptakan paragraf baru.

#### 3. Perbedaan Atribut `title` dan `alt` pada `<img>`:
Atribut `title` digunakan untuk menyediakan informasi tambahan saat pengguna mengarahkan kursor ke gambar. Informasi ini muncul sebagai tooltip.
Atribut `alt` adalah teks alternatif yang akan ditampilkan jika gambar tidak dapat dimuat. Ini juga penting untuk aksesibilitas, membantu
orang dengan keterbatasan penglihatan atau jika gambar gagal dimuat.

#### 4. Atribut `width` dan `height` untuk Ukuran Gambar:
Agar tampilan gambar proporsional, sebaiknya minimal salah satu atribut (width atau height) diisi. Jika hanya satu diisi, browser akan mengukur atribut yang tidak diisi secara proporsional berdasarkan atribut yang diisi. Mengisi keduanya dapat mempertahankan proporsi asli gambar, namun, jika proporsi asli gambar tidak cocok dengan proporsi yang diinginkan, gambar dapat terlihat terdistorsi.

#### 5. Atribut `target` pada Link:
Atribut `target` pada link mengontrol bagaimana tautan dibuka saat diklik:
`_blank`: Membuka tautan di jendela atau tab baru.
`_self`: Membuka tautan di jendela atau tab yang sama (default).
`_top`: Menggantikan seluruh konten dengan tampilan dari tautan tersebut.
`_parent`: Menggantikan tampilan frame parent dengan tampilan dari tautan tersebut.
