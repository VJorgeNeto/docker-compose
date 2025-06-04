# docker-compose

> Ambiente de containers orquestrados com Docker Compose para testes e desenvolvimento local.

## 📋 Descrição

Este repositório contém um arquivo `docker-compose.yml` com definição de serviços que podem ser usados em ambientes de testes, desenvolvimento ou demonstrações. O conteúdo do arquivo pode ser modificado conforme a necessidade de cada projeto.

## ⚙️ Requisitos

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/)

> **Nota:** Docker Compose V2 já está embutido no Docker Desktop e nas versões mais recentes do Docker CLI (`docker compose` ao invés de `docker-compose`).

## 🚀 Como Usar

1. Clone o repositório:

```bash
git clone https://github.com/VJorgeNeto/docker-compose.git
cd docker-compose
```
Inicie os containers:

```bash

docker compose up -d
Para verificar os logs:
```

```bash

docker compose logs -f
```

Para parar e remover os containers:

```bash
docker compose down
```

📁 Estrutura
```
.
├── docker-compose.yml
└── README.md
```

📄 Licença
Distribuído sob a licença MIT.
