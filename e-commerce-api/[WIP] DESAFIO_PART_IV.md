#  Desafio Mobile - React Native e Desafio CI/CD

# 📱 Desafio Mobile - React Native

## 🎯 Objetivo Geral

Expandir o projeto existente de e-commerce com um **aplicativo mobile** usando **React Native com Expo**, focando em componentização, integração com GraphQL.

---

### 🎯 Objetivos Específicos

- Construir um app funcional com Expo.
- Reutilizar integrações com o BFF GraphQL já criado.

---

## 🔧 Tarefas

### 1. React Native com Expo

- Criar projeto com `npx create-expo-app` usando `TypeScript`.
- Utilizar:
  - Navegação com `react-navigation`
  - Gerenciamento de estado com Context API
  - Apollo Client para integração GraphQL
  - Componentes reutilizáveis e com boas práticas
  - Responsividade e acessibilidade

#### Módulos obrigatórios no app:

- Tela de listagem de produtos
- Tela de detalhe do produto
- Carrinho com quantidade e total
- Finalização de pedido (pode ser simulado)
- Autenticação integrada integrada com backend

---

### 2. Testes Automatizados
A aplicação deve ser testada automaticamente para assegurar seu funcionamento correto.


---

## ✅ Entregáveis

| Entrega                                    | Status esperado |
|--------------------------------------------|-----------------|
| App mobile com funcionalidades básicas de e-commerce         | ✅              |
| Integração com GraphQL do projeto Web           | ✅              |             |             |        |
| Testes automatizados           | ✅
| README completo e funcional                | ✅              |

---

## 📌 Critérios de Qualidade

✅ Boas práticas de arquitetura mobile  
✅ Componentização reutilizável  
✅ Código limpo e tipado  
✅ Integração estável com GraphQL  
✅ Documentação clara do processo

---

## 📚 Material Complementar

- [Guia Rocketseat - React Native](https://react-native.rocketseat.dev/)
- [Documentação do Expo](https://docs.expo.dev/)
- [Apollo Client Docs](https://www.apollographql.com/docs/react/)


---

# ⚙️ Desafio CI/CD

## 🎯 Objetivo

Implementar um pipeline completo de **CI/CD com GitHub Actions** para o projeto web do **Desafio 3**, contemplando todas as etapas necessárias para garantir a **entrega contínua com qualidade**., incluindo etapas de:

- Instalação de dependências
- Execução de lint para garantir qualidade do código
- Execução de testes automatizados para validar funcionalidades
- Build de produção
- Deploy automático para ambiente público (GitHub Pages, Netlify ou Vercel)

para a aplicação Web React + GraphQL já existente.

---

## ✅ Requisitos do Pipeline

| Etapa       | Descrição                                                               |
|-------------|-------------------------------------------------------------------------|
| Checkout    | Clonar o repositório                                                    |
| Install     | Instalar dependências                                                   |
| Lint        | Executar lint para garantir padronização e qualidade do código         |
| Test        | Executar testes automatizados com cobertura mínima                      |
| Build       | Gerar build de produção                                                 |
| Deploy      | Publicar build em ambiente de produção automaticamente após sucesso     |

---

## 🧪 Requisitos de Testes

- A aplicação **deve estar testada** com testes automatizados que validem seu funcionamento e estabilidade.
- Testes unitários e/ou de integração devem cobrir as principais funcionalidades.
- Os testes devem ser executados como parte do pipeline CI/CD e falhas devem impedir o deploy.

---

## 📌 Critérios de Avaliação

- Pipeline acionado automaticamente no push para a branch principal.
- Falhas em lint ou testes impedem a continuação do deploy.
- Deploy automático ocorre somente após build e testes bem-sucedidos.
- Documentação clara no README explicando o funcionamento da pipeline e como rodar testes localmente.
- Testes automatizados confiáveis cobrindo funcionalidades críticas da aplicação.

---

## 📄 Entregáveis

- Pipeline CI/CD configurado e funcional no repositório
- Testes automatizados implementados no projeto
- Deploy público acessível e atualizado automaticamente
- README atualizado com instruções claras de CI/CD e testes
