# MovieFlix

MovieFlix é um projeto estilo **clone da Netflix**, desenvolvido em Angular. Ele oferece uma interface moderna para **login, cadastro e visualização de filmes**, com componentes bem organizados entre usuários autenticados (**Logged**) e não autenticados (**NotLogged**).

## Tecnologias Usadas
- Angular 15+
- Angular CLI 19.2.6
- TypeScript
- HTML/CSS
- Componentização


## Estrutura do Projeto
 ```
src/
├── app/
│   ├── components/
│   │   ├── logged/
│   │   │   ├── card/
│   │   │   ├── create-movie-modal/
│   │   │   └── header/
│   │   └── not-logged/
│   │       ├── header/
│   │       ├── sign-in/
│   │       └── sign-up/
│   └── pages/
│       ├── logged/
│       │   └── home/
│       └── not-logged/
│           ├── home/          # Página de Login
│           └── registration/  # Página de Cadastro
```

## Funcionalidades

### NotLogged

- `Home`: página de login.
- `Registration`: página de cadastro.
- Componentes auxiliares:
  - `SignIn`
  - `SignUp`
  - `Header`

### Logged

- `Home`: onde os filmes aparecem.
- Componentes:
  - `Card`: exibe o filme.
  - `CreateMovieModal`: modal para adicionar novos filmes.
  - `Header`: barra de navegação presente em todas as páginas.


## Como rodar o projeto

### 1. Clonar o repositório

```
git clone https://github.com/seu-usuario/movieflix.git
cd movieflix
```

### 2. Instalar as dependências
`npm install`

### 3. Iniciar o servidor de desenvolvimento
`ng serve`

#### Acesse no navegador:
#### http://localhost:4200/
#### A aplicação será recarregada automaticamente sempre que você salvar alguma alteração nos arquivos fonte.

### Comandos Úteis do Angular CLI

#### Criar novo componente
`ng generate component nome-do-componente`

#### Ver todos os comandos disponíveis
`ng generate --help`

#### Compilar o projeto
`ng build`
