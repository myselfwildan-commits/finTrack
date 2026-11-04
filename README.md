# FinTrack

Finance tracker sederhana menggunakan React, Vite, Tailwind CSS, dan LocalStorage.

## Struktur

```text
finance-tracker/
├── public/
├── src/
│   ├── project/
│   │   ├── App.jsx
│   │   ├── financeSummary.jsx
│   │   ├── transactionForm.jsx
│   │   └── transactionList.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── vercel.json
└── vite.config.js
```

## Jalankan lokal

Node.js 18+ diperlukan.

```bash
npm install
npm run dev
```

Build production: `npm run build`.

## Deploy Vercel

Import repository GitHub ke Vercel. Framework: Vite, Build Command: `npm run build`, Output Directory: `dist`.

## Fitur

- Ringkasan saldo, pemasukan, pengeluaran, dan sisa bulan berjalan.
- Tambah, edit, hapus transaksi.
- Kategori pemasukan dan pengeluaran.
- Filter bulan, jenis transaksi, dan pencarian.
- Ringkasan pengeluaran per kategori.
- Export CSV untuk transaksi yang sedang ditampilkan.
- Auto-save LocalStorage.

Data tersimpan di browser/perangkat yang digunakan, bukan sinkron antarperangkat.
