@ -1 +1,125 @@
"# Webpro" 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Diri</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 20px;
        }

        #profile-container {
            display: flex;
            gap: 20px;
        }

        #profile-image {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
        }

        #profile-info {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            padding: 8px;
            border: 1px solid #ddd;
            text-align: left;
        }

        th {
            background-color: #f2f2f2;
        }

        .button-container {
            display: flex;
            justify-content: center;
            margin-top: 10px;
        }

        .button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Profile Diri</h1>

    <div id="profile-container">
        <div>
            <img id="profile-image" src="Ergi.jpg" alt="Foto Profil"> <!-- Tag 'img' untuk menampilkan gambar -->
        </div>

        <div id="profile-info">
            <h2>Nama:</h2>
            <p>Muhammad Ergi Ananta Putra</p> <!-- Tag 'p' untuk paragraf -->

            <h2>Tentang Saya:</h2>
            <p>Halo semuanya, Perkenalkan nama saya Muhammad Ergi Ananta Putra dari jurusan Teknologi Infomari fakultas Informatika angkatan 2022. Saya lahir pada tanggal 9 April 2003 Palangka Raya Kalimantan Tengah, hobi saya Baca Webtoon, Kpopers, Otaku, Menulis cerita (semacam watpadd), main game (terutama horror dan action). </p> <!-- Tag 'p' untuk paragraf -->

            <h2>Informasi Kontak:</h2>
            <table> <!-- Tag 'table' untuk menampilkan data dalam format tabel -->
                <tr> <!-- Tag 'tr' untuk baris dalam tabel -->
                    <th>Email:</th> <!-- Tag 'th' untuk header kolom dalam tabel -->
                    <td>eunseosekai@student.telkomuniversity.ac.id</td> <!-- Tag 'td' untuk data dalam kolom tabel -->
                </tr>
                <tr> <!-- Tag 'tr' untuk baris dalam tabel -->
                    <th>Nomor Telepon:</th> <!-- Tag 'th' untuk header kolom dalam tabel -->
                    <td>+6282350992950</td> <!-- Tag 'td' untuk data dalam kolom tabel -->
                </tr>
            </table>

            <h2>Keahlian:</h2>
            <ul> <!-- Tag 'ul' untuk daftar tidak terurut -->
                <li>HTML</li> <!-- Tag 'li' untuk item dalam daftar -->
                <li>CSS</li> <!-- Tag 'li' untuk item dalam daftar -->
                <li>JavaScript</li> <!-- Tag 'li' untuk item dalam daftar -->
            </ul>

            <h2>Video Perkenalan:</h2>
            <video width="320" height="240" controls> <!-- Tag 'video' untuk menampilkan video -->
                <source src="perkenalan.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>

            <h2>Hubungi Saya:</h2>
            <form> <!-- Tag 'form' untuk membuat formulir -->
                <label for="nama">Nama:</label> <!-- Tag 'label' untuk label input -->
                <input type="text" id="nama" name="nama" required> <!-- Tag 'input' untuk input teks -->

                <label for="email">Email:</label> <!-- Tag 'label' untuk label input -->
                <input type="text" id="email" name="email" required> <!-- Tag 'input' untuk input teks -->

                <label for="pesan">Pesan:</label> <!-- Tag 'label' untuk label input -->
                <textarea id="pesan" name="pesan" rows="4" cols="50" required></textarea> <!-- Tag 'textarea' untuk input teks area -->

                <div class="button-container"> <!-- Tag 'div' untuk grouping elemen -->
                    <button type="submit" class="button">Kirim</button> <!-- Tag 'button' untuk tombol submit -->
                </div>
            </form>

            <h2>Media Sosial Saya:</h2>
            <a href="https://www.instagram.com/mark_regizz.park?igsh=cTM0d2l3NHAyZ3kz" target="_blank">Instagram</a> <!-- Tag 'a' untuk link -->
            <a href="https://x.com/Parkbongpal11" target="_blank">X</a> <!-- Tag 'a' untuk link -->
            <a href="https://www.tiktok.com/@ngg_2003" target="_blank">Tiktok</a> <!-- Tag 'a' untuk link -->
        </div>
    </div>
</body>
</html>
