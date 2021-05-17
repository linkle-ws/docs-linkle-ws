---
sidebar_position: 1
---

# Instalação

Nosso SDK está disponível em NodeJS pelo gerenciador de pacotes `npm`, suas dependências são:

- `emjs` 
- `axios` 

## Instalação do Pacote em NodeJS

Para instalar nosso pacote, você deverá ter o `npm` instalado em usa máquina:

```shell
npm install linkle-ws
```

Certifique-se que sua versão é superior a `0.0.7`, pois é a versão beta liberada pra desenvolvedores.

## Dependência salva no package.json

Entre dentro do `package.json` do projeto após a instalação:

```json title="package.json"
// ...
"dependencies": {
    "linkle-ws": "^0.0.7",
  }
// ...
```

Agora seu pacote esta pronto para ser consumido em ambiente de desenvolvimento e produção.
