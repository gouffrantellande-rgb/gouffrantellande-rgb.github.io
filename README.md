<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FC Barcelone — Fan Page</title>
    <style>
        :root {
            --barca-blue: #004d98;
            --barca-red: #a50044;
            --barca-gold: #ffd700;
        }

        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: var(--barca-blue);
            color: white;
        }

        header {
            background-color: var(--barca-red);
            text-align: center;
            padding: 30px 0;
        }

        header h1 {
            color: var(--barca-gold);
            font-size: 3rem;
        }

        main {
            max-width: 900px;
            margin: 20px auto;
            padding: 0 20px;
        }

        h2 {
            color: var(--barca-gold);
            text-align: center;
            margin: 40px 0 20px 0;
            border-bottom: 2px solid var(--barca-gold);
            padding-bottom: 10px;
        }

        p, ul {
            text-align: center;
            margin: 10px 0;
            line-height: 1.5;
        }

        ul {
            list-style: none;
        }

        ul li {
            margin: 5px 0;
        }

        a {
            color: var(--barca-gold);
            text-decoration: none;
            font-weight: bold;
        }

        
        .img-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin: 20px auto;
        }

        .img-container img {
            width: 100%;
            border-radius: 10px;
        }

        .overlay-text {
            position: absolute;
            bottom: 10px;
            left: 50%;
            transform: translateX(-50%);
            color: var(--barca-gold);
            background-color: rgba(0,0,0,0.6);
            padding: 10px 15px;
            border-radius: 5px;
            font-size: 18px;
            font-weight: bold;
            text-align: center;
            width: 90%;
            white-space: normal;
            word-wrap: break-word;
        }

        footer {
            text-align: center;
            padding: 20px 0;
            background-color: var(--barca-red);
            margin-top: 40px;
        }

    
       
            
        
    </style>
</head>
<body>

    <header>
        <h1>FC Barcelone</h1>
    </header>

    <main>
        <p>Le FC Barcelone est l’un des clubs de football les plus emblématiques au monde, reconnu pour son style de jeu basé sur la possession et le mouvement. Fondé en 1899, il incarne la devise « Més que un club », reflet de son importance culturelle en Catalogne. Avec son stade mythique, le Camp Nou, et une histoire marquée par des légendes,  le Barça reste une référence du football européen.
        <h2>Logo</h2>
        <div class="img-container">
            <img src="https://mcdn.wallpapersafari.com/medium/94/51/FQ2YrW.jpg" alt="Logo FC Barcelone">
            <div class="overlay-text">MÉS QUE UN CLUB</div>
        </div>

        <h2>Joueur emblématique</h2>
        <div class="img-container">
            <img src="https://th.bing.com/th/id/R.164a5abf05d4f9bc9d5acac5953fd6e6?rik=tQzxTmXQVkMuJw&riu=http%3a%2f%2f4.bp.blogspot.com%2f-Byvk_8RECUA%2fVXRvbNEN6uI%2fAAAAAAAAdWs%2fpItC-NHZ1ug%2fs1600%2fmessi-copa-champions-2015.jpg&ehk=VlEW%2fkgCy8q0a71zTVS8vFCv8iBfEgnDQhpwy0pElw4%3d&risl=&pid=ImgRaw&r=0" alt="Lionel Messi">
            <div class="overlay-text">Lionel Messi</div>
        </div>
        <p>Messi est considéré comme le plus grand joueur de l'histoire du FC Barcelone, auteur de records légendaires et symbole du jeu blaugrana.</p>

        <h2>Palmarès</h2>
        <ul>
            <li>La Liga : 27 titres</li>
            <li>Ligue des Champions : 5 titres</li>
            <li>Coupe du Roi : 31 titres</li>
        </ul>

        <h2>Le Camp Nou</h2>
        <div class="img-container">
            <img src="https://www.fcbarcelona.com/photo-resources/2021/08/09/276ad270-e5c6-453d-8d9f-212417ad7cb3/Camp-Nou-3.jpg?width=1200&height=750" alt="Camp Nou">
            <div class="overlay-text">Le Camp Nou</div>
        </div>

    </main>

    <footer>
        <p><a href="https://www.fcbarcelona.com" target="_blank">Visitez le site officiel du FC Barcelone</a></p>
    </footer>

</body>
</html>
