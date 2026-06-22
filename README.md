# 🛍️ Web Produtos

<p align="center">
  Aplicação Front-End desenvolvida com Angular 21 para gerenciamento de produtos, integrada a uma API REST hospedada na Microsoft Azure.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Angular-21-red" />
  <img src="https://img.shields.io/badge/TypeScript-Latest-blue" />
  <img src="https://img.shields.io/badge/Bootstrap-5-purple" />
  <img src="https://img.shields.io/badge/API-REST-green" />
  <img src="https://img.shields.io/badge/Azure-Cloud-0078D4" />
</p>

---

## 📖 Sobre o Projeto

O **Web Produtos** é uma aplicação SPA (Single Page Application) desenvolvida em Angular para gerenciamento de produtos.

A aplicação realiza integração com uma API REST publicada na Microsoft Azure, permitindo operações completas de cadastro, consulta, atualização e exclusão de produtos através de uma interface moderna e responsiva.

Este projeto foi desenvolvido com foco em boas práticas de desenvolvimento Front-End, componentização, integração HTTP e consumo de APIs.

---

## 🚀 Funcionalidades

### 📋 Consulta de Produtos

* Listagem dinâmica dos produtos cadastrados
* Atualização automática após operações

### ➕ Cadastro

* Inclusão de novos produtos
* Validação de campos obrigatórios

### ✏️ Atualização

* Edição de registros existentes
* Carregamento automático dos dados selecionados

### 🗑️ Exclusão

* Remoção de produtos cadastrados
* Confirmação antes da exclusão

### 🌐 Integração com API

* Comunicação via HttpClient
* Consumo de endpoints REST
* Operações assíncronas

---

## 🏗️ Arquitetura

```text
Angular 21
    │
    ▼
HttpClient
    │
    ▼
REST API
    │
    ▼
Microsoft Azure
```

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia        | Finalidade                      |
| ----------------- | ------------------------------- |
| Angular 21        | Framework Front-End             |
| TypeScript        | Linguagem principal             |
| Bootstrap 5       | Interface responsiva            |
| Reactive Forms    | Formulários e validações        |
| Signals           | Gerenciamento reativo de estado |
| HttpClient        | Comunicação com API             |
| Azure App Service | Hospedagem da API               |

---

## 📂 Estrutura do Projeto

```text
src
│
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

## 🔗 API Consumida

A aplicação consome uma API REST responsável pelo gerenciamento dos produtos.

### Endpoints

| Método | Endpoint              | Descrição         |
| ------ | --------------------- | ----------------- |
| GET    | /api/v1/produtos      | Listar produtos   |
| GET    | /api/v1/produtos/{id} | Obter produto     |
| POST   | /api/v1/produtos      | Cadastrar produto |
| PUT    | /api/v1/produtos/{id} | Atualizar produto |
| DELETE | /api/v1/produtos/{id} | Excluir produto   |

---

## ▶️ Executando o Projeto

### Clonar o repositório

```bash
git clone https://github.com/beatrizlima-tech/web-produtos.git
```

### Entrar na pasta

```bash
cd web-produtos
```

### Instalar dependências

```bash
npm install
```

### Executar

```bash
ng serve
```

Acesse:

```text
http://localhost:4200
```

---

## 💡 Conceitos Aplicados

* Componentização
* CRUD
* Consumo de API REST
* Reactive Forms
* Signals
* TypeScript
* Responsividade
* Integração Front-End e Back-End
* Deploy em Nuvem

---

## 👩‍💻 Desenvolvedora

**Beatriz Lima**

Desenvolvedora Java Full Stack em formação, com foco em Java, Spring Boot, Angular, APIs REST e aplicações em nuvem.
