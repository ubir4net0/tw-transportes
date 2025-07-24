## Projeto desenvolvido na TreinaWeb Cursos

Desenvolvido no projeto prático: Laravel - Aplicação de rastreamento de fretes

Trata-se de um sistema para gerenciamento e rastreamento de fretes, com recursos para cadastro de transportadoras, rotas e fretes, além de um painel administrativo com Filament. A aplicação inclui autenticação, controle de acesso por permissões, validação de dados e organização seguindo boas práticas do Laravel.

### Funcionalidades

- Cadastro e gerenciamento de fretes, rotas e transportadoras
- Painel administrativo com Filament Admin
- Autenticação de usuários com controle de permissões (roles)
- Validação de dados com Form Requests
- Listagens com paginação e ordenação
- Upload de arquivos
- API RESTful
- Banco de dados versionado com migrations e seeders

### Instalando o projeto

#### Clonar o repositório

git clone https://github.com/ubir4net0/tw-transportes.git

#### Instalar as dependências

composer install

css
Copiar
Editar

Ou em ambiente de desenvolvimento:

composer update

perl
Copiar
Editar

#### Criar arquivo de configurações de ambiente

Copiar o arquivo de exemplo `.env.example` para `.env` na raiz do projeto  
Configurar os detalhes da aplicação e conexão com o banco de dados.

#### Criar a estrutura no banco de dados

php artisan migrate



#### Iniciar o servidor de desenvolvimento

php artisan serve
