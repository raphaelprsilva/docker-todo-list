<div align="center">
  <h1>Docker todo list project 🐳</h1>
</div>

## :memo: Descrição do Projeto

Este é um projeto de um Aplicativo de tarefas (`to do list`), full-stack (com `back-end` e `front-end`) dockerizado.

## 📋 Tabela de conteúdos

<!--ts-->

- [🎯 Objetivo do projeto](#🎯-objetivo-do-projeto)
- [📝 O que pratiquei](#📝-o-que-pratiquei)
- [🛠 Tecnologias utilizadas](#🛠-tecnologias-utilizadas)
- [👉🏾 Arquivos Desenvolvidos](#👉🏾-arquivos-desenvolvidos)
- [🚀 Rodando o projeto na sua máquina](#🚀-rodando-o-projeto-na-sua-máquina)
  - [📍Pre Requisitos](#📍-pre-requisitos)
- [🤝 Colaboradores](#🤝-colaboradores)

<!--te-->

## 🎯 Objetivo do projeto

Este é um projeto de cunho educativo, desenvolvido durante o módulo de back-end do curso de desenvolvimento web full-stack da Trybe.

Foi fornecida uma aplicação full-stack (um aplicativo de tarefas) dividida em front-end, back-end e um aplicativo de teste que valida se as aplicações estão se comunicando.

> :warning: A aplicação possuí um [README](/docker/README.md) próprio, fornecido pela Trybe, que foi usado como referência na criação dos scripts.

## 📝 O que pratiquei

Neste projeto, foi possível testar as habilidades:

1. **_Conteinerização_** de aplicações;
1. Criar uma conexão entre elas;
1. Orquestração (`docker-compose`) do seu funcionamento.

## 🛠 Tecnologias utilizadas

As seguintes ferramentas foram usadas na construção do projeto:

- [Docker](https://www.docker.com/)
- [Dockerfile](https://docs.docker.com/engine/reference/builder/)
- [Docker Compose](https://docs.docker.com/engine/reference/commandline/compose/)

## 👉🏾 Arquivos Desenvolvidos

- Caminho `/docker/docker-commands/`
  - Arquivos `command01.dc` a `command12.dc`
  - docker-compose.yml
- Caminho `/docker/todo-app/back-end/`
  - Arquivo `Dockerfile`
- Caminho `/docker/todo-app/front-end/`
  - Arquivo `Dockerfile`
- Caminho `/docker/todo-app/tests/`
  - Arquivo `Dockerfile`

## 🚀 Rodando o projeto na sua máquina

Para rodar o projeto na sua máquina é necessário alguns pre requisitos:

### 📍Pre Requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).

Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)!

Comandos para clonar o projeto na sua máquina:

```bash
# Clone este repositório com o comando:
git clone git@github.com:raphaelprsilva/docker-todo-list.git

# Acesse a pasta do projeto no terminal/cmd com o comando:
cd docker-todo-list

# Instale as dependências com o comando:
npm install

# Você verá o projeto rodando na porta localhost:3000
```

## 🤝 Colaboradores

<table>
  <tr>
    <td align="center">
      <a href="http://github.com/raphaelprsilva">
        <img src="https://avatars.githubusercontent.com/u/50886915?s=400&u=fa3df0caab0c83b9f88678abd93e8d5a81a5cd6f&v=4" width="100px;" alt="Foto de Raphael Silva no GitHub"/><br>
        <sub>
          <b>raphaelprsilva</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
