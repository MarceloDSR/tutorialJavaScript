# Tutorial de Introdução ao JavaScript
![1_ahpxPO0jLGb9EWrY2qQPhg](https://github.com/MarceloDSR/tutorialJavaScript/assets/133075234/85e51d04-aae6-423c-a1d8-d9a5835c068e)

## O que iremos aprender?

Iremos aprender  uma forma geral sobre o JavaScript

## O que é JavaScript?

JavaScript é uma linguagem de programação que permite a você implementar itens complexos em páginas web.

## Configuração do Ambiente

1. **Instalação do Node.js**: O Node.js é um ambiente de execução JavaScript que permite rodar scripts no lado do servidor. Você pode baixá-lo e instalá-lo do site oficial.

2. **Gerenciador de Pacotes**: Junto com o Node.js, você obtém o npm (Node Package Manager) automaticamente. Você também pode optar por instalar o Yarn, outro gerenciador de pacotes popular para JavaScript.

3. **Editor de Código**: Escolha um editor de código de sua preferência. O Visual Studio Code é uma escolha comum devido à sua robustez e suporte extensivo para JavaScript.

4. **Iniciar um Projeto**: Crie um diretório para o seu projeto e dentro dele, execute npm init ou yarn init para criar um arquivo package.json. Este arquivo vai conter metadados sobre o seu projeto e suas dependências.

5. **Instalação de Dependências**: Use o npm ou o Yarn para instalar dependências do seu projeto. Por exemplo, npm install nome-do-pacote ou yarn add nome-do-pacote.

6. **Configuração do Ambiente de Desenvolvimento**: Configure quaisquer ferramentas adicionais que você possa precisar, como Babel para transpilação de código, Webpack para empacotamento de módulos, ESLint para linting de código, e assim por diante. Você pode instalar essas ferramentas globalmente ou localmente no seu projeto, dependendo das suas necessidades.

7. **Desenvolvimento e Testes**: Agora você está pronto para começar a escrever código! Use seu editor de código para escrever e editar arquivos JavaScript, e execute seus scripts usando o Node.js ou o ambiente de execução apropriado no seu navegador. Certifique-se também de escrever testes para o seu código e executá-los regularmente para garantir que tudo funcione como esperado.

Seguindo esses passos, você deve ter um ambiente de desenvolvimento JavaScript configurado e pronto para começar a construir seus projetos.

## Sintaxe Básica

1. **Variáveis**: Declare variáveis usando var, let ou const, seguido pelo nome da variável e, opcionalmente, um valor inicial. Exemplo: 
   
```
   let nome = "Marcelo";
   const idade = 33;
```

2. **Comentários**: Use // para comentários de uma linha e /* */ para comentários de várias linhas. Exemplo:
  
```
   // Este é um comentário de uma linha
   /* Este é
   um comentário
   de várias linhas */
```

3. **Tipos de Dados**: JavaScript possui tipos de dados como `string`, `number`, `boolean`, `null`, `undefined`, `object` e `symbol`.

4. **Operadores**: Use operadores aritméticos (`+`, `-`, `*`, `/`, `%`), operadores de atribuição (`=`, `+=`, `-=`), operadores de comparação (`==`, `===`, `!=`, `!==`, `>`, `<`, `>=`, `<=`), operadores lógicos (`&&`, `||`, `!`), entre outros.

## Variáveis

1. **Usando var**: pouco utilizada atualmente
   
  ```
   var nome = "Maria";
   var idade = 25;
   ```

3. **Usando let** (recomendado para variáveis que podem mudar de valor):
   
   ```
   let contador = 0;
   let preco = 10.99;
   ```

5. **Usando const** (para variáveis que não mudam de valor):
   
   ```
   const PI = 3.14;
   const COR_PRINCIPAL = "azul";
   ```

7. **Variáveis de diferentes tipos**:
   
   ```
   let nome = "João";
   let idade = 30;
   let estaChovendo = true;
   let listaDeCompras = ["maçã", "banana", "laranja"];
   let pessoa = { nome: "Ana", idade: 25 };
   ```

9. **Variáveis indefinidas ou nulas**:
   
   ```
   let endereco; // valor é undefined
   let telefone = null; // valor é null
   ```

11. **Reatribuição de valores**:
   
   ```
   let numero = 10;
   numero = 20; // reatribuindo o valor
   ``` 


## Tipos de Dados

1. **String**: Sequência de caracteres, representada por aspas simples ou duplas.
   ```
   let nome = "Ana";
   ```

2. **Number**: Números inteiros ou decimais.
   ```
   let idade = 25;
   let preco = 10.99;
   ```

3. **Boolean**: Valor lógico que pode ser verdadeiro ou falso.
   ```
   let estaChovendo = true;
   ```

4. **Null**: Representa a ausência intencional de qualquer valor ou objeto.
   ```
   let endereco = null;
   ```

5. *Undefined*: Indica que uma variável foi declarada, mas ainda não foi atribuída a um valor.
   ```
   let telefone;
   ```

6. *Object*: Conjunto de propriedades-chave associadas a valores.
   ```
   let pessoa = { nome: "João", idade: 30 };
   ```

7. *Array*: Coleção ordenada de valores, que podem ser de diferentes tipos.
   ```
   let listaDeCompras = ["maçã", "banana", "laranja"];
   ```

8. **Symbol**: Tipo de dado primitivo que é único e imutável.
   ```
   let chavePrivada = Symbol();
   ```
   Esses são os principais tipos de dados em JavaScript. Cada tipo tem suas    próprias características e usos específicos.
## Funções

Em JavaScript, as funções são blocos de código que podem ser executados quando são chamados. Elas podem aceitar argumentos e retornar valores. Aqui está um exemplo simples de como declarar e usar funções em JavaScript:

```
// Declaração de uma função simples
function saudacao(nome) {
    return "Olá, " + nome + "!";
}

// Chamando a função e armazenando o resultado em uma variável
let mensagem = saudacao("Marcelo");
console.log(mensagem); // Saída: Olá, Marcelo!
```
```
// Função que não retorna valor (undefined)
function mostrarMensagem() {
    console.log("Esta é uma mensagem de exemplo.");
}

mostrarMensagem(); // Saída: Esta é uma mensagem de exemplo.
```
```
// Função com múltiplos parâmetros e retorno
function soma(a, b) {
    return a + b;
}

let resultado = soma(5, 3);
console.log(resultado); // Saída: 8

```
Além disso, você também pode declarar funções como expressões de função:

```
// Expressão de função
let quadrado = function(x) {
    return x * x;
};

console.log(quadrado(3)); // Saída: 9

```
As funções em JavaScript são flexíveis e poderosas, e podem ser usadas de várias maneiras para modularizar e organizar o seu código.

## Estruturas de Controle

Em JavaScript, as estruturas de controle permitem controlar o fluxo de execução do seu código. Aqui estão algumas das estruturas de controle mais comuns:

1. **if...else**: Permite executar um bloco de código se uma condição for verdadeira e outro bloco de código se a condição for falsa.
   ```
   let idade = 18;
   if (idade >= 18) {
       console.log("Maior de idade");
   } else {
       console.log("Menor de idade");
   }
   ```

2. **switch**: Permite selecionar um dos muitos blocos de código para serem executados.
   ```
   let diaDaSemana = 3;
   switch (diaDaSemana) {
       case 1:
           console.log("Segunda-feira");
           break;
       case 2:
           console.log("Terça-feira");
           break;
       // outros casos...
       default:
           console.log("Dia não reconhecido");
   }
   ```

3. **for**: Executa um bloco de código várias vezes, com base em uma condição.
   ```
   for (let i = 0; i < 5; i++) {
       console.log(i);
   }
   ```

4. **while**: Executa um bloco de código enquanto uma condição específica for verdadeira.
   ```
   let contador = 0;
   while (contador < 5) {
       console.log(contador);
       contador++;
   }
   ```

5. **do...while**: Similar ao while, mas garante que o bloco de código seja executado pelo menos uma vez antes de verificar a condição.
   ```
   let x = 0;
   do {
       console.log(x);
       x++;
   } while (x < 5);
   ```

6. **for...in**: Itera sobre as propriedades de um objeto.
   ```
   let carro = { marca: "Toyota", modelo: "Corolla", ano: 2020 };
   for (let chave in carro) {
       console.log(chave + ": " + carro[chave]);
   }
   ```

Essas são algumas das estruturas de controle mais comuns em JavaScript, que permitem controlar o fluxo de execução do seu código de forma eficiente e flexível.
## Eventos e Manipulação do DOM

Em JavaScript, eventos são ações que ocorrem no navegador, como clique do mouse, pressionamento de tecla, carregamento da página, etc. A manipulação do DOM (Document Object Model) refere-se à interação com os elementos HTML de uma página web. Aqui está uma visão geral de como lidar com eventos e manipular o DOM em JavaScript:

1. **Adicionar Event Listeners**: Use o método `addEventListener` para vincular uma função a um evento específico em um elemento HTML.
   ```
   document.getElementById("meuBotao").addEventListener("click", function() {
       alert("Botão clicado!");
   });
   ```

2. **Manipulação do DOM**: Use métodos como `getElementById`, `getElementsByClassName`, `getElementsByTagName` ou `querySelector` para selecionar elementos HTML e manipulá-los.
   ```
   // Alterar o conteúdo de um elemento
   document.getElementById("meuDado").innerHTML = "Novo texto";

   // Alterar o estilo de um elemento
   document.getElementById("minhaDiv").style.backgroundColor = "red";
   ```

3. **Eventos de Carregamento da Página**: Você pode executar código quando a página é carregada usando o evento `DOMContentLoaded`.
   ```
   document.addEventListener("DOMContentLoaded", function() {
       // Código a ser executado após o carregamento da página
   });
   ```

4. **Acesso aos Elementos do Formulário**: Use `value` para acessar ou alterar o valor de um elemento de formulário.
   ```
   let nome = document.getElementById("nome").value;
   ```

5. **Prevenir Comportamento Padrão**: Você pode usar `preventDefault()` para evitar o comportamento padrão de um evento, como enviar um formulário ou seguir um link.
   ```
   document.getElementById("meuLink").addEventListener("click", function(event) {
       event.preventDefault();
       // Outro código aqui
   });
   ```

Esses são apenas alguns exemplos de como você pode lidar com eventos e manipular o DOM em JavaScript. Com essas técnicas, você pode criar interações dinâmicas e responsivas em suas páginas web.
