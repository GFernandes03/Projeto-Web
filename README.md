# Projeto Web

E-commerce simples desenvolvido para a disciplina de **Programação Web**.

## Funcionalidades

- Cadastro e login de usuários
- Autenticação
- Carrinho de compras
- Área de administrador: adicionar e remover produtos

## Tecnologias

- [Node.js](https://nodejs.org/)
- [AdonisJS](https://adonisjs.com/)
- TypeScript
- Edge (templates)
- Tailwind CSS
- Vite

## Estrutura do projeto

```
.
├── app/         # Controllers, models e lógica da aplicação
├── bin/         # Arquivos de inicialização do servidor
├── config/      # Configurações do projeto
├── database/    # Migrations e seeders
├── public/      # Arquivos estáticos
├── resources/   # Views (Edge), CSS e JS do front-end
├── start/       # Rotas e arquivos de boot
└── tests/       # Testes
```

## Como executar

### Pré-requisitos

- [Node.js](https://nodejs.org/) instalado
- Banco de dados configurado

### Passo a passo

1. Clone o repositório e entre na pasta:

```bash
git clone https://github.com/GFernandes03/Projeto-Web.git
cd Projeto-Web
```

2. Instale as dependências:

```bash
npm install
```

3. Crie o arquivo de variáveis de ambiente e preencha com as suas configurações (banco de dados, etc.):

```bash
cp .env.example .env
```

4. Gere a chave da aplicação:

```bash
node ace generate:key
```

5. Rode as migrations para criar as tabelas:

```bash
node ace migration:run
```

6. Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

A aplicação ficará disponível em `http://localhost:3333`.

## Autor

**Guilherme Fernandes**

Estudante de Ciência da Computação na UFRRJ.
