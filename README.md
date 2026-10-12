# Dashboard Alumni – Tracer Study (Vue 3 + Chart.js, tanpa build)
Struktur: index.html · css/style.css · js/config.js · js/app.js · data/alumni.json · apps-script/Code.gs

## Menyambungkan Google Sheets
1. Buka Sheet respons Form → Ekstensi → Apps Script → tempel `apps-script/Code.gs`.
2. Deploy → Aplikasi web → Jalankan sebagai: Saya, Akses: Siapa saja → salin URL.
3. Isi `DATA_URL` di `js/config.js` dengan URL tersebut. Sheet tetap privat; telepon, email, gaji individual, dan nama atasan tidak pernah dikirim ke browser.

## Menjalankan
Deploy statis (Vercel) atau lokal: `npx serve .` (jangan buka lewat file://, karena fetch diblokir).
