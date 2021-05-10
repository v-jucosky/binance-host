# Binance: Host

Este repositório contém os arquivos necessários para iniciar o ambiente utilizado pelo Bot, incluindo ferramentas de desenvolvimento e banco de dados.

Para iniciar a criação do ambiente, execute:

```shell
docker compose up
```

Ao final da inicialização, terão sido criados:

1. Instância PostgreSQL 13
    * String de conexão (sysadmin): `postgres://postgres:postgres@localhost:5432`
    * Bancos de dados: `history`, `training` e `bot`

2. Servidor PgAdmin 4
    * URL de acesso: http://localhost:15432/
    * Usuário: `pgadmin@pgadmin.com`
    * Senha: `pgadmin`
