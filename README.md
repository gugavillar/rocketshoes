# RocketShoes

![Imagem inicial da aplicação](/assets/inicio.png)

![Imagem do carrinho da aplicação](/assets/carrinho.png)

## Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

-  React
-  TypeScript
-  Json Server
-  React Toastify
-  Axios

## Como executar

Clone o projeto e acesse a pasta do mesmo.

```
$ git clone https://github.com/gugavillar/rocketshoes
$ cd rocketshoes
```

Para iniciá-lo, siga os passos abaixo:

```
# Instalar as dependências
$ yarn

# Iniciar o servidor com a fakeAPI
$ yarn server

# Iniciar o projeto
$ yarn dev
```

O app estará disponível no seu browser pelo endereço http://localhost:3000.

## 💻 Projeto

O Rocketshoes é um projeto de uma loja.

Funcionalidades do projeto:

-  Adicionar itens no carrinho, mas verificando se o item que deseja adicionar tem no estoque;
-  Verificar se o item já está adicionado e se estiver apenas aumentar a quantidade;
-  Excluir um item do carrinho;
-  Aumentar ou diminuir a quantidade de um item no carrinho verificando sua existência no estoque;
-  Salvar os itens adicionados no localstorage usando a localstorageAPI.

Esse projeto tem como objetivo consolidar conhecimentos sobre:

-  Criação e uso de hooks no React;
-  Uso da ContextAPI do React;
-  Uso de estados do React;
-  Uso da função reduce e map do javascript;
-  A exibição de erros com o uso da react-toastify;
-  Uso da localstorageAPI.

Esse foi um projeto realizado dentro do Ignite da Rocketseat.
