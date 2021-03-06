# api-vendas

Recursos implementados:

- API Restful

- CORS

- Tratamento de erros

- Sistema de roteamento

- Middlewares

- CRUD

- TypeORM com o padrão Repository

- Migrations

- Relacionamento Many-to-Many

- Filesystem/upload de arquivos

- Armazenamento de arquivos em Bucket Amazon S3

- Envio de email fake (dev env) e email profissional com o Zoho Mail e Amazon SES

- Autenticação JWT Token

- Cache com Redis

- Proteção contra ataque DDoS

- Design Patterns com Domain Driven Design (DDD) e Princípios SOLID

- Iniciando com Testes Automatizados com Jest

-----

Tecnologias Utilizadas:

Node.js

Express

Typescript

TypeORM

Postgres através de container Docker

Redis através de container Docker

Amazon S3

Amazon SES

-----
Estrutura de pastas:

Config - configurações de bibliotecas externas

Modules - abrange a área de rega de negócio da aplicação

Shared - Módulos de uso geral, compartilhado com mais de um módulo da aplicação

Services - Estarão dentro de cada módulo da aplicação e serão responsáveis pelas regras que a aplicação precisa atender
