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

O instrutor então mostrou como referenciar a tag < i m g > no HTML usando o método document.querySelector() e criar uma variável chamada banner. Em seguida, ele explicou como alterar a imagem dentro de eventos de clique usando o método setAttribute() para mudar o atributo src da tag <i m g>.

Quando o botão "Foco" é clicado, a imagem é alterada para a verde. Quando os botões "Descanso curto" e "Descanso longo" são clicados, a imagem é alterada para a azul. O instrutor também mencionou que os addEventListener() estão começando a ter códigos repetidos e que isso será refatorado na próxima aula.


Aqui está um resumo da aula:4

Nesta aula, o instrutor está trabalhando no projeto Fokus, que envolve alterar imagens e cores de fundo de uma página web. Ele percebeu que havia linhas de código repetidas dentro de cada addEventListener(), o que tornava o código menos eficiente.

Para resolver esse problema, o instrutor propôs separar as funções e métodos em uma função chamada alterarContexto(). Essa função recebe a variável html com o método setAttribute() para definir os parâmetros data-contexto e contexto. Ela também chama a variável banner com o método setAttribute() para definir o atributo src e o contexto, usando uma template string.

Em seguida, o instrutor ajustou os métodos addEventListener() para passar o contexto para a função alterarContexto(). Ele removeu as linhas de código desnecessárias e chamou a função alterarContexto() passando o valor correspondente ao contexto.

Ao final, o instrutor concluiu que o código foi refatorado e bem-reestruturado, e que agora é possível testar a aplicação. Ele ressaltou que ainda é necessário trabalhar em outros elementos, como a frase à esquerda da imagem e o efeito de clique em todas as opções do temporizador.



Aqui está um resumo da aula sobre manipulação de elementos no DOM com JavaScript:5

O instrutor está trabalhando no projeto Fokus, que envolve alterar o texto exibido na página principal de acordo com o contexto (foco, descanso curto, descanso longo).

Ele começa analisando o design no Figma e identificando os textos que precisam ser alterados.

No código, o instrutor encontra a tag "< h 1 >" que contém o texto a ser modificado e cria uma variável para referenciar esse elemento.

As alterações de texto serão feitas quando houver eventos de clique nos botões do temporizador. O instrutor usa um bloco switch para verificar o contexto atual e atualizar o texto da tag "< h 1 >" usando o método innerHTML.

Para o contexto de "foco", o texto exibido é "Otimize sua produtividade, mergulhe no que importa".

Nos contextos de "descanso curto" e "descanso longo", o instrutor adiciona tags "< s t r o n g >" para destacar partes do texto.

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


parte 2

Aula1

Nesta aula, o instrutor apresentou o projeto base que será utilizado ao longo do curso, explicando a estrutura de pastas e arquivos do projeto. Ele mencionou a extensão do VS Code chamada Live Server, que será utilizada para rodar o projeto em tempo real. O objetivo principal foi monitorar o clique no botão "Adicionar nova tarefa" e alternar a exibição do formulário de adicionar tarefa. Foi explicado como encontrar o botão no HTML do projeto, utilizando o método querySelector() e a classe app__button--add-task. Em seguida, o instrutor adicionou um evento de clique ao botão utilizando o método addEventListener() e explicou como utilizar o método classList.toggle() para alternar a classe hidden do formulário de adicionar tarefa. Por fim, o instrutor mostrou o formulário no HTML do projeto, utilizando a classe app__form-add-task e a classe hidden para escondê-lo. Essa funcionalidade é importante para permitir a interação do usuário com o projeto e será a base para o desenvolvimento das demais funcionalidades ao longo do curso.

Aula2

Nesta aula, aprendemos a interagir com um formulário em uma aplicação web. O instrutor mostrou como monitorar o envio do formulário, obter o valor digitado em um campo de texto (textarea) e criar uma lista de tarefas a partir desse valor. Além disso, ele explicou como armazenar essa lista de tarefas no armazenamento local do navegador usando o localStorage. Foram demonstrados o uso dos métodos preventDefault() e setItem() para evitar o comportamento padrão de envio do formulário e para guardar a lista de tarefas no localStorage, respectivamente. Também foi mostrado como verificar se os dados foram corretamente armazenados no localStorage usando as ferramentas de desenvolvedor do navegador.

