<p align="center">
  <h1 align="center">API do Fórum - DDD no Node.js</h1>
  <p align="center">Projeto desenvolvido durante a formação <strong>Node.js</strong>.</p>
</p>

<p align="center">
  <img src="https://img.shields.io/github/repo-size/felipe-dr/forum-api-nest?style=for-the-badge&color=4e5acf" alt="Repo size" />
  <a aria-label="Last Commit" href="https://github.com/felipe-dr/forum-api-nest/commits/main">
    <img src="https://img.shields.io/github/last-commit/felipe-dr/forum-api-nest?style=for-the-badge&color=4e5acf" alt="Last commit on GitHub" />
  </a>
  <!-- <img src="https://img.shields.io/badge/license-MIT-4e5acf?style=for-the-badge" alt="License" /> -->
  <img src="https://img.shields.io/badge/status-concluído-green?style=for-the-badge" alt="Status" />
</p>

<br>

<p align="center">
  <a target="_blank" href="https://nestjs.com/">
    <img src="https://img.shields.io/static/v1?style=plastic&color=red&label=Nest.js&message=TS&logo=nestjs" alt="Nest.js" />
  </a>
  <a target="_blank" href="https://www.typescriptlang.org/">
    <img src="https://img.shields.io/static/v1?style=plastic&color=red&label=Typescript&message=TS&logo=typescript" alt="Typescript" />
  </a>
  <a target="_blank" href="https://v10.fakerjs.dev/">
    <img src="https://img.shields.io/static/v1?style=plastic&color=red&label=Faker&message=TS" alt="Faker" />
  </a>
  <a target="_blank" href="https://day.js.org/">
    <img src="https://img.shields.io/static/v1?style=plastic&color=red&label=Day.js&message=TS" alt="Day.js" />
  </a>
  <a target="_blank" href="https://zod.dev/">
    <img src="https://img.shields.io/static/v1?style=plastic&color=red&label=Zod&message=TS&logo=zod" alt="Zod" />
  </a>
  <a target="_blank" href="https://www.npmjs.com/package/dotenv">
    <img src="https://img.shields.io/static/v1?style=plastic&color=red&label=Dotenv&message=TS&logo=dotenv" alt="Dotenv" />
  </a>
  <a target="_blank" href="https://www.jwt.io/">
    <img src="https://img.shields.io/static/v1?style=plastic&color=red&label=JWT&message=TS" alt="Passport/JWT" />
  </a>
  <a target="_blank" href="https://www.npmjs.com/package/bcryptjs">
    <img src="https://img.shields.io/static/v1?style=plastic&color=red&label=Bcrypt&message=TS" alt="Bcrypt.js" />
  </a>
  <a target="_blank" href="https://www.npmjs.com/package/@aws-sdk/client-s3">
    <img src="https://img.shields.io/static/v1?style=plastic&color=red&label=AWS-SDK-S3&message=TS" alt="AWS SDK S3" />
  </a>
  <a target="_blank" href="https://eslint.org/">
    <img src="https://img.shields.io/static/v1?style=plastic&color=red&label=ESLint&message=JS&logo=eslint" alt="ESLint" />
  </a>
  <a target="_blank" href="https://vite.dev/">
    <img src="https://img.shields.io/static/v1?style=plastic&color=red&label=Vite&message=TS&logo=vite" alt="Vite" />
  </a>
  <a target="_blank" href="https://vitest.dev/">
    <img src="https://img.shields.io/static/v1?style=plastic&color=red&label=Vitest&message=TS&logo=vitest" alt="Vitest" />
  </a>
  <a target="_blank" href="https://www.npmjs.com/package/supertest">
    <img src="https://img.shields.io/static/v1?style=plastic&color=red&label=Supertest&message=TS&logo=supertest" alt="Supertest" />
  </a>
</p>

