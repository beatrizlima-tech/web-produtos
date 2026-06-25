# 📦 Web Produtos

![Angular](https://img.shields.io/badge/Angular-21-DD0031?style=for-the-badge\&logo=angular)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge\&logo=typescript)
![REST API](https://img.shields.io/badge/API-REST-009688?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-lightgrey?style=for-the-badge)

---

# 📌 Sobre o projeto

O **Web Produtos** é uma aplicação frontend desenvolvida com **Angular 21** para consulta de produtos através do consumo de uma API REST.

A aplicação oferece uma interface simples para pesquisa de produtos por nome, utilizando **HttpClient** para comunicação com o backend e apresentando uma estrutura baseada em componentes standalone.

Este projeto foi desenvolvido com foco no aprendizado de integração entre aplicações Angular e APIs REST.

---

# 🚀 Funcionalidades

* Consulta de produtos por nome
* Consumo de API REST utilizando HttpClient
* Interface responsiva
* Componentes Standalone
* Comunicação assíncrona com backend

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

### Endpoint consumido

| Método | Endpoint                              | Descrição                   |
| ------ | ------------------------------------- | --------------------------- |
| GET    | `/api/v1/produtos/listar?nome={nome}` | Consulta produtos pelo nome |

---

# ⚙️ Como Executar

## 1. Clone o repositório

```bash
git clone https://github.com/beatrizlima-tech/web-produto.git
```

## 2. Instale as dependências

```bash
npm install
```

## 3. Execute a aplicação

```bash
ng serve
```

## 4. Acesse

```text
http://localhost:4200
```

> Certifique-se de que a API de produtos esteja em execução para que a consulta funcione corretamente.

---

# 📊 Arquitetura

```text
Angular
    │
    ▼
HttpClient
    │
    ▼
API REST
```

---

# 📚 Conceitos Aplicados

* Componentes Standalone
* Programação Reativa
* Consumo de APIs REST
* HttpClient
* TypeScript
* Organização de componentes
* Integração Frontend e Backend

---

# 📌 Melhorias Futuras

* Cadastro de produtos
* Atualização de produtos
* Exclusão de produtos
* Exibição dos resultados em tabela
* Reactive Forms
* Feedback visual para o usuário
* Paginação e filtros

---

# 👩‍💻 Autora

Desenvolvido por **Beatriz Lima**

🔗 GitHub
https://github.com/beatrizlima-tech

💼 LinkedIn
https://www.linkedin.com/in/beatrizlima-tech
