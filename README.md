<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>titulo</title>
    <style>
        body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    color: #333;
    background-color: #ffffff;
}
        header {
    background: #333;
    color: #ffffff;
    padding: 1rem 0;
    text-align: center;
}
        nav ul {
    list-style: none;
    padding: 0;
}
        nav ul li {
    display: inline;
    margin: 0 10px;
}
        nav ul li a {
    color: #ff0000a9;
    text-decoration: none;
}
        section {
    padding: 2rem;
    margin: 1rem auto;
    max-width: 800px;
    background: #fff;
    box-shadow:whitesmoke
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">Sobre</a></li>
                <li><a href="#projects">Projetos</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h1>Bem-vindo ao meu Portfólio!</h1>
        <p>Olá! Meu nome é (seu nome). Sou um desenvolvedor web iniciante com a excitação em criar sites bonitos e funcionais.</p>
    </section>

    <section id="projects">
        <h2>Projetos</h2>
        <div class="project">
            <h3>Projeto 1</h3>
            <p>Descrição do projeto 1.</p>
        </div>
        <div class="project">
            <h3>Projeto 2</h3>
            <p>Descrição do projeto 2.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contato</h2>
        <form id="contact-form">
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Mensagem:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 (seu nome). Todos os direitos reservados.</p>
    </footer>

    <script src="scripts.js"></script>
    
    
</body>
</html>
