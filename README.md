# Docker PHP template

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
- O nginx deve ser configurado para apontar para a pasta do projeto. Arquivos ***.conf** de exemplo esão disponíveis na pasta **[nginx/sites](https://github.com/waliqueiroz/docker-php-template/tree/master/nginx/sites)**. Para mais detalhes acesse a [documentação oficial](https://nginx.org/en/docs/).
- Por fim você deverá copiar o arquivo env-example para .env e editar os valores das variáveis de ambiente.

Após as configurações, execute:

```
$ docker-compose build
$ docker-compose up -d
```
