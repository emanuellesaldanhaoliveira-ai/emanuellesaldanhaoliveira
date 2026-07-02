# emanuellesaldanhaoliveira<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MC Negão Original | Fã-Page Oficial</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #121212;
            color: #ffffff;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(180deg, #ff0055 0%, #121212 100%);
            padding: 60px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
        }

        header p {
            font-size: 1.2rem;
            color: #e0e0e0;
            margin-top: 10px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        section {
            margin-bottom: 40px;
            background-color: #1e1e1e;
            padding: 25px;
            border-radius: 8px;
            border-left: 5px solid #ff0055;
        }

        section h2 {
            margin-bottom: 15px;
            color: #ff0055;
            font-size: 1.8rem;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid #ff0055;
            display: block;
            margin: 0 auto 20px auto;
            object-fit: cover;
        }

        /* Container responsivo para o vídeo do YouTube */
        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* Proporção 16:9 */
            padding-top: 30px; 
            height: 0; 
            overflow: hidden;
            margin-top: 15px;
            border-radius: 4px;
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }

        ul {
            list-style-type: none;
        }

        li {
            padding: 10px 0;
            border-bottom: 1px solid #333;
            display: flex;
            justify-content: space-between;
        }

        li:last-child {
            border-bottom: none;
        }

        .btn-link {
            display: inline-block;
            background-color: #ff0055;
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s ease;
            margin: 5px;
        }

        .btn-link:hover {
            background-color: #cc0044;
        }

        .links-center {
            text-align: center;
        }

        footer {
            text-align: center;
            padding: 20px;
            color: #777;
            font-size: 0.9rem;
            border-top: 1px solid #222;
        }
    </style>
</head>
<body>

    <header>
        <img src="https://via.placeholder.com/150" alt="MC Negão Original" class="profile-img">
        <h1>MC Negão Original</h1>
        <p>A voz marcante do Funk</p>
    </header>

    <div class="container">

        <section id="biografia">
            <h2>Biografia</h2>
            <p>MC Negão Original é um dos nomes que movimenta a cena do funk, trazendo autenticidade, ritmo e letras que retratam a realidade e o dia a dia das periferias. Com seu estilo único e flow inconfundível, ele conquista fãs por onde passa, consolidando sua presença nas plataformas digitais e nos bailes.</p>
        </section>

        <section id="clipe-em-destaque">
            <h2>Clipe em Destaque</h2>
            <div class="video-container">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/8IBXAIp1MdE?si=JwxzacLSdWluyQfa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>
        </section>

        <section id="sucessos">
            <h2>Principais Sucessos</h2>
            <ul>
                <li><span>🎵 Hit do Ano</span> <span>+1M de Plays</span></li>
                <li><span>🎵 Grave Pesado</span> <span>Nas Ruas</span></li>
                <li><span>🎵 Visão de Cria</span> <span>Disponível</span></li>
            </ul>
        </section>

        <section id="redes-sociais" class="links-center">
            <h2>Acompanhe o MC</h2>
            <p>Fique por dentro dos novos lançamentos e agenda de shows:</p>
            <br>
            <a href="#" target="_blank" class="btn-link">Spotify</a>
            <a href="#" target="_blank" class="btn-link">Instagram</a>
            <a href="#" target="_blank" class="btn-link">YouTube</a>
        </section>

    </div>

    <footer>
        <p>&copy; 2026 Página de Fã - MC Negão Original. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
