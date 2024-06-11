const perguntas = [
    enunciado: "Pergunta 1",
    alternativas: [
"Alternativa 1",
"Alternativa 2"
]
   ];`
const perguntas = [
    {
        enunciado: "Pergunta 1",
        alternativas: [
            "Alternativa 1",
            "Alternativa 2"
        ]
    },
    {
        enunciado: "Pergunta 2",
        alternativas: [
            "Alternativa 1",
            "Alternativa 2"
        ]
    }
];
const perguntas = [
    {
        enunciado: "Assim que saiu da escola você se depara com uma nova tecnologia, um chat que consegue responder todas as dúvidas que uma pessoa pode ter, ele também gera imagens e áudios hiper-realistas. Qual o primeiro pensamento?",
        alternativas: [
            "Isso é assustador!",
            "Isso é maravilhoso!"
        ]
    },
    {
        enunciado: "Com a descoberta desta tecnologia, chamada Inteligência Artificial (IA), uma professora de tecnologia da escola decidiu fazer uma sequência de aulas sobre esta tecnologia. No fim de uma aula ela pede que você escreva um trabalho sobre o uso de IA em sala de aula. Qual atitude você toma?",
        alternativas: [
            "Utiliza uma ferramenta de busca na internet que utiliza IA para que ela ajude a encontrar informações relevantes para o trabalho e explique numa linguagem que facilite o entendimento.",
            "Escreve o trabalho com base nas conversas que teve com colegas, algumas pesquisas na internet e conhecimentos próprios sobre o tema.",
        ]
    },
    {
        enunciado: "Após a elaboração do trabalho, a professora realizou um debate entre a turma para entender como foi realizada a pesquisa e escrita. Nessa conversa também foi levantado um ponto muito importante: como a IA impacta o trabalho do futuro. Nesse debate, como você se posiciona?",
        alternativas: [
            "Defende a ideia de que a IA pode criar novas oportunidades de emprego e melhorar habilidades humanas.",
            "Me preocupo com as pessoas que perderão seus empregos para máquinas e defendem a importância de proteger os trabalhadores."
        ]
    },
    {
        enunciado: "Ao final da discussão, você precisou criar uma imagem no computador que representasse o que pensa sobre IA. E agora?",
        alternativas: [
            "Criar uma imagem utilizando uma plataforma de design como o Paint.",
            "Criar uma imagem utilizando um gerador de imagem de IA."
        ]
    },
    {
        enunciado: "Você tem um trabalho em grupo de biologia para entregar na semana seguinte, o andamento do trabalho está um pouco atrasado e uma pessoa do seu grupo decidiu fazer com ajuda de uma IA. O problema é que o trabalho está totalmente igual ao do chat. O que você faz?",
        alternativas: [
           "Escrever comandos para o chat é uma forma de contribuir com o trabalho, por isso não é um problema utilizar o texto inteiro.",
            "O chat pode ser uma tecnologia muito avançada, mas é preciso manter a atenção pois toda máquina erra, por isso revisar o trabalho e contribuir com as perspectivas pessoais é essencial."
        ]
    },
];
let atual = 0;
let perguntaAtual;
function mostraPergunta() {
    perguntaAtual = perguntas[atual];
}
function mostraPergunta() {
    perguntaAtual = perguntas[atual];
    caixaPerguntas.textContent = perguntaAtual.enunciado;
}
mostraPergunta()
let atual = 0;
let perguntaAtual;

function mostraPergunta() {
  perguntaAtual = perguntas[atual];
  caixaPerguntas.textContent = perguntaAtual.enunciado;
}

mostraPergunta();
let atual = 0;
let perguntaAtual;

function mostraPergunta() {
  perguntaAtual = perguntas[atual];
  caixaPerguntas.textContent = perguntaAtual.enunciado;
  mostraAlternativas();
}
function mostraAlternativas() {}

mostraPergunta();
const alternativa
(const alternativa of perguntaAtual.alternativas)
function mostraAlternativas() {
  for (const alternativa of perguntaAtual.alternativas) {
  }
}
function mostraAlternativas() {
  for (const alternativa of perguntaAtual.alternativas) {
    const botaoAlternativas = document.createElement("button");
  }
}
function mostraAlternativas() {
  for (const alternativa of perguntaAtual.alternativas) {
    const botaoAlternativas = document.createElement("button");
    botaoAlternativa.textContent = alternativa;
  }
}
function mostraAlternativas() {
  for (const alternativa of perguntaAtual.alternativas) {
    const botaoAlternativas = document.createElement("button");
    botaoAlternativa.textContent = alternativa;
    caixaAlternativas.appendChild(botaoAlternativas);
  }
}
:root {
  --cor-fundo: #01080E;
  --cor-principal: #0B0D20 ;
  --cor-secundaria: #212333;
  --cor-destaque: #2BDEFD;
  --cor-texto: #D7F9FF;
}
body {
  background-color: var(--cor-fundo);
  color: var(--cor-texto);
}
body {
  background-color: var(--cor-fundo);
  color: var(--cor-texto);
  display: flex;
  justify-content: center;
  align-items: center;
}
body {
  background-color: var(--cor-fundo);
  color: var(--cor-texto);
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}
.caixa-principal{
  background-color: var(--cor-principal);
  width: 90%;
  text-align: center;
  padding: 20px;
}
h1{
 color: var(--cor-destaque);
}
const perguntas = [
  {
    enunciado:
      "Assim que saiu da escola você se depara com uma nova tecnologia”
    alternativas: [
      {
        texto: "Isso é assustador!",
        afirmacao: "afirmação",
      },
      {
        texto: "Isso é maravilhoso!",
        afirmacao: "afirmação",
      },
    ],
  },
]
const perguntas = [
  {
    enunciado:
      "Assim que saiu da escola você se depara com uma nova tecnologia, um chat que consegue responder todas as dúvidas que uma pessoa pode ter, ele também gera imagens e áudios hiper-realistas. Qual o primeiro pensamento?",
    alternativas: [
      {
        texto: "Isso é assustador!",
        afirmacao: "afirmação",
      },
      {
        texto: "Isso é maravilhoso!",
        afirmacao: "afirmação",
      },
    ],
  },
  {
    enunciado:
      "Com a descoberta desta tecnologia, chamada Inteligência Artificial, uma professora de tecnologia da escola decidiu fazer uma sequência de aulas sobre esta tecnologia. No fim de uma aula ela pede que você escreva um trabalho sobre o uso de IA em sala de aula. Qual atitude você toma?",
    alternativas: [
      {
        texto:
          "Utiliza uma ferramenta de busca na internet que utiliza IA para que ela ajude a encontrar informações relevantes para o trabalho e explique numa linguagem que facilite o entendimento.",
        afirmacao: "afirmação",
      },
      {
        texto:
          "Escreve o trabalho com base nas conversas que teve com colegas, algumas pesquisas na internet e conhecimentos próprios sobre o tema.",
        afirmacao: "afirmação",
      },
    ],
  },
  {
    enunciado:
      "Após a elaboração do trabalho escrito, a professora realizou um debate entre a turma para entender como foi realizada a pesquisa e escrita. Nessa conversa também foi levantado um ponto muito importante: como a IA impacta o trabalho do futuro. Nesse debate, como você se posiciona?",
    alternativas: [
      {
        texto:
          "Defende a ideia de que a IA pode criar novas oportunidades de emprego e melhorar habilidades humanas.",
        afirmacao: "afirmação",
      },
      {
        texto:
          "Me preocupo com as pessoas que perderão seus empregos para máquinas e defendem a importância de proteger os trabalhadores.",
        afirmacao: "afirmação",
      },
    ],
  },
  {
    enunciado:
      "Ao final da discussão, você precisou criar uma imagem no computador que representasse o que pensa sobre IA. E agora?",
    alternativas: [
      {
        texto:
          "Criar uma imagem utilizando uma plataforma de design como o Paint.",
        afirmacao: "afirmação",
      },
      {
        texto: "Criar uma imagem utilizando um gerador de imagem de IA.",
        afirmacao: "afirmação",
      },
    ],
  },
  {
    enunciado:
      "Você tem um trabalho em grupo de biologia para entregar na semana seguinte, o andamento do trabalho está um pouco atrasado e uma pessoa do seu grupo decidiu fazer com ajuda da IA. O problema é que o trabalho está totalmente igual ao do chat. O que você faz? ",
    alternativas: [
      {
        texto:
          "Escrever comandos para o chat é uma forma de contribuir com o trabalho, por isso não é um problema utilizar o texto inteiro.",
        afirmacao: "afirmação",
      },
      {
        texto:
          "O chat pode ser uma tecnologia muito avançada, mas é preciso manter a atenção pois toda máquina erra, por isso revisar o trabalho e contribuir com as perspectivas pessoais é essencial.",
        afirmacao: "afirmação",
      },
    ],
  },
];
function mostraAlternativas() {
  for (const alternativa of perguntaAtual.alternativas) {
    // Código omitido
    botaoAlternativas.textContent = alternativa.texto;

    // Código omitido
  }
}
function mostraAlternativas() {
  for (const alternativa of perguntaAtual.alternativas) {
    // Código omitido
    botaoAlternativas.textContent = alternativa.texto;
    botaoAlternativas.addEventListener();
    // Código omitido
  }
}
function mostraAlternativas() {
  for (const alternativa of perguntaAtual.alternativas) {
    const botaoAlternativas = document.createElement("button");
    botaoAlternativas.textContent = alternativa.texto;
    botaoAlternativas.addEventListener("click", function () {
      atual++;
      mostraPergunta();
    });
    caixaAlternativas.appendChild(botaoAlternativas);
  }
}
var botaoDescobrir = document.getElementById('descobrir');

function mostrarFato() {
    alert("O elefante é o maior animal terrestre!");
}

botaoDescobrir.addEventListener("clicar", mostrarFato);
botao.______ = opcao.texto;
botao.__________('click', () => cafeSelecionado(opcao));
containerDeOpcoes._________(botao);
elementoOpcoes.addEventListener("click", () => respostaSelecionada(opcao));
function respostaSelecionada(opcaoSelecionada) {
 atual++;

 mostraPerguntaAtual();
}
function respostaSelecionada(opcaoSelecionada) {
 const resposta = opcaoSelecionada.afirmacoes;
 atual++;
 mostraPerguntaAtual();
}
let atual = 0;
let perguntaAtual;
let historiaFinal = "";
function respostaSelecionada(opcaoSelecionada){
    const afirmacoes = opcaoSelecionada.afirmacoes;
    historiaFinal = afirmacoes;
    atual++;
    mostraPergunta();
}
function mostraPergunta() {
  if (atual >= perguntas.length) {
    mostraResultado();
    return;
  }
  perguntaAtual = perguntas[atual];
  caixaPerguntas.textContent = perguntaAtual.enunciado;
  mostraAlternativas();
}
function mostraPergunta() {
if (atual >= perguntas.length) {
  mostraResultado();
  return;
}
mostraResultado();
return;
perguntaAtual = perguntas[atual];
caixaPerguntas.textContent = perguntaAtual.enunciado;
mostraAlternativas();
}
function mostraPergunta() {
  if (atual >= perguntas.length) {
    mostraResultado();
    return;
  }
  perguntaAtual = perguntas[atual];
  caixaPerguntas.textContent = perguntaAtual.enunciado;
  caixaAlternativas.textContent = "";
  mostraAlternativas();
}
function mostraResultado() {
    caixaPerguntas.textContent = "Em 2049...";
    textoResultado.textContent = historiaFinal;
    caixaAlternativas.textContent = "";
}
function mostraResultado() {
caixaPergunta.textContent = "Em 2049…";
textoResultado.textContent = historiaFinal;
caixaAlternativas.textContent = "";
function mostraResultado() {
    caixaPerguntas.textContent = "Em 2049...";
    textoResultado.textContent = historiaFinal;
    caixaAlternativas.textContent = "";
}
function respostaSelecionada(opcaoSelecionada) {
    const afirmacoes = opcaoSelecionada.afirmacao;
    historia += afirmacoes + " ";
    atual++;
   mostraPergunta();
}
const afirmacoes = opcaoSelecionada.afirmacao;
historia += afirmacoes + " ";
