```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="pesonaindonesiaa.css">
    <title>Pesona Indonesia</title>
</head>
<body>
   <div class="container">
        
        <div class="kotak">
                <img src="./Aset/Aset6.png" class="logo">
                    <div class="tulisan">
                        <h4 class="teksnavbar">&nbsp;&nbsp;&nbsp;&nbsp;Beranda&nbsp;&nbsp;&nbsp;Berita&nbsp;&nbsp;&nbsp;About&nbsp;&nbsp;&nbsp;&nbsp;</h4>
                        <img src="./Aset/Aset7.png" class="samadengan">
                    </div>
        </div>

        <div class="box1">
            <h1 class="tek1ws2">Selamat Datang di Indonesia!</h1>
             <p class="teks3">Inilah webite yang berisi Keindahan Alam Indonesia.<br>Selamat menikmati Keindahan Indonesia teman-teman :D</p>
             <button class="tombol2">Klik disini!</button>
        </div>

        <div class="box2">
            <h1 class="judul" align="center">Berita</h1>
              <div class="berita">
                    <img src="./Aset/Aset2.jpg" class="gambar">
                    <h2 class="tk">Pantai Kuta</h2> <br>
                    <p class="teks33">Indonesia, dikenal dengan nama resmi Republik Indonesia 
                        atau lebih lengkapnya Negara Kesatuan Republik Indonesia,
                        adalah negara kepulauan di Asia Tenggara yang dilintasi garis khatulistiwa
                        dan berada di antara daratan benua Asia
                        dan Oseania sehingga dikenal sebagai negara lintas benua.</p>
                    <button class="tombol1">Baca selengkapnya >></button>
              </div>

              <div class="berita">
                    <img src="./Aset/Aset3.jpg" class="gambar">
                    <h2 class="tk">Kebun Tetta</h2> <br>
                    <p class="teks33">Indonesia, dikenal dengan nama resmi Republik Indonesia 
                        atau lebih lengkapnya Negara Kesatuan Republik Indonesia,
                        adalah negara kepulauan di Asia Tenggara yang dilintasi garis khatulistiwa
                        dan berada di antara daratan benua Asia
                        dan Oseania sehingga dikenal sebagai negara lintas benua.</p>
                    <button class="tombol1">Baca selengkapnya >></button>
              </div>

              <div class="berita">
                <img src="./Aset/Aset4.jpg" class="gambar">
                <h2 class="tk">Gunung Bromo</h2> <br>
                <p class="teks33">Indonesia, dikenal dengan nama resmi Republik Indonesia 
                    atau lebih lengkapnya Negara Kesatuan Republik Indonesia,
                    adalah negara kepulauan di Asia Tenggara yang dilintasi garis khatulistiwa
                    dan berada di antara daratan benua Asia
                    dan Oseania sehingga dikenal sebagai negara lintas benua.</p>
                <button class="tombol1">Baca selengkapnya >></button>
              </div>

              <div class="berita">
                <img src="./Aset/Aset5.jpg" class="gambar">
                <h2 class="tk">Jekadah!</h2> <br>
                <p class="teks33">Indonesia, dikenal dengan nama resmi Republik Indonesia 
                    atau lebih lengkapnya Negara Kesatuan Republik Indonesia,
                    adalah negara kepulauan di Asia Tenggara yang dilintasi garis khatulistiwa
                    dan berada di antara daratan benua Asia
                    dan Oseania sehingga dikenal sebagai negara lintas benua.</p>
                <button class="tombol1">Baca selengkapnya >></button>
              </div>
        </div>

       

        <div class="box3">
        <h1 class="about">About</h1>
        <div class="teks4">
                <img src="./Aset/Aset8.png" class="gambar1">
                <p class="teks5">Indonesia, dikenal dengan nama resmi Republik Indonesia
                    atau lebih lengkapnya <br> Negara Kesatuan Republik Indonesia,
                    adalah negara kepulauan di Asia Tenggara yang <br> dilintasi garis khatulistiwa
                    dan berada di antara daratan benua Asia dan Oseania <br> sehingga dikenal sebagai negara lintas benua.</p>
            </div>
        </div>

   </div>
</body>
</html>

```
```css
.container{
    width: auto;
    height: auto;
}

 .container >.kotak{
    width: 100%;
    height: 15%;
    position: fixed;
    background-color: white;
    margin-top: -1%;
    z-index: 1;
}

.box  >.tulisan{
    margin-left: 38%;
    font-size: 18px;
    padding-top: 40px;
   font-family: 'Segoe UI';
}

.logo{
    width: 100px;
    height: 100px;
    float: left;
}

.teksnavbar {
  margin-left: 15px;
  margin-top: 40px;
}


.samadengan{
  width: 30px;
  height: 15px;
  margin-left: 220px;
  float: left;
  margin-top: -36px;

}

.box1{
    padding-bottom: 20%;
    padding-top: 10%;
    background-image: url(./Aset/Aset1.jpg);
    width: 100%;
    height: 18%;
    margin-bottom: 40px;
    background-size:cover ;
}

.teks3{
    text-align: center;
    font-size: 15px;
    font-family: 'Segoe UI';
    margin-top: -10px;
}

.teks33{
    text-align: center;
    font-size: 15px;
    font-family: 'Segoe UI';
    margin-top: -5px;
    margin-right: 7px;
}

.teks2{
    margin-top: 150px;
    text-align: center;
    font-family: 'Segoe UI';
}

.teks2{
  color: white;
  text-align: center;
  font-family: 'Segoe UI';
}

.tombol2 {
  color: white;
  background-color: blue;
  width: 110px;
  height: 50px;
  margin-left: 45%;
  border-radius: 5px;
  box-shadow: 2px 2px 2px 2px blue;
  border: none;
  position: flex -15px;
}

.tombol2:hover {
  background-color: burlywood;
  color: black;
  box-shadow: 2px 3px 2px 3px gray;
  transition: all 0.5s ease-in;
}

.berita {
  margin-top: 150px;
    width: 275px;
    height: 520px;
    border-radius: 15px;
    box-shadow: 5px 4px 10px 4px #c7c1c1;
    float: left;
    margin: 16px;
    font-size: 15px;
    padding: 10px 0px 20px 20px;
  }

.tk{
    color: blue;
    font-family: 'Segoe UI';
   margin-bottom: 1px;
   margin-left: 3px;
  }

.gambar{
   width: 265px;
   border-radius: 20px;
   height: 170px;
  }

.tombol1{
    border: none;
    background-color: blue;
    width: 194px;
    height: 50px;
    color:white;
    box-shadow: 2px 3px 2px 3px #4c86df;
    border-radius: 10px;
    margin-top: 1px;
    margin-left: 30px;
  }

.tombol1:hover {
    background-color: burlywood;
    color: black;
    box-shadow: 2px 3px 2px 3px gray;
    transition: all 0.3s ease-in;
  }

  /*.tetx{
    margin-top: -1px;
    padding: 10px 20px 20px 20px;
    font-family: 'Segoe UI';
  }*/

.box3{    
    margin-top: 100px;
    background-color: blue;
    height: 360px;
    width: 100%;
    display: flex;
    flex-direction: column;
  }

.teks4 {
    display: flex;
    flex-direction: row;
}

.gambar1{
    width: 200px;
    height: 200px;
    border-radius: 100px;
    margin-left: 15%;
    margin-top: 50px;
    filter: grayscale(100%);
    margin-top: 0px;
}

.about{
    color: white;
    text-align: center;
    font-family: 'Segoe UI';
    padding-top: 35px;
    margin-top: -5px;
    margin-left: -10px;
  }

.teks5{
    text-align: justify;
    margin-top: 50px;
    font-family: 'Segoe UI';
    color: white;
    margin-left: 5%;
    display: flex;
    flex-direction: column;
  }
  
  .tambahan {
    margin-top: 650px;
    background-color: cadetblue;
    height: 500px;
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
  }
  
  .tomboltambahan{
      border: none;
      background-color: blue;
      width: 194px;
      height: 50px;
      color:white;
      box-shadow: 2px 3px 2px 3px #4c86df;
      border-radius: 10px;
      margin-top: 20px;
      margin-left: 35px;
    }
  
  .tomboltambahan:hover {
      background-color: burlywood;
      color: black;
      box-shadow: 2px 3px 2px 3px gray;
      transition: all 0.5s ease-in;
    }





@media (max-width: 701px){
    .tombol2 {
      margin-left: 275px;
    }

    .logo {
      margin-left: 150px;
    }

    .tulisan {
      margin-left: 150px;
    }

    .gambar1 {
      margin-left: 20px;
    }

    .teks5 {
      margin-top: 25px;
      margin-right: 30px;
    }
}

.{
    width: 145px;
    height: 200px;
    border-radius: 200px;
    margin-left: -150%;
    margin-top: 10px;
   display: flex;
   margin-top: 100px;   
   align-items: center;
  }

.deskripsi{
    margin-left: -350%;
    text-align: center;
    margin-top: 40px;
    font-family: 'Segoe UI';
    color: white;
    border: 10px;
    border-color: white;
    border-radius: 15px;
  }

  .satu {
    width: 100px;

  }

  .dua {
    width: 100px;
    float: left;
  }

  .tiga {
    width: 100px;
    float: left;
  }
```
# analisis program htmlnya
Program HTML di atas adalah sebuah halaman web yang bertujuan untuk menampilkan informasi tentang keindahan alam Indonesia. Berikut adalah analisis mendetail mengenai struktur dan elemen-elemen yang terdapat pada kode tersebut:

