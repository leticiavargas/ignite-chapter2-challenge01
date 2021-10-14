# 💻 Sobre o desafio

Nesse desafio, foi utilizado o template disponível pela Rocketseat.
![Layout do projeto Rocketshoes](https://user-images.githubusercontent.com/61559973/137410149-d121da27-aa7a-43bc-8d9f-5a09b9a392c6.png)


Essa é uma aplicação onde o principal objetivo é criar um hook de carrinho de compras.
Você terá acesso a duas páginas, um componente e um hook para implementar as funcionalidades pedidas nesse desafio:

- Adicionar um novo produto ao carrinho;
- Remover um produto do carrinho;
- Alterar a quantidade de um produto no carrinho;
- Cálculo dos preços sub-total e total do carrinho;
- Validação de estoque;
- Exibição de mensagens de erro;
- Entre outros.

## LocalStorage API
A persistência dos dados é realizada utilizando a localStorage API. Todos os dados são salvos utilizando o registro @RocketShoes:cart

## Fake API com JSON Server
Este desafio utliza o JSON Server para simular a API que possui as informações dos produtos e do estoque. Para executar utilize os comandos abaixo:

```
yarn
yarn server
```

## Erros: Toastify
Para mostrar os erros em tela, utilizamos o um pacote chamado **react-toastify**. Ela ajuda a mostra informações temporárias e rápidas de uma forma bem bonita.

De todos os métodos, foi utilizado apenas o `error` e com as mensagens predefinidas para que os testes do desafio passem.
