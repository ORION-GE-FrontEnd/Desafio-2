# 🛍️ Desafio Frontend — E-commerce com Autenticação, Estado Global e Experiência do Usuário

🔗 **Descrição da API e contexto do desafio (Parte I):**  
[https://github.com/ORION-GE-FrontEnd/Desafio-2/blob/main/e-commerce-api/DESAFIO_PART_I.md](https://github.com/ORION-GE-FrontEnd/Desafio-2/blob/main/e-commerce-api/DESAFIO_PART_I.md)

## 🎯 Objetivo

Desenvolver o frontend com autenticação para o sistema de e-commerce descrito anteriormente. O frontend deve consumir a API já criada,  **implementar autenticação de usuários na API**, usar gerenciamento de estado global com Redux e Context API (ou zustand) e aplicar testes automatizados (unitários e e2e). extra: aprimorar a experiência do usuário com feedbacks visuais e animações.

---

## ✅ Requisitos Obrigatórios

### 1. Autenticação

- Implementar autenticação de usuários na API.
- Criar uma tela de login simples com e-mail e senha.
- Após o login, armazenar o token (ou flag de login) no estado global.
- Utilizar estratégias de autenticação (ex: `localStorage`, cookies etc).
- Restringir o acesso às páginas principais apenas a usuários autenticados.

### 2. Gerenciamento de Estado Global

- Usar **Redux** para o estado do carrinho de compras.
- Usar **Context API** ou **Zustand** para gerenciar o estado do usuário logado (autenticação).

### 3. Fluxo de Usuário
Implementar as seguintes páginas com consumo real da API:


#### 📦 Catálogo de Produtos

- Listagem de produtos.
- Visualização de detalhes de um produto.

#### 🛒 Carrinho de Compras

- Adicionar/remover itens.
- Alterar quantidades.
- Exibir total.
- Iniciar processo de checkout.

#### 💳 Checkout e Pedido (Rotas autenticadas)

- Tela de checkout com formulário de endereço e pagamento (simulado, com validações).
- Confirmação do pedido.
- Exibição do resumo do pedido após o pagamento.

#### 👤 Área do Usuário (Rotas autenticadas)

- Visualizar pedidos feitos.
- Logout.

---

## 🧪 Testes

### ✅ Testes Unitários

Devem ser criados testes unitários com uma boa cobertura, e testando corner cases. 

### 🧪 Testes E2E

- Utilizar **Cypress** ou **Playwright** para testar os fluxos principais:

  - Login
  - Adicionar itens ao carrinho
  - Checkout
  - Confirmação do pedido

---

## 💅 Experiência do Usuário (UX/UI)

### 🎨 Feedbacks Visuais (Obrigatórios)

- Indicadores de loading (spinners, skeletons).
- Mensagens claras de erro e sucesso.
- Toasts para ações importantes.
- Tratar possíveis erros.

### 🎬 Animações (Extra)

- Adicionar animações pensando em experiência do usuário, evitando glitchs de layout, introdução de pop ups, etc..

---

## 📦 Tecnologias Sugeridas

- `React` (com `Vite`)
- `Redux Toolkit`
- `Context API` ou `Zustand`
- `React Router DOM`
- `Axios` ou `fetch` (livre escolha)
- UI Framework (livre escolha)
- `React Hook Form` ou `Formik` + `Zod` ou `Yup`
- `Cypress` ou `Playwright` (E2E)
- `Vitest`, `Jest` e `Testing Library` (unitários)

---

## 🚀 Deploy

- Realizar o deploy em plataformas como **Vercel**, **Netlify**, **Render** ou outra de sua escolha.

---

## 📋 Requisitos Extras (Desafio Estendido)

- Usar animações com `Framer Motion`, `CSS Animations`, `GSAP` ou `React Spring`.
- Criar temas claro/escuro com persistência.
- Criar layout responsivo e acessível.

---

## 📁 Entrega

- Link do repositório no **GitHub**.
- Link da aplicação publicada (Vercel, Netlify, etc).

### Documentação deve conter:

- Como rodar o projeto localmente.
- Lista de funcionalidades.
- Explicação das decisões de arquitetura (Redux vs Context, organização de pastas etc).
- Cobertura de testes (prints ou coverage report).

---

## 🧠 Dicas

- Comece pela estrutura de pastas e roteamento.
- Use `Redux Toolkit` com slices bem organizados.
- Evite overengineering — use Context/Zustand onde for mais simples.
- Valide formulários com `Zod` ou `Yup` para uma boa DX.
- Mantenha componentes pequenos e reutilizáveis.
- Invista nos testes e pense como um usuário final nos E2E.

