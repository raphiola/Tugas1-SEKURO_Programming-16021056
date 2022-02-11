# .gitignore
### Rangkuman oleh Dean Hartono

<p>&nbsp;</p>

## Video yang dirangkum
[#12 GITIGNORE](https://www.youtube.com/watch?v=LK3kX4n-vLM&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=12)

<p>&nbsp;</p>

## Definisi
Gitignore adalah cara agar Git mengabaikan file-file tertentu pada repository sehingga perubahannya tidak dipantau oleh Git. Hal ini dapat membantu salah satunya agar tidak perlu memasukkan satu-persatu file dengan ```git add <file_name>``` melainkan cukup ```git add .``` (memasukkan semua) dan membuat gitignore agar file tertentu yang diinginkan tidak masuk.

<p>&nbsp;</p>

## Cara Kerja
1. Pada repository, buat sebuah folder dengan nama ".gitignore"
2. ketikkan nama-nama file yang ingin diabaikan Git
3. Selesai, dapat dibuktikan dengan langsung mencoba perintah-perintah Git seperti ```git status``` dan ```git commit -m "pesan commit"```

## Gambar Ilustrasi
[Ilustrasi](https://ibb.co/0Y965tC)
