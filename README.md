# Lab9Web
## Nama   : Luthfi Al Ridwan
## NIM    : 312010112
## Kelas  : TI.20.A.1
## Matkul : Pemrograman Web

# Buat file baru dengan nama header.php seperti berikut :

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <title>Contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text/stylesheet"
    media="screen" />
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
    
 # Buat file baru dengan nama footer.php seperti berikut :
 
     <footer>
    <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
    </footer>
    </div>
    </body>
    </html>
    
 # Buat file baru dengan nama home.php seperti berikut :
 
    <?php require('header.php'); ?>
    <div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
    </div>
    <?php require('footer.php'); ?>
    
 # Buat file baru dengan nama about.php seperti berikut :
 
    <?php require('header.php'); ?>
    <div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
    </div>
    <?php require('footer.php'); ?>
    
 # Berikut adalah tampilan dari home.php :
 
 ![1 - Home](https://user-images.githubusercontent.com/73066008/171527079-df8918cd-e044-49cd-a2c7-4d67af4cb2ff.png)
