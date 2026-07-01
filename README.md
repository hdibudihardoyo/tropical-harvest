# 🌴 TropicalHarvest

Website modern untuk perusahaan ekspor buah Indonesia yang dibangun menggunakan **HTML**, **Tailwind CSS v4 (CLI)**, dan **JavaScript**.

---

## 📋 Prasyarat

Pastikan telah menginstal:

- **Node.js** v18 atau lebih baru
- **npm**

Cek versi:

```bash
node -v
npm -v
```

---

## 🚀 Instalasi

### 1. Clone repository

```bash
git clone https://github.com/username/namerepository.git
```

Masuk ke folder project:

```bash
cd namerepository
```

---

### 2. Install dependencies

```bash
npm install
```

Jika belum menginstal Tailwind CSS CLI, jalankan:

```bash
npm install tailwindcss @tailwindcss/cli
```

---

## 🎨 Konfigurasi Tailwind CSS

Pastikan file **`src/input.css`** berisi:

```css
@import "tailwindcss";
```

---

## ▶️ Menjalankan Project

Jalankan Tailwind CSS CLI dalam mode **watch**:

```bash
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

Atau jika project sudah memiliki script pada `package.json`:

```bash
npm run dev
```

Kemudian buka:

```
src/index.html
```

menggunakan **Live Server** atau web server lokal lainnya.

---

## 📝 Catatan

- Folder `node_modules/` tidak disertakan dalam repository.
- Setelah melakukan clone project, jalankan:

```bash
npm install
```

- Biarkan terminal tetap berjalan saat menggunakan mode `--watch`.
- Pastikan file `index.html` telah memuat stylesheet hasil kompilasi:

```html
<link rel="stylesheet" href="./output.css" />
```

---