# Projeto de CRUD de Agenda e Eventos usando Laravel

Este é um projeto de uma aplicação web para gerenciamento de agenda de eventos, desenvolvida utilizando o framework Laravel. A aplicação permite a criação, leitura, atualização e exclusão (CRUD) de eventos em uma agenda.

## Funcionalidades

- Criação de eventos com informações como título, data, hora, descrição e local.
- Listagem de eventos cadastrados.
- Visualização dos detalhes de um evento específico.
- Atualização dos dados de um evento existente.
- Exclusão de eventos.

## Requisitos

- PHP 7.4 ou superior
- Composer
- Laravel 8.x
- Banco de dados suportado pelo Laravel (por exemplo, MySQL, SQLite, PostgreSQL)

## Instalação

```shell
# Clone este repositório para o diretório local do seu servidor web:
git clone https://github.com/seu-usuario/seu-repositorio.git

# Acesse o diretório do projeto:
cd seu-repositorio

# Instale as dependências do projeto via Composer:
composer install

# Crie um arquivo .env na raiz do projeto, copiando o conteúdo do arquivo .env.example:
cp .env.example .env

# Gere uma nova chave de aplicação:
php artisan key:generate

# Configure as informações do banco de dados no arquivo .env:

 DB_CONNECTION=mysql
 DB_HOST=127.0.0.1
 DB_PORT=3306
 DB_DATABASE=nome-do-banco-de-dados
 DB_USERNAME=nome-de-usuario
 DB_PASSWORD=senha

# Execute as migrations para criar as tabelas do banco de dados:
php artisan migrate

# Inicie o servidor embutido do Laravel:
php artisan serve

A aplicação estará disponível em http://localhost:8000.
```

## Uso

Após a instalação e execução do projeto, você poderá acessar a aplicação no navegador. A partir daí, você poderá realizar as seguintes ações:

- Criar um novo evento clicando no botão "Novo Evento" na página inicial.
- Listar todos os eventos cadastrados na página inicial.
- Visualizar os detalhes de um evento clicando em seu título na lista de eventos.
- Editar as informações de um evento clicando no botão "Editar" na página de detalhes do evento.
- Excluir um evento clicando no botão "Excluir" na página de detalhes do evento.

## Contribuição

Contribuições para este projeto são bem-vindas. Sinta-se à vontade para abrir uma issue para relatar bugs, sugerir melhorias ou enviar pull requests.

Ao contribuir, por favor, siga as melhores práticas de desenvolvimento e respeite o código de conduta.

## Licença

Este projeto está licenciado sob a MIT License.

## Tecnologias utilizadas

![HTML](https://img.shields.io/badge/-HTML-121011?style=for-the-badge&logo=html5)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-121011?style=for-the-badge&logo=CSS3&logoColor=1572B6)&nbsp;
![JavaScript](https://img.shields.io/badge/-JavaScript-121011?style=for-the-badge&logo=javascript)&nbsp;
![JQuery](https://img.shields.io/badge/-Jquery-121011?style=for-the-badge&logo=jquery)&nbsp;
![Bootstrap](https://img.shields.io/badge/-Bootstrap-121011?style=for-the-badge&logo=bootstrap)&nbsp;
![PHP](https://img.shields.io/badge/-PHP-121011?style=for-the-badge&logo=php)&nbsp;
![Laravel](https://img.shields.io/badge/Laravel-121011?style=for-the-badge&logo=laravel)&nbsp;
![GIT](https://img.shields.io/badge/-GIT-121011?style=for-the-badge&logo=git)&nbsp;
