# Basic Git
### Rangkuman oleh Dean Hartono

<p>&nbsp;</p>

## Video yang dirangkum
[#5 BEKERJA DENGAN GIT](https://www.youtube.com/watch?v=e-6OkXRqWaE&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=5)

<p>&nbsp;</p>

## Menginstal Git
1. Unduh Git dari https://git-scm.com/
2. Pasang aplikasi pada perangkat dengan mengikuti proses instalasi, set-up standar bawaan cukup

## Manajemen Kerja Git
### Segmentasi area
1. Working tree: keseluruhan repository tempat Git bekerja
2. Staging area: area tempat file-file baru atau berubah dipantau Git
3. History: catatan Git tentang perubahan-perubahan file melalui commit
### Menetapkan repository yang dijadikan working tree
1. Buka Command Prompt atau Git Bash
2. Pilih tempat working tree dengan perintah ``` cd <location_path> ```
3. Terakhir, tetapkan sebagai working tree dengan perintah ``` git init ```
### Meletakkan file pada staging area
1. Dianjurkan memeriksa kondisi isi repository dengan ```git status```
2. Jika terdapat file yang belum dimasukkan ke staging area, masukkan dengan perintah ```git add <file_name>``` atau ```git add .``` untuk memasukkan semua file pada repository
3. Dianjurkan memeriksa kembali perubahan dengan ```git status```
### Melakukan commit, menjadikan perubahan file sebagai history
1. Jika semua file telah siap, lakukan perintah ```git commit -m "commit message"``` untuk melakukan commit
2. Gunakan perintah ```git log``` untuk melihat riwayat commit beserta pesan yang dibuat dan seri *hash*-nya

<p>&nbsp;</p>

## Gambar Pendukung
[Ilustrasi 1](https://ibb.co/6PJ3tmZ)
[Ilustrasi 2](https://ibb.co/ZHNMdd7)
