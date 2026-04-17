# gestão-clínica-laravel

Sistema de gerenciamento para clínica médica, desenvolvido em PHP com Laravel. O projeto permite cadastro e controle de profissionais, clientes e consultas em uma aplicação web organizada e funcional.

## Sobre

Este repositório contém um sistema de clínica voltado para o gerenciamento de:

- Profissionais de saúde
- Clientes/pacientes
- Consultas agendadas

A aplicação foi construída com foco em simplicidade, usabilidade e adaptação para uma clínica pequena ou média.

## Tecnologias utilizadas

- PHP 8.1.x
- Laravel 10.x
- Node.js 18.x
- Blade templates
- Bootstrap / AdminLTE

## Funcionalidades principais

- Cadastro, edição e exclusão de profissionais
- Cadastro, edição e exclusão de clientes
- Agendamento e gerenciamento de consultas
- Autenticação de usuários
- Interface responsiva para administração

## Instalação local

1. Clone o repositório:

   `git clone https://github.com/seu-usuario/clinicas-ilha.git`

2. Entre na pasta do projeto:

   `cd clinicasIlha`

3. Instale as dependências PHP:

   `composer install`

4. Instale as dependências JavaScript:

   `npm install`

5. Configure o arquivo de ambiente:

   `cp .env.example .env`

6. Gere a chave do Laravel:

   `php artisan key:generate`

7. Configure o banco de dados no `.env` e execute as migrations:

   `php artisan migrate`

8. Inicie o servidor de desenvolvimento:

   `php artisan serve`

## Estrutura do projeto

- `app/` - Lógica principal do Laravel e controllers
- `database/` - Migrations e seeders
- `resources/` - Views, CSS e scripts JS
- `routes/` - Definições de rotas
- `public/` - Arquivos públicos e assets

## Sugestão de nome para o GitHub

- `clinicas-ilha`
- `ilha-clinicas`
- `ilha-clinic`
- `saude-ilha`

## Descrição recomendada para o GitHub

"Sistema de gerenciamento de clínica médica em Laravel, com cadastro de profissionais, clientes e agendamento de consultas. Construído para simplificar a rotina de clínicas pequenas e médias."

## Licença

Este projeto pode ser compartilhado e adaptado conforme necessário.
