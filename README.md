# Soal ujian Akhir Semester Cloud Computing
Cara menggunakana git dan push ke repository di github

## Cara menambahkan repository Di local 
```
git init
```
## Cara melihat status
```
git status
```
## Cara menambahkan file dari working area ke stagging area
```
git add <file> 
```
atau 
```
git add .
```
## Cara Membuat commit 
```
git commit -m "Masukkan Pesan Commit Disini"
```
## Cara melihat log aktifitas
### semua log aktifitas
```
git log
```
### Mengambil 3 log aktifitas terakhir 
```
git log -3
```
## Cara Membuat Branch Baru 
```
git branch nama_branch
```
## Cara melihat branch yang sedang aktif ditandai dengan (*)
```
git branch
```
## Cara berpindah ke branch lain
```
git checkout nama_branch

```
## cara mengembalikan file yang terhapus berdasarkan waktu commit

### Melihat status file yang terhapus
```
git log -- nama_file_terhapus

```
### Mengembalikan file yang terahapus berdasarkan 5 kode dari hash commit 
```
git checkout 5_kode -- nama_file_terhapus

```
## Menampilkan tampilan graph
```
git log --all --decorate --oneline --graph

```
## Merge Branch
```
git merge nama_branch

```

## Melihat branch yang sudah di merge
```
git branch --merged

```
## Push Ke repository github

### Remote repository github
```
git remote add origin <link repository github>

```
### Samakan branch local dengan branch di repository github
```
git branch -M main

```

### Push Repository Local ke Repository Github
```
git push -u origin main

```



