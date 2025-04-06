Como Usar
1. Clone o Repositório
Para começar, clone ou baixe o repositório:

git clone https://github.com/fajarghifar/laravel-point-of-sale

2. Configure o Projeto
Depois de clonar o repositório, navegue até o diretório do projeto e instale as dependências:


composer install
Abra o projeto no seu editor de código preferido:



3. Configure o Ambiente
Renomeie o arquivo .env.example para .env:




cp .env.example .env
Gere a chave da aplicação:



php artisan key:generate
4. Defina o Idioma  (Opcional)
Para definir o idioma do Faker (por exemplo, adicione a seguinte linha no final do seu arquivo .env:


FAKER_LOCALE="id_ID"
5. Configure o Banco de Dados
Edite o arquivo .env com as credenciais corretas do seu banco de dados.

6. Popule o Banco de Dados
Execute o seguinte comando para migrar e popular o banco de dados:


php artisan migrate:fresh --seed
Observação: Se ocorrer algum erro, tente executar o comando novamente.

7. Crie o Link de Armazenamento
Crie um link simbólico para o armazenamento:


php artisan storage:link
8. Inicie o Servidor
Para executar a aplicação localmente, inicie o servidor 


php artisan serve
9. Faça Login
Use as seguintes credenciais para fazer login:

Usuário: admin

Senha: password



php artisan storage:link
1. Inicie o Servidor
Execute o servidor de desenvolvimento:

php artisan serve
2. Faça Login
Tente fazer login com:

Usuário: admin

Senha: password

