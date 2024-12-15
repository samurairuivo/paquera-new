# paquera-new
site online de paquera para conhecer pesssoas de todo mundo.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paquera.New</title>
    <style>
        /* Estilos gerais */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #6EC1E4, #F79DC4);
            color: #333;
        }

        header {
            background-color: #6EC1E4;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #F79DC4;
            padding: 0.5rem 0;
        }

        nav a {
            margin: 0 1rem;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            padding: 2rem;
            text-align: center;
        }

        .button {
            background-color: #6EC1E4;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            font-size: 1rem;
            cursor: pointer;
            border-radius: 5px;
        }

        .button:hover {
            background-color: #5CAED0;
        }

        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        /* Estilo do formulário */
        .form-container {
            max-width: 400px;
            margin: 0 auto;
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .form-container h2 {
            margin-bottom: 1rem;
            color: #333;
        }

        .form-container input, .form-container select, .form-container textarea {
            width: 100%;
            padding: 0.5rem;
            margin-bottom: 1rem;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .form-container button {
            width: 100%;
            background-color: #F79DC4;
            color: white;
            border: none;
            padding: 0.7rem;
            font-size: 1rem;
            cursor: pointer;
            border-radius: 5px;
        }

        .form-container button:hover {
            background-color: #E48AB1;
        }
    </style>
</head>
<body>
    <header>
        <h1>Paquera.New</h1>
        <p>Conecte-se com pessoas especiais agora mesmo!</p>
    </header>

    <nav>
        <a href="#cadastro">Cadastro</a>
        <a href="#chat">Chat</a>
        <a href="#sobre">Sobre</a>
    </nav>

    <div class="container">
        <section id="cadastro">
            <h2>Cadastre-se</h2>
            <div class="form-container">
                <form>
                    <h2>Informações Básicas</h2>
                    <label for="nome">Nome</label>
                    <input type="text" id="nome" name="nome" placeholder="Digite seu nome" required>

                    <label for="idade">Idade</label>
                    <input type="number" id="idade" name="idade" placeholder="Digite sua idade" required min="16">

                    <label for="interesses">Interesses</label>
                    <input type="text" id="interesses" name="interesses" placeholder="Descreva seus interesses">

                    <button type="submit">Cadastrar</button>
                </form>
            </div>
        </section>

        <section id="chat">
            <h2>Chat Online</h2>
            <p>Em breve você poderá conversar com seus matches aqui!</p>
            <button class="button">Abrir Chat</button>
        </section>

        <section id="sobre">
            <h2>Sobre o Paquera.New</h2>
            <p>Paquera.New é uma plataforma criada para conectar pessoas com interesses em comum e ajudar você a encontrar alguém especial de maneira segura e divertida!</p>
        </section>
    </div>

    <footer>
        <p>© 2024 Paquera.New - Todos os direitos reservados.</p>
    </footer>
</body>
</html>
