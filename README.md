# NotebookLM para Criação de Jogos

## 🎯 Objetivos

O assunto de interesse para aprender utilizando o NotebookLM foi criação de jogos. O objetivo é aprender do zero a como estruturar uma ideia e executar seu desenvolvimento. Esse guia tem objetivo de guiar a idealização, qual motor gráfico utilizar para iniciar o desenolvimento, materiais para sons e imagens e por fim onde publicar meu jogo desenvolvido.

## 🔍 Fontes
As fontes utilizadas foram de canais do youtube e textos da internet. De começo, foram apeans três vídeos e dois sites, mas com o mecanismo de _Deepsearch_ do NotebookLM, foi possível reunir mais fontes confiáveis para expandir o conteúdo e assim ter mais informação para o aprendizado do conteúdo em interesse.

### Fontes em vídeo

- https://youtu.be/YttotvHX_TU?si=k36scaoZfUKG-zCX
- https://youtu.be/91SBIbwSC6A?si=N5yfRMstPj64IH9G
- https://youtu.be/Tw0o1KarOG8?si=vt_VTTYJ7qGXnswl

### Fontes em texto

- https://ebaconline.com.br/blog/como-criar-um-jogo
- https://www.rj.senac.br/noticias/tecnologia-da-informacao/como-criar-um-jogo

## 🤖 Testes de Prompts

Com as fontes encontradas, é possível extrair suas informações e dessa maneira estudar o assunto de interesse. Para isso, prompts específicos podem ser utilizados para tal proposito. Contudo, o próprio NotebookLM proprem prompts para ajudar, então foi utilizada os prompts que ela sugeriu.

### Prompt 1

#### Pergunta: Como criar meu primeiro jogo do zero sem experiência?

#### Resposta:

Criar seu primeiro jogo do zero, mesmo sem experiência prévia, é uma jornada que envolve criatividade, planejamento e a escolha das ferramentas certas. O segredo para não desistir é começar pequeno e focar no aprendizado constante.
Abaixo estão os passos fundamentais baseados nas fontes:
1. Planejamento e Ideação
Antes de abrir qualquer software, você precisa definir o que será o seu jogo.

    __Comece Pequeno__: Não tente criar um "GTA" ou um "RPG gigante" de cara. Foque em um jogo simples com uma mecânica divertida, como um jogo de plataforma ou um quebra-cabeça.
    Defina o Core Loop: É o ciclo principal da jogabilidade (ex: matar inimigos para subir de nível e enfrentar um boss).
    Crie um GDD (_Game Design Document_): Este documento serve como um manual do seu jogo, detalhando mecânicas, história, público-alvo, estilo de arte e som. Manter um GDD simples ajuda a evitar o retrabalho e a perda de foco no escopo.

2. Escolha uma _Engine_ (Motor de Jogo)
Uma engine é um _software_ que facilita a criação do jogo, cuidando de partes complexas como física e renderização de som.

    __Para iniciantes sem código__:
        __Scratch__: Ótimo para aprender lógica através de blocos visuais.
        __Construct__: Focado em lógica visual e ideal para jogos 2D.
    __Para quem quer aprender a programar__:
        __Godot__: Gratuita, leve e de código aberto. Usa GDScript (similar a _Python_) e é excelente para iniciantes.
        __Unity__: A mais popular no mercado indie, usa a linguagem C# e possui uma vasta biblioteca de tutoriais e recursos.
        __GameMaker__: Especialista em jogos 2D e muito amigável para quem está começando.

3. Programação e Lógica
Mesmo usando engines visuais, entender a lógica de programação é essencial.

    __Linguagens comuns__: C# (Unity), GDScript (Godot), C++ (Unreal) e Python.
    Se você não gosta de programar, _engines_ como Unreal e Unity possuem sistemas de programação visual (_Blueprints_ e _Visual Scripting_).

4. Arte, Áudio e Assets
Você não precisa ser um artista profissional para começar.

    __Estilos Simples__: Opte por _pixel art_, arte vetorial ou _low poly_ (para 3D).
    __Ferramentas__: Use o _Aseprite_ ou _Photoshop_ para artes, e o _Audacity_ para editar sons.
    ___Assets_ Gratuitos__: Você pode encontrar músicas, efeitos sonoros e artes gratuitas em sites como o _itch.io_, desde que dê os devidos créditos aos autores.

5. Prototipação e Testes

    __Crie um Protótipo__: Antes de finalizar o jogo, faça uma versão funcional simples para testar se a mecânica é divertida. Isso pode ser feito até no papel.
    __Teste Constantemente__: Peça para amigos jogarem. O _feedback_ externo ajuda a identificar bugs e partes do jogo que estão confusas ou difíceis demais.

6. Publicação e Comunidade

    __Participe de _Game Jams___: São competições onde você deve criar um jogo em um curto período de tempo (como um final de semana). É a melhor maneira de aprender rápido e conhecer outros desenvolvedores.
    __Onde Publicar__: O _itch.io_ é excelente para lançar seus primeiros protótipos. Para lançamentos comerciais, a _Steam_ é a principal plataforma, exigindo uma taxa de aproximadamente US$ 100 por jogo.

__Dica Final__: O seu primeiro jogo provavelmente não será perfeito, e está tudo bem. O objetivo principal deve ser terminar o projeto, pois finalizar um jogo simples ensina mais do que passar anos sonhando com um projeto impossível

---

### Prompt 2

#### Pergunta: Como funciona a criação de um Game Design Document (GDD)?

#### Resposta:

