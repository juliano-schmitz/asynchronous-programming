# PROGRAMAÇÃO ASSÍNCRONA COM JAVASCRIPT

## 1. Sobre aspectos gerais da pesquisa

### 1.1 Como conheci as funções assíncronas

Eu utilizava os conceitos de assincronismo por meio da biblioteca jQuery. Anteriormente, eu desenvolvi alguns sistemas e utilizava o jQuery no front-end para facilitar a construção de páginas mais dinâmicas. O jQuery era um pré-requisito para o BootStrap, que é um framework front-end que eu utilizava para me auxiliar na construção das interfaces, principalmente, por conta conta do CSS. Como era um pré-requisito, fazia sentido eu manter o pacote completo do jQuery. O pacote completo incluía um conjunto de funcionalidades para requests. De certa forma, este conjunto de funcionalidade implementava os conceitos de assincronismo, então, em algum nível, eu possuía o entendimento de como funcionavam as requisições assíncronas.

### 1.2 Minha motivação para estudar o assunto

Primeiramente, quero aprofundar e consolidar o conhecimento prévio que já possuo. Além disso, estou migrando minha carreira de estudos e trabalho para utilizar JavaScript em aplicações WEB, principalmente, no back-end por meio da utilização de NodeJS. Identifiquei a necessidade de tornar as aplicações capazes de responderem com maior agilidade e performance às demandas, sendo necessário tornar o software assíncrono. Também identifiquei por meio de pesquisas que o assunto de assincronismo é muito difundido e é praticamente obrigatório quando relacionado com JavaScript.

## 2. Resumo sobre conceitos importantes

### 2.1 Assincronismo

O assincronismo é um conceito que surgiu para auxiliar a programação no melhoramento da performance das aplicações. Para uma melhor compreensão, é importante distinguir-se códigos síncronos de códigos assíncronos. Os códigos síncronos são executados parte a parte ou uma instrução após a outra, deixando a aplicação travada até que as etapas anteriores sejam concluídas. Já nos códigos assíncronos uma parte pode ser executada mesmo que outra ainda não tenha sido concluída, sendo que o código retornará ao sistema a informação sobre a conclusão de seu processamento, ficando disponível para quem o consumir.

### 2.2 Callback

Basicamente, pode-se dizer que callbacks são funções executadas após outras funções. Isto é, na implementação de uma função defini-se que entre os parâmetros, uma função será passada. Quando a lógica da própria função for concluída, ao final, defini-se que a função recebida como parâmetro será executada.

### 2.3 Promises

### 2.4 Async/Await

As palavras-chave async e await podem ser consideradas um sintax sugar (açúcar sintático) nas implementações com JavaScript. Ou seja, a utilização do async/await, na verdade, implementa promises "por baixo dos panos". Com async/await pode-se escrever métodos e funções assíncronas com a sintaxe muito parecida com os métodos e funções síncronos. Com async/await ainda é possível realizar requisições concorrentes ou paralelas, sendo que para as paralelas a utilização do método estático .all(), do pacote Promises (Promises.all()), talvez mantenha uma sintaxe e um código mais intuitivo. 

