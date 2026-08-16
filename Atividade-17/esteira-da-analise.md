# Esteira da Análise — BiblioTech

**Estudante:** Fabricio Canddo

## Funcionalidade 1: Reservar livro

* **Fala:** "Quero reservar um livro."
* **História:** Como aluno, quero reservar um livro, para garantir sua disponibilidade.
* **Requisito:** RF01 — O sistema deve permitir reservar um livro.
* **Caso de uso:** Aluno → "Reservar livro"

## Funcionalidade 2: Realizar empréstimo

* **Fala:** "Quero pegar um livro emprestado."
* **História:** Como aluno, quero realizar um empréstimo, para usar o livro.
* **Requisito:** RF02 — O sistema deve permitir realizar um empréstimo.
* **Caso de uso:** Aluno → "Realizar empréstimo"

## Rastreabilidade

| Caso de uso         | Requisito | Fala                               |
| ------------------- | --------- | ---------------------------------- |
| Reservar livro      | RF01      | "Quero reservar um livro."         |
| Realizar empréstimo | RF02      | "Quero pegar um livro emprestado." |

## Relacionamento

* **Tipo:** «include»
* **Entre:** Realizar empréstimo → Verificar disponibilidade
* **Por quê:** Verificar a disponibilidade é necessário para realizar o empréstimo.

## Autoavaliação

**Conceito pretendido:** B

* Conversei: ninguém
* Esteira: completa
* Diagrama: correto
* Rastreabilidade: feita
* Organização: Média

