<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata Dimas Andika Lismani</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #447fe6, hsl(236, 100%, 80%));
            color: #fff;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 700px;
            margin: 40px auto;
            background-color: rgba(255, 255, 255, 0.1);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
            backdrop-filter: blur(10px);
        }
        h1 {
            text-align: center;
            margin-bottom: 20px;
            color: #ffeb3b;
            font-size: 2.5em;
        }
        p {
            line-height: 1.8;
            color: #f3f3f3;
            font-size: 1.1em;
        }
        .label {
            font-weight: bold;
            color: #ffeb3b;
        }
        img {
            display: block;
            margin: 20px auto;
            width: 180px;
            height: 180px;
            border-radius: 50%;
            border: 4px solid #ffeb3b;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease-in-out;
        }
        img:hover {
            transform: scale(1.05);
        }
        .container:hover {
            background-color: rgba(255, 255, 255, 0.15);
        }
        .info {
            margin: 10px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px;
            border-bottom: 1px solid #ffeb3b;
        }
        .info:last-child {
            border-bottom: none;
        }
        .label, .value {
            font-size: 1.2em;
        }
        .value {
            text-align: right;
        }
        .skills {
            margin-top: 20px;
        }
        .skill {
            margin: 10px 0;
        }
        .skill-label {
            font-weight: bold;
            margin-bottom: 5px;
        }
        .skill-bar {
            background-color: #ddd;
            border-radius: 10px;
            overflow: hidden;
            height: 20px;
            box-shadow: inset 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .skill-bar-fill {
            height: 100%;
            border-radius: 10px;
            background: linear-gradient(90deg, #1f4300, #88ff00);
            transition: width 0.5s ease-in-out;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Biodata Dimas Andika Lismani</h1>
    <img src="profilekyu.jpg" alt="Foto Profil Dimas Andika Lismani">
    
    <div class="info">
        <span class="label">Nama:</span>
        <span class="value">Dimas Andika Lismani</span>
    </div>
    <div class="info">
        <span class="label">Tempat, Tanggal Lahir:</span>
        <span class="value">05/07/2005</span>
    </div>
    <div class="info">
        <span class="label">Alamat:</span>
        <span class="value">Palumbonsari lamaran, Jl. Manunggal VII, Perum. Buana Asri, Blok B6 No.29 RT.04 / RW.17</span>
    </div>
    <div class="info">
        <span class="label">Pekerjaan:</span>
        <span class="value">Mahasiswa Swasta di Universitas Buana Perjuangan Karawang, Jurusan Teknik Informatika</span>
    </div>
    <div class="info">
        <span class="label">Hobi:</span>
        <span class="value">Mengoprek-Hardware</span>
    </div>

    <!-- Menambahkan Skill Bar -->
    <div class="skills">
        <h2 class="label">Skill</h2>
        <div class="skill">
            <div class="skill-label">Keramahan: 90%</div>
            <div class="skill-bar">
                <div class="skill-bar-fill" style="width: 90%;"></div>
            </div>
        </div>
        <div class="skill">
            <div class="skill-label">Pemrograman: 55%</div>
            <div class="skill-bar">
                <div class="skill-bar-fill" style="width: 55%;"></div>
            </div>
        </div>
        <div class="skill">
            <div class="skill-label">Hardware: 64%</div>
            <div class="skill-bar">
                <div class="skill-bar-fill" style="width: 64%;"></div>
            </div>
        </div>
    </div>
</div>

</body>
</html>Biodata Saya.
