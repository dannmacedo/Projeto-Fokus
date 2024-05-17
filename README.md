Curso muito produtivo com enfase na manipulação de elementos no DOM

Aqui está um resumo da aula:1

O instrutor introduz a manipulação de elementos no DOM (Document Object Model) e apresenta alguns métodos para capturar elementos HTML na tela.

Ele mostra como acessar o projeto no VS Code e menciona a existência de arquivos de áudio e imagens que serão utilizados no curso.

O objetivo do curso é utilizar JavaScript puro para manipular os elementos no DOM.

O instrutor demonstra o uso dos métodos querySelector(), querySelectorAll(), getElementsByClassName() e getElementById() para capturar botões e outros elementos no projeto.

Ele explica que o DOM é uma estrutura em forma de nós de árvore que combina elementos HTML, CSS, JavaScript e outras APIs inseridas no projeto, e que o objeto global "document" é uma referência ao HTML, permitindo interagir com o conteúdo e os elementos da página.

No próximo vídeo, o instrutor abordará como conferir mais dinamismo ao projeto através da modificação dos atributos de dados (data attributes).



Aqui está um resumo da aula:2

Nesta aula, o instrutor Luan Alves abordou a implementação de um projeto relacionado à alteração de elementos na tela com base em diferentes cenários de temporizadores.

Ele começou explicando como alterar os atributos de dados (data attributes) em um arquivo HTML e CSS para modificar a cor de fundo da página. Em seguida, mostrou como adicionar interatividade à página usando JavaScript, através do uso de eventos de clique e do método setAttribute().

O instrutor também mencionou a importância do uso do atributo defer ao carregar arquivos JavaScript na página.

Por fim, foi proposto um desafio para o espectador implementar a mudança de cor de fundo ao clicar em um botão específico. O próximo vídeo promete abordar alterações de imagens.



Aqui está um resumo da aula sobre manipulação de elementos no DOM:3

Nesta aula, o instrutor Luan Alves ensinou como alterar imagens na página usando JavaScript. Ele começou mostrando os layouts de tela no Figma, onde existem três imagens diferentes: uma verde de uma mulher mergulhando, uma azul de outra mulher mergulhando, e uma roxa de um homem visto de costas.

O instrutor então mostrou como referenciar a tag <img> no HTML usando o método document.querySelector() e criar uma variável chamada banner. Em seguida, ele explicou como alterar a imagem dentro de eventos de clique usando o método setAttribute() para mudar o atributo src da tag <img>.

Quando o botão "Foco" é clicado, a imagem é alterada para a verde. Quando os botões "Descanso curto" e "Descanso longo" são clicados, a imagem é alterada para a azul. O instrutor também mencionou que os addEventListener() estão começando a ter códigos repetidos e que isso será refatorado na próxima aula.


Aqui está um resumo da aula:4

Nesta aula, o instrutor está trabalhando no projeto Fokus, que envolve alterar imagens e cores de fundo de uma página web. Ele percebeu que havia linhas de código repetidas dentro de cada addEventListener(), o que tornava o código menos eficiente.

Para resolver esse problema, o instrutor propôs separar as funções e métodos em uma função chamada alterarContexto(). Essa função recebe a variável html com o método setAttribute() para definir os parâmetros data-contexto e contexto. Ela também chama a variável banner com o método setAttribute() para definir o atributo src e o contexto, usando uma template string.

Em seguida, o instrutor ajustou os métodos addEventListener() para passar o contexto para a função alterarContexto(). Ele removeu as linhas de código desnecessárias e chamou a função alterarContexto() passando o valor correspondente ao contexto.

Ao final, o instrutor concluiu que o código foi refatorado e bem-reestruturado, e que agora é possível testar a aplicação. Ele ressaltou que ainda é necessário trabalhar em outros elementos, como a frase à esquerda da imagem e o efeito de clique em todas as opções do temporizador.



Aqui está um resumo da aula sobre manipulação de elementos no DOM com JavaScript:5

O instrutor está trabalhando no projeto Fokus, que envolve alterar o texto exibido na página principal de acordo com o contexto (foco, descanso curto, descanso longo).

Ele começa analisando o design no Figma e identificando os textos que precisam ser alterados.

No código, o instrutor encontra a tag "<h1>" que contém o texto a ser modificado e cria uma variável para referenciar esse elemento.

As alterações de texto serão feitas quando houver eventos de clique nos botões do temporizador. O instrutor usa um bloco switch para verificar o contexto atual e atualizar o texto da tag "<h1>" usando o método innerHTML.

Para o contexto de "foco", o texto exibido é "Otimize sua produtividade, mergulhe no que importa".

Nos contextos de "descanso curto" e "descanso longo", o instrutor adiciona tags "<strong>" para destacar partes do texto.

O instrutor explica que o método innerHTML pode ser usado não apenas para alterar o texto, mas também para inserir HTML formatado.

O próximo passo do projeto será alterar o estilo dos botões de acordo com o contexto selecionado.



Aqui está um resumo da aula sobre como adicionar e remover classes em elementos do DOM usando JavaScript:6

O instrutor ensina como alterar o estilo dos botões em um projeto utilizando HTML, CSS e JavaScript.

Inicialmente, o botão "Foco" possui a classe "active" aplicada, enquanto os outros botões não.

É explicado como alterar a classe "active" dinamicamente conforme o clique nos botões.

Usando JavaScript, é mostrado como adicionar a classe "active" ao botão clicado, utilizando o método ".classList.add('active')".

