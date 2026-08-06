<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Servidor do Discord</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #1e1f22;
            color: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            text-align: center;
            background-color: #2b2d31;
            padding: 40px 30px;
            border-radius: 16px;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.4);
            max-width: 400px;
            width: 100%;
        }

        h1 {
            font-size: 1.8rem;
            margin-bottom: 8px;
            color: #f2f3f5;
        }

        p {
            font-size: 1.1rem;
            color: #b5bac1;
            margin-bottom: 20px;
        }

        .seta {
            font-size: 2rem;
            color: #5865f2;
            margin-bottom: 15px;
            animation: apontar 1.2s infinite alternate ease-in-out;
        }

        @keyframes apontar {
            0% {
                transform: translateY(0);
            }
            100% {
                transform: translateY(10px);
            }
        }

        .btn-discord {
            display: inline-block;
            background-color: #5865f2;
            color: #ffffff;
            font-size: 1.1rem;
            font-weight: bold;
            text-decoration: none;
            padding: 14px 28px;
            border-radius: 8px;
            transition: background-color 0.2s, transform 0.2s;
        }

        .btn-discord:hover {
            background-color: #4752c4;
            transform: scale(1.03);
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Servidor de Conversa e Amizades</h1>
        <p>Venha trocar uma ideia e fazer novos amigos!</p>
        
        <div class="seta">⬇️</div>

        <a href="https://discord.gg/WXGCK9R73" target="_blank" class="btn-discord">
            Entrar no Discord
        </a>
    </div>

</body>
</html>
