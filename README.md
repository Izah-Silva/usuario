# 👤 API de Usuários - Spring Boot

Projeto desenvolvido com **Spring Boot** com o objetivo de praticar a construção de uma API REST para gerenciamento de usuários.

Este repositório faz parte da minha jornada de transição e evolução como desenvolvedora backend.

---

## 🚀 Objetivo

* Praticar desenvolvimento de APIs REST com Java
* Aplicar conceitos de arquitetura em camadas
* Trabalhar com persistência de dados
* Simular cenários reais de backend

---

## 🛠️ Tecnologias utilizadas

* Java
* Spring Boot
* Spring Web
* Spring Data JPA
* Banco de dados (H2 / PostgreSQL)
* Maven ou Gradle

---

## 📂 Estrutura do projeto

O projeto segue o padrão de arquitetura em camadas:

```
src/main/java
└── com.seuprojeto.usuario
    ├── controller   → Camada de entrada (endpoints REST)
    ├── service      → Regras de negócio
    ├── repository   → Acesso a dados (JPA)
    ├── entity       → Representação da tabela no banco
    └── dto          → Objetos de transferência de dados
```

---

## 🔗 Endpoints principais

| Método | Endpoint       | Descrição            |
| ------ | -------------- | -------------------- |
| GET    | /usuarios      | Lista todos usuários |
| GET    | /usuarios/{id} | Busca usuário por ID |
| POST   | /usuarios      | Cria novo usuário    |
| PUT    | /usuarios/{id} | Atualiza usuário     |
| DELETE | /usuarios/{id} | Remove usuário       |

---

## ▶️ Como rodar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/Izah-Silva/usuario.git
```

### 2. Entrar na pasta

```bash
cd usuario
```

### 3. Rodar a aplicação

Se estiver usando Maven:

```bash
./mvnw spring-boot:run
```

Ou pelo IntelliJ:

* Rodar a classe principal (`@SpringBootApplication`)

---

## 🧪 Como testar

Você pode testar os endpoints utilizando:

* Postman
* Insomnia

Exemplo de requisição:

```http
POST /usuarios
Content-Type: application/json

{
  "nome": "Izabela",
  "email": "izabela@email.com"
}
```

---

## 📚 Aprendizados

Neste projeto estou praticando:

* Criação de APIs RESTful
* Injeção de dependência (IoC)
* Organização em camadas
* Uso do Spring Data JPA
* Boas práticas de backend

---

## 📌 Próximos passos

* [ ] Validações com Bean Validation
* [ ] Tratamento de exceções global
* [ ] Autenticação com JWT
* [ ] Testes unitários
* [ ] Documentação com Swagger

---

## 👩‍💻 Autora

Desenvolvido por **Izabela Silva** 🚀
Em transição para Engenharia de Software Backend

---

## ⭐ Observação

Este projeto faz parte de estudos e evolução contínua.
Feedbacks são muito bem-vindos!
