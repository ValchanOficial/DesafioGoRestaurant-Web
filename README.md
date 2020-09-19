# Rocketseat - Desafio: GoRestaurant Web

## Sobre o desafio

Desenvolvimento da aplicação GoRestaurant. Focando na prática do React.js juntamente do TypeScript, praticando o conceito de CRUD (Create, Read, Update, Delete).

Essa será uma aplicação que irá se conectar a uma fake API, e exibir os pratos de comida criados e permitir a criação, remoção e atualização desses pratos.

## Funcionalidades da aplicação

- Listar os pratos de comida: A página Dashboard deve ser capaz de exibir uma listagem, com o campo title, value, e description e available de todos os pratos de comida que estão cadastrados na API.

- Adicionar novos pratos de comida na API: Na página Dashboard, deve ser possível abrir um modal ao clicar no botão Novo Prato no Header. Esse modal deve ser responsável por cadastrar uma nova food passando os campos image, name, description, value.

- Editar pratos de comida da API: Na página Dashboard, deve ser possível abrir um modal ao clicar no botão Editar Prato. Esse modal deve ser responsável por editar uma food passando os campos image, name, description, value.

- Remover pratos de comida da API: Na página Dashboard, deve ser possível remover um prato de comida ao clicar no botão com ícone de lixeira no componente Food.

- Alterar disponibilidade dos pratos de comida da API: Na página Dashboard, deve ser possível alterar a disponibilidade de um prato de comida ao clicar no switch que é controlado pelo valor de available.


## Start
```js
    yarn                                  // instala dependências
    yarn json-server server.json -p 3333  // executa fake API
    yarn start                            // inicia aplicação
    yarn test                             // executa os testes
```
