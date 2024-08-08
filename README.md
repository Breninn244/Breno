# Breno<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site de Agronomia</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #4CAF50;
            color: #ffffff;
            text-align: center;
            padding: 1em;
        }
        nav {
            background-color: #333;
            color: #ffffff;
            text-align: center;
            padding: 0.5em;
        }
        nav a {
            color: #ffffff;
            text-decoration: none;
            padding: 1em;
        }
        nav a:hover {
            background-color: #555;
        }
        .content {
            padding: 1em;
            margin: 0 auto;
            max-width: 800px;
        }
        footer {
            background-color: #333;
            color: #ffffff;
            text-align: center;
            padding: 1em;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Site de Agronomia</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">Sobre</a>
        <a href="#">Serviços</a>
        <a href="#">Contato</a>
    </nav>
    <div class="content">
        <h2>Bem-vindo ao Site de Agronomia</h2>
        <p>Este é um site fictício para demonstrar informações sobre agronomia.</p>
        <h3>Serviços Oferecidos</h3>
        <ul>
            <li>Consultoria agronômica</li>
            <li>Planejamento de culturas</li>
            <li>Análise de solo</li>
            <li>Manejo integrado de pragas</li>
        </ul>
        <h3>Contato</h3>
        <p>Para mais informações, entre em contato conosco através do formulário abaixo:</p>
        <form>
            <label for="nome">Nome:</label><br>
            <input type="text" id="nome" name="nome"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="mensagem">Mensagem:</label><br>
            <textarea id="mensagem" name="mensagem" rows="4" cols="50"></textarea><br><br>
            <input type="submit" value="Enviar">
        </form>
    </div>
    <footer>
        <p>&copy; 2024 Site de Agronomia. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
