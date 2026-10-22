# Blue Sky Hotel – Web App

Web statis (HTML + CSS + JS, tanpa build) untuk alur Tamu dan Admin/Resepsionis.

## Akun demo
- Tamu: email apa saja + kata sandi minimal 4 karakter
- Admin: `admin@bluesky.com` / `admin123`

## Deploy
1. Buat repo GitHub, unggah `index.html` dan `README.md`.
2. Di vercel.com: Add New → Project → pilih repo → Deploy (Framework: Other, tanpa build command).

## Catatan
Data tersimpan di `localStorage` browser. Pesanan tamu dan persetujuan admin
tersinkron antar tab di browser yang sama. Untuk sinkron antar perangkat,
hubungkan ke database (mis. Supabase atau Vercel KV).
