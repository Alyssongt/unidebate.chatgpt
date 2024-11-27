<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Acessar ChatGPT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        .btn {
            display: inline-block;
            padding: 15px 25px;
            font-size: 18px;
            color: white;
            background-color: #007BFF;
            border: none;
            border-radius: 5px;
            text-decoration: none;
        }
        .btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>Acessar o ChatGPT</h1>
    <p>O link abaixo abrirá o navegador e, em seguida, o ChatGPT.</p>
    <a href="https://chat.openai.com" class="btn">Abrir ChatGPT</a>

    <script>
        // Ao clicar no botão, primeiro abre o navegador
        document.querySelector('.btn').addEventListener('click', function(event) {
            event.preventDefault();  // Previne o comportamento padrão do link

            // Redireciona para o navegador
            window.location.href = "https://chat.openai.com";  // Redireciona para o ChatGPT
        });
    </script>
</body>
</html>
