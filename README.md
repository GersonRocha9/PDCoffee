# Coffee Delivery

## Sobre

O desafio do Coffee Delivery consiste em criar uma aplicação de delivery de cafés que carrega todos os produtos disponíveis através de uma API com JSON Server. A aplicação deve permitir que o usuário adicione produtos ao carrinho, remova produtos do carrinho, altere a quantidade de produtos no carrinho e preencha o formulário de entrega, com auto completar do endereço através do input de CEP utilizando a API pública do Via Cep. O usuário deve ser capaz de concluir o pedido, que será salvo na API com JSON Server. A aplicação deve apresentar todos os produtos em um formato amigável, com informações como nome do produto, descrição, imagem e preço. O carrinho deve ser exibido em todas as páginas e atualizado em tempo real à medida que o usuário adiciona ou remove produtos.

![Logo do Projeto](https://raw.githubusercontent.com/MatheusAndrade23/Coffee_Delivery/main/src/assets/homeImage.png)

## Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/)

## Rodando a Aplicação

```bash
# Clone este repositório
$ git clone https://github.com/GersonRocha9/PDCoffee.git

# Acesse a pasta do projeto no terminal/cmd
$ cd PDCoffee

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn dev

# Execute o banco de dados JSON Server
$ yarn server

# O servidor inciará na porta:5173 - acesse <http://localhost:5173/>
# O banco de dados inciará na porta:3000 - acesse <http://localhost:3000/coffees>
```
