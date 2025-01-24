# Sistema de Quiz de Programação

## Introdução

Este documento apresenta os requisitos para o desenvolvimento de um sistema de quiz sobre programação utilizando tecnologias fullstack. O projeto será composto por um frontend desenvolvido em *React*, um backend em *Node.js* e um banco de dados à escolha do candidato. O prazo de entrega do projeto é de **5 dias**, e o objetivo é avaliar as habilidades do candidato no desenvolvimento de uma aplicação completa, com foco na simplicidade e funcionalidade.

---

## Escopo do Projeto

O sistema de quiz deve permitir que usuários realizem as seguintes ações:

1. Responder perguntas de um quiz sobre programação.
2. Visualizar seu desempenho ao final do quiz.

---

## Funcionalidades

### 1. Quiz de Programação

- O sistema deve disponibilizar perguntas com as seguintes características:
  - Pergunta (texto).
  - Quatro alternativas de resposta.
  - Indicação de qual alternativa é correta, após interação do usuário.
- As perguntas podem ser cadastradas diretamente no banco de dados (não é necessário implementar CRUD de perguntas).
- O quiz deve ser composto por no mínimo 5 perguntas.

### 2. Resolução do Quiz

- Usuários devem poder iniciar o quiz.
- Após responder todas as perguntas, o sistema deve calcular e exibir:
  - Total de questões respondidas.
  - Número de acertos.
  - Percentual de acertos.

### 3. Backend

- O backend deve ser implementado em Node.js.
- Deve expor uma API RESTful com as seguintes rotas:
  - **/quiz**:
    - **GET**: Obter perguntas do quiz.
    - **POST**: Submeter respostas e calcular o desempenho.

### 4. Frontend

- O frontend deve ser implementado em React.
- Funcionalidades esperadas:
  - Tela para exibição de perguntas e envio de respostas.
  - Tela de resultados ao final do quiz.
  - Layout simples e responsivo.

---

## Requisitos Não Funcionais

- O sistema deve ser responsivo, com design simples e intuitivo.
- O candidato pode escolher a ferramenta de banco de dados mais adequada (relacional ou não-relacional).
- O código deve ser organizado, com boa estrutura de pastas e boas práticas.
- O backend deve ser funcional, lidando com erros de forma clara e retornando mensagens apropriadas ao usuário.
- A documentação do projeto deve incluir:
    - Descrição das funcionalidades principais.
    - Tecnologias e bibliotecas utilizadas.
    - Passos para rodar o sistema localmente (frontend e backend).
    - Estrutura definida para o banco de dados.

---

## Critérios de Avaliação

1. **Funcionalidades Implementadas**: Avaliação das funcionalidades entregues de acordo com os requisitos.
2. **Qualidade do Código**: Organização, boas práticas, e legibilidade.
3. **Design e Usabilidade**: Aparência da interface e experiência do usuário.
4. **Criatividade: Qualquer** funcionalidade ou melhoria adicional, como animações, gráficos ou design diferenciado, será considerada um diferencial.
5. **Banco de Dados**: Qualidade da estrutura de dados, uso eficiente de consultas e organização geral do banco de dados.

---

Boa sorte no desenvolvimento do projeto!
