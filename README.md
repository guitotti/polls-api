<img src="http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=GREEN&style=for-the-badge"/>

## 🧩 Polls API - Projeto em desenvolvimento para estudo pessoal.

Projeto desenvolvido durante o evento NLW Expert da Rocketseat.

## Desafio

Criar um sistema de votação de enquetes em tempo real, utilizando as tecnologias listadas abaixo. 
O armazenamento dos dados foi feito utilizando PostgreSQL e Redis. Para a atualizar os votos em tempo real, foi utilizado WebSocket seguindo o <i>pattern Pub/Sub</i>.

## 🚀 Tecnologias

- [Node.js](https://nodejs.org/en/)
- [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Fastify](https://fastify.dev/) 
- [Prisma](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Redis](https://redis.io/)
- [Zod](https://zod.dev/)
- [Docker](https://www.docker.com/)

***

## :information_source: Configuração do projeto

<i>Para clonar e rodar a aplicação, é necessário [Git](https://git-scm.com), [Node.js](https://nodejs.org/en/) e [Docker](https://www.docker.com/) instalados.</i>

Siga o passo-a-passo a seguir:

```bash
# Clonar o repositório
$ git clone https://github.com/guitotti/polls-api

# Navegar até o repositório
$ cd polls-api

# Instalar dependências
$ npm install

# Preencher as credenciais do PostgreSQL no arquivo .env

# Subir os containers do Docker
$ docker compose up -d

# Executar as migrations do Prisma
$ npx prisma migrate dev

# Rodar o projeto em ambiente de desenvolvimento
$ npm run dev
```

***

Desenvolvido por [Guilherme Totti](https://www.github.com/guitotti).
