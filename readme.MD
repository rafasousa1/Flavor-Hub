# API de compartilhamento de receitas 🍜
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)

## Descrição
Uma API de compartilhamento de receitas para uma comunidade ativa, onde é possível criar comentários e uma nota de avaliação do que achou ao executar a refeição.

Projeto desenvolvido com o framework Fastify, utilizando Prisma ORM para a interação com o banco de dados. A API permite cadastro, atualização e exclusão de receita.

## Instrução de instalação

### Pré-Requisitos
- Node.js v18+
- Fastify
- Prisma
- Typescript

## Instrução de uso

1. Ferramenta de teste de API (Insomnia, Postman etc)
2. Executar localhost:3333/recipes

## Endpoints 

### GET Receitas, 
```
GET /recipes/search - Listando receitas criadas
```

### GET detalhes de uma receita
```
GET /recipes/details - Listando detalhes de uma receita
```

### GET Receita pelo id
```
GET /recipes/:recipeId - Listando uma receita específica pelo id
```

### POST Receitas
```
POST /recipes - Criando uma nova receita
```

### DELETE Receitas
```
DELETE /recipes/:recipeId - Removendo um lutador específico pelo seu id
```
