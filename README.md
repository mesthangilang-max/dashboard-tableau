[README.md](https://github.com/user-attachments/files/21765807/README.md)
# GitHub Pages + Tableau (Starter)
Halaman statis sederhana untuk memuat dashboard Tableau Public menggunakan `iframe`.

## Cara pakai
1. Publikasikan dashboard Anda ke **Tableau Public** atau pastikan link dari **Tableau Cloud/Server** memperbolehkan akses publik/guest.
2. Buka file `index.html`, lalu **ganti** bagian `src="https://public.tableau.com/views/REPLACE_THIS_WITH_YOUR_PATH?:showVizHome=no&:embed=yes"` dengan URL share dari Tableau Anda.
3. Unggah seluruh isi folder ini ke repository GitHub **publik**.
4. Aktifkan **GitHub Pages** di `Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main (/root) → Save`.
5. Akses situs di `https://username.github.io/namarepo/`.

## Tips
- Responsivitas: container memakai `aspect-ratio` agar iframe selalu proporsional.
- Jika tinggi kurang, ubah rasio atau pakai `height: 100vh`.
- Jika iframe diblokir oleh kebijakan server Tableau (X-Frame-Options), minta admin mengaktifkan embedding / guest access.
