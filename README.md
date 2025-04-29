1. Clone o Repositório
   
Para começar, clone ou baixe o repositório:

git clone https://github.com/fajarghifar/laravel-point-of-saleZ

2. Configure o Projeto
   
Após clonar o repositório, navegue até o diretório do projeto e instale as dependências:

cd laravel-point-of-sale
composer install
Abra o projeto no seu editor de código preferido:

code.

3. Configure o Ambiente
   
Renomeie o arquivo .env.example para .env:

cp .env.example .env
Gere a chave do aplicativo:

php artisan key:generate

4. Defina a localidade do Faker (opcional)
5. 
Para definir a localidade do Faker (por exemplo, para indonésio), adicione a seguinte linha ao final do seu arquivo .env:

FAKER_LOCALE="id_ID"

5. Configure o Banco de Dados
   
Configure as credenciais do seu banco de dados no arquivo .env.

7. Propagar o Banco de Dados
   
Execute o seguinte comando para migrar e propagar o banco de dados:

php artisan migrate:fresh --seed

Observação: se encontrar algum erro, tente executar o comando novamente.

7. Criar Link de Armazenamento
   
Crie um link simbólico para armazenamento:

php artisan storage:link

8. Iniciar o Servidor
   
Para executar a aplicação localmente, inicie o servidor de desenvolvimento Laravel:

php artisan serve

9. Login
    
Use as seguintes credenciais para fazer login:

Nome de usuário: admin
Senha: password

🚀 Configuração

1. Configurar o Carrinho
   
Abra o arquivo ./config/cart.php para definir configurações como taxas de impostos, formatos de números e muito mais.

Para mais detalhes, consulte a documentação do hardevine/shoppingcart.

2. Link de Armazenamento
   
Se ainda não o fez, execute este comando para criar o link de armazenamento:

php artisan storage:link

3. Iniciar o Servidor
   
Execute o servidor de desenvolvimento:

php artisan serve

4. Login
   
Tente fazer login com:

Nome de usuário: admin
Senha: password
