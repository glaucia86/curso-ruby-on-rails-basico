# Curso Básico: Ruby on Rails by Jackson Pires

Curso básico de Ruby on Rails do canal do Youtube - [Jackson Pires](https://www.youtube.com/watch?v=ZHPondVB9RQ&list=PLe3LRfCs4go-mkvHRMSXEOG-HDbzesyaP).
O Curso tem como objetivo ensinar conceitos básicos do framework do Ruby: Rails.

## Recursos Utilizados no Desenvolvimento:

- Ruby on Rails ~ 5.0.1;
- Ruby ~ 2.2.6;
- Gem ~ 2.4.5.2;
- PostgreSQL;

## Ementa dos conteúdos estudados durante o Curso:


## Configurando o PostgreSQL no projeto:

Vá até a pasta 'config' e depois no arquivo 'database.yml'. Depois de abrir o arquivo, procure a seção 'default' e acrescente 
bloco de código depois de "pool: 5":

```
host: localhost
username: pguser
password: pguser_password

```

Salve o arquivo.

Agora para poder criar a Base de Dados da aplicação, abre o cmd e digite o seguinte comando:

```
rake db:create

```

Ao digitar esse comando irá criar de maneira correta os schemas das bases de dados criadas no arquivo 'database.yml'.

Vamos testar a configuração. Para isso, basta digitar o seguinte comando:

```
rails server

```

Se aparecer a seguinte mensagem: "Welcome aboard" na sua página Ruby on Rails é porque foi corretamente configurada 
a sua aplicação e conectada com sucesso com o PostgreSQL.

Fonte: [AQUI](https://www.digitalocean.com/community/tutorials/how-to-use-postgresql-with-your-ruby-on-rails-application-on-ubuntu-14-04)