1. **Struktur Dasar HTML**:
    
    - Tag `<!DOCTYPE html>` menunjukkan bahwa dokumen ini menggunakan HTML5.
    - Tag `<html>` dimulai dan diakhiri pada baris pertama dan terakhir.
    - Tag `<head>` berisi link ke file CSS eksternal (`pesonaindonesiaa.css`) dan judul halaman (`Pesona Indonesia`).
    - Tag `<body>` memuat konten utama dari halaman web.
2. **Elemen `div.container`**:
    
    - Ini adalah elemen pembungkus utama yang mengandung semua konten halaman.
3. **Bagian Navigasi (`div.kotak`)**:
    
    - Mengandung logo (gambar dengan sumber `./Aset/Aset6.png`) dan teks navigasi (`Beranda`, `Berita`, `About`) yang dirender menggunakan elemen `<h4>`.
    - Gambar `Aset7.png` juga disertakan di dalam `div.kotak`.
5. **Bagian Selamat Datang (`div.box1`)**:
    
    - Mengandung elemen judul `Selamat Datang di Indonesia!` menggunakan tag `<h1>`.
    - Deskripsi singkat tentang keindahan alam Indonesia dalam tag `<p>`.
    - Sebuah tombol (`Klik disini!`) yang menggunakan class `tombol2`.
 5. **Bagian Berita (`div.box2`)**:
    
    - Judul `Berita` ditampilkan di bagian tengah menggunakan tag `<h1>`.
    - Mengandung beberapa `div.berita` yang masing-masing berisi:
        - Gambar destinasi wisata.
        - Judul destinasi (`Pantai Kuta`, `Kebun Tetta`, `Gunung Bromo`, `Jekadah!`).
        - Paragraf deskripsi singkat tentang Indonesia.
        - Tombol `Baca selengkapnya >>` yang menggunakan class `tombol1`.   
