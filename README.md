# Lab3Web

## Deskripsi Singkat ##

Repository ini berisi hasil Praktikum 3: Membuat List, Table, dan Form pada mata kuliah Pemrograman Web.
Seluruh latihan dikerjakan menggunakan HTML dan CSS dasar, serta telah divalidasi melalui W3C Validator untuk memastikan struktur HTML yang benar dan sesuai standar.


---

## Isi Repository ##

1. lab3_list.html → berisi latihan membuat Ordered List, Unordered List, Description List, dan Nested List.

2. lab3_tabel.html → berisi latihan membuat tabel HTML, termasuk penggunaan atribut colspan dan rowspan.

3. lab3_form.html → berisi latihan membuat form input data, form login, serta dropdown dan listbox multiple selection.

4. Folder screenshots/ → berisi hasil tampilan setiap file HTML di browser.
<img width="1366" height="768" alt="Screenshot 2025-10-08 095906" src="https://github.com/user-attachments/assets/beacbd75-7f0c-4cf8-93a2-58e5184c6a5d" />

<img width="1366" height="768" alt="Screenshot 2025-10-08 095924" src="https://github.com/user-attachments/assets/2252eb48-2f74-4927-a37b-802010bb932a" />

<img width="1366" height="768" alt="Screenshot 2025-10-08 100044" src="https://github.com/user-attachments/assets/a3f01f7f-bb14-41e8-a6df-858783d306f8" />

<img width="1366" height="768" alt="Screenshot 2025-10-08 100641" src="https://github.com/user-attachments/assets/de597c5d-8fe4-45b1-bbd4-5dbff1c27d70" />

<img width="1366" height="768" alt="Screenshot 2025-10-08 100921" src="https://github.com/user-attachments/assets/184942e3-f41e-4b16-b2df-5c62246c6da8" />

<img width="1366" height="768" alt="Screenshot 2025-10-08 101214" src="https://github.com/user-attachments/assets/ebb4bf52-5778-41ff-9121-cb064211dc85" />

<img width="1366" height="768" alt="Screenshot 2025-10-08 101239" src="https://github.com/user-attachments/assets/ad6f9d0f-3b93-437d-8c31-8cc8b45a4381" />

<img width="1366" height="768" alt="Screenshot 2025-10-08 101259" src="https://github.com/user-attachments/assets/79d06bb8-50f3-4990-8522-53f9af401a43" />


6. README.md → penjelasan langkah-langkah pengerjaan praktikum disertai dokumentasi visual.


---

## Langkah Pengerjaan ##

1. Membuat struktur dasar HTML (<!DOCTYPE html>, <html>, <head>, <body>).
2. Menambahkan tag <ol>, <ul>, <dl> untuk membuat berbagai jenis list.
3. Membuat tabel menggunakan tag <table>, <tr>, <td>, <th>, dan menambahkan atribut rowspan & colspan.
4. Membuat form login dan form data pelanggan menggunakan <form>, <fieldset>, <legend>, <input>, <textarea>, <select>, serta penerapan CSS sederhana.
5. Menambahkan elemen dropdown menu dan listbox multiple selection pada form untuk memenuhi tugas tambahan.
6. Melakukan validasi HTML di https://validator.w3.org.
7. Mengunggah hasil akhir ke repository GitHub Lab3Web.


---

## Hasil Validasi ##

Semua file HTML telah divalidasi menggunakan W3C HTML Validator tanpa error, hanya terdapat informational notice (trailing slash info) yang tidak memengaruhi struktur dokumen.

---

## Pertanyaan & Jawaban Praktikum ##

**1️⃣ Pertanyaan:**

Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.

💡 Jawaban:
Form tersebut telah dibuat pada file lab3_form.html dengan menambahkan elemen:

<!-- Dropdown Menu -->
<select id="provinsi" name="provinsi">
  <option value="">--Pilih--</option>
  <option value="JKT">DKI Jakarta</option>
  <option value="JBR">Jawa Barat</option>
  <option value="JTG">Jawa Tengah</option>
</select>

<!-- Listbox Multiple Selection -->
<select id="hobi" name="hobi[]" multiple size="4">
  <option value="membaca">Membaca</option>
  <option value="olahraga">Olahraga</option>
  <option value="musik">Musik</option>
  <option value="coding">Coding</option>
</select>

**Penjelasan:**

1. multiple → memungkinkan pengguna memilih lebih dari satu opsi.
2. size="4" → menentukan tinggi listbox (jumlah opsi yang terlihat langsung).
3. name="hobi[]" → tanda [] menandakan bahwa nilai akan dikirim dalam bentuk array ke server.

Dengan begitu, form dapat menerima satu pilihan dari dropdown (provinsi) dan beberapa pilihan dari listbox (hobi), sesuai instruksi tugas praktikum.


---

## Cara Menjalankan ##

1. Clone atau download repository ini.
2. Buka file HTML (lab3_list.html, lab3_tabel.html, lab3_form.html) di browser.
3. Lihat tampilan sesuai latihan yang telah dikerjakan.

---

## Author ##

Nama: Muhammad Raffi Pasya Perdana
NIM: 312410450
Mata Kuliah: Pemrograman Web
Dosen Pengampu: Agung Nugroho, S.Kom., M.Kom
Universitas: Universitas Pelita Bangsa
