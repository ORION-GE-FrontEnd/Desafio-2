# Desafio 2: The Task & Cart Challenge

## Este repositório contém o resultado de um desafio do nosso Grupo de Estudo de Frontend, onde fomos desafiados a criar duas aplicações distintas: um To-Do App simples e um E-commerce funcional. Ambas as aplicações têm como objetivo praticar e aplicar conceitos de React, APIs, gerenciamento de estado e design responsivo.

---

## 🚀 **Diretrizes do Desafio**

Para garantir a organização do trabalho e a colaboração eficiente entre os membros do grupo, pedimos que sigam as seguintes diretrizes:

### 1. **Criação de Branches**
Cada tarefa ou feature deve ser desenvolvida em uma branch separada com o seguinte padrão de nomenclatura:

**Formato da branch:**  
`ge-frontend/nome1-nome2`

**Exemplo:**  
`ge-frontend/joao-silva-maria-santos`  

- Cada parte do nome da branch após a `/` representa o nome do membro que está desenvolvendo.
- Esta será a feature branch, poderá ser criada outras branchs a partis desta seguindo um padrão `ge-frontend/nome1-feature` exemplo `ge-frontend/joao-silva-add-cart-product`

Este modelo ajudará na abertura de PRs, onde o companheiro irá analisar o código e aprovar ou não, com comentários.

### 2. **Estrutura do Repositório**
O repositório deve ser organizado de forma clara e funcional. A estrutura sugerida é a seguinte:

/root
/ge-frontend
/nome1-nome2
/todo-app
/ecommerce
README.md


- A pasta `ge-frontend` deve conter todas as branches de trabalho dos membros, sendo cada subpasta a feature ou tarefa desenvolvida por um membro.
- Dentro de cada subpasta, a estrutura do código deve ser mantida conforme a organização de cada aplicação (To-Do App ou E-commerce).
  - **To-Do App:** 
    - A estrutura do To-Do App deve estar dentro da pasta `todo-app`.
  - **E-commerce:**
    - A estrutura do E-commerce deve estar dentro da pasta `ecommerce`.

### 3. **Padrões de Commit**
- Sempre use mensagens de commit **descritivas** e **clara** sobre o que foi alterado ou implementado.
  
**Exemplo de boas mensagens de commit:**
- `feat: adiciona funcionalidade de adicionar tarefas no To-Do App`
- `fix: corrige erro ao remover item do carrinho de compras no E-commerce`

**Exemplo de mensagens de commit inadequadas:**
- `Atualização`
- `Corrigido`

### 4. **Documentação**
A documentação do projeto, como instruções de configuração e execução, deve ser mantida no arquivo `README.md` na raiz do repositório. O arquivo `README.md` de cada aplicação também pode conter informações específicas sobre como rodar e testar o app individualmente.

---

## 🛠 **Tecnologias e Ferramentas**

Este desafio visa praticar os seguintes conceitos e ferramentas:

- **React**: para desenvolvimento das interfaces.
- **React Router**: para gerenciamento de rotas.
- **Axios**: para realizar requisições HTTP à API (para o To-Do App e E-commerce).
- **Context API/Redux**: para gerenciamento de estado no React.
- **CSS/Styled Components/Tailwind CSS**: para estilização das interfaces.
- **Responsividade**: Certifique-se de que o design seja responsivo para telas de diferentes tamanhos.
  
---

## 💡 **Requisitos de Testes**

- **To-Do App**:
  - Testar funcionalidades básicas como adicionar, editar, excluir e marcar tarefas como concluídas.
  - Testar a persistência dos dados (utilizando armazenamento local ou uma API simples).

- **E-commerce**:
  - Testar funcionalidades como adição de produtos ao carrinho, remoção de produtos, atualização de quantidade e finalização de pedido.
  - Testar integração com a API do backend (se necessário).
  - Testar o controle de estoque para garantir que o produto não possa ser comprado se não houver estoque suficiente.

---

## 📝 **Conclusão**
Este desafio tem como objetivo consolidar os conhecimentos adquiridos até agora e proporcionar uma experiência de desenvolvimento prático de aplicações reais. Ao seguir as diretrizes acima, garantimos um fluxo de trabalho organizado e eficiente, além de facilitar a colaboração entre os membros do grupo.

Boa sorte e divirta-se desenvolvendo! 👨‍💻🎨

