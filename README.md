<!DOCTYPE html>
<html lang="en" style="height: 100%;">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ALGELI</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="../css/home.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        /* CSS for hover effects */
        .navbar-nav .nav-link:hover {
            color: #ffffff !important;
            background-color: #06f8a7;
            border-radius: 5px;
            transition: background-color 0.3s ease-in-out, color 0.3s ease-in-out;
        }
    </style>
</head>

<body style="margin-top: 0;">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <a class="navbar-brand" href="home.html"><b>Alge</b>braic <b>Li</b>mits</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" 
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                    <a class="nav-link active" href="home.html">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="materi.html">Materi Limit</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="">Contoh & Latihan</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="">Profile Kelompok</a>
                </li>
            </ul>
        </div>
    </nav>
    <div class="container mx-auto my-8 px-4">
        <div class="flex flex-wrap justify-center items-center">
            <!-- Image -->
            <div class="w-full md:w-1/2 text-center md:text-right mb-4 md:mb-0">
                <img src="../img/mathematikaHome.svg" alt="Karikatur" class="img-Karikatur">
            </div>
            <!-- Description -->
            <div class="w-full md:w-1/2 text-center md:text-left md:pl-4">
                <h1 class="text-6xl font-semibold mb-4" id="welcomeText">SELAMAT DATANG PARA PELAJAR</h1>
                <p class="text-lg animate-float" id="calculationText">Belajar Kalkulus materi Limit Fungsi Aljabar akan menjadi lebih menyenangkan bersama ALGELI.</p>
                <p class="text-lg animate-float" id="websiteText">Kamu berada di tempat yang tepat untuk belajar Kalkulus 1 materi limit & Limit fungsi Alabar.</p>
            </div>
        </div>
    </div>
    <script src="../js/home.js"></script>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>
