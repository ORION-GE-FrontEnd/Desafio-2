# 📝 Exercício: To-Do App em React

## 🎯 Objetivo

Criar um simples **To-Do App em React** que permita ao usuário **gerenciar suas tarefas** de forma prática e eficiente.

---

## ✅ Funcionalidades Principais

- **Criar**: Adicionar novas tarefas.
- **Editar**: Modificar o título ou a descrição de uma tarefa existente.
- **Deletar**: Remover tarefas.
- **Marcar como feito**: Marcar tarefas como concluídas.
- **Indicativo de tarefa concluída**:
  - Exibir um **ícone visual (check ou similar)**.
  - Diferenciar visualmente as tarefas **pendentes** das **concluídas**.
- **Confirmação de alterações**:
  - Sempre perguntar ao usuário se ele tem certeza antes de editar, excluir ou marcar como feito.

---

## 📄 Estrutura JSON das Tarefas

```json
{
  "todos": [
    {
      "id": 1,
      "title": "Estudar React",
      "description": "Revisar os conceitos principais do React e praticar os hooks.",
      "completed": false
    },
    {
      "id": 2,
      "title": "Comprar leite",
      "description": "Ir ao mercado comprar leite, pão e ovos.",
      "completed": true
    },
    {
      "id": 3,
      "title": "Ler documentação do React",
      "description": "Ler a documentação oficial do React para entender os conceitos de renderização.",
      "completed": false
    },
    {
      "id": 4,
      "title": "Fazer exercício",
      "description": "Fazer 30 minutos de corrida ou caminhada.",
      "completed": true
    }
  ]
}
