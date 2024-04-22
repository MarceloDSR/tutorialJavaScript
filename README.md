# Tutorial de Introdução ao JavaScript

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

## funções

## Estruturas de Controle

## Eventos e Manipulação do DOM