Aula3

Nesta aula, aprendemos sobre a limitação da API do local storage em armazenar objetos complexos, como arrays, devido ao fato de que ela só consegue lidar com strings. Para resolver esse problema, o instrutor introduziu a API JSON e seus métodos stringify() e parse(), que permitem transformar arrays em strings e vice-versa, possibilitando o armazenamento adequado no local storage. Também vimos como utilizar esses métodos para armazenar e recuperar dados do local storage, garantindo que as informações sejam salvas corretamente.

Aula4

Nesta aula, o instrutor ensina como criar uma tarefa utilizando JavaScript. Ele começa mostrando a estrutura de uma tarefa em HTML, que inclui uma lista, um ícone, um parágrafo e um botão com uma imagem. Em seguida, ele explica como criar uma função em JavaScript que recebe uma tarefa como parâmetro e retorna o HTML correspondente a essa tarefa. O instrutor destaca que o foco é o JavaScript, não o HTML e CSS, e que o objetivo é gerar o HTML dinamicamente. Ao final, ele menciona que o próximo passo é testar as linhas de código escritas, verificando se há uma lista de tarefas no localStorage e, se houver, recuperando-a e criando automaticamente as tarefas correspondentes. Este trecho do vídeo é útil para quem está aprendendo a desenvolver aplicações web utilizando JavaScript e deseja aprender como criar elementos HTML dinamicamente com base em dados fornecidos.

Aula5

Nesta aula, aprendemos a ler tarefas gravadas no localStorage. Primeiramente, verificamos se a lista de tarefas existe no localStorage utilizando o método localStorage.getItem() com a chave "tarefas". Em seguida, utilizamos o método JSON.parse() para converter a string retornada em um objeto JavaScript, que é um array contendo a lista de tarefas. Caso o retorno seja nulo, atribuímos um array vazio à variável tarefas utilizando o operador ||.

Depois de obter a lista de tarefas do localStorage, mostramos como percorrê-la utilizando o método forEach(). Para cada tarefa, chamamos a função criarElementoTarefa(), que retorna o elemento HTML correspondente. Esse elemento é então adicionado à lista de tarefas no DOM.

O instrutor também ressaltou a importância de separar as responsabilidades das funções, onde a função criarElementoTarefa() é responsável apenas por criar o elemento HTML e a função que a chama é responsável por decidir o que fazer com esse elemento. Ao recarregar a página, as tarefas cadastradas devem aparecer corretamente na lista. No entanto, o instrutor mencionou que ainda há algo errado com a configuração do elemento e sugeriu a depuração para identificar o problema.

Aula6

Nesta aula, o instrutor abordou a correção do estilo da lista de tarefas, a remoção de elementos desnecessários, a adição de classes CSS aos elementos e a adição de uma nova tarefa à lista. Ele mostrou como resolver problemas de estilo e adicionar funcionalidades, como criar um elemento para a nova tarefa e adicioná-lo à lista, limpar o campo de texto do formulário e ocultar o formulário após adicionar a tarefa. O instrutor também destacou a importância dessas etapas no desenvolvimento da aplicação e mencionou que ainda há muito a ser feito.

Aula7

Nesta aula, o instrutor abordou a funcionalidade de edição de tarefas na aplicação Fokus. Ele mostrou como criar um botão de edição utilizando o método document.createElement('button') e como manipular o evento de clique desse botão utilizando a propriedade onclick. Além disso, ele utilizou a função prompt() para exibir uma caixa de diálogo onde o usuário pode informar o novo nome da tarefa. O valor digitado pelo usuário é armazenado em uma variável e utilizado para atualizar o texto da tarefa no DOM. No entanto, o instrutor ressaltou que essa atualização é apenas no DOM e não no localStorage(), e que isso será abordado no próximo vídeo.

