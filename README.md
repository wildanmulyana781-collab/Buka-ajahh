# Buka-ajahh
Rahasia
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>🎂 Selamat Ulang Tahun</title>

<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    min-height: 100vh;
    overflow: hidden;
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #667eea, #764ba2);
    display: flex;
    justify-content: center;
    align-items: center;
}

/* Kartu */
.card {
    width: 90%;
    max-width: 400px;
    padding: 30px 20px;
    background: rgba(255,255,255,0.95);
    border-radius: 25px;
    text-align: center;
    box-shadow: 0 15px 40px rgba(0,0,0,0.3);
    animation: muncul 1s ease;
    z-index: 10;
}

@keyframes muncul {
    from {
        transform: scale(0.5);
        opacity: 0;
    }

    to {
        transform: scale(1);
        opacity: 1;
    }
}

/* Kue */
.kue {
    font-size: 80px;
    animation: goyang 1s infinite alternate;
}

@keyframes goyang {
    from {
        transform: rotate(-5deg);
    }

    to {
        transform: rotate(5deg);
    }
}

h1 {
    color: #6c5ce7;
    font-size: 30px;
    margin-bottom: 10px;
}

p {
    color: #555;
    font-size: 17px;
    line-height: 1.6;
}

/* Tombol */
button {
    margin-top: 15px;
    padding: 14px 25px;
    border: none;
    border-radius: 30px;
    background: #6c5ce7;
    color: white;
    font-size: 17px;
    font-weight: bold;
    cursor: pointer;
    transition: 0.2s;
}

button:hover {
    transform: scale(1.05);
}

button:active {
    transform: scale(0.9);
}

/* Pesan */
#pesan {
    display: none;
    margin-top: 20px;
    padding: 15px;
    border-radius: 15px;
    background: #f1efff;
    color: #6c5ce7;
    font-weight: bold;
    animation: pesan 0.5s ease;
}

@keyframes pesan {
    from {
        opacity: 0;
        transform: translateY(20px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* Balon */
.balon {
    position: absolute;
    bottom: -100px;
    font-size: 45px;
    animation: naik 7s linear infinite;
}

@keyframes naik {
    from {
        transform: translateY(0);
    }

    to {
        transform: translateY(-120vh);
    }
}

/* Bintang */
.bintang {
    position: absolute;
    color: white;
    font-size: 20px;
    animation: kedip 1.5s infinite alternate;
}

@keyframes kedip {
    from {
        opacity: 0.2;
    }

    to {
        opacity: 1;
    }
}
</style>
</head>

<body>

<!-- Balon -->
<div class="balon" style="left:10%; animation-delay:0s;">🎈</div>
<div class="balon" style="left:30%; animation-delay:2s;">🎈</div>
<div class="balon" style="left:70%; animation-delay:1s;">🎈</div>
<div class="balon" style="left:90%; animation-delay:3s;">🎈</div>

<!-- Bintang -->
<div class="bintang" style="left:15%; top:15%;">✦</div>
<div class="bintang" style="left:80%; top:20%;">✦</div>
<div class="bintang" style="left:25%; top:75%;">✦</div>
<div class="bintang" style="left:85%; top:70%;">✦</div>

<!-- Kartu utama -->
<div class="card">

    <div class="kue">🎂</div>

    <h1>Selamat Ulang Tahun!</h1>

    <p>
        Semoga di umur yang baru ini
        kamu semakin sukses, sehat,
        bahagia, dan semua cita-citamu
        bisa tercapai.
    </p>

    <button onclick="bukaPesan()">
        🎁 Buka Pesan
    </button>

    <div id="pes
