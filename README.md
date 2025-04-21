# 🥃 Bob - The Spirit Guide (n8n Agent)

Bob é um agente de IA criado para analisar a "bar" de um usuário no ecossistema BAXUS e recomendar bebidas personalizadas com base nos seus gostos, preferências e histórico de preços. Ele foi implementado usando [n8n](https://n8n.io/) e roda via Docker.

## 🚀 Como rodar o projeto localmente

### Pré-requisitos

- Docker instalado ([instruções](https://docs.docker.com/get-docker/))

### Passo a passo

```bash
# Clone este repositório
git clone https://github.com/seu-usuario/bob-n8n.git

# Acesse a pasta
cd bob-n8n

# Suba o container com o n8n e o workflow do Bob
docker compose up -d


# Acesse o n8n no seu navegador:
http://localhost:5678