# Buggy Puzzle

**Buggy Puzzle** adalah web puzzle sederhana untuk menyusun potongan gambar “Buggy” agar terlihat utuh dan masuk akal.

## Preview Fitur
- Tampilan puzzle berbasis **CSS Grid**
- Potongan gambar Buggy disusun dalam beberapa tile
- Bagian **Reference** untuk melihat gambar acuan
- Copyright year otomatis (mengambil tahun dari `Date()`)

## Tahap Pengerjaan (Cara Main)
1. Buka halaman **Buggy Puzzle**.
2. Perhatikan bagian **Reference** (gambar acuan).
3. **Susun puzzle supaya jadi benar**: atur/posisikan potongan-potongan gambar Buggy hingga membentuk gambar yang sesuai dengan reference dengan mengedit HTML dan CSS nya menggunakan Prinsip Grid Layout.
4. Jika sudah tersusun dengan benar, puzzle terlihat utuh dan “make sense”.

## Struktur Folder
- `index.html` — halaman utama
- `src/style.css` — styling utama
- `assets/` — aset gambar (icon, potongan puzzle, reference, favicon, dll.)

## Cara Menjalankan (Local)
Karena ini static website, kamu bisa menjalankannya langsung tanpa install dependencies.

### Opsi 1 — Buka langsung
1. Download / clone repo ini
2. Buka file `index.html` di browser

### Opsi 2 — Pakai Live Server (disarankan)
Kalau kamu pakai VS Code:
1. Install extension **Live Server**
2. Klik kanan `index.html` → **Open with Live Server**

## Catatan
- Styling ada di `src/style.css`
- Semua gambar puzzle mengarah ke folder `assets/img/`

---

© Buggy Pirates x National University of Sumedang
