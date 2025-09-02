# API de Tarefas - O Backend do seu Full-Stack

Este projeto é a espinha dorsal de um sistema completo de gerenciamento de tarefas. Trata-se de uma API RESTful robusta, construída para centralizar toda a lógica de negócio e o acesso aos dados, servindo como o cérebro por trás de duas interfaces de usuário distintas: uma aplicação web e uma aplicação desktop.

---

### Arquitetura da Solução

O projeto é dividido em três repositórios independentes que se comunicam via API REST, seguindo uma arquitetura de microsserviços desacoplada.

1.  **Backend (Este Repositório):**
    * API central construída com **Java** e **Spring Boot**.
    * Gerencia todas as operações **CRUD** (Criar, Ler, Atualizar, Deletar).
    * Utiliza um banco de dados em memória **H2** para facilitar o desenvolvimento.

2.  **Frontend Web:**
    * Cliente web moderno construído com **Angular**.
    * **Link para o repositório:** ``

3.  **Frontend Desktop:**
    * Cliente desktop nativo construído com **JavaFX**.
    * **Link para o repositório:** ``

---

### Tecnologias Utilizadas

* Java 21
* Spring Boot 3
* Spring Data JPA
* Maven
* H2 Database

---

### Como Executar

**Pré-requisitos:** Ter o JDK 21 instalado.

1.  **Clone este repositório:**
    ```bash
    git clone [https://github.com/Vitor-gomes919/listadetarefas-API.git]
    ```

2.  **Abra o projeto em sua IDE** (VS Code, IntelliJ, etc.).

3.  **Execute a classe principal** `ListaTarefasApiApplication.java`.
    * **Caso esteja no VS Code:** instale a extensão 'Spring Boot Dashboard', clique no ícone da extensão e execute 'lista-tarefa-api'.

A API estará rodando em `http://localhost:8080`.

---

### Endpoints da API

| Método | URL | Descrição |
| :--- | :--- | :--- |
| **GET** | `/api/tarefas` | Lista todas as tarefas. |
| **POST** | `/api/tarefas` | Cria uma nova tarefa. |
| **PUT** | `/api/tarefas/{id}` | Atualiza uma tarefa existente. |
| **DELETE** | `/api/tarefas/{id}` | Deleta uma tarefa. |

---

### Autor

**Vitor Hugo Gomes Gouveia**
