<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Conteúdo Diário</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');
        
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background: url('https://img.freepik.com/vetores-gratis/material-escolar-no-quadro-negro_23-2148587747.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #333;
        }

        header {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 20px;
            text-align: center;
            font-size: 28px;
            font-weight: bold;
            color: white;
        }

        .content-wrapper {
            max-width: 900px;
            margin: 30px auto;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .content-section {
            margin-bottom: 20px;
        }

        .content-section h3 {
            font-size: 24px;
            color: #333;
            border-bottom: 2px solid #333;
            padding-bottom: 5px;
        }

        .content-section p {
            font-size: 18px;
            margin: 10px 0;
            color: #555;
        }

        .content-section img {
            max-width: 100%;
            border-radius: 10px;
            margin-top: 10px;
        }

        .back-button {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 18px;
            font-weight: 600;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: background-color 0.3s ease;
        }

        .back-button:hover {
            background-color: #0056b3;
        }

        a {
            color: #007BFF;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        a:hover {
            color: #0056b3;
        }
    </style>
</head>
<body>

<header>
    Portal da Turma - Conteúdo Diário
</header>

<div class="content-wrapper">
    <div class="content-section">
        <h3>Matéria: Português - Tema: Análise Sintática</h3>
        <p><strong>Data:</strong> 09/01/2025</p>
    </div>

    <div class="content-section">
        <h3>Descrição</h3>
        <p>Estudamos as diferenças entre orações coordenadas e subordinadas. Identificamos, classificamos e criamos exemplos práticos de cada uma delas.</p>
    </div>

    <div class="content-section">
        <h3>Material de Apoio</h3>
        <p>Livro: <a href="https://example.com/gramatica-avancada-cap5" target="_blank">Gramática Avançada - Capítulo 5</a></p>
    </div>

    <div class="content-section">
        <h3>O que foi passado no quadro</h3>
        <p>- Definição de oração coordenada e subordinada.</p>
        <p>- Exemplos práticos de cada tipo.</p>
    </div>

    <div class="content-section">
        <h3>Foto</h3>
        <img src="exemplo-foto-quadro.jpg" alt="Foto do conteúdo do quadro">
    </div>

    <div class="content-section">
        <h3>Explicação da Aula</h3>
        <p>Exploramos como identificar relações entre orações em frases complexas, compreendendo a hierarquia entre ideias e a construção de argumentos claros e coesos.</p>
    </div>

    <div class="content-section">
        <h3>Observações do Professor</h3>
        <p>Revisar as definições de oração subordinada substantiva para a próxima aula. Estudo extra sugerido: resolver exercícios das páginas 60 a 65 do livro de apoio.</p>
    </div>

    <a href="ConteudoDiario.html" class="back-button">Voltar</a>
</div>

</body>
</html>
