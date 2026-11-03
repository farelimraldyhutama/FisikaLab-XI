# FisikaLab XI

Website pembelajaran fisika kelas XI dalam satu file HTML mandiri.

## Isi paket
- `index.html` — aplikasi utama FisikaLab XI.
- `.nojekyll` — membantu GitHub Pages menyajikan berkas statis tanpa pemrosesan Jekyll.

## Cara memasang ke GitHub Pages
1. Buat repository baru di GitHub, misalnya `fisikalab-xi`.
2. Ekstrak ZIP ini.
3. Unggah `index.html` dan `.nojekyll` ke direktori utama (root) repository.
4. Buka **Settings → Pages**.
5. Pada **Build and deployment**, pilih **Deploy from a branch**.
6. Pilih branch `main` dan folder `/ (root)`, lalu tekan **Save**.
7. Tunggu proses deployment selesai. Alamat situs akan ditampilkan pada halaman Settings → Pages.

## Menjalankan secara lokal
Buka `index.html` di browser. Aplikasi ini dikemas sebagai HTML mandiri dan tidak memerlukan proses build.

## Catatan
- Paket ini mempertahankan versi aplikasi yang diberikan; tidak ada perubahan fitur atau desain dalam proses pengemasan.
- GitHub Pages memerlukan koneksi internet untuk pertama kali mengakses situs. Paket ini belum dikonfigurasi sebagai PWA dengan cache offline otomatis.
- Uji kembali fitur interaktif di browser desktop dan ponsel setelah dipublikasikan.
