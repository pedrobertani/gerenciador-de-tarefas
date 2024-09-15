# Gerenciador de Tarefas (Frontend)

Este é um projeto front-end para gerenciar tarefas de usuários, construído com Angular. O sistema possui as seguintes funcionalidades:

- **Listagem de Usuários**: Exibe uma lista de usuários mockados.
- **Visualização de Tarefas**: Ao selecionar um usuário, são exibidas suas tarefas mockadas.
- **Adicionar Tarefas**: Permite adicionar novas tarefas a um usuário selecionado.

## Tecnologias Utilizadas
- **Framework**: Angular
- **Mock**: Dados de usuários e tarefas são mockados utilizando serviços internos.

## Estrutura do Projeto
- **src/app/components/header/**: Componente para exibir o cabeçalho
- **src/app/components/tasks/**: Componente para exibir as tarefas do usuário selecionado.
- **src/app/components/tasks/task**: Componente para adicionar novas tarefas.
- **src/app/models/**: Modelos TypeScript para usuários e tarefas.
- **src/app/services/**: Serviços Angular para fornecer dados mockados.
