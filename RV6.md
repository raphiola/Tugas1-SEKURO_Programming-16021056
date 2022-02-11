# Git Branch
### Rangkuman oleh Dean Hartono

<p>&nbsp;</p>

## Video yang dirangkum
[#6 GIT BRANCH & MERGE](https://www.youtube.com/watch?v=EGl7KxVOyNs&list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf&index=6)

<p>&nbsp;</p>

## Membuat Branch
1. Buat branch dengan perintah ```git branch <branch_name>```
2. Branch yang ada dapad diperiksa dengan perintah ```git branch```, hal ini sekaligus dapat memeriksa keberhasilan pembuatan branch

## Bekerja pada Branch
1. Pindah ke branch yang dijadikan tempat bekerja dengan perintah ```git checkout <branch_name>```
2. Bekerja mengedit, menambah, dan menghapus file seperti biasa, layaknya pada branch master (sesuai penjelasan RV5.md)

## Merge Branch
1. Jika setelah bekerja pada branch, kembali dahulu ke branch master dengan perintah ```git checkout master```
2. Satukan master dengan pekerjaan pada branch dengan perintah ```git merge <branch_name>```
3. Keberhasilan penyatuan dapat diperiksa dengan perintah ```git branch --merged```

## Delete Branch
1. Jika branch telah dimerge, dapat dihapus dengan cara ```git branch -d <branch_name>```
2. Untuk sembarang branch, perintah ```git branch -D <branch-name>``` dapat menghapus branch tersebut

## Gambar Ilustrasi
[Ilustrasi](https://ibb.co/gJswDtG)
