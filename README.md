![nlw-pocket](https://github.com/user-attachments/assets/662b632b-3010-4eaa-8118-bc37169ec1ce)

# in-orbit

[English](#en-us) - [Português](#pt-br)

## pt-BR

### Configurações de desenvolvimento
Instale as dependências
```shell
npm install
```

Crie o arquivo de ambiente na pasta raiz do projeto (.env)
```env
DATABASE_URL=<sua_url_do_database> # Padrão: postgresql://docker:docker@localhost:5432/inorbit
```

Inicie o container da base de dados
```shell
docker compose up -d
```

Aplique as migrações
```shell
npx drizzle-kit migrate
```

*Adicione os dados iniciais
```shell
npm run seed
```

Inicie a aplicação
```shell
npm run dev
```
_(*) - Opcional_

### Rotas desenvolvidas
- [x] Criar uma nova meta
- [x] Registrar conclusão da meta
- [x] Buscar metas da semana
- [x] Resumo da semana

> Essa aplicação foi criada durante o evento [NLW Pocket JS](https://www.youtube.com/watch?v=7LRQ93tju1A) da [Rocketseat](https://www.rocketseat.com.br/)

## en-US

### Development setup
Install dependencies
```shell
npm install
```

Create environment file at project root directory (.env)
```env
DATABASE_URL=<your_database_url> # Default: postgresql://docker:docker@localhost:5432/inorbit
```

Start database container
```shell
docker compose up -d
```

Apply migrations
```shell
npx drizzle-kit migrate
```

*Add initial data
```shell
npm run seed
```

Start application
```shell
npm run dev
```

_(*) - Optional_

### Developed routes
- [x] Create new goal
- [x] Register goal completion
- [x] Get week goals
- [x] Get week summary

> This application were created during the event [NLW Pocket JS](https://www.youtube.com/watch?v=7LRQ93tju1A) by [Rocketseat](https://www.rocketseat.com.br/)
