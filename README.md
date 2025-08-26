# 📝 Sistem Frontend Konsultasi Skripsi Online

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Repositori ini berisi kode *frontend* untuk antarmuka pengguna (UI) dari Sistem Konsultasi Skripsi Online. Desain ini dibuat dengan fokus pada pengalaman pengguna yang bersih, modern, dan intuitif untuk memudahkan mahasiswa dan dosen dalam proses bimbingan skripsi.

---

### ✨ Fitur Utama

-   **Formulir Interaktif**: Formulir yang terstruktur dengan baik, dibagi menjadi beberapa panel logis untuk kemudahan pengisian data.
-   **Input Dinamis**: Kolom input untuk data mahasiswa (Nama, NIM) dan *dropdown* untuk pemilihan Dosen Pembimbing.
-   **Unggah File Modern**: Fitur unggah file dengan mekanisme *drag-and-drop* dan pratinjau file yang diunggah.
-   **Validasi Real-time**: Tombol "Kirim" bersifat dinamis, hanya aktif ketika semua kolom wajib telah diisi untuk mencegah pengiriman data yang tidak lengkap.
-   **Umpan Balik Visual**: Notifikasi *loading state* saat formulir dikirim dan *modal* konfirmasi sukses setelah proses selesai.
-   **Desain Responsif**: Tampilan yang optimal di berbagai perangkat, baik desktop maupun seluler, berkat Tailwind CSS.

---

### 🚀 Teknologi yang Digunakan

-   **HTML5**: Sebagai struktur dasar halaman web.
-   **Tailwind CSS**: Untuk *styling* yang cepat, modern, dan responsif.
-   **JavaScript (Vanilla JS)**: Untuk menangani semua logika interaktivitas di sisi klien, seperti validasi formulir, *event handling*, dan manipulasi DOM.

---

### 📂 Cara Menjalankan Proyek

Karena proyek ini murni *frontend* dan tidak memerlukan proses *build*, Anda bisa langsung menjalankannya dengan sangat mudah:

1.  **Clone repositori ini:**
    ```bash
    git clone [https://github.com/NAMA_USER/NAMA_REPO.git](https://github.com/NAMA_USER/NAMA_REPO.git)
    ```
2.  **Buka file `index.html`:**
    Navigasikan ke direktori proyek dan buka file `index.html` (atau nama file HTML utama Anda) langsung di browser pilihan Anda (misalnya, Google Chrome, Firefox, atau Edge).

    Tidak ada instalasi atau dependensi yang diperlukan!

---

### 🛠️ Integrasi dengan Backend

Desain *frontend* ini telah disiapkan untuk diintegrasikan dengan *backend*. Berikut adalah beberapa poin penting untuk tim *backend*:

-   **Endpoint Pengiriman Form**: Elemen `<form>` dengan `id="consultation-form"` akan mengirimkan data saat disubmit. Data yang dikirim mencakup semua input dari mahasiswa, termasuk file yang diunggah.
-   **Data Dosen**: Daftar dosen pada elemen `<select id="supervisor-lecturer">` dapat diisi secara dinamis dengan data yang diambil dari *database*.
-   **Autentikasi**: Pada implementasi produksi, data "Informasi Mahasiswa" idealnya diisi secara otomatis setelah pengguna *login*, bukan diisi manual.

---

### 📄 Lisensi

Proyek ini dilisensikan di bawah [Lisensi MIT](https://choosealicense.com/licenses/mit/).
