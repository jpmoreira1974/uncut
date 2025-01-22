A Arte de Contar Histórias através da imagem.
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UnCut - Portefólio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background: #000;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #333;
            padding: 10px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 16px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background: url('https://via.placeholder.com/1920x600') no-repeat center center/cover;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-align: center;
        }
        .hero h1 {
            font-size: 3em;
            background: rgba(0, 0, 0, 0.5);
            padding: 10px 20px;
        }
        .portfolio {
            padding: 20px;
            text-align: center;
        }
        .portfolio h2 {
            margin-bottom: 20px;
        }
        .videos {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .video {
            width: 300px;
            background: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        .video iframe {
            width: 100%;
            height: 200px;
            border: none;
        }
        footer {
            background: #000;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
        footer a {
            color: #00f;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>UnCut</h1>
        <p>Transformamos ideias em histórias visuais inesquecíveis</p>
    </header>

    <nav>
        <a href="#portfolio">Portefólio</a>
        <a href="#contact">Contacto</a>
    </nav>

    <section class="hero">
        <h1>Bem-vindo à UnCut</h1>
    </section>

    <section id="portfolio" class="portfolio">
        <h2>O Nosso Portefólio</h2>
        <div class="videos">
            <div class="video">
                <iframe src="https://www.youtube.com/embed/your_video_id1" title="Vídeo 1"></iframe>
                <p>Projeto 1: Nome do Projeto</p>
            </div>
            <div class="video">
                <iframe src="https://www.youtube.com/embed/your_video_id2" title="Vídeo 2"></iframe>
                <p>Projeto 2: Nome do Projeto</p>
            </div>
            <div class="video">
                <iframe src="https://www.youtube.com/embed/your_video_id3" title="Vídeo 3"></iframe>
                <p>Projeto 3: Nome do Projeto</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contacto</h2>
        <p>Entre em contacto connosco para discutir o seu próximo projeto!</p>
        <p>Email: <a href="mailto:contacto@uncut.com">contacto@uncut.com</a></p>
        <p>Telefone: +351 912 345 678</p>
    </section>

    <footer>
        <p>&copy; 2025 UnCut - Todos os direitos reservados.</p>
        <p><a href="#">Voltar ao topo</a></p>
    </footer>
</body>
</html>
