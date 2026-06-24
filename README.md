# API Soma com Flask

Projeto acadêmico desenvolvido no **Módulo 2 – Aplicação para ambiente WEB**, com o objetivo de praticar conceitos básicos de **API REST**, **Flask**, **requisições HTTP**, **integração cliente-servidor** e **autenticação com Bearer Token**.

A aplicação consiste em uma pequena API feita em Flask que disponibiliza rotas para realizar soma de números via requisições `GET` e `POST`, além de uma rota protegida por token.

---

## Objetivos do projeto

- Criar um servidor web com Flask.
- Implementar uma rota `GET` que recebe parâmetros pela URL.
- Criar clientes Python usando a biblioteca `requests`.
- Enviar dados no corpo da requisição usando `POST`.
- Trabalhar com cabeçalhos HTTP.
- Implementar uma rota protegida com `Bearer Token`.
- Praticar versionamento com Git e GitHub.

---

## Tecnologias utilizadas

- Python 3.8+
- Flask
- Requests
- Git
- GitHub

---

## Estrutura do projeto

```text
api-soma/
│
├── servidor.py
├── cliente.py
├── cliente_post.py
├── cliente_token.py
├── .gitignore
└── README.md