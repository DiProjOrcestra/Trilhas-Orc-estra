# Unidade VI - React

**Tempo Estimado**: 3 semanas

Unidade final da trilha, onde você aplica tudo o que aprendeu em um framework (base de código pré-construída que serve como um "esqueleto" para o desenvolvimento de software) chamado **React**. Vamos seguir o curso gratuito do professor Matheus Battisti no YouTube.

!!! warning "Aviso Importante: Versão do React Router (v5 vs v8)"
    O curso ensina o React Router na versão 5, mas a versão atual é a 8 e essa parte específica mudou bastante entre as versões. Então, siga as seguintes orientações:

    * Ao chegar na parte de rotas, você vai notar que `<Switch>` virou `<Routes>` e `useHistory()` virou `useNavigate()`. Se o código do vídeo não funcionar, é por isso, não é erro seu.
    * Sempre que for usar rotas no projeto final, pesquise se o que está sendo passado no vídeo condiz com a sintaxe atual. É recomendado a consulta da [documentação oficial do React Router](https://reactrouter.com) pra pegar a sintaxe atualizada.
    * Fora a parte de rotas, o resto do curso (componentização, JSX, props, useState, useEffect) segue válido e compatível com a versão atual do React — o descompasso está concentrado mesmo na parte de navegação entre páginas.

O último módulo desta unidade contempla a criação de um projeto do zero, juntamente com o professor que consolida tudo que você irá aprender de React. É importante que você construa o projeto juntamente com o professor e não apenas assista às aulas. A entrega também será feita via repositório público no GitHub.

---

### Módulo 6.1: Introdução e Preparação do Ambiente
Instalar as dependências necessárias (Node.js e NPM), compreender o funcionamento do empacotador Vite e inicializar o primeiro projeto React rodando localmente.

**Links:**
- 🎥 [Playlist: Módulo 6.1 — Introdução e Preparação do Ambiente](https://www.youtube.com/playlist?list=PLUg1vQowR3YM)

### Módulo 6.2: Fundamentos de React e Componentização
Transcrever HTML para a sintaxe JSX, quebrar interfaces em componentes reutilizáveis e compartilhar dados entre eles de forma estática utilizando as *Props*.

**Links:**
- 🎥 [Playlist: Módulo 6.2 — Fundamentos de React e Componentização](https://www.youtube.com/playlist?list=PLI11CS_BkvD4)

### Módulo 6.3: Estado e Manipulação de Eventos
Utilizar o *hook* `useState` para criar estados dinâmicos que atualizam a tela automaticamente, além de interceptar e gerenciar eventos do usuário, como cliques e digitação em formulários.

**Links:**
- 🎥 [Playlist: Módulo 6.3 — Estado e Manipulação de Eventos](https://www.youtube.com/playlist?list=PLcEgWmgCi0jU)

### Módulo 6.4: Renderização e React Router
Navegar entre diferentes telas sem recarregar a página da web utilizando o React Router, e gerenciar requisições HTTP e efeitos colaterais utilizando o *hook* `useEffect`.

**Links:**
- 🎥 [Playlist: Módulo 6.4 — Renderização e React Router](https://www.youtube.com/playlist?list=PLCxlbA0FcNmA)

### Módulo 6.5: [Projeto Final] Costs

!!! example "[Projeto Prático Final] Costs"
    Consolidar todo o conteúdo teórico do curso na construção de um gerenciador de projetos com controle de orçamento, cadastrando, editando e excluindo projetos e serviços associados, com validação de regras de negócio (impedir custos que ultrapassem o orçamento definido).

    **Links:**
    - 🎥 [Playlist: Módulo 6.5 — Projeto Costs](https://www.youtube.com/playlist?list=PLboCKp6EE6Kg)
