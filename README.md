# Retroscope
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><em>Retroscope</em></title>
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        body {
            font-family: 'the seasons';
            background-color: #fcf8f0;
            color: #392e26;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #b6a593;
            padding: 10px 20px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }

        .nav a {
            text-decoration: none;
            font-size: 18px;
            color: #4f3a24;
            font-weight: bold;
        }

        .nav a:hover {
            color: #392e26;
            text-decoration: underline;
        }

        h1 {
            color: #392e26;
        }

        footer {
            background-color: #b6a593;
            color: #392e26;
        }

        .carousel-inner img {
            height: 400px;
            object-fit: cover;
        }

        main {
            padding: 50px 15px;
            text-align: center;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="d-flex justify-content-between align-items-center">
                <h1><strong><em>Retroscope</em></strong></h1> <font-family:Moontime></font-family:Moontime>
                <img src="Logo.jpg" alt="Retroscope Logo" style="float:left; width:100px;">
                <nav>
                    <ul class="nav">
                        <li class="nav-item"><a class="nav-link" href="#karussell"><h4><strong>Radiospot</strong></h4></a></li>
                        <li class="nav-item"><a class="nav-link" href="#impressum"><h4><strong>Impressum</strong></h4></a></li>
                        <li class="nav-item"><a class="nav-link" href="#quellen"><h4><strong>Quellen</strong></h4></a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hauptinhalt -->
    <main id="startseite">
        <h1><strong><em>Erinnerung neu erleben</em></strong></h1> 
        <h3><em>Mit der Zeitreise-Kamera kannst Du nicht nur Momente festhalten, sondern sie vollständig nacherleben.</h3>
        <h3>Früher war alles besser?</h3> 
        <h3>Finde es heraus!</em></h3><br>
        <h3><strong>Willkommen auf unserer Startseite</strong></h3>
        <h3><strong>Entdecke die Schönheit der Vergangenheit!</strong></h3>
    </main>
<!-- Karussell -->
<section id="karussell" class="py-5">
    <div class="container text-center">
        <h1><strong>Unsere Highlights</strong></h1><br>
        <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel" data-interval="3000">
            <ol class="carousel-indicators">
                <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="4"></li>
            </ol>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="Foto.1.jpg" class="d-block w-100" alt="Grafik 1">
                </div>
                <div class="carousel-item">
                    <img src="Foto.2.jpg" class="d-block w-100" alt="Grafik 2">
                </div>
                <div class="carousel-item">
                    <img src="Foto.3.jpg" class="d-block w-100" alt="Grafik 3">
                </div>
                <div class="carousel-item">
                    <img src="Foto.4.jpg" class="d-block w-100" alt="Grafik 4">
                </div>
                <div class="carousel-item">
                    <img src="Foto.5.jpg" class="d-block w-100" alt="Grafik 5">
                </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
    </div>
</section>

<!-- Bootstrap Scripts -->
<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.4.4/dist/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>



    <!-- Radiospot -->
    <section id="radiospot" class="py-5">
        <div class="container text-center">
            <h1><strong>Unser Radiospot</strong></h1>
            <h4>Listen to our latest radio spot below:</h4><br>
            <audio controls>
                <source src="Radiospot_albers_vollerthun_salami.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </div>
    </section>

    <!-- Video als Wasserzeichen -->
<div class="video-container">
    <video autoplay loop muted>
        <source src="Video.mp4" type="video/mp4">
        Ihr Browser unterstützt kein HTML5-Video.
    </video>
</div>
<style>
.video-container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #fcf8f0;
}
.video-container video {
    max-width: 100%;
    max-height: 100%;
    border: 2px solid #babba4;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
}
</style>

    <section id="impressum" class="py-5">
        <div class="container text-center">
            <h1><strong>Impressum</strong></h1><br>
    
            <!-- Angaben gemäß TMG -->
            <h2><strong>Angaben gemäß § 5 TMG:</strong></h2>
            <p>
                <h4>Universität Bremen<br>
                    28359, Bremen<br>
                    Deutschland</h4><br>
            </p>
            <p>
                <h2><strong>Vertreten durch:</strong></h2>
                <h4>Emma Vollerthun<br>
                    Mehrnaz Salami<br>
                    Nadine Albers</h4><br>
            </p>
            <p>
                <h2><strong>Kontakt:</strong></h2>
                <h4><a href="mailto:Emmvol@uni-bremen.de">emmvol@uni-bremen.de</a><br>
                    <a href="mailto:Mehrnaz@uni-bremen.de">mehrnaz@uni-bremen.de</a><br>
                    <a href="mailto:Albersn@uni-bremen.de">albersn@uni-bremen.de</h4></a><br>
            </p>
            <p>
                <h2><strong>Verantwortlich für den Inhalt nach § 55 Abs. 2 RStV:</strong></h2>
                <h4>Emma Vollerthun<br>
                    Mehrnaz Salami<br>
                    Nadine Albers</h4><br>
                <h4>Universität Bremen<br>
                28359, Bremen<br>
                Deutschland</h4><br>
            </p>
    
            <!-- Autoren/-innen -->
            <h2><strong>Autorinnen</strong></h2>
            <p>
                <h4>Emma Vollerthun<br>
                    Mehrnaz Salami<br>
                    Nadine Albers</h4><br>
                <h4>Übungsaufgabe im Kurs Grundlagen der Medieninformatik 1</h4><br>
            </p>
    
            <!-- Veranstalter -->
            <h2><strong>Veranstalter</strong></h2>
            <p>
                <h4>Prof. Dr.-Ing. Udo Frese<br>
                Universität Bremen<br>
                Enrique-Schmidt-Str. 5<br>
                28359 Bremen<br>
                <a href="mailto:ufrese@uni-bremen.com">ufrese@uni-bremen.de</a></h4><br>
            </p>
    
            <!-- Übergeordnete Website -->
            <h2><strong>Übergeordnete Website</strong></h2>
            <p>
                <h4><a href="https://www.uni-bremen.de/impressum.html">Impressum der Universität Bremen</a></h4><br>
            </p>
    
            <!-- Haftungsausschluss -->
            <p>
                <h2><strong>Haftungsausschluss:</strong></h2><br>
                <h4><strong><em>Haftung für Inhalte</em></strong><br>

                Die Inhalte unserer Seiten wurden mit größter Sorgfalt erstellt. Für die Richtigkeit, Vollständigkeit und Aktualität der Inhalte können wir jedoch keine Gewähr übernehmen.</h4><br>
            </p>
            <p>
                <h4><strong><em>Haftung für Links</em></strong><br>

                Unser Angebot enthält Links zu externen Webseiten Dritter, auf deren Inhalte wir keinen Einfluss haben. Deshalb können wir für diese fremden Inhalte auch keine Gewähr übernehmen. Für die Inhalte der verlinkten Seiten ist stets der jeweilige Anbieter oder Betreiber der Seiten verantwortlich.</h4><br>
            </p>
    
            <!-- Urheberrecht -->
            <p>
                <h2><strong>Urheberrecht:</strong></h2><br>
                <h4>Die durch die Seitenbetreiber erstellten Inhalte und Werke auf diesen Seiten unterliegen dem deutschen Urheberrecht. Beiträge Dritter sind als solche gekennzeichnet. Die Vervielfältigung, Bearbeitung, Verbreitung und jede Art der Verwertung außerhalb der Grenzen des Urheberrechtes bedürfen der schriftlichen Zustimmung des jeweiligen Autors bzw. Erstellers.</h4>
            </p>
        </div>
    </section>
    

    
      <!-- Quellen -->
      <section id="quellen" class="py-5">
        <div class="container text-center">
            <h1><strong>Quellen</strong></h1><br>
            <h4>Hier finden Sie unsere Quellen:</h4><br>
            <iframe src="mi1_uebung3_albers_vollerthun_salami.pdf" width="100%" height="600px">
                Ihr Browser unterstützt keine eingebetteten PDFs. 
                <a href="mi1_uebung3_albers_vollerthun_salami.pdf">PDF herunterladen</a>
            </iframe>
            <iframe src="mi1_uebung4_albers_vollerthun_salami.pdf" width="100%" height="600px">
                Ihr Browser unterstützt keine eingebetteten PDFs. 
                <a href="mi1_uebung4_albers_vollerthun_salami.pdf">PDF herunterladen</a>
            </iframe>
        </div>
    </section>


    <!-- Footer -->
    <footer class="#b6a593 text-schwarz py-4">
        <div class="container text-center">
            <p>&copy; Copyright 2025</p> 
            <p><em>Emma Mehrnaz Nadine</em></p>
        </div>
    </footer>
</body>
</html>

