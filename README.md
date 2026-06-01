# agrinho_1a
#agrinho
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MIP no Campo - Projeto Agrinho</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>MIP no Campo</h1>
            <p>Sustentabilidade e Inovação na Agricultura - Projeto Agrinho</p>
        </div>
    </header>

    <main class="container">
        <!-- Seção de Introdução -->
        <section class="card">
            <h2>O que é o Manejo Integrado de Pragas (MIP)?</h2>
            <p>O MIP é um sistema que associa diferentes técnicas de controle (cultural, biológico, químico e físico) para manter as pragas abaixo do nível de dano econômico, priorizando a saúde humana e o meio ambiente, em linha com os valores do Agrinho.</p>
        </section>

        <!-- Pilares do MIP -->
        <section class="grid">
            <div class="card pilar" onclick="mostrarDetalhes('cultural')">
                <h3>1. Controle Cultural</h3>
                <p>Rotação de culturas e escolha de sementes saudáveis.</p>
            </div>
            <div class="card pilar" onclick="mostrarDetalhes('biologico')">
                <h3>2. Controle Biológico</h3>
                <p>Uso de inimigos naturais (predadores e parasitoides).</p>
            </div>
            <div class="card pilar" onclick="mostrarDetalhes('quimico')">
                <h3>3. Controle Químico</h3>
                <p>Uso consciente e seletivo de defensivos agrícolas.</p>
            </div>
        </section>

        <!-- Painel Interativo Intermediado por JS -->
        <section class="card display-info">
            <h2>Detalhes do Manejo</h2>
            <p id="info-texto">Clique em um dos pilares acima para entender sua importância no Agrinho!</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Projeto Agrinho - Desenvolvido com foco em Sustentabilidade.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
