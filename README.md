# NoteBoard — Pusat Catatan & Deadline

Aplikasi manajemen catatan dan deadline dalam **satu file HTML**. Tanpa server, tanpa instalasi, tanpa internet. Cukup *double click* `index.html` dan langsung jalan di browser.

> Dibangun dengan HTML, CSS, dan JavaScript murni (Vanilla JS). Data tersimpan di `localStorage` browser dan **auto-save** di setiap perubahan.

---

## Cara Pakai

1. Unduh atau clone repo ini.
2. Buka file `index.html` (double click).
3. Login dengan akun default:
   - **Username:** `admin`
   - **Password:** `admin123`

Atau jalankan langsung lewat tautan **GitHub Pages** (lihat bagian bawah).

---

## Fitur

- **Login** sederhana berbasis `localStorage`
- **Dashboard** statistik otomatis (total, baru, diproses, selesai, deadline hari ini, deadline terlewat)
- **Catatan** dengan CRUD penuh: tambah, edit, hapus, duplikat, arsip, favorit, pin, checklist
- **Auto-save** — setiap perubahan langsung tersimpan, tanpa tombol Save
- **Timeline** riwayat aktivitas setiap catatan
- **Kalender** bulanan untuk semua deadline
- **Pencarian instan** di judul, isi, tag, dan kategori
- **Filter & sort** (status, hari ini, besok, minggu ini, terlewat, favorit)
- **Backup**: export & import JSON
- **Export**: JSON, CSV, HTML, dan PDF (via print)
- **Pengaturan**: dark/light mode, warna aksen, ukuran font, konfirmasi hapus
- **Keyboard shortcut**: `Ctrl+N` (catatan baru), `Ctrl+F` (cari), `Ctrl+D` (duplikat), `Delete` (hapus), `Esc` (tutup)
- UI modern: glassmorphism, gradien, sidebar collapsible, FAB, toast, modal, loading screen

---

## Teknologi

| Aspek | Detail |
|-------|--------|
| Bahasa | HTML5, CSS3, JavaScript (ES6) |
| Penyimpanan | `localStorage` (browser) |
| Dependensi | Tidak ada — 100% vanilla, single file |
| Deploy | Cukup buka file, atau GitHub Pages |

---

## Menjalankan via GitHub Pages

Aktifkan di **Settings → Pages → Source: branch `main` / root**. Setelah aktif, aplikasi bisa diakses dari:

```
https://kusumaeditz.github.io/noteboard/
```

---

## Catatan & Batasan

- Password disimpan sebagai teks biasa di `localStorage`. Aplikasi ini ditujukan untuk pemakaian lokal pribadi — **jangan menyimpan data sensitif**.
- Font Inter / Plus Jakarta Sans memakai *fallback* font sistem agar tetap berjalan offline.
- Export PDF menggunakan dialog cetak browser (Save as PDF).

---

## Lisensi

Bebas digunakan dan dimodifikasi untuk keperluan pribadi.
