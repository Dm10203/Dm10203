<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo de Vídeos - Basquete</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f3f3;
            color: #333;
        }

        header {
            background-color: #2c3e50;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 15px;
        }

        .video-card {
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
            overflow: hidden;
        }

        .video-card iframe {
            width: 100%;
            height: 315px;
            border: none;
        }

        .video-content {
            padding: 15px;
        }

        .video-title {
            font-size: 1.2em;
            margin-bottom: 10px;
            color: #2c3e50;
        }

        .video-description {
            font-size: 1em;
            color: #666;
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background: #2c3e50;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Catálogo de Vídeos de Basquete</h1>
    </header>

    <div class="container">
        <!-- Vídeo 1 -->
        <div class="video-card">
            <iframe src="https://www.youtube.com/embed/your_video_id" allowfullscreen></iframe>
            <div class="video-content">
                <h2 class="video-title">Título do Vídeo 1</h2>
                <p class="video-description">Descrição breve sobre o vídeo 1.</p>
            </div>
        </div>

        <!-- Vídeo 2 -->
        <div class="video-card">
            <iframe src="https://www.youtube.com/embed/your_video_id" allowfullscreen></iframe>
            <div class="video-content">
                <h2 class="video-title">Título do Vídeo 2</h2>
                <p class="video-description">Descrição breve sobre o vídeo 2.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Catálogo de Basquete</p>
    </footer>
</body>
</html>

