# 📝 Fórum Hub

Projeto desenvolvido durante o programa **Oracle Next Education (ONE)** em parceria com a **Alura**.  
O objetivo foi criar uma **API REST** com **Java + Spring Boot**, aplicando boas práticas de desenvolvimento back-end.

---

## 🚀 Funcionalidades
- CRUD de usuários 👤  
- Criação e listagem de tópicos 🗂️  
- Comentários em tópicos 💬  
- Autenticação e controle de acesso 🔑  

---

## 🛠️ Tecnologias
- Java 17  
- Spring Boot + Spring Security  
- JPA / Hibernate  
- MySQL  
- Lombok  
- Maven  

---

## ⚙️ Como Rodar
1. Crie o banco no MySQL:
   ```sql
   CREATE DATABASE forum_hub_db;
   ```
2. Configure o ```application.properties``` com usuário e senha.
3. Rode a aplicação:
  ```
  mvn spring-boot:run
  ```
## 🔗 Endpoints Principais
- POST /usuarios → Cadastrar usuário
- GET /usuarios → Listar usuários
- POST /topicos → Criar tópico
- GET /topicos → Listar tópicos
- POST /comentarios → Comentar em tópico

## Créditos
Este projeto foi proposto como desafio pelo programa:
- Programa Oracle Next Education (ONE)
- Alura - Cursos de tecnologia

### 👩‍💻 Desenvolvido por Iasmin Oliveira