<p align="center">
  <a target="_blank" href="https://www.prisma.io/">
    <img src="https://img.shields.io/static/v1?style=plastic&color=yellow&label=Prisma&message=ORM&logo=prisma" alt="Prisma" />
  </a>
  <a target="_blank" href="https://redis.io/">
    <img src="https://img.shields.io/static/v1?style=plastic&color=yellow&label=Redis&message=CACHE&logo=redis" alt="Redis" />
  </a>  
</p>

## Índice

<ol>
  <li><a href="#sobre">Sobre</a></li>
  <li><a href="#requisitos-e-funcionalidades">Requisitos e funcionalidades</a></li>
  <li><a href="#arquitetura">Arquitetura</a></li>
  <li><a href="#rotas-da-api">Rotas da API</a></li>  
  <li><a href="#como-executar">Como executar</a></li>
  <li><a href="#tecnologias">Tecnologias</a></li>
  <li><a href="#autor">Autor</a></li>
</ol>

## Sobre

API desenvolvida em Node.js com o Nest.js e Typescript, afim de gerenciar recursos de um fórum, similar ao Stack Overflow. Os usuários podem se registrar, se autenticar, criar, editar, responder e comentar em perguntas e respostas, etc.

## Requisitos e funcionalidades

### Autenticação
- [x] Deve ser possível criar uma conta;
- [x] Deve ser possível se autenticar;

### Perguntas
- [x] Deve ser possível criar uma nova pergunta;
- [x] Deve ser possível listar as perguntas mais recentes;
- [x] Deve ser possível buscar uma pergunta pelo slug;
- [x] Deve ser possível editar uma pergunta;
- [x] Deve ser possível deletar uma pergunta;

### Respostas
- [x] Deve ser possível adicionar uma resposta a uma pergunta;
- [x] Deve ser possível listar as respostas de uma pergunta;
- [x] Deve ser possível editar uma resposta;
- [x] Deve ser possível marcar uma resposta como a melhor;
- [x] Deve ser possível deletar uma resposta;

### Comentários

- [x] Deve ser possível adicionar um comentário a uma pergunta;
- [x] Deve ser possível listar os comentários de uma pergunta;
- [x] Deve ser possível deletar um comentário de uma pergunta;
- [x] Deve ser possível adicionar um comentário a uma resposta;
- [x] Deve ser possível listar comentários de uma resposta;
- [x] Deve ser possível deletar um comentário de uma resposta;

### Anexos

- [x] Deve ser possível fazer upload de um anexo;

### Notificações

- [x] Deve ser possível marcar uma notificação como lida;

## Arquitetura

O projeto segue os princípios da **Clean Architecture**, separando claramente as responsabilidades, favorecendo o desacoplamento e a coesão. Essa estrutura modular objetiva facilitar o desenvolvimento, manutenção e escalabilidade, podendo-se facilmente ser convertida futuramente em microsserviços.

- `src/core`: contém a lógica de negócio mais genérica e artefatos para a construção do domínio com **entities, value objects, etc**;
- `src/domain`: contém a lógica principal de negócio dividida por contextos **forum e notification** com as implementações de **entities, use cases, repositories, domain events, etc**;
- `src/infra`: contém a implementação dos artefatos da camada externa com **controllers, gateways, providers, framework, database, etc**;
- `src/test`: contém os repositórios de **testes, fakers, factories, testes e2e, etc**.

## Rotas da API

( TODO: implementar swagger )

### Autenticação

- `POST /sessions`: autentica um usuário e retorna um `access_token`.
- `POST /accounts`: cria uma nova conta de usuário.

### Perguntas

- `POST /questions`: cria uma nova pergunta.
- `GET /questions`: lista as perguntas mais recentes.
- `GET /questions/:slug`: busca uma pergunta pelo seu slug.
- `PUT /questions/:id`: edita uma pergunta.
- `DELETE /questions/:id`: deleta uma pergunta.

### Respostas

- `POST /questions/:questionId/answers`: adiciona uma resposta a uma pergunta.
- `GET /questions/:questionId/answers`: lista as respostas de uma pergunta.
- `PUT /answers/:id`: edita uma resposta.
- `DELETE /answers/:id`: deleta uma resposta.
- `PATCH /answers/:answerId/choose-as-best`: marca uma resposta como a melhor.

