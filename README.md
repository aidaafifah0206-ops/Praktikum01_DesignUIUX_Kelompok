<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title></title>
</head>

<body>
  <!-- BAGIAN HEADER -->
    <header>
        <!-- Bagian Judul Utama -->
        <div style="text-align: center;">
            <h2>👥</h2> <!-- Icon kelompok (sementara pakai emoji) -->
            <h1>Kelompok 2</h1>
            <p>Desain UI/UX & Pemrograman Web</p>
            <hr width="50px"> <!-- Garis pendek di bawah sub-judul -->
        </div>
    </header>
  <!-- KONTEN UTAMA: DAFTAR ANGGOTA -->
<main>
<!-- BAGIAN INTRO -->
<div class="kotak-intro">
    <span class="icon-intro">👥</span>
    <div>
        <strong style="display: block; margin-bottom: 5px;">Intro / Kata Pengantar</strong>
        <p style="margin: 0; font-size: 14px; color: #000000;">
            Selamat datang di website profil Kelompok 2. Website ini dibuat untuk memenuhi tugas Praktikum 1 Mata Kuliah Desain UI/UX & Pemrograman Web. Di sini berisi informasi mengenai profil singkat dari masing-masing anggota kelompok kami.
        </p>
    </div>
</div>
    <!-- MENGATUR TAMPILAN KOTAK DAN TATA LETAK -->
    <style>
      footer {
    text-align: center;
    padding: 15px;
    margin-top: 30px;
    border-top: 1px solid #ccc;
    color: #666;
}
      .kotak-intro {
    border: 1px solid #ccc;
    border-radius: 8px;
    padding: 10px 15px;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 10px;
      }
       .container-kartu {
    display: flex;
    flex-direction: column;
    gap: 20px;
}

