<img src="c:\BIODATA DIRI AJID\Saved Pictures\jinuy.jpg" alt="AJIDINNOR">
<!DOCTYPE html>
<html lang="id">
<meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ucapan Selamat</title>
    <style>
    </style>
</head>
<body>
    <div class="container">
        <h1>Masukkan Nama Anda</h1>
        <input type="text" id="nameInput" placeholder="Nama Anda">
        <button onclick="ucapan()">Kirim</button>
        <div class="message" id="message"></div>
    </div>

    <script>
        function ucapan() {
            var nama = document.getElementById('nameInput').value;
            var ucapan = "Selamat datang, " + nama + "! di biodata kamu semoga kamu bahagia selalu.";
            document.getElementById('message').innerText = ucapan;
        }
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata Diri</title>
    <style>
a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
}
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            color: #cf1111;
        }
        p {
            margin-bottom: 10px;
        }
        .info {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <h1>Biodata Diri</h1>
    <div class="info">
        <p><strong>Nama:</strong> ajidinnor</p>
        <p><strong>Umur:</strong> 21 tahun</p>
        <p><strong>Alamat:</strong> Jl.Alabio-danau panggan No. 123, Kota Hulu Sungai Utara</p>
        <p><strong>Email:</strong> Ajidinnornordin@gmail.com</p>
        <p><strong>No. Telepon:</strong> 0857058199348</p>
    </div>
    <h2>Pendidikan</h2>
    <div class="info">
        <p><strong>Universitas:</strong>Universitas Nahdatul Ulama Kalsel</p>
        <p><strong>Jurusan:</strong> Teknik informatika</p>
        <p><strong>Tahun lulus:</strong> 2026</p>
    </div>
    <h2>ORGANIASISI</h2>
    <div class="info">
        <p><strong>NAMA ORGANISASI:</strong> IPNU KALSEL</p>
        <p><strong>Jabatan:</strong> KOMANDAN DKW CBP IPNU KALSEL</p>
        <p><strong>Tahun Masuk:</strong> 2023</p>
        <p><strong>Tahun Keluar:</strong>2026</p>
    </div>
</body>
</html>
<h2>ANDA MASUKAN KLIK INI</h2>
<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>
<p><a href="https://www.google.com/">Google</a></p>