6. **Bagian About (`div.box3`)**:
    
    - Judul `About` ditampilkan menggunakan tag `<h1>`.
    - Mengandung gambar (`Aset8.png`) dan deskripsi singkat tentang Indonesia di dalam `div.teks4`.


# analisis cssnya
Program CSS di atas mengontrol tata letak dan tampilan elemen HTML dalam sebuah halaman web. Berikut adalah analisisnya:

1. **.container**: Mengatur lebar dan tinggi elemen container secara otomatis.
2. **.kotak**: Menetapkan lebar 100%, tinggi 15%, posisi tetap (fixed), dan latar belakang putih. Juga menetapkan z-index.
3. **.box .tulisan**: Mengatur tata letak dan gaya font untuk teks dalam sebuah kotak.
4. **.logo**: Mengatur ukuran dan posisi elemen gambar logo.
5. **.teksnavbar**: Menetapkan tata letak dan jarak untuk teks dalam navbar.
6. **.samadengan**: Menetapkan tata letak dan gaya untuk elemen dengan kelas 'samadengan'.
7. **.box1**: Mengatur gambar latar belakang, ukuran, dan tata letak elemen kotak.
8. **.teks2**: Mengatur tampilan dan gaya untuk teks.
9. **.tombol2**: Menetapkan gaya untuk tombol dan efek hover.
10. **.berita**: Menetapkan tampilan untuk elemen berita.
11. **.tk**: Mengatur gaya untuk teks dengan warna biru.
12. **.gambar**: Mengatur ukuran dan sudut lengkung gambar.
13. **.tombol1**: Menetapkan gaya untuk tombol dan efek hover.
14. **.box3**: Mengatur tata letak dan tampilan elemen 'box3'.
15. **.teks4**: Mengatur tata letak dan tampilan untuk teks dalam 'box3'.
16. **.gambar1**: Mengatur ukuran, posisi, dan filter gambar.
17. **.about**: Mengatur gaya untuk teks 'about'.
18. **.teks5**: Mengatur tata letak dan tampilan untuk teks dalam 'teks5'.
19. **.tambahan**: Mengatur tampilan dan tata letak untuk elemen tambahan.
20. **.tomboltambahan**: Menetapkan gaya untuk tombol tambahan dan efek hover.

Terdapat juga beberapa bagian yang di-comment, mungkin merupakan bagian yang sedang dalam pengembangan atau sudah tidak digunakan.


# contoh program 
![](aset/Screenshot_20240520-115728_Acode.jpg)

![](aset/Screenshot_20240520-115731_Acode.jpg)
![](aset/Screenshot_20240520-115740_Acode.jpg)