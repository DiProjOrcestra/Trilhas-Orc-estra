# Central de Projetos e Desafios — Back-end

---

Esta página reúne o guia completo e detalhado dos projetos práticos da Trilha de Back-end. Os projetos acompanham a evolução do aluno desde os fundamentos de Java e Orientação a Objetos no terminal até a criação de uma API REST completa com Spring Boot, H2 Database e Spring Security.

---

## 1. Mini Projeto 1: POO & Terminal (Gerenciador de Tarefas)

### Objetivo
Colocar em prática os principais conceitos de **Programação Orientada a Objetos (POO)** utilizando apenas a linguagem Java e execução via terminal.

> **Importante:** Não utilize banco de dados, interfaces gráficas ou frameworks nesta etapa. Todo o projeto deve funcionar apenas pelo terminal.

### Parte 1 — Requisitos Básicos de POO

#### Usuário
A classe `Usuario` deverá possuir os seguintes atributos: `id`, `nome`, `email`, e `tarefas` (lista de tarefas).

#### Tarefa com Prazo (`TaskComPrazo`)
Crie uma classe `TaskComPrazo` que herde da classe `Task`. Ela deverá possuir também: `prazo` e `prioridade`. A prioridade deverá ser representada por um Enum `Prioridade` (`BAIXA`, `MEDIA`, `ALTA`).

#### Estrutura Sugerida
```text
src/
├── Main.java
├── Usuario.java
├── Task.java
├── TaskComPrazo.java
└── Prioridade.java
```

#### Menu do Terminal
O programa deverá possuir um menu simples executado pelo terminal:
```text
=============================
 GERENCIADOR DE TAREFAS
=============================
1 - Cadastrar usuário
2 - Listar usuários
3 - Criar tarefa
4 - Criar tarefa com prazo
5 - Listar tarefas de um usuário
6 - Concluir tarefa
0 - Sair
```

### Parte 2 — Estruturas de Dados & Desafios de Manipulação de Listas

Após concluir a Parte 1 básica, evolua seu projeto aplicando os conceitos intermediários da **Unidade III** (Collections, Stream API, Generics e Records):

- **Nível 1 (Edição e Remoção):** Implementar funcionalidades para editar usuário, editar tarefa, remover tarefa e remover usuário.
- **Nível 2 (Buscas):** Implementar busca de usuário pelo nome e busca de tarefa pelo título.
- **Nível 3 (Estatísticas):** Mostrar total de usuários cadastrados, total de tarefas, tarefas concluídas e pendentes.
- **Nível 4 (Ordenação):** Ordenar tarefas por prioridade, prazo ou título utilizando `Stream API` e `Comparators`.

### Critérios de Aceite
- Classes `Usuario`, `Task`, `TaskComPrazo` e Enum `Prioridade` implementados.
- Menu funcional via terminal.
- Cadastro e associação de tarefas a usuários.
- Listagem de usuários e tarefas.
- Marcar tarefas como concluídas.

---

## 2. Mini Projeto 2: Modelagem do Banco de Dados

### Objetivo
Planejar como as informações serão armazenadas no banco de dados do projeto **Gerenciador de Tarefas**, aplicando os conceitos de modelagem conceitual e lógica.

### Etapa 1 — Modelagem Conceitual
Elabore o Diagrama de Classes UML ou Diagrama Entidade-Relacionamento (DER) representando:
- As entidades do sistema (`Usuario`, `Task`, `TaskComPrazo`);
- Os atributos de cada entidade e relacionamentos;
- As cardinalidades (1:1, 1:N, N:N) e herança entre os tipos de tarefas.

### Etapa 2 — Modelagem Lógica
Detalhe como cada entidade será implementada:
- Nome das tabelas/classes, atributos e tipos de dados;
- Chaves primárias (PK) e chaves estrangeiras (FK);
- Mapeamento de enums e herança.

### Critérios de Aceite
- Modelagem Conceitual completa.
- Modelagem Lógica completa com chaves e cardinalidades.

---

## 3. Mini Projeto 3: API REST com Spring Boot & H2 Database

### Objetivo
Transformar a aplicação de terminal em uma **API REST** utilizando **Spring Boot**, arquitetura **MVC** e o banco de dados em memória **H2 Database**.

> **Importante:** Utilize o banco de dados H2. Não é necessário instalar PostgreSQL ou MySQL nesta etapa.

### Dependências Iniciais
Crie o projeto Spring Boot com:
- `Spring Web`
- `Spring Data JPA`
- `H2 Database`
- `Lombok`
- `Validation`

### Estrutura de Arquitetura MVC
```text
src/main/java/
├── controller/
│   ├── UsuarioController.java
│   └── TaskController.java
├── service/
│   ├── UsuarioService.java
│   └── TaskService.java
├── repository/
│   ├── UsuarioRepository.java
│   └── TaskRepository.java
├── model/
│   ├── Usuario.java
│   ├── Task.java
│   ├── TaskComPrazo.java
│   └── Prioridade.java
└── Application.java
```

### Resumo dos Endpoints REST

#### Usuários (`/usuarios`)
| Método | Endpoint | Descrição |
| :--- | :--- | :--- |
| `GET` | `/usuarios` | Lista todos os usuários |
| `GET` | `/usuarios/{id}` | Retorna um usuário pelo ID |
| `POST` | `/usuarios` | Cadastra um novo usuário |
| `PUT` | `/usuarios/{id}` | Atualiza os dados de um usuário |
| `DELETE` | `/usuarios/{id}` | Remove um usuário |

#### Tarefas (`/tasks`)
| Método | Endpoint | Descrição |
| :--- | :--- | :--- |
| `GET` | `/tasks` | Lista todas as tarefas |
| `GET` | `/tasks/{id}` | Retorna uma tarefa pelo ID |
| `POST` | `/tasks` | Cadastra uma nova tarefa |
| `PUT` | `/tasks/{id}` | Atualiza uma tarefa existente |
| `DELETE` | `/tasks/{id}` | Remove uma tarefa |

### Exemplos de Payload JSON para Teste no Postman

#### Criar Usuário (`POST /usuarios`)
```json
{
  "nome": "João Silva",
  "email": "joao@orcestra.com"
}
```

#### Criar Tarefa (`POST /tasks`)
```json
{
  "titulo": "Implementar Controller",
  "descricao": "Criar endpoints REST da aplicação",
  "concluida": false,
  "usuarioId": 1
}
```

### Acesso ao Console do H2 Database
Após iniciar a aplicação, acesse no navegador: `http://localhost:8080/h2-console`

### Critérios de Aceite
- Arquitetura MVC organizada (Controller, Service, Repository, Model).
- Persistência das entidades no H2 Database.
- Operações CRUD completas nos endpoints REST.
- Validação e testes dos endpoints via Postman ou Insomnia.

---

## 4. Projeto Final: Spring Security & Autenticação

### Objetivo
Implementar autenticação e autorização de usuários na API REST com **Spring Security**, garantindo proteção e controle de acesso aos endpoints da aplicação.

### Funcionalidades
- Mapeamento de usuários com senhas criptografadas (BCrypt).
- Autenticação e geração de tokens de acesso (ex: JWT ou Session-based).
- Proteção de rotas privadas (ex: apenas o próprio usuário pode editar/excluir suas tarefas).

### Critérios de Aceite
- Endpoints de login e cadastro protegidos.
- Controle de acesso e autenticação ativos na API.
- Teste completo de fluxo seguro via Postman.

---

[← Voltar para a Visão Geral do Back-end](index.md){ .md-button }