.kartu-anggota {
    width: 100%;
    box-sizing: border-box;
}

        /* Tampilan setiap 1 Kotak Kartu Anggota */
        .kartu-anggota {
            border: 1px solid #ccc; /* Garis pinggir kotak */
            border-radius: 8px;    /* Sudut melengkung */
            padding: 15px;
            width: 100%;            /* Ukuran lebar biar muat 2 kartu menyamping */
            box-sizing: border-box;
        }

        /* Mengatur bagian atas kartu (Foto di kiri, Teks di kanan) */
        .bagian-atas {
            display: flex;
            gap: 15px;
        }

        /* Kotak tempat foto */
        .kotak-foto {
            width: 100px;
            height: 200px;
            border: 1px solid #FFFFFF;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: #b8e9f6;
        }

        /* Bagian biodata sebelah kanan foto */
        .info-biodata {
            flex: 1;
        }

        .header-nama {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .badge-role {
            background-color: #d2ebef;
            padding: 3px 8px;
            border-radius: 12px;
            font-size: 12px;
        }

        /* Garis bawah di dalam kartu */
        .garis-bawah-kartu {
            height: 10px;
            background-color: #e0e0e0;
            margin-top: 15px;
            border-radius: 4px;
        }
    </style> 

    <!-- CONTAINER PEMBUNGKUS KARTU -->
    <div class="container-kartu">

        <!-- KARTU ANGGOTA 1 (KIRI) -->
        <div class="kartu-anggota">
            <div class="bagian-atas">
                <!-- Foto -->
                <div class="kotak-foto">
                    <img src="/images/aida.png" style="width: 100%; height: 100%; object-fit: cover; border-radius: 4px;">
                </div>
                
                <!-- Detail Nama & Biodata -->
                <div class="info-biodata">
                    <div class="header-nama">
                        <strong>Nama Anggota 1</strong>
                        <span class="badge-role">Role</span>
                    </div>
                    <p style="margin: 5px 0;">Nama : Aida Afifah</p>
                    <p style="margin: 5px 0;">NIM : 0110226046</p>
                    <p style="margin: 5px 0;">Program Studi : Teknik Informatika</p>
                    <p style="margin: 5px 0;">Tempat/Tanggal Lahir : Depok,02 Oktober 2006</p>
                    <p style="margin: 5px 0;">Alamat : Jln Kramat Benda VI, No. 88, RT.004/RW.027, Kel Baktijaya, Kec Sukmajaya, Depok</p>
                    <p style="margin: 5px 0;">No HP : 089639706078</p>
                    <p style="margin: 5px 0;">Hobi : Menulis</p>
                  
                </div>
            </div>
            <!-- Elemen dekorasi bawah kartu -->
            <div class="garis-bawah-kartu"></div>
        </div>

        <!-- KARTU ANGGOTA 2 (KANAN) -->
        <div class="kartu-anggota">
            <div class="bagian-atas">
                <!-- Foto -->
                <div class="kotak-foto">
                    <img src="/images/ahmadreza.jpg" style="width: 100%; height: 100%; object-fit: cover; border-radius: 4px;">
                </div>
                
                <!-- Detail Nama & Biodata -->
                <div class="info-biodata">
                    <div class="header-nama">
                        <strong>Nama Anggota 2</strong>
                        <span class="badge-role">Role</span>
                    </div>
                    <p style="margin: 5px 0;">Nama : Ahmad Reza Siregar</p>
                    <p style="margin: 5px 0;">NIM : 0110226155</p>
                    <p style="margin: 5px 0;">Program Studi : Teknik Informatika</p>
                    <p style="margin: 5px 0;">Tempat/Tanggal Lahir : Padangsidimpuan,23 Juli 2008</p>
                    <p style="margin: 5px 0;">Alamat : Jln. Sawo No.30,RT.3/RW.7, Pondok Cina, Depok</p>
                    <p style="margin: 5px 0;">No HP : 085788319418</p>
                    <p style="margin: 5px 0;">Hobi : Main Game</p>
                </div>
            </div>
            <!-- Elemen dekorasi bawah kartu -->
            <div class="garis-bawah-kartu"></div>
        </div>
<!-- KARTU ANGGOTA 3 (Bawah Kiri) -->
        <div class="kartu-anggota">
            <div class="bagian-atas">
                <!-- Foto -->
                <div class="kotak-foto">
                    <img src="/images/ahmad fathur.png" style="width: 100%; height: 100%; object-fit: cover; border-radius: 4px;">
                </div>
                
                <!-- Detail Nama & Biodata -->
                <div class="info-biodata">
                    <div class="header-nama">
                        <strong>Nama Anggota 3</strong>
                        <span class="badge-role">Role</span>
                    </div>
                    <p style="margin: 5px 0;">Nama : Ahmad Fathurrahman Ramdhani</p>
                    <p style="margin: 5px 0;">NIM : 0110226133</p>
                    <p style="margin: 5px 0;">Program Studi : Teknik Informatika</p>
                    <p style="margin: 5px 0;">Tempat/Tanggal Lahir : 27 Oktober 2005</p>
                    <p style="margin: 5px 0;">Alamat : Prov.Kalimantan Barat Kab Sambas Kec.Jawai</p>
                    <p style="margin: 5px 0;">No HP : 085820645698</p>
                    <p style="margin: 5px 0;">Hobi : Olahraga</p>
                </div>
            </div>
            <!-- Elemen dekorasi bawah kartu -->
            <div class="garis-bawah-kartu"></div>
        </div>

        <!-- KARTU ANGGOTA 4 (Bawah Kanan) -->
        <div class="kartu-anggota">
            <div class="bagian-atas">
                <!-- Foto -->
                <div class="kotak-foto">
                    <img src="/images/agung.png" style="width: 100%; height: 100%; object-fit: cover; border-radius: 4px;">
                </div> 
                
                <!-- Detail Nama & Biodata -->
                <div class="info-biodata">
                    <div class="header-nama">
                        <strong>Nama Anggota 4</strong>
                        <span class="badge-role">Role</span>
                    </div>
                    <p style="margin: 5px 0;">Nama : Agung Satriawan</p>
                    <p style="margin: 5px 0;">NIM : 0110226068</p>
                    <p style="margin: 5px 0;">Program Studi : Teknik Informatika</p>
                    <p style="margin: 5px 0;">Tempat/Tanggal Lahir : Tegal, 13 Juli 2008</p>
                    <p style="margin: 5px 0;">Alamat : Jln. Menpor Palsigunung No.01C, RT.05/RW.03, Tugu, Kec. Cimanggis, Kota Depok, Jawa Barat 16451</p>
                    <p style="margin: 5px 0;">No HP : 083832546699</p>
                    <p style="margin: 5px 0;">Hobi : Baca Buku</p>
                </div>
            </div>
            <!-- Elemen dekorasi bawah kartu -->
            <div class="garis-bawah-kartu"></div>
        </div>
    </div>
</main>
  <!-- BAGIAN FOOTER -->
<footer>
  <p>Copyright &copy; 2026 Kelompok 2 Desain UI/UX</p>
</footer>

</html>
