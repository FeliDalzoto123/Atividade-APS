# Esteira da Análise — BiblioTech

**Estudante:** Felipe Dalzoto

## Funcionalidade 1: Emprestar livro

- **1.1 Fala do cliente:** "Eu quero ir na biblioteca e emprestar um livro para eu estudar."
- **2.1 História de usuário:** Como Leitor, quero emprestar um livro, para aumentar o meu conhecimento.
- **3.1 Requisito:** RF01 — O sistema deve Realizar emprestimos para os leitores
- **4.1 Caso de uso (RF01):** Ator Leitor → "Emprestar Livro " (verbo + objeto)

## Funcionalidade 2: Buscar livro no acervo

- **1.2 Fala do cliente:** "Eu quero chegar na biblioteca e procurar o livro sem precisar de auxilio."
- **2.2 História de usuário:** Como Leitor, quero Buscar o livro sem auxilio nenhum, para estudar.
- **3.2 Requisito:** RF02 — O sistema deve ter uma funcionalidade para buscar livros sem nenhum auxilio. 
- **4.2 Caso de uso (RF02):** Ator Leitor → "Buscar Livro" (verbo + objeto)

## Rastreabilidade

| Elipse no diagrama | Veio do requisito | Que veio da fala |
||---|---|
|Emprestar Livro | 3.1 RF01: O sistema deve Realizar emprestimos para os leitores | "Eu quero ir na biblioteca e emprestar um livro para eu estudar." |

|Buscar Livro | 3.2 RF02: O sistema deve ter uma funcionalidade para buscar livros sem nenhum auxilio. | "Eu quero chegar na biblioteca e procurar o livro sem precisar de auxilio." |

<!-- Nível A: conte o caminho completo de cada funcionalidade,
     da fala do cliente até o que está desenhado no diagrama. -->

## Relacionamento entre casos de uso (nível A)

- Tipo: «include» ou «extend»
- Entre: Emprestar Livro e Buscar Livro
- Por que é esse e não o outro: Por que para emprestar um livro voce tem que obrigatoriamente buscar um livro na biblioteca antes de fazer um emprestimo.

## Autoavaliação

**Conceito pretendido:** B (A / B / C)

- Conversei sobre esta atividade com: ninguém (ou "ninguém")
- Esteira da análise: No repositorio do github (diga onde)
- Diagrama e notação: diagrama feito seguindo a notação UML
- Rastreabilidade: requisitos relacionados aos casos de uso
- Organização da entrega: organizada e completa