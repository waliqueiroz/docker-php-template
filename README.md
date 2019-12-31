# docker-template

## Descrição

Template docker-compose para aplicações PHP.

- nginx:latest
- php:7.1.9-fpm
- postgres:latest

## Pré-requisitos
- Docker
- Docker-compose

## Utilização

- Os projetos devem ser postos dentro da pasta htdocs.
- O nginx deve ser configurado para apontar para a pasta do projeto. Arquivos *.conf de exemplo esão disponíveis na pasta nginx/sites.
- Por fim você deverá copiar o arquivo env-example para .env e editar os valores das variáveis de ambiente do sistema.

Após as configurações, execute:

```
$ docker-compose build
$ docker-compose up -d
```
