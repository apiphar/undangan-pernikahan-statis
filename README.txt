# Undangan Pernikahan Digital

Website statis 1 file (`index.html`), responsif untuk desktop dan mobile.

## Cara pakai
1. Buka `index.html` di browser.
2. Ganti nama mempelai, tanggal, venue, nama orang tua, dan link Google Maps.
3. Ganti nomor WhatsApp di fungsi `sendRSVP()`.
4. Untuk musik, tambahkan `music.mp3` di folder yang sama lalu ubah:
   `<audio id="music" loop>`
   menjadi:
   `<audio id="music" loop src="music.mp3">`
5. Untuk foto, ganti elemen `.photo` dengan `<img src="foto1.jpg">` dan seterusnya.

## Upload gratis
Bisa di-host sebagai static site di GitHub Pages, Netlify, Vercel, atau hosting biasa.
