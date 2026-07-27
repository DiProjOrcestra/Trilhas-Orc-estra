# Unidade V – Protocolo & Métodos HTTP

---

## 1. Visão Geral

Para conectar o back-end ao mundo Web, precisamos entender a linguagem de comunicação da internet: o protocolo HTTP.

Nesta unidade, você aprenderá sobre verbos HTTP (`GET`, `POST`, `PUT`, `DELETE`), cabeçalhos, parâmetros de URL, corpo da requisição (`Body` JSON) e códigos de status HTTP.

---

## 2. Conteúdo em Vídeo

- 🎥 [Vídeo: Entendendo o Protocolo HTTP](https://www.youtube.com/watch?v=PcHbyGVoqZk)
- 🎥 [Vídeo: Desvendando Requisições HTTP (Métodos, Parâmetros, Body e Status Codes)](https://www.youtube.com/watch?v=bMmdksBHyXc&t=5s&pp=ygULaHR0cCBtZXRvZG8%3D)

---

## 3. Tabela de Referência: Códigos de Status HTTP

Confira os códigos de status HTTP mais utilizados em APIs REST desenvolvidas com Spring Boot:

| Código | Significado | Quando Usar no Spring Boot |
| :---: | :--- | :--- |
| `200 OK` | Sucesso | Retorno padrão para buscas (`GET`) e atualizações (`PUT`). |
| `201 Created` | Criado | Retorno para cadastro com sucesso (`POST`). |
| `400 Bad Request` | Requisição Inválida | Erro nos dados ou falha de validação enviada pelo cliente. |
| `404 Not Found` | Não Encontrado | Quando buscar um Usuário ou Tarefa que não existe no banco. |
| `500 Internal Error` | Erro no Servidor | Falha interna ou exceção não tratada na aplicação. |

---

## 4. Atividade Prática com Postman

!!! tip "Demonstração com Postman"
    Ao final desta unidade, utilize o **Postman** ou o **Insomnia** para criar uma coleção de testes simulando requisições HTTP e gravando um breve vídeo demonstrando os conceitos aprendidos.