### Comentários

- `POST /questions/:questionId/comments`: adiciona um comentário a uma pergunta.
- `GET /questions/:questionId/comments`: lista os comentários de uma pergunta.
- `DELETE /questions/comments/:id`: deleta um comentário de uma pergunta.
- `POST /answers/:answerId/comments`: adiciona um comentário a uma resposta.
- `GET /answers/:answerId/comments`: lista os comentários de uma resposta.
- `DELETE /answers/comments/:id`: deleta um comentário de uma resposta.

### Anexos

- `POST /attachments`: faz o upload de um anexo.

### Notificações

- `PATCH /notifications/:notificationId/read`: marca uma notificação como lida.

## Como executar

Se estiver utilizando outro gerenciador de pacotes, basta trocar o `pnpm` por `npm`, `yarn`, etc.

### Pré-requisitos

- Node.js ( versão 18 ou superior )
- Docker

Instalar as dependências do projeto.

```bash
pnpm install
```

Renomeie o arquivo `.env.example` para `.env` na raiz do projeto e preencha as variáveis de ambiente com as suas configurações.

```text
# Database (Prisma)
DATABASE_URL="postgresql://postgres:docker@localhost:5432/forum?schema=public"

# Cache (Redis)
REDIS_HOST=""
REDIS_PORT=""
REDIS_DB=""

# Auth (JWT)
JWT_PRIVATE_KEY=""
JWT_PUBLIC_KEY=""

# Upload (AWS / Cloudflare)
CLOUDFLARE_ACCOUNT_ID=""
AWS_BUCKET_NAME=""
AWS_ACCESS_KEY_ID=""
AWS_SECRET_ACCESS_KEY=""
```

Criar imagem com o docker compose.

```bash
docker-compose up -d
```

Executar as `migrations`.

```bash
npx prisma generate
```

```bash
npx prisma migrate dev
```

### Testes

#### Unitário

```bash
pnpm test
```

```bash
pnpm test:watch
```

#### E2E

```bash
pnpm test:e2e
```

```bash
pnpm test:e2e:watch
```

#### Coverage

```bash
pnpm test:coverage
```

#### Visualização em UI 

( TODO: adicionar )

```bash
pnpm test:ui
```

#### Debug

```bash
pnpm test:debug
```

### Localmente

```bash
pnpm start:dev
```

A aplicação estará disponível em http://localhost:3333.

### Produção

```bash
pnpm build
```

```bash
pnpm start:prod
```

## Tecnologias

- [Node.js](https://nodejs.org/en)
- [Nest.js](https://nestjs.com/)
- [Typescript](https://www.typescriptlang.org/)
- [Faker.js](https://v10.fakerjs.dev/)
- [Day.js](https://day.js.org/)
- [Zod](https://zod.dev/)
- [Dotenv](https://www.npmjs.com/package/dotenv)
- [JWT](https://www.jwt.io/)
- [Bcrypt.js](https://www.npmjs.com/package/bcryptjs)
- [AWS-SDK-S3](https://www.npmjs.com/package/@aws-sdk/client-s3)
- [ESLint](https://eslint.org/)
- [Vite](https://vite.dev/)
- [Vitest](https://vitest.dev/)
- [Supertest](https://www.npmjs.com/package/supertest)
- [Prisma](https://www.prisma.io/)
- [Redis](https://redis.io/)

> **DICA !**
>
> Todas as demais dependências utilizadas podem ser visualizados acessando o [package.json](./package.json).

## Autor

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/felipe-dr">
        <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/62888625?s=96&v=4" width="100px;" alt="Avatar do autor" />
        <br />
        <sub>
          <b>Felipe DR</b>
        </sub>
      </a>
      <br />
      <a href="mailto:felipe.corp7@gmail.com" title="E-mail">📩</a>
    </td>
  </tr>
</table>
