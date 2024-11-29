# Testes Automatizados com Cypress

Este repositório contém uma série de testes automatizados utilizando o Cypress para validar funcionalidades em sites de e-commerce, login e navegação.

![Status do Projeto](https://img.shields.io/badge/Status%20do%20Projeto-Concluído-brightgreen)

[![Kéure Passos Soares](https://img.shields.io/badge/GitHub-Black?style=flat-square&logo=github&logoColor=white)](https://github.com/keurepassos)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/keurepassos)
## Sumário

- [Objetivo](#objetivo)
- [Testes](#testes)
  - [Teste de Navegação e Pesquisa por "Dress"](##teste-de-navegação-e-pesquisa-por-dress)
  - [Teste de Checkout com Login](##teste-de-checkout-com-login)
  - [Teste de Checkout sem Login](##teste-de-checkout-sem-login)
  - [Teste de Login no Site The Internet](##teste-de-login-no-site-the-internet)
  - [Teste de Pesquisa na Amazon](##teste-de-pesquisa-na-amazon)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)

## Objetivo

O objetivo deste repositório é fornecer uma série de testes automatizados utilizando o Cypress para validar funcionalidades de e-commerce, checkout e login em sites populares como "AutomationExercise", "The Internet" e "Amazon". Os testes cobrem uma variedade de cenários, desde navegação até o processo de compra.

## Testes

### Teste de Navegação e Pesquisa por "Dress"
- **Objetivo**: Validar a navegação para a página de produtos e a pesquisa por "Dress".
- **Passos**:
  1. Visita a página inicial.
  2. Clica no link "Products".
  3. Pesquisa por "Dress".
  4. Verifica se a URL e os resultados contêm "Dress".
     
### Teste de Checkout com Login
- **Objetivo**: Validar o processo de compra com login.
- **Passos**:
    1. Realiza login com usuário existente.
    2. Adiciona um produto ao carrinho.
    3. Finaliza o pedido no checkout.

### Teste de Checkout sem Login
- **Objetivo**: Validar o processo de compra sem login.
- **Passos**:
   1. Tenta finalizar a compra sem login.
   2. Verifica se o pop-up de login é exibido.
 
### Teste de Login no Site The Internet
- **Objetivo**: Validar o login no site "The Internet".
- **Passos**:
   1. Realiza login com credenciais válidas.
   2. Verifica a mensagem de sucesso.
   3. Testa login com credenciais inválidas e valida a mensagem de erro.

### Teste de Pesquisa na Amazon
- **Objetivo**: Validar a pesquisa de um produto na Amazon.
- **Passos**:
   1. Pesquisa por "smartphone".
   2. Verifica se o produto aparece nos resultados.
  
## Tecnologias Utilizadas
- **Objetivo**: Cypress para testes end-to-end.


