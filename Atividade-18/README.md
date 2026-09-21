# Atividade 18 — Diagrama de Classes do BiblioTech

Nome: Fabricio
Turma: 2º ano — Técnico em Informática Integrado

## Diagrama

![Diagrama de Classes do BiblioTech](diagrama-classes.pn)

## Por que estes números (associação Bibliotecario — Emprestimo)

- Perto de Emprestimo eu coloquei **0..*** porque um bibliotecário pode registrar vários empréstimos.
- Perto de Bibliotecario eu coloquei **1** porque cada empréstimo é registrado por um bibliotecário.

## Rastreabilidade (nível B)

- A operação **realizarEmprestimo()** da classe **Bibliotecario** atende ao caso de uso **Realizar empréstimo**.

## Autoavaliação

- Conceito que pretendo: B
- Onde isso se prova no diagrama (classe / linha / número): **Na classe Reserva, que está ligada ao Livro, e na ligação entre Bibliotecario e Emprestimo.**