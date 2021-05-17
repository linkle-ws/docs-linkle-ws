---
sidebar_position: 1
---

# Introdução

Vamos entender o que é  **o Linkle Web Service em 5 minutos**.

## Sobre a Linkle

A Linkle é uma startup fundada na Flórida. Nosso propósito é facilitar o processo de contratação, usando inteligência artificial para encaixar candidatos e vagas usando os critérios de **localização e análise de skills**.

Para entender mais **baixe nosso app** ou ente em nosso site **[linkle.io](https://www.linkle.io/intro/)**.

## Usando via pacote NPM

Para códigos em NodeJS em javascript ou typescript **use nosso pacote npm**:

```shell
npm install linkle-ws
```

## Usando via APIs

Disponibilizamos algumas features vias APIs, usando uma API Key:

```shell
curl --header "apikey: suaAPiKey" https://linkle-ws-dev.herokuapp.com/promocode?email=exemplo@email.com
```

Você receberá seu response apenas se estiver autenticado pela parametro de apikey no header.

Com apikey você poderá ter acesso aos dados relacionados ao usuário Linkle cuja a chave fora copiada. Cada `apikey` é um hash JWT, e pode ser recuperado no Linkle Web Company.

## Como resgatar meu apikey

Descrever passo a passo para resgatar.
