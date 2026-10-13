
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Pribadi</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f0f4ff;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #6c63ff, #48c6ef);
            color: white;
            text-align: center;
            padding: 30px 15px;
        }

        header img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
        }

        nav {
            background: #343477;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 10px;
        }

        main {
            max-width: 800px;
            margin: 20px auto;
            padding: 15px;
        }

        section {
            background: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 12px;
        }

        h2 {
            color: #6258d9;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        td {
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }

        .skill {
            display: inline-block;
            background: #e4e1ff;
            color: #4538a8;
            padding: 8px 12px;
            margin: 5px;
            border-radius: 15px;
        }

        footer {
            background: #343477;
            color: white;
            text-align: center;
            padding: 15px;
        }

        @media (max-width: 600px) {
            nav a {
                display: inline-block;
                margin: 7px;
            }
        }
    </style>
</head>

<body>

<header>
    <img src="foto.jpg" alt="Foto saya">
    <h1>Nama Lengkap Kamu</h1>
    <p>Kelas X PPLG</p>
    <p>Calon Web Developer</p>
</header>

<nav>
    <a href="#tentang">Tentang Saya</a>
    <a href="#biodata">Biodata</a>
    <a href="#keahlian">Keahlian</a>
    <a href="#kontak">Kontak</a>
</nav>

<main>
    <section id="tentang">
        <h2>Tentang Saya</h2>
        <p>
            Halo! Saya seorang pelajar jurusan PPLG.
            Saya senang belajar teknologi, membuat desain,
            dan mempelajari pemrograman website.
        </p>
    </section>

    <section id="biodata">
        <h2>Biodata</h2>
        <table>
            <tr>
                <td>Nama</td>
                <td>Nama Lengkap Kamu</td>
            </tr>
            <tr>
                <td>Tempat, Tanggal Lahir</td>
                <td>Isi tempat dan tanggal lahir</td>
            </tr>
            <tr>
                <td>Alamat</td>
                <td>Isi alamat</td>
            </tr>
            <tr>
                <td>Kelas</td>
                <td>X PPLG</td>
            </tr>
            <tr>
                <td>Email Sekolah</td>
                <td>emailkamu@contoh.com</td>
            </tr>
        </table>
    </section>

    <section id="keahlian">
        <h2>Keahlian dan Hobi</h2>
        <span class="skill">HTML</span>
        <span class="skill">CSS</span>
        <span class="skill">Desain Canva</span>
        <ul>
            <li>Membuat poster</li>
            <li>Mendengarkan musik</li>
            <li>Belajar coding</li>
        </ul>
    </section>

    <section id="kontak">
        <h2>Kontak Saya</h2>
        <p>Email:
            <a href="mailto:emailkamu@contoh.com">
                Kirim Email
            </a>
        </p>
        <p>Instagram:
            <a href="https://www.instagram.com/">
                Kunjungi Instagram
            </a>
        </p>
    </section>
</main>

<footer>
    <p>© 2026 Website Profil Pribadi</p>
    <p>Dibuat dengan HTML dan CSS</p>
</footer>

</body>
</html>
