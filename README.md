<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Original Filmes</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }
        
        header {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 10px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        section {
            padding: 20px;
            text-align: center;
        }

        /* Adiciona a imagem de fundo */
        body {
            background-image: url('family-watching-movie.jpg');
            background-size: cover;
            background-position: center;
            color: white;
        }

        #home {
            background: rgba(0, 0, 0, 0.5);
            padding: 40px;
        }

        #filmes {
            background: rgba(0, 0, 0, 0.5);
            padding: 40px;
        }

        .filme-card {
            display: inline-block;
            margin: 10px;
            background-color: rgba(255, 255, 255, 0.7);
            padding: 20px;
            border-radius: 10px;
        }

        .filme-card img {
            width: 250px;
            height: 350px;
            object-fit: cover;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
        }
    </style>
</head>
<body>

<header>
    <h1>Original Filmes</h1>
    <nav>
        <ul>
            <li><a href="#home">Início</a></li>
            <li><a href="#filmes">Filmes</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>
</header>

<section id="home">
    <h2>Bem-vindo ao nosso site de filmes!</h2>
    <p>Descubra os melhores filmes e séries disponíveis para você.</p>
</section>

<section id="filmes">
    <h2>Nossos Filmes</h2>
    <div class="filme-card">
        <img src="https://via.placeholder.com/250" alt="Filme 1">
        <h3>Filme Exemplo 1</h3>
        <p>Gênero: Ação</p>
    </div>
    <div class="filme-card">
        <img src="https://via.placeholder.com/250" alt="Filme 2">
        <h3>Filme Exemplo 2</h3>
        <p>Gênero: Drama</p>
    </div>
    <div class="filme-card">
        <img src="https://via.placeholder.com/250" alt="Filme 3">
        <h3>Filme Exemplo 3</h3>
        <p>Gênero: Comédia</p>
    </div>
</section>

<section id="contato">
    <h2>Entre em Contato</h2>
    <p>Tem dúvidas ou sugestões? Fale conosco através do nosso e-mail: <a href="mailto:contato@originalfilmes.com.br">contato@originalfilmes.com.br</a></p>
</section>

<footer>
    <p>&copy; 2025 Original Filmes. Todos os direitos reservados.</p>
</footer>

</body>
</html>