Aula8

Nesta aula, o instrutor abordou a necessidade de atualizar o localStorage() quando o usuário editar uma tarefa já criada. Ele mostrou o código atual, onde a atualização do localStorage é feita dentro do evento onclick do botão, mas apontou que essa abordagem pode se tornar frágil no futuro. Para resolver esse problema, o instrutor propôs uma nova estratégia, criando uma função chamada atualizarTarefas() que é responsável por atualizar o localStorage. Essa função encapsula a lógica de atualização do localStorage, tornando o código mais organizado e menos suscetível a futuras alterações. Além disso, o instrutor também atualizou o texto da tarefa no objeto que representa a tarefa, para refletir a nova descrição. No final, ele identificou um bug e mencionou que será abordado em um próximo vídeo.

Aula9

Nesta aula, o instrutor abordou a correção de bugs e a aplicação de técnicas de debugging no código. Ele explicou a utilização do console.log() para exibir mensagens no navegador, além de mostrar como utilizar o prompt para interagir com o usuário e obter informações. Também foi demonstrado o uso da estrutura condicional if para verificar se uma variável possui um valor válido antes de executar determinadas ações. O instrutor ressaltou a importância das ferramentas de debugging para identificar e solucionar problemas no código, destacando o console.log() e o debugger como ferramentas úteis no arsenal dos alunos.

Aula10

Nesta aula, o instrutor abordou a manipulação de elementos HTML em uma aplicação chamada Fokus. Ele explicou como selecionar uma tarefa ao clicar nela, atualizando a descrição da tarefa em andamento e adicionando uma classe específica ao item clicado. O instrutor mostrou o código no VS Code, destacou a tag de parágrafo onde a descrição da tarefa deve ser preenchida e explicou como selecioná-la utilizando um seletor CSS. Além disso, ele demonstrou como adicionar um evento de clique nas tarefas e como adicionar uma classe para indicar que a tarefa está ativa. No entanto, ele percebeu que todas as tarefas estavam com a classe ativa ao mesmo tempo e mencionou que no próximo vídeo irá mostrar como refinar o método para garantir que apenas uma única tarefa tenha a classe ativa por vez.

Aula11

Neste trecho do vídeo, o instrutor aborda a estratégia de garantir que apenas uma única tarefa tenha a classe ativa. Ele explica a diferença entre os métodos querySelectorAll e querySelector e demonstra como utilizar o querySelectorAll para selecionar e iterar sobre os elementos que possuem a classe ativa. O instrutor também adiciona a funcionalidade de deselecionar a tarefa selecionada e utiliza a técnica de "Early Return" para interromper a execução do código quando necessário.

Aula12

Nesta aula, o instrutor está explicando como adicionar funcionalidades ao código de um projeto chamado "Fokus". Ele começa explicando que o código possui uma função chamada "contagemRegressiva" que verifica se o tempo decorrido em segundos é menor ou igual a zero. Em seguida, ele menciona que o tempo decorrido se refere ao tempo que está sendo contado pelo timer do projeto, que é configurado para 30 segundos. Quando o tempo chega a zero, o código executa um trecho que emite um alerta, toca um som e zera o timer.

O instrutor explica que o objetivo é adicionar um evento que seja disparado quando o timer chegar a zero, de forma que outras partes da aplicação possam reagir a esse evento. Para isso, ele mostra que no arquivo "script.js" é possível verificar qual é o valor do atributo "data-contexto" do elemento HTML, que indica se o foco está ativo ou não. Se o valor desse atributo for "foco", significa que a tarefa está sendo executada e, nesse caso, o código cria um evento customizado chamado "FocoFinalizado" e o dispara usando a função "dispatchEvent" do objeto "document".

O instrutor ressalta que outras partes da aplicação podem ouvir e reagir a esse evento, e que no próximo vídeo será mostrado como tratar esse evento no arquivo "script-crud" para indicar que a tarefa foi finalizada.

Aula13

