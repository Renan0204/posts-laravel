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