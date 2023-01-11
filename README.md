# Nextcloud-Nginx-Postgres-MariaDB-Docker-Compose
Docker compose para instalação de container's com Nextcloud, nginx como proxy reverso com banco de dados PostgresQL ou MariaDB

**Importante:** este é um trabalho em andamento.

**Ainda mais importante:** Se você realmente planeja usar isso, não se esqueça de editar os arquivos de configuração de acordo com suas necessidades (arquivos de serviço, arquivos de configuração YAML, etc.). Os arquivos de configuração fornecidos aqui são apenas arquivos genéricos.

Este script baixa os arquivos no diretório atual. Você poderia mudar isso.

# Atualmente o repositorio conta com duas configurações, sendo elas:

* Docker compose contendo, Nextcloud, Nginx-fpm e Postgres.

* Docker compose contendo, Nextcloud, Nginx Proxy Manager e MariaDB.

Quaisquer sugestões e contribuições são bem-vindas.

# Como usar isso?

* docker-compose up -d

## Instalação completa

A instalação completa instalará o seguinte:

* Nextcloud

* Nginx

* Postgresql

# Acesso

* http://localhost/nextcloud
* http://seu-host-name/nextcloud

* Basta criar um usuario e senha no momento do login, exemplo: User (Admin) senha (Admin)

# Acesso banco de dados de acordo com a config disponibilizada no Docker compose qual recomando a alteração das mesmas

