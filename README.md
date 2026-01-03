<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DogeAI ($DOGEAI)</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow: hidden; /* evita barras de rolagem */
        }

        /* Container quadrado full screen */
        .full-screen-square {
            position: relative;
            width: 100vw;            /* 100% da largura da tela */
            height: 100vh;           /* 100% da altura da tela */
            overflow: hidden;
        }

        /* Imagem de fundo quadrada centralizada */
        .full-screen-square img {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            min-width: 100%;
            min-height: 100%;
            width: auto;
            height: auto;
            object-fit: cover;       /* corta as bordas se necessário */
            /* object-fit: contain;  /* alternativa: mostra toda a imagem com barras pretas se precisar */
        }

        /* Conteúdo por cima da imagem (opcional) */
        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            text-shadow: 2px 2px 10px black;
        }
    </style>
</head>
<body>

    <div class="full-screen-square">
        <!-- TROQUE PELO LINK DA SUA IMAGEM (suba no Imgur e cole aqui) -->
        <img src="https://i.imgur.com/SEU_LINK_DA_IMAGEM_AQUI.png" alt="DogeAI Big Giveaway">

        <!-- Texto ou botões por cima (opcional) -->
        <div class="overlay">
            <h1 style="font-size: 4em;">DOGE AI</h1>
            <p style="font-size: 2em;">BIG GIVEAWAY 🚀🐕</p>
            <a href="#conteudo" style="background: #FFD700; color: black; padding: 15px 30px; border-radius: 10px; text-decoration: none; font-weight: bold;">Entre Agora</a>
        </div>
    </div>

</body>
</html>

    <header>
     <p   <img src="<img width="593" height="604" alt="image" src="https://wallpapers.com/images/hd/astronaut-doge-meme-ysh8psu98frsd3yt.jpg" ><p/>
        <h1>DogeAI ($DOGEAI)</h1>
        <p>A meme coin que une o clássico Doge com o futuro da Inteligência Artificial! 🐕🤖</p>
    </header>

    <section>
        <h2>O que é DogeAI?</h2>
        <p>DogeAI é uma meme coin comunitária que combina o icônico meme do Dogecoin com o hype da IA (como Grok da xAI). Muitos a chamam de "a primeira memecoin criada por Grok AI", mas atenção: isso é marketing divertido da comunidade. <strong>Não há conexão oficial com Elon Musk, xAI ou Grok.</strong> É pura especulação e memes!</p>
        
        <div class="warning">
            ⚠️ AVISO DE RISCO: Meme coins são altamente voláteis. Pode perder 100% do investimento. Faça sua própria pesquisa (DYOR). Não é conselho financeiro!
        </div>

        <!-- NOVA SEÇÃO: Carteira Solana -->
        <h2>Carteira Oficial (Contract Address) - Solana</h2>
        <div class="contract-box">
            <p><strong>Endereço do Token $DOGEAI na Solana:</strong></p>
            <div class="contract-address" id="contractAddress">
                CeRkiyFidWu96R8xFuArXgxG1eqXkvJFU2fjktaVrGCo
            </div>
            <button class="copy-btn" onclick="copyAddress()">Copiar Endereço</button>
            <p style="margin-top: 10px; font-size: 0.9em;">Sempre verifique este endereço antes de comprar ou enviar tokens!</p>
        </div>

        <h2>Como Comprar</h2>
        <p>
            1. Use uma wallet Solana (Phantom, Solflare, etc.)<br>
            2. Vá para uma DEX como <strong>Raydium</strong> ou <strong>Jupiter</strong><br>
            3. Cole o contract address acima para trocar por $DOGEAI<br>
            4. Tenha SOL para pagar as taxas de rede
        </p>

        <h2>Dados Atuais (Dezembro 2025 - verifique em tempo real)</h2>
        <ul>
            <li><strong>Blockchain Principal:</strong> Solana</li>
            <li><strong>Contract Address:</strong> CeRkiyFidWu96R8xFuArXgxG1eqXkvJFU2fjktaVrGCo</li>
            <li><strong>Onde ver preço:</strong> DexScreener, Birdeye, CoinGecko</li>
        </ul>

        <h2>Links Úteis</h2>
        <p style="text-align: center;">
            <a href="https://dexscreener.com/solana/CeRkiyFidWu96R8xFuArXgxG1eqXkvJFU2fjktaVrGCo" class="btn" target="_blank">DexScreener</a>
            <a href="https://www.geckoterminal.com/solana/pools/CeRkiyFidWu96R8xFuArXgxG1eqXkvJFU2fjktaVrGCo" class="btn" target="_blank">GeckoTerminal</a>
            <a href="https://birdeye.so/token/CeRkiyFidWu96R8xFuArXgxG1eqXkvJFU2fjktaVrGCo?chain=solana" class="btn" target="_blank">Birdeye</a>
            <a href="https://raydium.io/swap/?inputCurrency=sol&outputCurrency=CeRkiyFidWu96R8xFuArXgxG1eqXkvJFU2fjktaVrGCo" class="btn" target="_blank">Comprar na Raydium</a>
        </p>
    </section>

    <footer>
        <p>DogeAI Site Informativo - Oficial | 2025 | DYOR & Invista com responsabilidade 🚀🐕</p>
    </footer>

    <!-- Script para copiar o endereço -->
    <script>
        function copyAddress() {
            const address = document.getElementById("contractAddress").innerText;
            navigator.clipboard.writeText(address).then(() => {
                alert("Endereço copiado para a área de transferência!");
            });
        }
    </script>

</body>
</html>
