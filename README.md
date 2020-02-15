<h1 align="center">
    <img alt="GoStack" src="https://rocketseat-cdn.s3-sa-east-1.amazonaws.com/bootcamp-header.png" width="200px" />
</h1>

<h3 align="center">
  GoBarber
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/rocketseat/bootcamp-gostack-desafio-01?color=%2304D361">

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
</p>

<p align="center">
  <a href="#rocket-sobre-o-projeto">Sobre o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#executando-localmente">Executando localmente</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :rocket: Sobre o projeto

O **GoBarber** é uma plataforma de agendamento de serviços de beleza para barbearias e salões de beleza, desenvolvida em **NodeJS**, **ReactJS** e **React Native**, durante o Bootcamp GoStack da Rocketseat.

## Tecnologias

- **Express** - Micro-framework que acelera o desenvolvimento em NodeJS;
- **Insomnia** - Ferramenta utilizada para testar APIs;
- **PostgreSQL** - Banco de dados SQL;
- **Docker** - Criação de ambientes isolados (contêineres);
- **Sequelize** - ORM que permite a abstração do banco de dados, possibilitando o uso do JavaScript para montá-lo e acessá-lo;
- **JWT** - Biblioteca de tokens que auxilia na validação e autenticação de usuários;
- **Bcrypt** - Criptografia de senhas;
- **Yup** - Validação dos dados vindos das requisições;
- **Sucrase** - Biblioteca que possibilita a utilização da sintaxe de import/export no JavaScript;
- **ESLint, Prettier e EditorConfig** - Ferramentas que auxiliam na padronização do código. 

## Executando Localmente

Para executar localmente, serão necessárias as seguintes ferramentas:
- Docker
- Yarn
- Node

1. Vá para o diretório one você quer que esse repositório fique;
2. Clone o repositório:
```
git clone https://github.com/Zardosh/backend-gobarber
```
3. Vá para o diretório do repositório;
4. Baixe as dependências:
```
yarn
```
5. Crie um banco de dados PostgreSQL usando o Docker;
6. Edite as configurações de autenticação e banco de dados na pasta "src/config/" e renomeie os arquivos como indicado nos mesmos;
7. Execute as migrations:
```
yarn sequelize db:migrate
```
8. Inicie o projeto:
```
yarn dev
```
9. Pronto! Agora é só acessar as rotas no endereço "localhost:3333/[rota]".

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
