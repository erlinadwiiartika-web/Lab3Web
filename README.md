Lab3Web - Praktikum 3: CSS Dasar

Proyek ini berisi laporan dan hasil pengerjaan Praktikum 3: CSS Dasar pada mata kuliah Pemrograman Web.

👤 Data Mahasiswa

Nama: Erlina Dwi Artika

NIM: 312510039

Kelas: I252A

Mata Kuliah: Pemrograman Web

Program Studi: Teknik Informatika

Perguruan Tinggi: Universitas Pelita Bangsa

Tahun: 2026

🎯 Tujuan Praktikum

Memahami konsep dasar Cascading Style Sheet (CSS).

Memahami aturan penulisan dan struktur pada CSS (selector, property, dan value).

Memahami penggunaan selector sebagai pengontrol tampilan elemen HTML.

Membuat pengaturan CSS pada HTML menggunakan metode Internal, Inline, dan External CSS.

🛠️ Peralatan yang Digunakan

Text Editor: Visual Studio Code

Web Browser: Google Chrome / Microsoft Edge / Mozilla Firefox

Tools Validasi: W3C CSS Validation Service

Version Control: Git & GitHub

📁 Struktur File

Lab3Web/
│
├── lab3_css_dasar.html    # Dokumen utama HTML
├── style_eksternal.css    # File CSS eksternal
└── README.md              # Dokumentasi proyek


🚀 Langkah Praktikum

1. Membuat Dokumen HTML Dasar

Membuat file lab3_css_dasar.html dengan struktur tag HTML5 standar yang mencakup header, nav, dan div dengan elemen-elemen heading, paragraf, serta link.

<img width="950" height="501" alt="image" src="https://github.com/user-attachments/assets/e8c7ee53-5bce-4a3a-90b5-3adaab882c19" />

2. Menambahkan Internal CSS

Menambahkan tag <style> pada bagian <head> untuk mengatur tampilan font, header, dan tag <h1>.

<style>
  body {
    font-family: 'Open Sans', sans-serif;
  }
  header {
    min-height: 80px;
    border-bottom: 1px solid #77CCEF;
  }
  h1 {
    font-size: 24px;
    color: #0F189F;
    text-align: center;
    padding: 20px 10px;
  }
  h1 i {
    color: #6d6a6b;
  }
</style>
<img width="950" height="498" alt="image" src="https://github.com/user-attachments/assets/144c23cc-4dc2-4b57-827f-01cfc0617098" />


3. Menambahkan Inline CSS

Penerapan atribut style secara langsung pada elemen HTML:

<p style="text-align: center; color: #ccd8e4;">Paragraf dengan Inline CSS</p>
<img width="950" height="499" alt="image" src="https://github.com/user-attachments/assets/ae3e8e23-74e1-401f-a053-1ff0d2fb14ed" />


4. Membuat CSS Eksternal

Membuat file terpisah bernama style_eksternal.css dan menautkannya ke dokumen HTML menggunakan tag <link>:

<link rel="stylesheet" href="style_eksternal.css" type="type/css">
<img width="950" height="498" alt="image" src="https://github.com/user-attachments/assets/d07cad8b-4e69-47ed-b5dc-a53bd8fc0283" />


5. Menambahkan ID dan Class Selector

ID Selector (#intro): Digunakan untuk styling khusus bagian intro.

Class Selector (.button, .btn-primary): Digunakan untuk penataan tombol.
<img width="950" height="500" alt="image" src="https://github.com/user-attachments/assets/9ea7cbe0-2b8d-4574-9943-fca9bd705f1c" />


6. Eksperimen Properti CSS & Validasi

Menambahkan property seperti background-color, margin, padding, border-radius, box-shadow, serta efek :hover.

Melakukan validasi CSS pada W3C CSS Validation Service untuk memastikan kode bebas error (Congratulations! No Error Found!).
<img width="950" height="474" alt="image" src="https://github.com/user-attachments/assets/43eff994-0880-4ac4-a25e-355b659cd098" />


❓ Jawaban Tugas & Pertanyaan Praktikum

1. Jelaskan perbedaan antara h1 {...} dan #intro h1 {...}!

h1 {...} adalah Element Selector. Aturan ini bersifat global dan berlaku untuk seluruh elemen <h1> yang ada di dalam dokumen HTML.

#intro h1 {...} adalah Descendant Selector yang lebih spesifik. Aturan ini hanya memengaruhi elemen <h1> yang berada di dalam elemen berkode id="intro". Memiliki nilai specificity lebih tinggi.

2. Bagaimana prioritas penerapan jika terdapat Inline, Internal, dan External CSS secara bersamaan?

Secara umum (tanpa !important), tingkat prioritas (specificity) CSS dari yang tertinggi adalah:

Inline CSS (Terkuat / Prioritas Utama).

Internal CSS dan External CSS (Sederajat, mana yang ditulis atau dimuat paling akhir dalam urutan kode HTML yang akan menang).

3. Jika elemen memiliki ID dan Class sekaligus, mana aturan CSS yang akan berlaku?

Deklarasi dari ID Selector yang akan menang dan diterapkan. Hal ini terjadi karena ID selector memiliki tingkat specificity (1-0-0) yang lebih tinggi dibandingkan dengan Class selector (0-1-0).

⚙️ Cara Mengunggah ke GitHub

# Inisialisasi repository git
git init

# Menambahkan semua file ke staging area
git add .

# Melakukan commit
git commit -m "Praktikum 3 CSS Dasar"

# Mengubah nama branch ke main
git branch -M main

# Menghubungkan ke remote repository GitHub
git remote add origin https://github.com/erlinadwiiartika/Lab3Web.git

# Mengunggah perubahan ke GitHub
git push -u origin main


📑 Referensi / Daftar Pustaka

Nugroho, Agung. Modul Praktikum Pemrograman Web – Praktikum 3: CSS Dasar. Universitas Pelita Bangsa, Bekasi.
