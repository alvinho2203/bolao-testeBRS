# Projeto Bolão - Laravel - André Alves Rutter Salles

Projeto realizado para teste na empresa BRS Software.

Utiliza Laravel como framework.

Versão Laravel utilizada: 5.6.39.

Para criar as tabelas no bando de dados:

php artisan migrate

Para utilizar os seeders deste projeto, basta rodar o comando:

php artisan db:seed

O seed criará dois usuários:
user 	email 	password 	role
Admin 	admin@mail.com 	123456 	Admin
Manager 	manager@mail.com 	123456 	Gerente

Para criar as tabelas e já utlizar os seeds:

php artisan migrate --seed

Passos para criação de novo CRUD no admin:

    Model e migration.
    Controller.
    Traduções.
    Interface.
    Repository.
    Registrar no AppServiceProvider.
    Views.
    Registrar views nas rotas.


Este projeto utiliza a [licença MIT](https://opensource.org/licenses/MIT).