Claro! Nesta aula, o instrutor está explicando como adicionar funcionalidades ao evento customizado "FocoFinalizado" no código JavaScript. Ele mostra como adicionar um event listener para esse evento no objeto "document" e verifica se existe uma tarefa selecionada e um elemento "li" da tarefa selecionada. Caso existam, ele remove a classe "app__section-task-list-item-active" desse elemento "li" e adiciona a classe "app__section-task-list-item-complete". Além disso, ele desabilita o botão da tarefa selecionada usando o método "setAttribute" com o atributo "disabled". O instrutor também menciona a importância de fazer um "double check" para garantir que o elemento "li" da tarefa selecionada não seja nulo. Essa implementação permite que, ao finalizar a contagem regressiva de uma tarefa, a classe e o estado do botão sejam atualizados corretamente. Por fim, o instrutor menciona que o próximo passo será lidar com a persistência do estado de tarefa concluída dentro do localStorage.

Aula14

Nesta aula, o instrutor abordou a necessidade de atualizar o local storage da aplicação para que o estado das tarefas completadas seja persistido mesmo após a recarga da página. Ele mostrou o código onde é adicionado um event listener para o evento "FocoFinalizado" e explicou como verificar se existe uma tarefa selecionada, remover a classe que indica que o item está ativo, adicionar a classe que indica que o item está completo, desabilitar o botão dentro do item e adicionar a propriedade "completa" à tarefa selecionada com o valor "true". Além disso, ele tratou o clique em um item de tarefa, adicionando condições para verificar se a tarefa já está completa e para tratar o caso em que a tarefa não está completa. O instrutor ressaltou que essas modificações são suficientes para persistir a informação de tarefa completa no local storage e recuperá-la corretamente ao recarregar a página. Ele finalizou mencionando que esse foi o último bug corrigido no curso, mas que ainda há mais coisas a serem desenvolvidas.

Aula15

Nesta aula, o instrutor discute a implementação de um menu de contexto ao lado da lista de tarefas na interface do aplicativo Fokus. Esse menu oferece duas opções: limpar as tarefas concluídas ou limpar todas as tarefas. O instrutor mostra o código HTML e JavaScript necessários para implementar a opção de limpar tarefas concluídas. Ele explica como selecionar o botão correspondente no arquivo index.html usando o id do elemento e como adicionar um evento onclick a esse botão. Dentro da função onclick, ele utiliza o método querySelectorAll para selecionar todos os elementos que possuem a classe indicando que a tarefa está completa, e em seguida, utiliza o método forEach para iterar sobre esses elementos e removê-los do DOM usando o método remove. Além disso, ele também mostra como atualizar a lista de tarefas na local storage, filtrando apenas as tarefas que não estão completas. O instrutor menciona um erro na linha 122 do código, onde ele tenta fazer um assignment de uma constante, e explica que é necessário alterar a declaração da lista de tarefas de const para let, pois ela precisa ser mutável. Por fim, ele testa a funcionalidade no navegador e verifica que as tarefas concluídas são removidas tanto do DOM quanto da local storage. O instrutor menciona que o próximo passo é implementar o método para remover todas as tarefas, concluídas ou não.

Aula16

Nesta aula, aprendemos a implementar a funcionalidade de remover todos os itens em uma aplicação chamada Fokus. Para isso, foi criada uma constante chamada "removerTarefas" e associada à função que estava anteriormente dentro do "onclick" do botão de remover itens concluídos. Foi adicionado um parâmetro na função "removerTarefas" chamado "somenteCompletas" para remover apenas os itens completos ou todos os itens, dependendo do valor do parâmetro. Foi feito um filtro condicional na lista de tarefas para remover apenas as tarefas completas ou atribuir um array vazio à lista de tarefas, removendo todas as tarefas. Por fim, foi encontrado o botão de remover todas as tarefas no arquivo "index.html" e foi atribuída a função "removerTarefas" ao clique desse botão, passando o valor "false" para o parâmetro "somenteCompletas". Com essa implementação, a aplicação Fokus ficou mais robusta, permitindo a remoção de todos os itens ou apenas dos itens completos.
