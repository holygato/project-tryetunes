# Bem-vindo ao projeto Trybetunes

Este projeto é uma aplicação desenvolvida em React.js que acessa uma API do iTunes e cria um ambiente em que o usuário pode pesquisar músicas, ouvir uma prévia e favoritar suas músicas preferidas.

## Sumário
- [Bem-vindo ao projeto Trybetunes](#bem-vindo-ao-projeto-trybetunes)
- [Preview](#preview)
- [Sumário](#sumário)
- [Contexto](#contexto)
- [Tecnologias e Ferramentas Utilizadas](#tecnologias-e-ferramentas-utilizadas)
- [Instalação e Execução](#instalação-e-execução)
- [Notas](#notas)
 - [Git, GitHub e Histórico de Commits](#git-github-e-histórico-de-commits)
 - [Lint](#lint)

## Preview

https://user-images.githubusercontent.com/98184355/220769604-2292f905-9bf2-48bf-a664-02d51c2c51cc.mp4

## Contexto
O __aplicativo Trybetunes__ permite que o usuário:
 - Pesquise músicas pelo nome do artista e receba informações sobre os álbuns disponíveis.
 - Ouça uma prévia da música.
 - Adicione e remova músicas favoritas.
 - Acesse o perfil do usuário e altere suas informações.

*A pasta de serviços foi fornecida pela Trybe para que a solicitação à API pudesse ser executada*.

## Tecnologias e Ferramentas Utilizadas
Este projeto utilizou as seguintes tecnologias e ferramentas:
  - [React.js com classes](https://reactjs.org/docs/getting-started.html) | Biblioteca para criar interfaces de usuário.
  - [Styled Components](https://styled-components.com/) | Biblioteca para estilização do CSS.
  - [API do iTunes](https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/iTuneSearchAPI/index.html#//apple_ref/doc/uid/TP40017632-CH3-SW1) | API utilizada para obter informações sobre os artistas e suas músicas.

  O React.js foi escolhido porque é uma das bibliotecas mais populares e amplamente utilizadas para criar interfaces de usuário. Além disso, ele oferece suporte a programação orientada a objetos, o que é importante para o desenvolvimento de projetos maiores. Já o Styled Components foi escolhido porque permite que os desenvolvedores escrevam o CSS em formato de componente, o que torna o código mais legível e fácil de entender. A API do iTunes foi utilizada para obter informações sobre os artistas e suas músicas, e fornece informações precisas e detalhadas.

## Instalação e Execução
### Download do projeto
```
git clone git@github.com:imsamuelcovalero/Project-Trybetunes.git
```
### Install dependencies
```
cd Project-Trybetunes
npm install
```
### Run the application
```
cd Project-Trybetunes
npm start
```

## Notas
### Git, GitHub e Histórico de Commits
Este projeto utilizou a especificação de commits convencionais, com alguns tipos da convenção Angular. Além disso, foi utilizado o pacote conventional-commit-cli para ajudar a seguir a convenção de commits. É importante utilizar a convenção de commits em projetos para manter o histórico de commits organizado e facilitar a leitura e o entendimento do que foi desenvolvido.

### Lint
- O projeto foi desenvolvido seguindo os padrões de Clean Code especificados pelo [Lint da Trybe](https://github.com/betrybe/eslint-config-trybe).
