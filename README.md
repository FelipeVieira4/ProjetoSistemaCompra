# *Projeto - Sistema Compra*
O projeto faz uso de Banco de Dados tendo suporte para MySQL e MariaDB.

Ideias futuras, refazer esse projeto usando Spring Boot + React(ou Vaadin) e colocar para rodar em um container Docker

## Drivers utilizados

### MYSQL
https://mvnrepository.com/artifact/com.mysql/mysql-connector-j/8.0.33

### MariaDB
https://mariadb.com/downloads/connectors/connectors-data-access/java8-connector/
https://mvnrepository.com/artifact/com.github.waffle/waffle-jna/3.3.0

## Criar Banco de Dados da aplicação

### Windows

Basta apenas executar o arquivo "comando_sql.sql" no MySQL Workbench.

### Linux

Execute o seguinte comando:

#### MySQL

***sudo sql < comando_sql.sql***

#### MariaDB

***sudo mariadb < comando_sql.sql***
