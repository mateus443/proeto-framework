Como Usar
1. Clone o Repositório
Para começar, clone ou baixe o repositório:

bash
Copiar
Editar
git clone https://github.com/fajarghifar/laravel-point-of-sale
2. Configure o Projeto
Depois de clonar o repositório, navegue até o diretório do projeto e instale as dependências:

bash
Copiar
Editar
cd laravel-point-of-sale
composer install
Abra o projeto no seu editor de código preferido:

bash
Copiar
Editar
code .
3. Configure o Ambiente
Renomeie o arquivo .env.example para .env:

bash
Copiar
Editar
cp .env.example .env
Gere a chave da aplicação:

bash
Copiar
Editar
php artisan key:generate
4. Defina o Idioma do Faker (Opcional)
Para definir o idioma do Faker (por exemplo, para indonésio), adicione a seguinte linha no final do seu arquivo .env:

bash
Copiar
Editar
FAKER_LOCALE="id_ID"
5. Configure o Banco de Dados
Edite o arquivo .env com as credenciais corretas do seu banco de dados.

6. Popule o Banco de Dados
Execute o seguinte comando para migrar e popular o banco de dados:

bash
Copiar
Editar
php artisan migrate:fresh --seed
Observação: Se ocorrer algum erro, tente executar o comando novamente.

7. Crie o Link de Armazenamento
Crie um link simbólico para o armazenamento:

bash
Copiar
Editar
php artisan storage:link
8. Inicie o Servidor
Para executar a aplicação localmente, inicie o servidor de desenvolvimento do Laravel:

bash
Copiar
Editar
php artisan serve
9. Faça Login
Use as seguintes credenciais para fazer login:

Usuário: admin

Senha: password

🚀 Configuração
1. Configure as Opções do Carrinho
Abra o arquivo ./config/cart.php para configurar taxas de imposto, formatos de número e mais.

Para mais detalhes, consulte a documentação do pacote hardevine/shoppingcart.

2. Link de Armazenamento
Se ainda não fez, execute este comando para criar o link simbólico de armazenamento:

bash
Copiar
Editar
php artisan storage:link
3. Inicie o Servidor
Execute o servidor de desenvolvimento:

bash
Copiar
Editar
php artisan serve
4. Faça Login
Tente fazer login com:

Usuário: admin

Senha: password