Também é necessário remover a classe "active" dos outros botões quando um deles é clicado, para que apenas um botão fique ativo por vez. Isso é feito com o método ".classList.remove('active')".

O instrutor menciona que o método ".classList" possui outras funcionalidades, como ".toggle()" e ".contains()", que serão abordadas em um próximo vídeo.

No próximo vídeo, será ensinado como adicionar música ao projeto.



Aqui está um resumo da aula sobre como inserir e manipular um arquivo de áudio em uma página web:7

O objetivo é aprender a reproduzir um arquivo de áudio quando o usuário clicar em um input específico, criando uma música de fundo relaxante para a pessoa desenvolvedora se concentrar.

O input de música é identificado pelo ID "alternar-musica" e pode ser acessado usando document.querySelector('#alternar-musica').

O arquivo de áudio é criado como um objeto JavaScript do tipo Audio, com o caminho "sons/luna-rise-part-1.mp3".

É recomendado armazenar os arquivos de áudio em variáveis no início do código, para que o projeto já tenha todos os arquivos disponíveis durante a leitura.

Um evento change é adicionado ao input de música, que verifica se a música está pausada ou não. Se estiver pausada, a música é reproduzida usando musica.play(), caso contrário, é pausada usando musica.pause().

Para a música tocar continuamente, a propriedade musica.loop = true é definida, fazendo a música ser reproduzida em loop.

O próximo passo é iniciar o temporizador, que será abordado em um próximo vídeo.

Espero que este resumo tenha sido útil! Lembre-se de que estou aqui para ajudá-lo com qualquer dúvida relacionada ao conteúdo da aula.


Claro, vou fazer um resumo da aula para você:8

Nesta aula, o instrutor Luan Alves está ensinando sobre como implementar um temporizador no projeto Fokus, utilizando JavaScript e manipulação do DOM.

Ele começa explicando que o temporizador deve exibir diferentes valores de tempo, como 25 minutos, 5 minutos e 15 minutos, de acordo com os botões clicados pelo usuário.

O instrutor então mostra como declarar a variável "tempoDecorridoEmSegundos" e criar uma função de seta para decrementar esse valor. Ele também explica como referenciar o botão "Começar" no código HTML e criar um evento de clique para chamar a função de contagem regressiva.

Em seguida, o instrutor demonstra como automatizar o temporizador usando o método setInterval() e como associar a função de inicialização à função de contagem regressiva.

Por fim, o instrutor destaca a importância de interromper a execução do temporizador para evitar o consumo excessivo de recursos da máquina.

Espero que este resumo tenha sido útil! Lembre-se de que, se você tiver alguma dúvida específica sobre o conteúdo da aula, eu estarei aqui para ajudá-lo.



Aqui está um resumo da aula sobre como pausar o temporizador usando a função clearInterval():9

O instrutor mostra como utilizar a função clearInterval() para pausar a execução do temporizador.

Ele remove a chamada da função contagemRegressiva do evento de clique, substituindo-a pela função iniciar().

Adiciona um bloco condicional if dentro da função contagemRegressiva para verificar se o tempo decorrido em segundos é menor ou igual a zero. Quando essa condição é verdadeira, ele exibe um alerta informando que o tempo foi finalizado e usa o return para interromper a execução do código.

Cria a função zerar(), que usa o clearInterval() para interromper a execução do temporizador e define intervaloId como null.

Modifica a função iniciar(), adicionando um bloco condicional if para verificar se a variável intervaloId possui algum valor. Se tiver, ele chama a função zerar() para pausar o temporizador. Caso contrário, ele usa o setInterval() para iniciar a contagem regressiva.

O instrutor sugere adicionar sons de notificação ao iniciar, pausar e finalizar o temporizador como uma melhoria adicional.


Aula 10

Nesta aula, o instrutor finaliza o projeto Fokus, mostrando como adicionar áudios em momentos específicos. Ele faz correções no código, como comentar uma linha que aciona o áudio quando o temporizador termina e ajustar a lógica de redefinição do temporizador. Além disso, ele ensina como alterar o texto do botão de "Começar" para "Pausar" quando o temporizador é iniciado, utilizando o método textContent. Por fim, ele menciona a possibilidade de alternar a imagem do botão entre "play_arrow.png" e "pause.png" como um desafio para o espectador.

Aula 11

Nesta aula, o instrutor finaliza a implementação do temporizador em um projeto, explicando como exibir o tempo na tela. Ele destaca a criação da função "mostrarTempo()" para inserir o tempo decorrido na div "tempoNaTela" utilizando o método innerHTML. Além disso, o instrutor menciona a necessidade de chamar a função "mostrarTempo()" durante a contagem regressiva e no escopo global do código para que o tempo seja sempre exibido. No próximo vídeo, ele abordará o ajuste do formato do tempo para "25:00" em vez de "1500" utilizando métodos do objeto Date.

Aula 12

Nesta aula, o instrutor discutiu sobre a formatação do tempo exibido na tela do projeto Fokus. Inicialmente, o temporizador exibia o número "1.500", que correspondia a 25 minutos. O objetivo foi resolver esse problema utilizando código em JavaScript. O instrutor mostrou como utilizar o objeto "Date" do JavaScript para formatar o tempo e como ajustar os valores dos temporizadores de acordo com o contexto. Além disso, foram feitos ajustes nos EventListeners de cada temporizador para garantir que os valores fossem atualizados corretamente. Por fim, o instrutor mencionou um último ajuste a ser feito, que foi descomentar o código responsável por reproduzir um áudio quando o tempo é finalizado.

#AprendiNaAlura @luanalvesdev 
