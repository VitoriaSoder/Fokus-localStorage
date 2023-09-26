Documentação do processo de desenvolvimento para fins de estudo 

Objetivo do projeto: O objetivo do projeto é desenvolver um crud completo. O projeto deve conter: Criação de lista, edição de lista, deleta lista 

Motantando o crud 

Primeiro foi realizado a criação de uma variavel chamada "taskListContainer", com o objetivo de retornar o primeiro elemento do documento. Selecionando assim, a classes "app_section-task-list", aonde serão feitas as interações do crud.

Segundo passo foi criar uma lista de objetos chamada tarefas, dentro dessa lista possui a variavel "descrição", que tem como objetivo retornar um texto que irá especificar se a tarefa foi concluída ou não. Dentro do mesmo objeto foi colocado outra variavel booleana chamada de "concluido", afim de retornar se a lista foi concluída ou não.

Terceiro passo foi colocar o icone em svg, aonde foi criado uma variavel chamada "taskIconSvg" e passado seu svg. Criei uma variavel chamada "svgIcon" que recebe um novo elemento chamado "svgIcon". Logo após acessei o conteúdo html com innerHTML que recebeu o a variavel "taskIconSvg" que contem o svg.

Depois  desse processo de criação dessas variaveis, criei uma função que será responsavel por criar as tarefas. O nome dado para a função foi "createTarefas", passei a lista para dentro da função e criei uma variavel chamada "li" que recebe createElement("li"), foi utilizado o createElement para criar um novo elemento html especifico. Depois adicionei mais uma classe chamada "app__section-task-list-item"

realizei a criação de outra variavel chamada paragrafy, que irá acessar o elemento do html especico chamado de "p", que é uma abreviação de paragrafo "<p>" do html que já existe. Logo após adicionei a classe "app__section-task-list-item-description" para o elemento <p>.


Depois passei o paragrafy.textContent recebendo o tarefas.descrição, ou seja, atribui o valor da propriedade descricao do objeto tarefa ao conteúdo de texto do elemento <p>.

Logo após  adicinei o elemento <p> e o svg representado pela variável paragrafo e o icone como um filho de um elemento <li>
