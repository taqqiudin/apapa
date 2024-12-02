
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pembelajaran Fungsi Linear Kelas 8 SMP</title>
    <style>
        /* Pengaturan umum untuk seluruh halaman */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #e0f7fa, #ffffff);
            min-height: 100vh;
        }

        header {
            background: #007bff;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background: #333;
            padding: 10px 0;
        }

        nav a {
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            text-align: center;
            display: inline-block;
        }

        nav a:hover {
            background: #575757;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .line {
            position: absolute;
            left: 0;
            top: 0;
            width: 5px;
            height: 30px; /* Membatasi tinggi garis ke area judul */
            background: #007bff;
        }

        h2 {
            color: #007bff;
            position: relative;
            padding-left: 20px;
        }

        .video iframe {
            width: 100%;
            height: 315px;
        }

        .latihan, .bentuk, .rumus {
            background-color: #f9f9f9;
            border-left: 5px solid #007bff;
            padding: 10px;
            margin: 20px 0;
        }

        .jawaban {
            background-color: #f0f0f0;
            border-left: 5px solid #28a745;
            padding: 10px;
            margin: 10px 0;
        }

        /* Gambar latar belakang */
        .bg-image {
            position: relative;
            height: 400px;
            overflow: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .bg-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            opacity: 0.8;
        }

        .welcome-text {
            position: absolute;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
            font-size: 2.5rem;
            animation: bounce 1s infinite;
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-20px);
            }
            60% {
                transform: translateY(-10px);
            }
        }

        /* Menambahkan responsivitas untuk perangkat kecil */
        @media (max-width: 768px) {
            body {
                padding-top: 56px;
            }

            header h1 {
                font-size: 1.8rem;
            }

            nav {
                flex-direction: column;
            }

            nav a {
                padding: 12px;
                text-align: left;
                width: 100%;
                border-bottom: 1px solid #ccc;
            }

            .container {
                max-width: 100%;
                padding: 10px;
            }

            .bg-image {
                height: 250px;
            }

            .welcome-text {
                font-size: 1.8rem;
                text-align: center;
            }

            .video iframe {
                height: 250px;
            }

            .latihan, .bentuk, .rumus {
                padding: 8px;
            }
        }

        @media (max-width: 480px) {
            body {
                padding-top: 56px;
            }

            header {
                padding: 15px;
            }

            nav a {
                padding: 10px;
            }

            h2 {
                font-size: 1.4rem;
            }

            .video iframe {
                height: 200px;
            }

            .welcome-text {
                font-size: 1.5rem;
                text-align: center;
            }

            .latihan, .bentuk, .rumus {
                padding: 6px;
            }

            .bg-image img {
                height: 250px;
            }
        }
    </style>
