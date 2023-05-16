# Página de Carrinho de Compras

![GIF](gif-readme.gif)

Este repositório é uma atividade da Pós Graduação na Descomplica no qual se trata de uma página de carrinho de compras, desenvolvida utilizando Bootstrap e manipulação do DOM com JavaScript. O objetivo deste projeto é demonstrar a manipulação dinâmica do DOM em um template pré-existente do Bootstrap.

## Funcionalidades

- **Constructor:** Foi definido um construtor chamado `productsCart` que permite criar objetos de produto utilizando os parâmetros informados, os quais podem ser utilizados posteriormente.
- **Inclusão de Produtos:** O método `incluir` é responsável por incluir os produtos na página de carrinho de compras. Ele atualiza os elementos do DOM correspondentes com as informações do produto, como código, nome, cor, tamanho e valor.
- **Adição de Itens:** O método `addItem` permite aumentar a quantidade de itens selecionados para um determinado produto. Ele atualiza a quantidade exibida no DOM e calcula o valor total para o produto específico.
- **Remoção de Itens:** O método `removeItem` possibilita remover itens selecionados para um determinado produto. Ele atualiza a quantidade exibida no DOM e recalcula o valor total para o produto específico.
- **Atualização do Total:** A função `updateTotal` é utilizada para atualizar o valor total do carrinho. Ela soma os valores totais dos produtos armazenados no array `totalCar` e atualiza o elemento correspondente no DOM.

## Observações
Vale ressaltar que o código original não fazia manipulação de Objetos e que foi incrementado como forma de pratica sobre o conteudo também abordado nas aulas.