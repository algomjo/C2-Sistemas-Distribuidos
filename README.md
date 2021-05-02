
<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href=" https://github.com/">
    <img src="https://i1.wp.com/www.docker.com/blog/wp-content/uploads/2020/02/Compose.png?resize=200%2C219&ssl=1" alt="Logo" width="100" height="100">
  </a>


### Docker Hub

* [MySQL](https://hub.docker.com/_/mysql)
* [phpMyAdmin](https://hub.docker.com/_/phpmyadmin)
* [Portainer](https://hub.docker.com/r/portainer/portainer)

O build da imagem `php_app` será criada na execução do docker compose.

## Como rodar o projeto

1. Faça o download do diretório (ou faça um clone deste repositório inteiro);
   ```sh
   git clone https://github.com/
   ```
2. Executar o docker-compose na raiz do projeto via terminal
   ```sh
   Docker-compose -f Docker-compose.yml up -d --build
   ```
Após processo  ser concluído, será necessário importar a tabela do banco de dados, que está localizada no diretório: 

  ```sh
  ./mysql/database/employees.sql
   ```
Todo processo de importar a tabela `employees.sql`, pode ser realizada diretamente pelo phpMyAdmin.

### URL

* [Aplicativo php](http://localhost/)
* [phpMyAdmin](http://localhost:8080/)
* [Portainer](http://localhost:9000/)


 