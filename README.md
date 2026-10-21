# NinjaTravel Platform — Interactive Demo

Prototype presentasi NinjaTravel berdasarkan arahan UI/UX dan pilihan scope proyek.

## Modul
- Public Website: landing page, pencarian paket, destinasi, detail paket, dan promo.
- Core Admin: dashboard analytics, partner approval, konten/promo, membership, dan simulasi SaaS billing hybrid.
- Travel Partner: dashboard, paket, booking, pelanggan, dan estimasi billing.
- Member: register/login demo, membership benefit, dan riwayat booking.

## Menjalankan demo
Repository ini menggunakan HTML/CSS/JavaScript statis, tanpa framework dan tanpa proses build. Buka `index.html` atau aktifkan GitHub Pages pada Settings → Pages → Deploy from a branch → Branch `main` → Folder `/ (root)`.

## Penting
Ini adalah **prototype demonstrasi**, bukan sistem produksi. Data bersifat simulasi dan perubahan tersimpan hanya dalam sesi/browser yang aktif. Login tidak melakukan autentikasi sesungguhnya. Jangan gunakan password atau data pribadi nyata. Backend dan database diperlukan untuk authentication, penyimpanan bersama, authorization, CMS persisten, audit log, dan invoice produksi.

Tarif contoh billing saat ini dapat diubah pada demo:
- Biaya dasar bulanan per partner: IDR 350.000
- Biaya per penumpang: IDR 2.500
- Rumus: biaya dasar + (tarif penumpang × penumpang tertagih)

Angka tersebut hanya untuk diskusi presentasi dan bukan keputusan harga final.