A criação de um _Game Design Document_ (GDD) funciona como a elaboração de um manual de montagem ou guia completo para o desenvolvimento de um jogo. Ele serve para organizar ideias, detalhar mecânicas e garantir que todos os envolvidos no projeto estejam alinhados com a visão inicial, evitando a fuga de escopo e o retrabalho.
Abaixo estão os passos fundamentais para criar um GDD eficiente:
1. Definição do Conceito e Público

    __Resumo Inicial__: Comece definindo o conceito do jogo em uma única frase que explique sua premissa e o que o torna único.
    __Público-alvo__: Determine quem será o jogador típico e realize pesquisas de mercado para observar concorrentes. Isso influenciará diretamente as decisões de arte e jogabilidade.

2. Detalhamento das Mecânicas e Gameplay

    __Mecânicas Principais__: Liste todas as ações que o jogador pode realizar (como pular, interagir ou atacar) e as regras que regem o mundo do jogo.
    __Core Loop__: Defina o ciclo principal de jogabilidade (ex: explorar, coletar recursos e melhorar o personagem).
    __Níveis e Inimigos__: Detalhe como as fases serão estruturadas e quais tipos de desafios ou inimigos o jogador enfrentará.

3. Identidade Visual e Sonora

    __Estilo de Arte__: Descreva o estilo visual (como _pixel art_, 3D realista ou vetorial) e inclua referências visuais para guiar os artistas.
    __Áudio__: Especifique o estilo musical e os efeitos sonoros necessários para cada ação ou ambiente do jogo.

4. Tecnologia e Recursos

    __Ferramentas__: Anote quais motores de jogo (_engines_) serão usados, como Unity, Godot ou Unreal, além de bibliotecas e softwares externos.
    __Habilidades e Orçamento__: Liste as funções de cada membro da equipe e estipule o orçamento disponível para garantir que o projeto seja viável.

5. Cronograma e Metas

    __Prazos__: Estabeleça metas de entrega para cada etapa do desenvolvimento.
    __Margem de Erro__: Sempre adicione tempo extra ao final do cronograma para refinamentos, correções de bugs e melhorias após os testes.

Dicas Práticas para um GDD Eficiente:

  __Seja Direto__: Evite textos excessivamente longos; prefira o uso de tabelas e tópicos para agilizar o entendimento da equipe.
  
  __Documento Vivo__: O GDD não deve ser estático. Ele precisa ser atualizado constantemente, pois o projeto evolui à medida que novas ideias surgem ou mecânicas são testadas.
  
  __Acessibilidade__: Para desenvolvedores independentes (indies), manter um GDD simples é uma estratégia para economizar tempo e manter o foco no essencial.

Embora o GDD seja mais comum em projetos maiores para guiar equipes multidisciplinares, ele é recomendado para qualquer desenvolvedor que deseje transformar uma ideia em um produto jogável e profissional.

---

### Prompt 3

#### Pergunta: Qual melhor game engine para quem quer criar um jogo 2D estilo Sonic?

#### Resposta:

Para criar um jogo 2D no estilo do Sonic, que exige foco em mecânicas de plataforma e física de movimento, as fontes sugerem que a escolha da engine ideal depende do seu perfil e experiência:

  __GameMaker__: É apontada como a melhor opção para quem deseja foco total em 2D e produtividade. É uma engine clássica, extremamente amigável para iniciantes e utiliza uma linguagem própria (GML) que é simples de aprender. Sua interface intuitiva acelera o desenvolvimento de projetos 2D.
  
  __Godot Engine__: Se você procura uma ferramenta gratuita, leve e de código aberto, a Godot é altamente recomendada para o desenvolvimento 2D. Ela oferece um fluxo de trabalho simples através de um sistema de nós que permite montar cenas e comportamentos de forma visual.
 
  __Construct__: Se o seu objetivo é criar um jogo sem precisar programar de forma tradicional, o Construct é a engine mais indicada. Ele utiliza um sistema de lógica visual baseado em condições e ações, sendo muito acessível para quem está começando.
  
  __Unity__: É a escolha para quem busca versatilidade total e uma vasta biblioteca de recursos. Embora suporte 3D, a Unity possui ferramentas robustas para jogos 2D performáticos, incluindo iluminação, sombras e animação esquelética. Exemplos de jogos 2D de sucesso feitos na Unity incluem _Ori and the Blind Forest_ e _Cuphead_.

Para um projeto estilo Sonic, o GameMaker costuma ser muito lembrado pela sua eficiência em plataformas 2D, enquanto a Godot é uma excelente alternativa gratuita que vem crescendo em popularidade no meio indie. O importante é focar em uma mecânica central divertida (como a velocidade e o pulo, no caso do Sonic) e desenvolver o jogo em torno dela.

---

O _prompt_ 3 foi elaborado por mim, dessa forma eu poderia escolher qual engine seria melhor para o meu propósito de acordo com o que a IA descreveria para mim. Os demais prompts elaboradas por ela mesma foram de grande ajuda ao aprendizado, guiando um iniciante que não sabe como começar e mostrando as ferramentas já existentes. 

## Miniguia

Do assunto escolhido, para criar um jogo mesmo sem experiência, é sempre recomendável que não comece com projetos muito grandes. Começar com objetivos simples e mecânicas divertidas e ir evoluindo a medida com que aprende no desenvolvimento.

Destaca-se o aprendizado sobre o GDD (_Game Design Document_), que é o guia definitivo de como vai ser o desenvolvimento do jogo em si, todo o escopo, mecânicas, personagens, história. Não importante a game engine que será usada, saber o que será criado e como organizar esse processo é fundamental para que a criação não desande no meio do caminho.

Para a criação de um jogo e a utilização do NotebookLM, é sempre bom ter alguns prompts prontos para sempre usá-los por sua importância na criação de um jogos, que são eles: 

- Como criar um GDD
- Como encontrar fontes de áudio e imagem
- Como criar mecânicas divertidas para meu jogo