</head>
<body>

    <main class="container mt-5 content">
        <div class="bg-image">
            <img src="fkip1.jpg" alt="Mathematics Image"> 
            <h2 class="welcome-text"><i class="icon fa fa-book"></i> Selamat datang brooo!</h2>
        </div>
        <header>
            <h1>Pembelajaran Fungsi Linear Kelas 8 SMP</h1>
        </header>
        
        <nav>
            <a href="#pengantar">Pengantar Fungsi Linear</a>
            <a href="#grafik">Bentuk Fungsi Linear</a>
            <a href="#bentuk">Grafik Fungsi Linear</a>
            <a href="#contoh">Contoh Soal</a>
            <a href="#latihan">Latihan</a>
            <a href="#latihan">GeoGebra</a>
        </nav>
        
        <div class="container">
            <section id="pengantar">
                <div class="line"></div>
                <h2>Pengantar Fungsi Linear</h2>
                <div class="Pengertian">
                    <p>Fungsi linear adalah suatu jenis fungsi matematis yang menggambarkan hubungan antara dua variabel, yaitu variabel independen (sering disebut 𝑥) dan variabel dependen (sering disebut 𝑦).</p>
                </div>
                <div class="video">
                    <iframe src="https://www.youtube.com/embed/-x96E4ytpeI?si=ffBjI8hRx0jpACZq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <p>Materi: Pengenalan fungsi linear dan konsep dasar. Fungsi linear adalah fungsi yang memiliki grafik berbentuk garis lurus.</p>
                </div>
            </section>
        
            <section id="bentuk">
                <div class="line"></div>
                <h2>Bentuk Fungsi Linear</h2>
                <div class="bentuk">
                    <h3>Bentuk dan Contoh:</h3>
                    <p>Fungsi linear dapat dinyatakan dalam bentuk :</p>
                    <ul>
                        <strong>y = mx + c</strong>
                        <p><strong>Dimana:</strong></p>
                        <li>y adalah variabel dependen.</li>
                        <li>𝑥 adalah variabel independen.</li>
                        <li>𝑚 adalah kemiringan (gradien) garis, yang menunjukkan seberapa banyak nilai 𝑦 berubah ketika 𝑥 bertambah satu satuan.</li>
                        <li>𝑐 adalah titik potong pada sumbu 𝑦, yaitu nilai 𝑦 ketika 𝑥 = 0.</li>
                    </ul>
                </div>
                <div class="video">
                    <iframe src="https://www.youtube.com/embed/VyHgCGgoOxE?si=BU5YqYgKHFD6nAAN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <p>Materi: Memahami rumus fungsi linear dan aplikasinya dalam menyelesaikan soal.</p>
                </div>
            </section>
        
            <section id="grafik">
                <div class="line"></div>
                <h2>Grafik Fungsi Linear</h2>
                <div class="rumus">
                    <h3>Pengertian:</h3>
                    <p>Grafik fungsi linear adalah representasi visual dari fungsi linear pada bidang koordinat Cartesian, yang berbentuk garis lurus.</p>
                </div>
                <div class="video">
                    <iframe src="https://www.youtube.com/embed/YXqTWFEa1A4?si=pQ3d-kv2K3RIia7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <p>Materi: Cara menggambar grafik fungsi linear dan memahami gradien serta intercept.</p>
                </div>
            </section>
        
            <section id="contoh">
                <div class="line"></div>
                <h2>Contoh Soal Fungsi Linear</h2>
                <div class="latihan">
                    <h3>Contoh Soal:</h3>
                    <p>1. Diberikan fungsi <strong>y = 3x + 1</strong>, hitung nilai y untuk <strong>x = 2</strong>.</p>
                    <div class="jawaban">
                        <p>Jawaban: <strong>y = 3(2) + 1 = 6 + 1 = 7</strong>.</p>
                    </div>
                    <p>2. Jika titik (1, 5) berada pada grafik fungsi <strong>y = mx + 2</strong>, cari nilai m.</p>
                    <div class="jawaban">
                        <p>Jawaban: <strong>5 = m(1) + 2 ⟹ m = 3</strong>.</p>
                    </div>
                </div>
            </section>
        
            <section id="latihan">
                <div class="line"></div>
                <h2>Latihan Fungsi Linear</h2>
                <div class="latihan">
                    <h3>Latihan Soal:</h3>
                    <p>1. Tentukan gradien dari fungsi <strong>y = -4x + 7</strong>.</p>
                    <p>2. Gambar grafik fungsi <strong>y = 3x - 5</strong>.</p>
                    <h3>Diskusi:</h3>
                    <p>Diskusikan hasil grafik yang kalian gambar dengan teman sekelas dan temukan kesamaan serta perbedaan.</p>
                </div>
            </section>
            
            <section id="geogebra">
                <div class="geogebra">
                    <h3>Interaksi dengan GeoGebra:</h3>
                    <iframe scrolling="no" width="100%" height="600" src="https://www.geogebra.org/material/iframe/id/yrnjjyha/width/800/height/600/border/888888/rc/true/ai/true/sdz/true" frameborder="0" allowfullscreen></iframe>
                    <p>Materi: Eksplorasi interaktif grafik fungsi linear menggunakan GeoGebra.</p>
                </div>
            </section>
        </div>
    </main>
</body>
</html>
