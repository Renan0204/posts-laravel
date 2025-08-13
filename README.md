## Instalação e execução
1. Clonar repositório
2. Instalar dependências:
   composer install
3. Configurar banco de dados no .env
4. Rodar migrations:
   php artisan migrate
5. Sincronizar dados:
   php artisan sync:posts
6. Testar:
   GET /api/posts

## Como rodar
1. Clonar ou extrair o projeto.
2. Rodar composer install.
3. Configurar o banco.
4. Rodar php artisan key:generate.
5. Rodar php artisan migrate.
6. Rodar php artisan sync:posts.
7. Acessar http://localhost:8000/api/posts.
