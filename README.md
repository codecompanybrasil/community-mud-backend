# community-mud-backend
Backend para MultiUser Dungeon, rpg baseado em texto.

<!-- 
[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://coveralls.io/github/nestjs/nest?branch=master" target="_blank"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#9" alt="Coverage" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>
</p> -->
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

<!-- ## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository. -->

## Pré-requisitos
_Necessário para build e geração de arquivos_ 
```bash
npm i -g @nestjs/cli
```

_Necessário para rodar os seeders_
```bash
npm install -g ts-node
```

## Instalação

```bash
$ npm install
```

## Rodando a aplicação

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Inserindo seeds no Banco de Dados

```bash
$ npm run seed
```

## Variáveis de Ambiente

Variável | Tipo | Default
:------- | :--: | :------
PORT | number | 3000
API_URL | string | "http://localhost:3000"
ADMIN_URL | string | undefined
GAME_URL | string | undefined
DATABASE_HOST | string | "localhost"
DATABASE_PORT | number | 3306
DATABASE_USERNAME | string | "root"
DATABASE_PASSWORD | string | "" (**sem senha**)
DATABASE_SYNC | boolean | false

> **Warning** - Observações sobre **DATABASE_SYNC**<br/> 
>_Embora a sincronização seja uma boa opção para sincronizar sua entidade com o banco de dados, ela não é segura para bancos de dados de produção. Caso utilize esse projeto em produção opte por implementar migrations ou atualizar pontualmente o banco de dados via comandos._

<!-- 
## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
-->

## Documentações
<a href="https://drive.google.com/drive/folders/19GYy39HNOUnAPsD6v0ji23vtTp7FQ0oi?usp=sharing" target="_blank">Google Drive</a>

## Mantenedores
- [Pablo Pereira](https://github.com/pablopereira27)

## Tecnologias Utilizadas
<a href="http://nestjs.com/" target="_blank">
    <img src="https://img.shields.io/static/v1?label=NestJS&message=9.0.0&logo=nestjs&logoColor=red&color=red&style=flat-square" alt="NestJS Version"/>
</a>

## Licença
[![Licença GPLv3](https://img.shields.io/github/license/FastDevelopmentBR/community-mud-backend?label=Licen%C3%A7a&style=flat-square)](LICENSE)

O link abaixo contém uma tradução da licença que pode estar desatualizada em relação a versão utilizada no projeto.<br/>
[![Licença GPLv3 (pt-BR)](https://img.shields.io/github/license/FastDevelopmentBR/community-mud-backend?label=Licen%C3%A7a%20(pt-BR)&style=flat-square)](https://www.gnu.org/licenses/quick-guide-gplv3.pt-br.html)
