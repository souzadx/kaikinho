<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Honey</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            text-align: center;
            padding: 20px;
        }

        h1 {
            font-size: 36px;
            color: #ff0066;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.1);
            }
            100% {
                transform: scale(1);
            }
        }

        #love-note {
            font-size: 24px;
            color: #333;
            display: none;
        }

        #show-love-note-button {
            background-color: #ff0066;
            color: #fff;
            padding: 10px 20px;
            font-size: 18px;
            border: none;
            cursor: pointer;
            margin-top: 20px;
        }

        #show-love-note-button:hover {
            background-color: #ff0033;
        }

        #image-container {
            margin-top: 20px;
        }

        img {
            max-width: 20%; /* Reduzindo o tamanho da imagem para 20% */
            height: auto;
        }
    </style>
</head>
<body>
    <h1>Posso clicar no botão mo?</h1>

    <button id="show-love-note-button">Clique aqui</button>

    <div id="love-note">
        <p>Você é a luz da minha vida Kai, você é o ar que eu respiro, o ar que passa por cada canto do meu corpo .</p>
        <p>Com você os meus dias são muito mais felizes, obrigada por fazer parte da minha vida.</p>
        <p>Eu te amo mais do que você imagina. Sempre vou amar você, apenas você!</p>
    </div>

    <div id="image-container">
        <img src=".vscode/kai.jpeg" alt="Imagem de Amor">
    </div>

    <script>
        document.getElementById('show-love-note-button').addEventListener('click', function() {
            document.getElementById('love-note').style.display = 'block';
        });
    </script>
</body>
</html>

