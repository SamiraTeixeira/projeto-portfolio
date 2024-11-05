# projeto-portfolio
simulação de um site para mostrar meus projetos feito em html e css já ajustado para a tela
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samira Teixeira - Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <!--Inicio header -->
    <nav class="nav">
        <ul class="nav-list">
            <li><a href="#home">Home</a></li>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#projetos">Projetos</a></li>
        </ul>
    </nav>
    <!--Fim Header -->

    <!--Inicio do Main -->
    <section id="home" class="main">
        <div>
            <h1>Olá, <br> Seja bem vindo</h1>
            <p>Crie soluções para seu negócio!</p>
            <a href="#projetos">
                <button class="call-to-action">
                    Veja meus projetos 👇
                </button>
            </a>
        </div>
    </section>
    <!--Fim do Main -->
    
    <!-- Inicio Area sobre -->
    <section id="sobre" class="about">
       <div>
        <h2>Sobre</h2>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eos esse corporis veniam in fugit voluptates delectus nam ex impedit. Ipsa 
            <br><br>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptatum atque, consequatur, mollitia adipisci tempora aspernatur dolorum excepturi, odio ex voluptas est voluptates! Dignissimos velit necessitatibus molestiae unde tenetur incidunt. Enim. voluptatibus veritatis est fugit mollitia illum eum atque esse beatae.</p>
       </div>
       <img src="imagens/foto-pc.png" alt="Imagem do pc">
    </section> 
    <!-- Fim Area sobre -->
     <!--Criando sessao projeto -->
     <section id="projetos" class="projects">
        <h2>Meus projetos</h2>
        <p>Conheça meus ultimos projetos</p>

        <div class="project-list">
            <img src="imagens/projeto1.png" alt="Foto do projeto 1">
            <img src="imagens/projeto2.png" alt="Foto do projeto 2">
            <img src="imagens/projeto3.png" alt="Foto do projeto 3">
        </div>

        <div class="project-list">
            <img src="imagens/projeto2.png" alt="foto do projeto 2">
            <img src="imagens/projeto1.png" alt="foto do projeto 1">
            <img src="imagens/projeto3.png" alt="foto do projeto 3">
        </div>
        <button class="action">
            Faça um orçamento
        </button>
     </section>
     <!--Fim da sessao projeto-->
     <!--Inicio do Footer -->
     <footer>
        <h3><a href="#">Giordano Dorneles</a></h3>
        <p>Todos os direitos reservados</p>
    </footer>
     <!--Fim do Footer -->
</body>
</html>
