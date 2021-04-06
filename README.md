# CRUDMongo [![Github Badge](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white&link=https://youtu.be/BqIseJbbxSY)](https://youtu.be/BqIseJbbxSY)

Exemplo de uso do MongoDB com NodeJS desenvolvido durante aula da disciplina de Bancos de Dados II, do Curso Superior de Tecnologia em Análise e Desenvolvimento de Sisteas do IFPB, campus Cajazeiras.

## Inicialização
Para inicializar a API vocês deverão:
1. Clonar o repositório
2. Criar na pasta raiz um arquivo .env, que apresenta os parâmetros de configuração do banco

Exemplo do arquivo .env (trocar os valores das chaves pelos dados do seu banco):
```
MONGO_HOST={IP do container}
MONGO_PORT={Porta padrão 27017}
MONGO_DATABASE={nome do banco}
```

3. ```npm i```
4. ```npm start```

## Alterar parâmetros
Você pode alerar os dados da conexão do banco e da porta da API no arquivo .env

## Uso
Todos os comandos do uso do banco estão no arquivo index.js. É necessário realizar refatoração do código, pois foi feito de forma simples para facilitar na didática do exemplo.
