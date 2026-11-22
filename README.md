# Borang Audit Pengeluaran

Aplikasi satu fail (`index.html`) untuk menyediakan muka depan dokumen audit pembelanjaan:

- **Halaman 1 – A4 landskap**: tahun, pengeluaran ke-, tarikh, amaun, baki sebelum, pembelanjaan, baki dibawa kehadapan, tandatangan.
- **Halaman 2 – A4 potret**: tajuk projek, senarai perkara dengan pecahan a, b, c… dan jumlah.

## Cara guna
Buka `index.html` dalam Chrome / Edge. Panel kiri ada 4 tab:

| Tab | Fungsi |
|---|---|
| **Isi borang** | Isi maklumat. Tambah/buang/susun amaun, perkara dan pecahan. Setiap amaun boleh tulis formula (`1200+350*2`, `4 x 125.50`, `5000*6%`). Pecahan boleh ada amaun dan dicampur automatik. |
| **Kalkulator** | Semakan logik (Baki sebelum + Pengeluaran − Pembelanjaan = Baki) dengan amaran jika tidak tepat. Kalkulator resit: hantar jumlah ke perkara / pembelanjaan / amaun, atau hantar setiap baris sebagai pecahan. |
| **Tulisan & margin** | Jenis tulisan, jarak baris, skala, margin (mm) setiap halaman, jarak antara baris, jajaran, saiz/tebal/condong/garis bawah setiap elemen, label, gaya nombor. |
| **Simpanan** | Simpan/buka sandaran `.json`. |

**Cetak** menetapkan orientasi setiap halaman secara automatik. **Muat turun PDF** menjana PDF terus (perlu internet kali pertama).
**+ Baru** mewarisi gaya rekod semasa dan mengambil bakinya sebagai *baki sebelum*.
