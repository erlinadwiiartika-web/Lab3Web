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

🛠️️ Peralatan yang Digunakan

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
<img width="950" height="501" alt="image" src="https://github.com/user-attachments/assets/454c9e4b-58b2-4b68-a2ab-8bc6981a97bd" />


2. Menambahkan Internal CSS

Menambahkan tag 'style' pada bagian 'head' untuk mengatur tampilan font, header, dan tag 'h1'.

<img width="372" height="211" alt="image" src="https://github.com/user-attachments/assets/e58ac0f3-df4b-457e-b47e-68539e6870d1" />

<img width="950" height="498" alt="image" src="https://github.com/user-attachments/assets/7e267211-634e-41d2-9941-e662f7ff0d4b" />


3. Menambahkan Inline CSS

Penerapan atribut style secara langsung pada elemen HTML:

<img width="388" height="24" alt="image" src="https://github.com/user-attachments/assets/dedbc836-0f12-408a-8de5-0b2c74ecadd3" />

<img width="950" height="499" alt="image" src="https://github.com/user-attachments/assets/1c00f693-c468-4e37-9b3f-951aee377b60" />



4. Membuat CSS Eksternal

Membuat file terpisah bernama style_eksternal.css dan menautkannya ke dokumen HTML menggunakan tag <link>:

<img width="383" height="19" alt="image" src="https://github.com/user-attachments/assets/23f3cedd-4621-4c7a-96e4-cb03afdec8a9" />

<img width="950" height="498" alt="image" src="https://github.com/user-attachments/assets/88e4f966-0157-4a93-a050-0f2494c68b12" />


5. Menambahkan ID dan Class Selector

ID Selector (#intro): Digunakan untuk styling khusus bagian intro.

Class Selector (.button, .btn-primary): Digunakan untuk penataan tombol.
<img width="950" height="500" alt="image" src="https://github.com/user-attachments/assets/473c88b3-4ec5-480d-9a8e-b0c9f9185c66" />


6. Eksperimen Properti CSS & Validasi

Menambahkan property seperti background-color, margin, padding, border-radius, box-shadow, serta efek :hover.

Melakukan validasi CSS pada W3C CSS Validation Service untuk memastikan kode bebas error (Congratulations! No Error Found!).
<img width="950" height="474" alt="image" src="https://github.com/user-attachments/assets/2989229c-a6ce-4ac5-b806-e36004492f58" />


❓ Jawaban Tugas & Pertanyaan Praktikum

1. Jelaskan perbedaan antara h1 {...} dan #intro h1 {...}!

h1 {...} adalah Element Selector. Aturan ini bersifat global dan berlaku untuk seluruh elemen 'h1' yang ada di dalam dokumen HTML.

#intro h1 {...} adalah Descendant Selector yang lebih spesifik. Aturan ini hanya memengaruhi elemen 'h1' yang berada di dalam elemen berkode id="intro". Memiliki nilai specificity lebih tinggi.

2. Bagaimana prioritas penerapan jika terdapat Inline, Internal, dan External CSS secara bersamaan?

Secara umum (tanpa !important), tingkat prioritas (specificity) CSS dari yang tertinggi adalah:

Inline CSS (Terkuat / Prioritas Utama).

Internal CSS dan External CSS (Sederajat, mana yang ditulis atau dimuat paling akhir dalam urutan kode HTML yang akan menang).

3. Jika elemen memiliki ID dan Class sekaligus, mana aturan CSS yang akan berlaku?

Deklarasi dari ID Selector yang akan menang dan diterapkan. Hal ini terjadi karena ID selector memiliki tingkat specificity (1-0-0) yang lebih tinggi dibandingkan dengan Class selector (0-1-0).

⚙️ Cara Mengunggah ke GitHub

git init
git add .
git commit -m "Praktikum 3 CSS Dasar"
git branch -M main
git remote add origin https://github.com/erlinadwiiartika/Lab3Web.git
git push -u origin main


📑 Referensi / Daftar Pustaka

Nugroho, Agung. Modul Praktikum Pemrograman Web – Praktikum 3: CSS Dasar. Universitas Pelita Bangsa, Bekasi.
