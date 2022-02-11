# GitHub Branch
### Rangkuman oleh Dean Hartono

<p>&nbsp;</p>

## Video yang dirangkum
[#3 GITHUB : BRANCH](https://www.youtube.com/watch?v=k1QXd-8VbPY&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=3)

<p>&nbsp;</p>

## Membuat Branch
### Cara 1
1. Buat file atau pilih sebuah file untuk diedit
2. Pada bagian bawah, pilih opsi untuk membuat branch
3. Tekan "Commit new file", maka commit tercatat sebagai branch
### Cara 2
1. Pada halaman utama repository, tekan opsi branch di bagian kiri atas
2. Ketikkan nama branch untuk membuat atau masuk ke branch dengan nama tersebut
3. Buat atau edit file seperti biasanya dan otomatis commitnya tercatat pada branch yang dipilih

<p>&nbsp;</p>

## Merge Branch
1. Pada halaman utama di suatu branch, pilih "Compare & pull request"
2. Masukkan judul dan deskripsi secukupnya untuk disampaikan kepada pemilik master branch, bagian ini dapat dilewati jika merge dilakukan langsung oleh pemilik
3. Pilih "Create pull request"
##### Bagian selanjutnya dilakukan oleh pemilik master branch
4. Pada halaman utama, pilih menu "Pull requests"
5. Tekan request yang ingin di-merge untuk melihat detailnya
6. Dua kemungkinan:
    - Merge dapat dilakukan, jika perubahan dirasa cocok, langsung tekan "Merge pull request"
    - Merge tidak dapat dilakukan (e.g. terdapat bagian yang ada pada master tetapi tidak ada pada modifikasi di branch dan sebaliknya), edit hingga dirasa sesuai, baru kemudian tekan "Merge pull request"
7. Merge selesai, branch yang telah di-merge tidak terpakai lagi dan dapat dihapus melalui menu "Branches" pada halaman utama
