<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  API GoBarber
</h3>

<blockquote align="center">“Não espere para plantar, apenas tenha paciência para colher”!</blockquote>


## :rocket: Sobre a aplicação

API da aplicação GoBaber que conecta prestadores de serviço (Barbeiros e Cabeleireiros) aos clientes em suas regiões. Feita dentro do Bootcamp GoStack 2020. :smile:



## Tecnologias utilizadas :memo:

- NodeJS
- TypeScript
- Express
- PostgreSQL ( usando docker com a imagem do [postgres](https://hub.docker.com/_/postgres/) :tada: )
- TypeORM
- uuidv4
- ts-node-dev
- ESLint + Prettier


## Como utilizar 🤔

Primeiramente clone este repositório.

```
git clone https://github.com/ruanvalente/gostack-gobarber-api
```
Entre na pasta `gostack-gobarber-api` e rode o comando `yarn` ou `npm install`, para instalar as dependências do projeto.

```
cd gostack-gobarber-api
```

Dentro do arquivo `ormconfig.json` altere as seguintes linhas: 
- `username: seu_username`
- `password: seu_password`
- `database: nome_da_sua_database`

Execute as **migrations**

```
yarn typeorm migration:run
```

Agora é só executar.

```
yarn dev:server
```

E agora é só se divertir :smile:

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.