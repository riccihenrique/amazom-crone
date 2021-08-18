# Amazom Crone

Este projeto tem como objetivo o desenvolvimento de uma aplicação que simule um e-commerce.

Você deverá desenvolver endpoints para `buscar categorias`, `produtos por categorias`, `todos os produtos`, `login` e `comprar produtos` (pode ser 1 ou vários produtos na mesma compra).
As informações de `categorias`, `produtos` e `usuários` devem ser inseridas no banco de dados por meio de seeder, não sendo necessário a criação de endpoints para inserir essas informações (podem ter quantas informações foram necessárias).

O endpoint de `comprar produtos` deverá enviar um e-mail assim que a compra for efetivada, informando a pessoa usuária de que a compra está em processamento. Essas informações de compra deverão ser salvas em um `banco de dados não relacional`.

Uma tarefa automática será responsavél por ler as informações do `banco de dados não relacional` de 3 em 3 minutos, salvar corretamente as informações em um `banco de dados relacional` e enviar um e-mail para a pessoa usuária avisando que a compra foi processada e em breve ela receberá os produtos.

Não é necessário tratar estoque ou pagamento, mas é importante salvar o `total dos produtos vendidos`.

Utilize o modelo de banco de dados abaixo e a biblioteca [nodemailer](https://nodemailer.com/about/) para o envio de e-mail.

![alt](https://i.ibb.co/S7p9nC7/Capturar.png)

DICA: Utilizem o projeto `Front-end Online Store`para vizualizar a aplicação por completo. Não é algo obrigatório.

A criação dos testes não é algo obrigatório, porém será um diferencial.

Bos sorte e VQV!!!
