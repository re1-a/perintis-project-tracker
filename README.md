# Perintis Didik — Ruang Projek

Website statik BM untuk melihat proses dan pending projek laporan perkembangan murid. Diterbitkan melalui GitHub Pages; tiada kebergantungan ChatGPT, AI, database atau server rumah.

## Kemampuan

- Ringkasan, lima fasa, butiran sembilan tugasan awal, pemilik dan status.
- Rajah workflow enam langkah beranak panah; peranan cikgu/sistem, butiran input/hasil/pending dan pautan tugasan.
- Dua paparan proses: cara penggunaan sistem yang dicadangkan dan pelan pembangunan projek.
- Tapisan pemilik/status, carian dan paparan catatan/keputusan.
- Mod cerah/gelap, pilihan disimpan pada peranti.
- Pautan awam mesra telefon, tanpa akaun untuk melihat.

## Kemas kini

`project.json` ialah rekod kandungan yang diterbitkan, termasuk enam langkah dalam `workflow`. Semua fungsi sistem dalam rajah ialah cadangan; rajah bukan automation yang sudah berjalan. Ubah status, pemilik, penerangan dan `updatedAt`, kemudian commit/push ke `main`. GitHub Pages menerbitkan semula website. Browser kedua melihat kandungan terbitan yang sama selepas refresh.

Tiada perubahan status atau komen terus pada website. Jangan tambah borang yang berpura-pura menyimpan rekod bersama melalui localStorage. Jangan letak token GitHub dalam browser.

## Kandungan awam sahaja

Repository dan laman ini awam. Jangan masukkan data murid, akaun pengguna, fail kertas murid, nombor telefon peribadi, credential, harga perjanjian sulit atau catatan peribadi. Laman ini bukan sistem rekod akademik atau produk SaaS berbayar.

## Pratonton

Jalankan `python3 -m http.server 5182 --bind 127.0.0.1` dari folder ini dan buka alamat server. Membuka `index.html` terus sebagai fail mungkin menyekat fetch JSON.

## Penerbitan

GitHub Pages menggunakan branch `main`, root folder `/`, dan `.nojekyll`. Semua pautan aset relatif supaya berfungsi pada URL subfolder Pages. Fail source platform lama dan data D1 tidak diimport ke repository ini.
