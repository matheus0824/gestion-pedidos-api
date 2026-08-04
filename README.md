# Gestion Pedidos - API REST

API RESTful para gerenciamento de produtos e pedidos, desenvolvida em **Java** utilizando o framework **Spring Boot**.

---

## Sobre a Aplicação

A aplicação foi criada com o objetivo de disponibilizar endpoints para o cadastro, consulta, atualização e remoção (CRUD) de produtos e pedidos, utilizando um banco de dados em memória para rápida execução e testes.

---

## Tecnologias Utilizadas

- **Java**
- **Spring Boot**
- **Spring Data JPA**
- **H2 Database** (Banco de dados em memória)
- **Maven**

---

## Como Executar a Aplicação

1. Clone o repositório ou baixe o projeto.
2. Abra o terminal na pasta raiz do projeto.
3. Execute o comando:

   - **Windows:**
     ```powershell
     .\mvnw.cmd spring-boot:run
     ```
   - **Linux / Mac:**
     ```bash
     ./mvnw spring-boot:run
     ```

4. A aplicação estará rodando em: `http://localhost:8080`

---

## Principais Endpoints

- `GET /api/produtos` - Lista todos os produtos
- `GET /api/produtos/{id}` - Busca um produto pelo ID
- `POST /api/produtos` - Cadastra um novo produto
- `PUT /api/produtos/{id}` - Atualiza um produto existente
- `DELETE /api/produtos/{id}` - Remove um produto

---

## Console do Banco H2

Para visualizar os dados no navegador:
- **URL:** `http://localhost:8080/h2-console`
- **JDBC URL:** `jdbc:h2:mem:testdb`
- **User:** `sa`
- **Password:** *(deixe vazio)*
