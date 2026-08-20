# Atividade 18 — Diagrama de Classes do BiblioTech
Nome: Felipe Dalzoto
Turma: 2º ano — Técnico em Informática Integrado

## Diagrama
![Diagrama de Classes do BiblioTech](diagrama-classes-Felipe.png)

## Por que estes números (associação Bibliotecario — Emprestimo)
- Perto de Emprestimo eu coloquei 0 porque um bibliotecário pode estar relacionado a nenhum ou vários empréstimos.
- Perto de Bibliotecario eu coloquei 1 porque cada empréstimo deve estar relacionado a um bibliotecário responsável.

## Rastreabilidade (nível B)
- A operação marcarComoEmprestado() da classe Livro atende ao caso de uso Realizar emprestimo.

## Autoavaliação
- Conceito que pretendo: B
- Onde isso se prova no diagrama (classe / linha / número): na classe Livro, na operação marcarComoEmprestado(), e nas multiplicidades das associações.