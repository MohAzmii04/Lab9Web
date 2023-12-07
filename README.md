# Lab9web

Nama : Mohammad Azmi Abdussyukur

NIM  : 312210109

Kelas : TI.22.A1

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Instruksi Praktikum|[Click Here](#instruksi-praktikum)|
|2|Langkah-langkah Praktikum|[Click Here](#langkah-langkah-praktikum)|
|3|Pertanyaan dan Tugas|[Click Here](#pertanyaan-dan-tugas)|

## Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode

2. Buat folder baru dengan nama `lab9_php_modular` pada docroot webserver (htdocs)

3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya

## Langkah-langkah Praktikum
- Jalankan Apache dan MySQL server dari menu XAMPP Control
- Kemudian buat folder baru dengan nama lab9_php_modular pada docroot webserver (c:\xampp\htdocs). Kemudian buka melalui browser dengan mengakses URL: http://localhost/lab9_php_modular/.

![1](https://github.com/syifaaurellia/Lab9web/assets/115867244/ab5f4256-e26d-47be-974b-67e51867e1aa)

1. Buat file dengan nama `header.php`
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text/stylesheet" media="screen" />
</head>
<body>
    <div class="container">
        <header>
            <h1>Modularisasi Menggunakan Require</h1>
        </header>
        <nav>
            <a href="home.php">Home</a>
            <a href="about.php">Tentang</a>
            <a href="kontak.php">Kontak</a>
        </nav>
```

2. Buat file dengan nama `footer.php`
```
        <footer>
            <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>
```

3. Buat file dengan nama `home.php`
```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

4. Buat file dengan nama `about.php`
```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

- Output halaman `Home` :
![2](https://github.com/syifaaurellia/Lab9web/assets/115867244/c1058bc0-3584-4a84-865d-046af8369cfc)


- Output halaman `About` :
![3](https://github.com/syifaaurellia/Lab9web/assets/115867244/51313ca1-49ee-4552-914e-6e2abc1ce828)


## Pertanyaan dan Tugas
> Implementasikan konsep modularisasi pada kode program Praktikum 8 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama.

1. Buat folder baru dengan nama `lab9_php_praktikum`
![4](https://github.com/syifaaurellia/Lab9web/assets/115867244/f79373d0-08c9-4b93-9d46-7e7d11ac8e0a)

- Setelah itu buat beberapa file sama seperti file-file yang ada pada praktikum 8, untuk script lebih lengkapnya kalian dapat langsung lihat pada folder [lab9_php_praktikum](https://github.com/syifaaurellia/Lab9web/tree/main/lab9_php_praktikum).

2. Hasil Output `koneksi.php` :
![5](https://github.com/syifaaurellia/Lab9web/assets/115867244/e5ab73df-70c2-46df-b2ca-3e5209718cf2)

3. Hasil Output `home.php` :
<img width="960" alt="database2" src="https://github.com/MohAzmii04/Lab9Web/assets/115864496/9384e9b2-e61b-472f-b4a9-70cb512a5bfc">

4. Hasil Output `tambah.php` :
   
<img width="960" alt="tambah barang" src="https://github.com/MohAzmii04/Lab9Web/assets/115864496/0327cba9-9295-4282-b27f-b5d3572532e9">

5. Hasil Output `ubah.php` :
<img width="960" alt="database2" src="https://github.com/MohAzmii04/Lab9Web/assets/115864496/c9ebac2c-4a89-4337-b3d0-fc66fd0abc73">

6. Hasil Output `hapus.php` :
<img width="960" alt="database2" src="https://github.com/MohAzmii04/Lab9Web/assets/115864496/bcb1617b-7f24-445e-8ca8-930742d1b1b8">

## Finish, Terima Kasih
