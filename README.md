# Move.it

<img src="https://github.com/thuram/moveit-nlw-04/blob/main/public/favicon.png?raw=true" align="right"
     alt="Move.it logo by Rockeatseat" width="120" height="178">

Projeto desenvolvido durante a NLW 04 oferecido pela @rockeatseat.

A aplicação se resume em uma plataforma que utiliza o método pomoro + resolução de desafios. A cada 25 minutos de foco total o usuário recebe um novo desafio focado em exercícios para o corpo e os olhos.

O projeto é baseado em um sistema de gamificação, a cada desafio concluído o usuário ganha uma quantidade de XP (experiência) que será usada para subir de nível!

<p align="center">
  <img src="https://github.com/thuram/moveit-nlw-04/blob/main/public/print.png?raw=true" alt="Size Limit CLI" width="738">
</p>

## Tecnologias utilizadas

* [NextJS](https://nextjs.org)
* [Typescript](https://www.typescriptlang.org)


## Como funciona

1. O usuário inicia um ciclo de 25 minutos focado em uma tarefa.
2. Quando o ciclo se encerra é gerado um desafio, um exércicio focado no corpo ou nos olhos.
3. Caso o usuário complete o desafio, ele receberá uma quantidade de XP que será somada ao seu nível atual. 
4. Caso o usuário não complete o desafio, ele não receberá XP.
5. Após o feedback do usuário sobre o desafio o ciclo se repete.


## Iniciando a aplicação

### JS Applications

1. Clone o projeto.
2. Entre na pasta do projeto e execute o seguinte comando: 
```sh
  $ yarn
```
3. Após a instalação de todas as dependências, basta execute o seguinte comando:
```sh
  $ yarn dev
```
3. A aplicação ficará disponível na url http://localhost:3000.
