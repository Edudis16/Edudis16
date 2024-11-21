<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html><html lang="pt-br">
    <head>
      <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Flashcard</title><main>

        </main>
        <footer>
            <p>Projeto desenvolvido pela Alura, sem fins lucrativos.</p>
        </footer><main>
            <section id= “container”> 
        
        </section><article class="cartao">
            <div class="cartao__conteudo">

            </div>
        </article><h3> Programação </h3><div class="cartao__conteudo__pergunta">
            O que é Java Script?
            </div><div class="cartao__conteudo__resposta">
                O Java Script é uma linguagem de programação.
                </div>
                <article class="cartao">
                        <div class="cartao__conteudo">
                                <h3> Programação </h3>
                                      <div class="cartao__conteudo__pergunta">
                                            O que é CSS?
                                        </div>                        
                                       <div class="cartao__conteudo__resposta">
                                            O CSS é uma linguagem de estilização.
                                         </div>
                                        </div>
                                            
                         </article><head>
                            <meta charset="UTF-8" />
                            <meta name="viewport" content="width=device-width, initial-scale=1.0" />
                            <link rel="preconnect" href="https://fonts.googleapis.com" />
                            <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
                            <link
                              href="https://fonts.googleapis.com/css2?family=Bai+Jamjuree:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;1,200;1,300;1,400;1,500;1,600;1,700&display=swap"
                              rel="stylesheet"
                            />
                            <title>Flashcard</title>
                          </head><link rel="stylesheet" href="assets/style.css">body {
                            background-color: bisque;
                        }footer {
                            background-color: black;
                            color: white;
                        }footer {
                            background-color: black;
                            color: white;
                            bottom:0;
                            position:fixed;
                            width:100%;
                        }footer p{
                            text-align: center;
                            font-size: 0.6rem;
                        }    height:2rem;    margin-top: 0,5rem; font-family: Bai Jamjuree;.cartao:hover .cartao__conteudo {
                            transform: rotateY(180deg);
                        }.cartao__conteudo {
                            background-color: var(--card-front-color);
                            text-align: center;
                            height: 100%;
                            transform-style: preserve-3d;
                            transition: transform 300ms ease-in-out;
                        }.cartao__conteudo h3 {
                            color: var(--text-color);
                            border: 1px solid var(--text-color);
                            text-align: left;
                            padding: 0.5rem;
                            position: absolute;
                            margin: 0.6rem;
                            border-radius: 0.6rem;
                            font-size: 1vw;
                            backface-visibility: hidden;
                        }.cartao__conteudo__pergunta,
                        .cartao__conteudo__resposta {
                            backface-visibility: hidden;
                        }.cartao__conteudo__resposta {
                            transform: rotateY(180deg);
                        }.cartao__conteudo__pergunta,
                        .cartao__conteudo__resposta {
                            backface-visibility: hidden;
                            position: absolute;
                            height: 100%;
                            width: 100%;
                        }.cartao__conteudo p {
                            margin-top: 1rem;
                            padding: 2rem;
                            margin-top: 4rem;
                        }button:hover {
                            background-color: pink;
                          }div {
                            transform: rotate(45deg);
                          }button {
                            transition: background-color 0.3s ease;
                          }<article class="cartao">
                            <div class="cartao__conteudo">
                                <h3>Programação</h3>
                                <div class="cartao__conteudo__pergunta">
                                    <p>0 que é JavaScript?</p>
                                </div>
                                <div class="cartao__conteudo__resposta">
                                    <p>0 JavaScript é uma linguagem de programação</p>
                                </div>
                            </div>
                        </article><article class="cartao">
                            <div class="cartao__conteudo">
                                <h3>Geografia</h3>
                                <div class="cartao__conteudo__pergunta">
                                    <p>Qual a capital da França?</p>
                                </div>
                                <div class="cartao__conteudo__resposta">
                                    <p>A capital da França é Paris</p>
                                </div>
                            </div>
                        </article><article class="cartao">
                            <div class="cartao__conteudo">
                                <h3>Programação 2.0</h3>
                                <div class="cartao__conteudo__pergunta">
                                    <p>0 que é JavaScript?</p>
                                </div>
                                <div class="cartao__conteudo__resposta">
                                    <p>0 JavaScript é uma linguagem de programação</p>
                                </div>
                            </div>
                        </article>#container {
                            display: flex;
                             flex-wrap: wrap;
                        }#container {
                            display: flex;
                             flex-wrap: wrap;
                             justify-content: space-between;
                             padding: 4rem;
                        }#container {
                            display: flex;
                             flex-wrap: wrap;
                             justify-content: space-between;
                             padding: 4rem;
                             gap: 3rem;
                        }criaCartao(
                            categoria,
                            pergunta,
                            resposta
                        )criaCartao(
                            categoria,
                            pergunta,
                            resposta
                        )
                        
                        criaCartao(
                            categoria,
                            pergunta,
                            resposta
                        )
                        
                        criaCartao(
                            categoria,
                            pergunta,
                            resposta
                        )criaCartao(
                            'Programação',
                            'O que é Python?',
                            'O Python é uma linguagem de programação'
                        )
                        
                        criaCartao(
                            'Geografia',
                            'Qual a capital da França?',
                            'A capital da França é Paris'
                        )
                        
                        criaCartao(
                            'Programação',
                            'O que é uma função?',
                            'Uma função é um bloco de código que executa alguma tarefa'
                        )criaCartao(
                            'Programação',
                            'O que é Python?',
                            'O Python é uma linguagem de programação'
                        )
                        
                        criaCartao(
                            'Geografia',
                            'Qual a capital da França?',
                            'A capital da França é Paris'
                        )
                        
                        criaCartao(
                            'Programação',
                            'O que é uma função?',
                            'Uma função é um bloco de código que executa alguma tarefa'
                        )<script src=""></script><script src="perguntas.js"></script><script src="app.js"></script>
                        <script src="perguntas.js"></script>function criaCartao (categoria, pergunta, resposta) {

                        }function criaCartao (categoria, pergunta, resposta) {
                            console.log(categoria, pergunta, resposta)
                        }function criaCartao(categoria, pergunta, resposta) {
                            let container 
                    }function criaCartao(categoria, pergunta, resposta) {
                        let container = document.getElementById('container')
                }function criaCartao(categoria, pergunta, resposta) {
                    let container = document.getElementById('container')
                    let cartao = document.createElement('article')
            }function criaCartao(categoria, pergunta, resposta) {
                let container = document.getElementById('container')
                let cartao = document.createElement('article')
                cartao.className = 'cartao'
        }cartao.innerHTML = `
        <div class="cartao__conteudo">
        <h3>Programação</h3>
        <div class="cartao__conteudo__pergunta">
                <p>O que é JavaScript?</p>
        </div>
        <div class="cartao__conteudo__resposta">
                <p>O JavaScript é uma linguagem de programação</p>
        </div>
        </div>
        `container.appendChild(cartao)        <!-- <article class="cartao">
            <div class="cartao__conteudo">
                    <h3>Programação</h3>
                    <div class="cartao__conteudo__pergunta">
                            <p>O que é JavaScript?</p>
                    </div>
                    <div class="cartao__conteudo__resposta">
                            <p>O JavaScript é uma linguagem de programação</p>
                    </div>
            </div>
    </article> -->cartao.innerHTML = `
        <div class="cartao__conteudo">
            <h3>${categoria}</h3>
            <div class="cartao__conteudo__pergunta">
                    <p>${pergunta}</p>
            </div>
            <div class="cartao__conteudo__resposta">
                    <p>${resposta}</p>
            </div>
            </div>
    `    criaCartao(
        'Lingua inglesa',
        'Como se diz OI em inglês?',
        'Oi em ingles é HI (RAI)'
    ) let container = document.getElementById('container')cartao.innerHTML = `
    <div class="cartao__conteudo">
    <!-- Código omitido… -->
    </div>
    `let cartao = document.createElement('article')container.appendChild(cartao)let respostaEstaVisivel = falsefunction viraCartao(){
        respostaestaVisivel = !respostaEstaVisivel
    }.cartao.active .cartao__conteudo {
        transform: rotateY(180deg);
    }function viraCartao() {
        respostaEstaVisivel = !respostaEstaVisivel
        cartao.classList.toggle('active', respostaEstaVisivel)
    }cartao.addEventListener('click', viraCartao).cartao__conteudo__resposta{
        transform: rotateY(180deg);
        background-color: rdba(0, 244, 191, 0.2);
    }.cartao__conteudo__resposta{
        transform: rotateY(180deg);
        background-color: rgba(0, 244, 191, 0.2);
        border: 4px solid var(--card-back-color);
    }.cartao_conteudo_pergunta,
    .cartao_conteudo_resposta {
        backface-visibility: hidden;
        position: absolute;
        height: 100%;
        width: 100%;
        box-sizing: border-box;
    }.cartao__conteudo p {
        margin-top: 1rem;
        padding: 2rem;
        margin-top: 4rem;
        font-size: 1.4vw;
    }@media (max-width: 560px){

    }@media (max-width: 560 px) {

        body {
            background: url('img/bd-mobile.webp');
        }
    
    }.cartao {
        flex: 1 0 calc(100% - 1rem);
    }.cartao__conteudo h3 {
        font-size: 3vw;
    }.cartao__conteudo p {
        font-size: 3.8vw;
    }
