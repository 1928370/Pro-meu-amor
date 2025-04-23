<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <initial-scale=1.0">
    <title>detail tag</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
    <title>Evellyn Santos</title>
    <link rel="website icon" type="image/png"
    href="img/love-line-text-silver-and-gold-with-heart-3d-png.webp">
</head>
<header>
    <img src="img/love-line-text-silver-and-gold-with-heart-3d-png.webp" alt="Logo" style="max-width: 100px; border-radius: 50%;">
</nav>
</header>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta charset="UTF-8">
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
<title>Evellyn Santos</title>
<link rel="website icon" type="image/png"
href="img/love-line-text-silver-and-gold-with-heart-3d-png.webp"

>
<body>
    <details>
        <summary>Evellyn</summary>

        <p>
            Você e uma mulher incrivel, conquistou meu coração e sempre esteve comigo
            sem nunca reclamar de nada, semore me apoiando e me ajundando a ser uma pessoa
            melhor, sou muito grato por ter vocé na minha vida, e espero que possamos 
            passar muitos e muitos anos juntinhos.
        </p>
    </details>

    <details>
        <summary>Arrependimentos</summary>

        <p>
            Meu maior arrependimento e ter cometido erros no passado, e ter te deixado
            triste, espero que possamos superar isso e seguir em frente, pois eu te amo muito
            e você e a mulher da minha vida, e quero passsar o resto da minha vida com você.
        </p>
    </details>

    <details>
        <summary>Desejos</summary>

        <p>
            Desejos estar sempre ao seu lado,e poder te fazer feliz,e poder te dar o mundo
            e tudo que você sempre sonhou, e poder te fazer feliz todos os dias da sua vida.
            Quero poder te dar tudo que voce sempre sonhou, e poder te fazer feliz todos os dis
            da sua vida, e poder te dar o mundo e tudo que voce sempre sonhou.
        </p>
    </details>

    <details>
        <summary>Realização</summary>

        <p>
            Algo que eu sinceramente nunca imaginei que poderia acontecer,eu me casando,
            e me casando com a mulher mais linda desse mundo ainda em, e com a mulher que quero
            passar o resto da minha vida juntos, eu te amo e você sempre estará no meu coração.
        </p>
    </details>

    <details>
        <summary>Momentos</summary>

        <p>
            Momentos incriveis ao seu lado, momentos que eu nunca vou esquecer, momentos que eu quero
            e que sempre estarão guardados na minha memória, pois cada instante ao seu lado é especial.
        </p>
    </details>

    <details>
        <summary>Novos Sonhos</summary>

        <p>
            Sonhos que ainda quero realizar, aventuras que quero viver ao seu lado, e momentos que
            espero que possamos criar juntos, pois cada dia é uma nova oportunidade para sermos felizes.
        </p>
    </details>

    <details>
        <summary>Realização</summary>

        <p>
            Algo que eu sinceramente nunca imaginei que poderia acontecer,eu me casando,
            e me casando com a mulher mais linda desse mundo ainda em, e com a mulher que quero
            passar o resto da minha vida juntos, eu te amo e você sempre estará no meu coração.
        </p>
    </details>

    <details>
        <summary>Vida</summary>

        <p>
            Uma Vida sem você não e nada, uma vida sem você não tem sentido, uma vida sem você
            não tem graça, uma vida sem você não tem amor, vivo pra ter amar e te ver bem.
        </p>
    </details>

    <div id="love-container" style="text-align: center; margin-top: 20px;">
        <button id="love-button" style="padding: 15px 30px; font-size: 18px; font-weight: bold; color: white; background: linear-gradient(135deg, #ff7f50, #ff1493); border: none; border-radius: 8px; cursor: pointer; transition: transform 0.3s;">
            Eu te amo
        </button>
        <div id="heart-animation" style="display: none; margin-top: 20px;">
            ❤️
        </div>
    </div>

    <script>
        const loveButton = document.getElementById('love-button');
        const heartAnimation = document.getElementById('heart-animation');
    
        loveButton.addEventListener('click', () => {
            // Esconde o botão
            loveButton.style.display = 'none';
    
            // Mostra o coração com animação
            heartAnimation.style.display = 'block';
    
            // Adiciona um efeito de "explosão"
            setTimeout(() => {
                heartAnimation.innerHTML = '💖💖💖';
            }, 1000); // Após 1 segundo, muda para vários corações
        });
    </script>
</body>
</body>
</html>
