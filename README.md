# SUAP-RN-9-24

esse projeto tem como objetivo criar um protótipo para funcionalidades
que precisam ser inseridas no suap, com relação as capacitações dos docentes.

## Requisitos:

- Rails >= 7.1.3.4
- ruby >= 3.3.3
- postgresql 16+

## como rodar

primeiro instale as dependências:

     bundle install

rode o comando para gerar o banco de dados

     bin/rails db:create

por fim, as migrations:

     bin/rails db:migrate

agora é só rodar:

     bin/rails server