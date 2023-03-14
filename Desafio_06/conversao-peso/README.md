# Desafio 06 - Projeto conversão de peso

O projeto conversão de peso é um projeto desenvolvido em C# com .NET Core 5.0. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando .NET.

## Requisitos do Projeto:

Antes de começar, você vai precisar ter instalado em sua máquina os seguintes recursos:

- [Git](https://git-scm.com/downloads)
- [Docker](https://docs.docker.com/get-docker/)

## Executando o Projeto:

Para testarmos a aplicação, temos que executar os passos a seguir:

1. [Fazer download do Projeto](#download-github)
2. [Executar Docker Compose](#docker-compose)
3. [Acessar a Aplicação](#acessando-app)

<a name="download-github"></a>
### 1. Fazer download do Projeto:
 1. Baixe este Repositório, executando o comando Git:
```bash
git clone https://github.com/leandroph/DevOpsPro-Desafios.git
```

<a name="docker-compose"></a>
### 1. Fazer downloa do do Projeto:
1. Acesar o diretório `Desafio_06/conversao-peso`, executar o compando:
```bash
docker compose up -d
```

<a name="acessando-app"></a>
### 3. Acessar a Aplicação do Redis Commander:

1. Em seu navegador, de sua preferência, acesse a url `http://localhost:80` para visualizar a Aplicação;

2. Se os passos anteriores foram executados corretamente, a resposta será semelhante a tela abaixo:

![alt text](images/conv-peso.png
)

