# 🚀 Desafio de Refatoração e Arquitetura: TypeScript + BFF GraphQL

## 🎯 Objetivo Geral
Evoluir o projeto atual de e-commerce, focando em boas práticas de arquitetura e tecnologia moderna. O desafio será dividido em duas partes:

1️⃣ **Refatoração total para TypeScript (Backend e Frontend)**  
2️⃣ **Criação de um BFF GraphQL para centralizar regras de negócio**

O objetivo final é que o frontend se torne completamente "dumb", consumindo dados apenas do BFF e deixando a lógica no backend.

---

## 🟦 Parte 1: Refatorar para TypeScript

### 🎯 Objetivo
- Tipar todo o código existente.
- Eliminar `any` do projeto.
- Organizar as tipagens de forma clara e sustentável.

### 🔧 Tarefas

#### Backend (API REST)
- Configurar TypeScript (`tsconfig.json`).
- Tipar rotas, controllers, services e models.
- Usar `types/interfaces` para dados trafegados.

#### Frontend (React)
- Configurar TypeScript no projeto React.
- Tipar:
  - Componentes
  - Props
  - Hooks personalizados
  - Stores (Redux, Zustand, Context API)
- Configurar `eslint/prettier` para TypeScript.

### ✅ Entregáveis
- Backend 100% refatorado e tipado.
- Frontend 100% refatorado e tipado.
- Sem `any`.

---

## 🟦 Parte 2: Criar BFF GraphQL e Desacoplar o Frontend

### 🎯 Objetivo
- Criar um Backend for Frontend (BFF) usando GraphQL.
- Transferir todas as regras de negócio para o BFF.
- Tornar o Frontend uma aplicação "burra", apenas exibindo dados.

### 🔧 Tarefas

#### Backend (BFF - GraphQL)
- Criar projeto com Node.js + Express + Apollo Server.
- Criar Schema GraphQL (Queries e Mutations) para:
  - Produtos
  - Carrinho
  - Pedidos
  - Usuários / Login
- Implementar Resolvers que integrem a API REST atual ou banco de dados.
- Organizar a camada de serviços separando regras de negócio.

#### Frontend (React + GraphQL)
- Configurar Apollo Client ou urql.
- Consumir todos os dados via GraphQL.
- Remover qualquer regra de negócio do Frontend.

### ✅ Entregáveis
- BFF funcionando, centralizando todas as regras de negócio.
- Frontend consumindo exclusivamente GraphQL.
- Componentes React “dumb”: recebem dados e exibem.
- Zero fetch/axios direto no Frontend.

---

## 🏁 Resultado Esperado

| Entrega                           | Status esperado |
|-----------------------------------|-----------------|
| Backend refatorado para TS         | ✅              |
| Frontend refatorado para TS        | ✅              |
| BFF GraphQL criado e funcional     | ✅              |
| Frontend consumindo só GraphQL     | ✅              |
| Código limpo e desacoplado         | ✅              |

---

## 📌 Critérios de Qualidade
✅ Zero `any`  
✅ Tipagem forte e clara  
✅ Lógica isolada no backend (não no frontend)  
✅ GraphQL com Queries, Mutations e Schema bem definidos  
✅ Código limpo, modular e sustentável  
