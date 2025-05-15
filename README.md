<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Site sobre Agronomia com informações e serviços relacionados ao campo.">
    <title>AgroConexão - Agronomia e Soluções para o Campo</title>
    <link rel="stylesheet" href="styles.css">
    <!-- Adicionar um link para um arquivo CSS externo -->
</head>
<body>
    <header>
        <div class="logo">
            <h1>AgroConexão</h1>
            <p>Conectando o campo ao futuro</p>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#servicos">Serviços</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="home">
        <h2>Bem-vindo à AgroConexão!</h2>
        <p>Estamos aqui para trazer as melhores soluções em agronomia, com foco no uso sustentável e eficiente dos recursos naturais.</p>
        <img src="campo.jpg" alt="Paisagem rural">
    </section>

    <section id="sobre" class="sobre">
        <h2>Sobre Nós</h2>
        <p>A AgroConexão é uma empresa especializada em serviços e consultoria no setor agrícola, com foco em otimizar a produtividade e sustentabilidade das lavouras.</p>
        <p>Com uma equipe de agrônomos experientes, oferecemos soluções personalizadas para o aumento da eficiência e sustentabilidade no campo.</p>
    </section>

    <section id="servicos" class="servicos">
        <h2>Nossos Serviços</h2>
        <ul>
            <li>
                <h3>Consultoria Agrícola</h3>
                <p>Aconselhamento especializado para gestão eficiente de propriedades agrícolas.</p>
            </li>
            <li>
                <h3>Análise de Solo</h3>
                <p>Realizamos análises detalhadas de solo para otimizar o uso de fertilizantes e aumentar a produtividade.</p>
            </li>
            <li>
                <h3>Gestão de Irrigação</h3>
                <p>Desenvolvemos planos de irrigação eficientes e sustentáveis para todos os tipos de culturas.</p>
            </li>
            <li>
                <h3>Planejamento de Colheita</h3>
                <p>Estratégias para melhorar o rendimento e a qualidade da colheita.</p>
            </li>
        </ul>
    </section>

    <section id="blog" class="blog">
        <h2>Blog</h2>
        <p>Confira os artigos mais recentes sobre agronomia, sustentabilidade e inovação no campo:</p>
        <ul>
            <li><a href="#">Como escolher a melhor variedade de sementes para sua região</a></li>
            <li><a href="#">Tecnologias que estão transformando a agricultura</a></li>
            <li><a href="#">Dicas para aumentar a produtividade do solo de forma sustentável</a></li>
        </ul>
    </section>

    <section id="contato" class="contato">
        <h2>Contato</h2>
        <p>Tem alguma dúvida ou deseja mais informações sobre nossos serviços? Entre em contato conosco!</p>
        <form action="#" method="post">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 AgroConexão | Todos os direitos reservados</p>
        <div class="social">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">LinkedIn</a>
        </div>
    </footer>

</body>
</html>
