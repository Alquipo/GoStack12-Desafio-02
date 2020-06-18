<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<p align="center">
    
<img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Alquipo/GoStack12-desafio-02">

<img alt="Repository size" src="https://img.shields.io/github/repo-size/Alquipo/GoStack12-desafio-02">

<a href="https://www.linkedin.com/in/alquiponeto/">
    <img alt="Made by Alquipo" src="https://img.shields.io/badge/made%20by-AlquipoNeto-blue">
</a>

<a href="https://github.com/Alquipo/GoStack12-desafio-02/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Alquipo/GoStack12-desafio-02?color=blue">
</a>

<img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen?color=blue">
</p>

<p align="center">
<a href="https://nodejs.org/en/" rel="nofollow">
    <img src="https://camo.githubusercontent.com/aed2c3876a97dab0bdadd00ece0a12f9291d1dab/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d4e6f6465266d6573736167653d4a5326636f6c6f723d626c75653f7374796c653d706c6173746963266c6f676f3d4e6f64652e6a73" alt="NodeJS" data-canonical-src="https://img.shields.io/static/v1?label=Node&amp;message=JS&amp;color=blue?style=plastic&amp;logo=Node.js" style="max-width:100%;">
  </a>
</p>
<h2 align="center">
  Desafio 02: Conceitos do Node.js
</h2>

## 🚀 Sobre o desafio

Segundo desafio foi desenvolver uma `API` fake onde os dados ficam salvos em um array, enquanto o servidor está sendo executado, foi criado algo muito interessante que serve como base para uma api utilizando banco de dados....

## 🔨 Tecnologias:

- [NodeJs][nodejs]
- [Express][express]
- [uuidv4][uuidv4]
- [Nodemon][nodemon]

## 🚀 Como rodar este projeto

Para clonar e executar este aplicativo, você precisará de [Git](https://git-scm.com), [NodeJs][nodejs] Instalado em seu computador.

### 🌀 Clonando o repositório

```bash
# Clone este repositório
$ git clone https://github.com/Alquipo/GoStack12-desafio-02

# Acesse a pasta do projeto no terminal/cmd
$ cd GoStack12-desafio-02
```

### 🎲 Rodando a API

```bash
# Instale as dependências
$ yarn

# Execute a Aplicação
$ yarn dev

# Execute o teste da Aplicação
$ yarn test

# O servidor inciará na porta:3333 - acesse http://localhost:3333
```

## 🔑 Rotas da aplicação

- **`POST /repositories`**: Essa rota serve para criação de um repositorio, e recebe os seguintes parametros, {title:.. , url:... , techs:[{ 'node', 'deno'}]}

- **`GET /repositories`**: Rota que lista todos os repositórios;

* **`PUT /repositories/:id`**: Essa rota serve para alterar apenas o `title`, a `url` e as `techs` do repositório que possua o `id` igual ao `id` presente nos parâmetros da rota;

* **`DELETE /repositories/:id`**: A rota deve deletar o repositório com o `id` presente nos parâmetros da rota;

* **`POST /repositories/:id/like`**: Essa rota serve para o usuario dar like nos repositorios, se o `id` for igual passado nos parâmetros

## 🤔 Como contribuir para o projeto

- Faça um **fork** do projeto;
- Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
- Salve as alterações e crie uma mensagem de commit contando o que você fez:`git commit -m "feature: My new feature"`
- Envie as suas alterações: `git push origin my-feature`

> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](https://github.com/firstcontributions/first-contributions)

## 📝 Licença

Este projeto esta sobe a licença MIT. Veja a [LICENÇA][license] para saber mais.

Feito com ❤️ por Alquipo Neto 👋🏽 [Entre em contato!](https://www.linkedin.com/in/alquiponeto/)

[nodejs]: https://nodejs.org/
[express]: https://expressjs.com/
[uuidv4]: https://www.npmjs.com/package/uuidv4
[nodemon]: https://www.npmjs.com/package/nodemon
[rs]: https://rocketseat.com.br
[license]: https://opensource.org/licenses/MIT
