# 🛍️ Web Produtos

Aplicação web desenvolvida com **Angular 21** para gerenciamento de produtos, consumindo uma API REST hospedada na **Microsoft Azure**.

O sistema permite realizar operações completas de **CRUD (Create, Read, Update e Delete)** através de uma interface moderna, responsiva e intuitiva.

---

## 🚀 Funcionalidades

* ✅ Cadastro de produtos
* ✅ Consulta de produtos
* ✅ Atualização de produtos
* ✅ Exclusão de produtos
* ✅ Consumo de API REST com HttpClient
* ✅ Formulários reativos com validações
* ✅ Interface responsiva utilizando Bootstrap
* ✅ Atualização dinâmica da listagem

---

## 🛠️ Tecnologias Utilizadas

* Angular 21
* TypeScript
* Bootstrap 5
* HttpClient
* Reactive Forms
* Signals
* REST API
* Microsoft Azure

---

## 📂 Estrutura do Projeto

```text
src
 ├── app
 │   ├── app.ts
 │   ├── app.html
 │   ├── app.css
 │   ├── app.config.ts
 │   └── app.routes.ts
 ├── main.ts
 └── index.html
```

---

## 🔗 Integração com API

A aplicação consome uma API REST hospedada na Azure:

```text
/api/v1/produtos
```

Operações disponíveis:

| Método | Endpoint       | Descrição         |
| ------ | -------------- | ----------------- |
| GET    | /produtos      | Listar produtos   |
| GET    | /produtos/{id} | Consultar produto |
| POST   | /produtos      | Cadastrar produto |
| PUT    | /produtos/{id} | Atualizar produto |
| DELETE | /produtos/{id} | Excluir produto   |

---

## 📸 Funcionalidades da Interface

### Cadastro

Permite registrar novos produtos informando:

* Nome
* Preço
* Quantidade

### Consulta

Exibe todos os produtos cadastrados em uma tabela dinâmica.

### Edição

Atualiza informações de produtos existentes.

### Exclusão

Remove produtos cadastrados mediante confirmação.

---

## ▶️ Como executar

### Clonar o projeto

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

### Executar aplicação

```bash
ng serve
```

Acesse:

```text
http://localhost:4200
```

---

## 👩‍💻 Desenvolvedora

Beatriz Lima

Projeto desenvolvido para prática de desenvolvimento Front-End com Angular e integração com APIs REST.
