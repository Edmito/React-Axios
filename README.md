# Projeto Iniciante com React e Axios

Este é um projeto iniciante que utiliza React e Axios para realizar requisições HTTP e exibir uma lista de posts com título e conteúdo. O projeto se conecta à API JSONPlaceholder (baseURL: 'https://jsonplaceholder.typicode.com') para obter os dados dos posts.

## Pré-requisitos

Antes de começar, certifique-se de ter o Node.js instalado em sua máquina. Você pode baixá-lo e instalá-lo a partir do [site oficial do Node.js](https://nodejs.org/).

## Configuração do Projeto

1. Clone este repositório para o seu computador ou faça o download como arquivo ZIP.

2. Abra o terminal e navegue até o diretório do projeto.

3. Instale as dependências do projeto executando o seguinte comando:

```bash
npm install
```

## Estrutura de Arquivos

A estrutura de arquivos do projeto é a seguinte:

- `package-lock.json` e `package.json`: Configurações e dependências do projeto.
- `src/`: Pasta que contém o código-fonte do projeto.
  - `App.css` e `App.jsx`: Componente principal do aplicativo.
  - `axios/config.js`: Configurações do Axios para a requisição HTTP.
  - `components/`: Pasta para componentes reutilizáveis.
    - `Navbar.css` e `Navbar.jsx`: Componente de barra de navegação.
  - `index.css` e `main.jsx`: Arquivos de entrada do aplicativo.
  - `routes/`: Pasta para os componentes das rotas.
    - `Home.css` e `Home.jsx`: Página principal que exibe a lista de posts.
    - `NewPost.css` e `NewPost.jsx`: Página para criar um novo post.
- `vite.config.js`: Configurações do Vite (bundler do projeto).

## Como Executar o Projeto

Após configurar o projeto e instalar as dependências, você pode executar a aplicação usando o seguinte comando:

```bash
npm run dev
```
Isso iniciará o servidor de desenvolvimento e abrirá a aplicação em seu navegador padrão.
