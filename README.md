<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bai+Jamjuree:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;1,200;1,300;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">
    <title>Minha viajem para fora do Brasil</title>
</head>
<body>
    <main>
        <div class="passo ativo" id="passo-0">
            <img src="img/cenario-passo0.png" alt="">
            <p>Um dia eu decidi viajar, e  então escolhi dois lugares. Então fiz uma lista, para a lista eu escolhi, Itália e Grécia. Chegou o dia da viagem e eu escolhi.</p>
            <button class="btn-proximo" data-proximo="1">Itália</button>
            <button class="btn-proximo" data-proximo="2">Grécia</button>
        </div>
        <div class="passo" id="passo-1">
            <p>Eu chego na Itália, e começo a pesquisar os pontos turistícos principais da cidade:</p>
            <button class="btn-proximo" data-proximo="3">Procuro Sobre Coliseu e Vaticano</button>
            <button class="btn-proximo" data-proximo="4">Desisto e vou para o meu hotel</button>
        </div>
        <div class="passo" id="passo-2">
            <p>Chego na Grécia e vou para os pontos turistícos mais famosos no momento:</p>
            <button class="btn-proximo" data-proximo="5">Vou para o Templo de Olímpia</button>
            <button class="btn-proximo" data-proximo="6">Vou visitar o Acrópole de Atenas</button>
        </div>
        <div class="passo" id="passo-3">
            <p>Vejo o maior anfiteatro do Império Romano, com capacidade para 50.000 espectadores, e depois  exploro os Museus do Vaticano e a Basílica de São Pedro</p>
            <button class="btn-proximo" data-proximo="7">Depois de visitar esses lugares vou para o hotel descansar</button>
        </div>

        <div class="passo" id="passo-4">
            <img src="img/cenario-passo4-voltar-casa.png" alt="Desisto e vou para o meu hotel">
            <p>Eu desisto e vou para o hotel descansar. Depois decido voltar para casa por estar sem ideia.</p>
        </div>

        <div class="passo" id="passo-5">
            <p>Vou no Templo de Olímpia, e  chego ansiosa para reviver os momentos gloriosos da Grécia Antiga. Ao chegar lá, fui envolvida pela grandiosidade das colunas dóricas e pela majestade da estátua de Zeus, Fico apaixonada pelo o lugar.
</p>
            <button class="btn-proximo" data-proximo="7">Depois de um bom tempo fora decido ir para casa, volto pra casa super feliz com essa viagem feita.</button>
        </div>

        <div class="passo" id="passo-6">
            <p>Vou visitar o Acrópole de Atenas, e fico muito ansiosa para desvendar os segredos da cidade mais antiga do mundo. Ao chegar ao topo, fui surpreendida pela majestade do Partenon, sua arquitetura dórica imponente e a beleza eterna da deusa Atena.</p>
            <button class="btn-proximo" data-proximo="8">Fico um pouquinho mais para apreciar</button>
        </div>

        <div class="passo" id="passo-7">
            <p>Depois vou para o hotel descansar</p>
            <button class="btn-proximo" data-proximo="9">Depois continuo a minha viagem encerrando . E indo para minha casa.</button>
            <button class="btn-proximo" data-proximo="10">Chego em casa super feliz com essas viagens feitas, e com muitas memórias incríveis.</button>
        </div>

        <div class="passo" id="passo-8">
            <p>De volta às igrejas, você finalmente encontra o mapa antigo. Agora, para o Amazonas!</p>
            <button class="btn-proximo" data-proximo="7">Seguir para o Amazonas</button>
        </div>

        <div class="passo" id="passo-9">
            <p>O rio à esquerda leva você a uma cachoeira escondida com inscrições antigas que revelam a entrada da
                cidade perdida.</p>
            </div>
    </main>
    <script src="script.js"></script>
</body>
</html>
