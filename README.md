# Santander Dev Week 2023 Java API

package com.exemplo.santander;

# 🚀 Santander Dev Week 2023 – Java API

Projeto desenvolvido como parte da **Santander Dev Week 2023**, utilizando o ecossistema **Java + Spring Boot**, com foco na construção e aprendizagem sobre o que é uma API REST e como usar para simular os dados de um aplicativo bancário.

---

## 🧠 Sobre o Projeto

Esta aplicação representa um backend que permite a **gestão de usuários, contas, cartões, funcionalidades e notícias**. A API foi construída com boas práticas de desenvolvimento, utilizando **POO**, **camadas de serviço**, e **persistência de dados com JPA/Hibernate**.

---

## 🛠️ Tecnologias e Ferramentas

- **Java 17**
- **Spring Boot**
- **Spring Data JPA**
- **dados com JPA/Hibernate**
---

## 📦 Estrutura da API

### Entidades principais:

- `Usuario` – Representa o cliente bancário  
- `Conta` – Informações bancárias (número, agência, saldo, limite)  
- `Cartao` – Dados do cartão e limite de crédito  
- `Funcionalidade` – Funcionalidades disponíveis para o usuário  
- `Noticia` – Notícias e informações financeiras

---

## 🔄 Endpoints REST

| Método | Endpoint           | Descrição                        |
|--------|--------------------|----------------------------------|
| GET    | `/usuarios`        | Lista todos os usuários          |
| GET    | `/usuarios/{id}`   | Retorna um usuário por ID        |
| POST   | `/usuarios`        | Cria um novo usuário             |
| DELETE | `/usuarios/{id}`   | Remove um usuário existente      |

---
