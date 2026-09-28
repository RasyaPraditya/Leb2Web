# Leb2Web

### 1. Elemen Tabel pada HTML
* `<table>` : Digunakan sebagai wadah utama untuk membungkus atau membentuk struktur tabel.
* `<tr>` *(Table Row)* : Menentukan baris baru dalam sebuah tabel.
* `<th>` *(Table Header)* : Membuat sel judul/kepala kolom. Secara bawaan, teks di dalamnya akan dicetak tebal dan rata tengah.
* `<td>` *(Table Data)* : Membuat sel isi data biasa di dalam baris tabel.

---

### 2. Beda `<th>` dan `<td>`
* **`<th>`** dipakai untuk bagian judul kolom/baris. Karakteristik bawaannya adalah teks otomatis tebal (*bold*) dan posisinya di tengah sel.
* **`<td>`** dipakai untuk mengisikan data/konten tabel. Teks bertipe standar (tidak tebal) dan posisinya rata kiri secara bawaan.

---

### 3. Kegunaan Atribut `colspan`
Atribut `colspan` (*column span*) berguna untuk menggabungkan beberapa kolom yang sejajar menjadi satu sel yang lebih lebar secara horizontal.

---

### 4. Peran Elemen `<form>`
Elemen `<form>` berfungsi sebagai penampung berbagai komponen input (seperti *text field*, tombol, pilihan, dll.) yang nantinya digunakan untuk mengumpulkan data dari pengguna dan meneruskannya ke server untuk diproses.

---

### 5. Radio Button vs Checkbox
* **Radio Button (`<input type="radio">`)** : Digunakan ketika pengguna hanya diizinkan memilih **satu pilihan saja** dari sekumpulan opsi yang ada (misal: Jenis Kelamin).
* **Checkbox (`<input type="checkbox">`)** : Digunakan jika pengguna boleh memilih **lebih dari satu pilihan** atau bahkan tidak memilih sama sekali (misal: Hobi / Keahlian).

---

### 6. Pentingnya Menghubungkan `<label>` dengan `id` Input (`for`)
Menghubungkan atribut `for` pada label ke `id` milik input sangat membantu dari segi aksesibilitas (*UX*). Pengguna tidak harus mengklik kotak/lingkaran input yang kecil, cukup mengklik teks labelnya saja maka kolom input tersebut akan langsung aktif/terpilih.

---

### 7. Beda `<input type="text">` dan `<textarea>`
* **`<input type="text">`** : Hanya menyediakan satu baris isian (*single-line*), cocok untuk input pendek seperti nama, username, atau judul.
* **`<textarea>`** : Menyediakan kotak isian banyak baris (*multi-line*), cocok untuk input panjang seperti alamat, pesan, atau deskripsi. Ukuran kotaknya juga bisa disesuaikan melalui atribut `rows` dan `cols`.

---

### 8. Elemen Semantic HTML
* `<header>` : Bagian atas atau kepala dari halaman/bagian web (biasanya berisi judul utama atau logo).
* `<nav>` : Wadah khusus untuk menu navigasi utama.
* `<main>` : Menyimpan konten inti utama dari halaman web tersebut.
* `<section>` : Mengelompokkan bagian-bagian konten berdasarkan topik tertentu.
* `<article>` : Bagian konten independen yang bisa berdiri sendiri (seperti postingan blog, berita, atau artikel).
* `<aside>` : Bagian samping yang berisi informasi tambahan atau pelengkap yang berkaitan dengan konten utama.
* `<footer>` : Bagian bawah/kaki halaman yang biasanya memuat hak cipta, kontak, atau tautan tambahan.

---

### 9. Atribut Validasi Form
* `required` : Wajib diisi. Form tidak bisa dikirim jika bagian ini masih kosong.
* `min` : Batas nilai angka atau tanggal terkecil yang boleh dimasukkan.
* `max` : Batas nilai angka atau tanggal terbesar yang boleh dimasukkan.
* `minlength` : Batas minimal jumlah karakter huruf/teks yang harus diketik.

---

### 10. Beda Elemen `<audio>` dan `<video>`
* **`<audio>`** : Digunakan khusus untuk memutar berkas suara/musik saja tanpa visual.
* **`<video>`** : Digunakan untuk menampilkan dan memutar berkas video (gambar bergerak beserta suaranya), serta memiliki atribut pendukung seperti `width` dan `height` untuk mengatur dimensi tampilannya.
