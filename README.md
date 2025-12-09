📘 README Project 1 — File Management (FINAL)

# 📁 Project 1 – File Management (CMD)

## 🎯 Tujuan
Mengorganisir file kuliah/pekerjaan menggunakan Command Prompt (CMD) dengan membuat *minimal 5 kategori folder*, lalu merapikan file yang awalnya acak.

---

# 🟦 1. Membuat Folder Utama
```cmd
mkdir MyFiles
cd MyFiles


---

🟦 2. Membuat Minimal 5 Kategori Folder

mkdir Tugas Materi Dokumen Gambar Video

Struktur folder:

MyFiles
 ├── Tugas
 ├── Materi
 ├── Dokumen
 ├── Gambar
 └── Video


---

🟦 3. Membuat File Acak (Sengaja Ditempatkan di Folder Yang Salah)

echo. > Tugas\foto.jpg
echo. > Video\catatan.txt
echo. > Materi\materi.pdf
echo. > Gambar\video.mp4
echo. > Dokumen\tugas.docx

Hasil: file berada di folder yang tidak sesuai.


---

🟦 4. Memindahkan File ke Folder yang Benar

▪ Memindahkan gambar:

move *.jpg Gambar
move *.png Gambar

▪ Memindahkan video:

move *.mp4 Video

▪ Memindahkan dokumen:

move *.txt Dokumen
move *.docx Dokumen
move *.pdf Dokumen

▪ Memindahkan file tugas (jika nama mengandung 'tugas'):

move tugas Tugas


---

🟦 5. Mengecek Hasil Akhir

tree /f

Contoh hasil:

MyFiles
 ├── Tugas
 │     └── tugas.docx
 ├── Materi
 │     └── materi.pdf
 ├── Dokumen
 │     └── catatan.txt
 ├── Gambar
 │     └── foto.jpg
 └── Video
       └── video.mp4


Terakhir buat Folder kuliah
