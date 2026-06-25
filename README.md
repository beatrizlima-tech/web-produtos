# 📦 Web Produtos

![Angular](https://img.shields.io/badge/Angular-21-DD0031?style=for-the-badge\&logo=angular)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge\&logo=typescript)
![REST API](https://img.shields.io/badge/API-REST-009688?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-lightgrey?style=for-the-badge)

---

# 📌 Sobre o projeto

O **Web Produtos** é uma aplicação frontend desenvolvida com **Angular 21** para gerenciamento de produtos, consumindo uma API REST desenvolvida em Java com Spring Boot.

A aplicação permite consultar produtos por nome, cadastrar novos produtos e excluir registros, exibindo os dados em uma interface responsiva com tabela, formulário e mensagens de retorno para o usuário.

Este projeto foi desenvolvido com foco no aprendizado de integração entre frontend Angular e backend REST.

---

# 🚀 Funcionalidades

* Consulta de produtos por nome
* Cadastro de novos produtos
* Exclusão de produtos
* Exibição dos produtos em tabela
* Cálculo e exibição do valor total por produto
* Mensagens de confirmação para o usuário
* Consumo de API REST utilizando HttpClient
* Interface responsiva
* Componentes Standalone

---

# 🧱 Tecnologias Utilizadas

* Angular 21
* TypeScript
* HTML5
* CSS3
* HttpClient
* REST API

---

# 🏗️ Estrutura do Projeto

```text
src/
├── app
│   ├── app.ts
│   ├── app.html
│   ├── app.css
│   ├── app.config.ts
│   └── app.routes.ts
│
├── main.ts
└── index.html
```

---

# 🔗 Integração com API

A aplicação realiza requisições HTTP para uma API responsável pelo gerenciamento de produtos.

## Endpoints consumidos

| Método | Endpoint                              | Descrição                   |
| ------ | ------------------------------------- | --------------------------- |
| GET    | `/api/v1/produtos/listar?nome={nome}` | Consulta produtos pelo nome |
| POST   | `/api/v1/produtos/criar`              | Cadastra um novo produto    |
| DELETE | `/api/v1/produtos/excluir/{id}`       | Exclui um produto           |

---

# ⚙️ Como Executar

## 1. Clone o repositório

```bash
git clone https://github.com/beatrizlima-tech/web-produtos.git
```

## 2. Acesse a pasta do projeto

```bash
cd web-produtos
```

## 3. Instale as dependências

```bash
npm install
```

## 4. Execute a aplicação

```bash
ng serve
```

## 5. Acesse no navegador

```text
http://localhost:4200
```

> Certifique-se de que a API de produtos esteja em execução em `http://localhost:8081`.

---

# 📊 Arquitetura

```text
Angular
    │
    ▼
HttpClient
    │
    ▼
API REST Produtos
    │
    ▼
PostgreSQL
```

---

# 📚 Conceitos Aplicados

* Componentes Standalone
* Signals
* Data Binding
* Event Binding
* Diretivas estruturais do Angular
* Consumo de APIs REST
* HttpClient
* Integração Frontend e Backend
* Organização de interface responsiva

---

# 📌 Melhorias Futuras

* Edição de produtos
* Validação de campos do formulário
* Reactive Forms
* Paginação de resultados
* Filtros avançados
* Tratamento de erros mais detalhado

---

# 👩‍💻 Autora

Desenvolvido por **Beatriz Lima**

🔗 GitHub
https://github.com/beatrizlima-tech

💼 LinkedIn
https://www.linkedin.com/in/beatrizlima-tech
