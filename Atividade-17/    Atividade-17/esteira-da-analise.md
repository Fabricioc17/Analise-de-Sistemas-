# Esteira da Análise — BiblioTech

**Estudante:** Fabricio Candido

## Funcionalidade 1: Listar Livro

* **1. Fala do cliente:** "Preciso conseguir ver a lista de livros do acervo para saber quais livros estão cadastrados."
* **2. História de usuário:** Como bibliotecário, quero listar os livros do acervo, para conseguir consultar os livros cadastrados.
* **3. Requisito:** RF01 — O sistema deve permitir listar os livros cadastrados no acervo.
* **4. Caso de uso (RF01):** Ator Bibliotecário → "Listar Livro"

## Funcionalidade 2: Reservar Livro

* **1. Fala do cliente:** "Quero reservar um livro que esteja disponível para poder pegar ele depois."
* **2. História de usuário:** Como leitor, quero reservar um livro, para garantir que eu possa pegá-lo depois.
* **3. Requisito:** RF02 — O sistema deve permitir a reserva de um livro.
* **4. Caso de uso (RF02):** Ator Bibliotecário → "Reservar Livro"

## Rastreabilidade

| Elipse no diagrama | Veio do requisito | Que veio da fala                                                                               |
| ------------------ | ----------------- | ---------------------------------------------------------------------------------------------- |
| Listar Livro       | RF01              | "Preciso conseguir ver a lista de livros do acervo para saber quais livros estão cadastrados." |
| Reservar Livro     | RF02              | "Quero reservar um livro que esteja disponível para poder pegar ele depois."                   |

<!-- Nível A: conte o caminho completo de cada funcionalidade, 
     da fala do cliente até o que está desenhado no diagrama. --> 

## Relacionamento entre casos de uso (nível A)

* Tipo: «include» ou «extend»
* Entre: "Reservar Livro" e "Verificar disponibilidade do livro"
* Por que é esse e não o outro: É «include» porque, para reservar um livro, é necessário verificar se ele está disponível. Essa verificação faz parte do processo de reserva.

## Autoavaliação

**Conceito pretendido:** C

* Conversei sobre esta atividade com: ninguém
* Esteira da análise: As duas funcionalidades estão organizadas com fala do cliente, história de usuário, requisito e caso de uso.
* Diagrama e notação: O diagrama tem a fronteira BiblioTech, o ator fora dela, os casos de uso dentro e as associações sem seta.
* Rastreabilidade: Os nomes dos casos de uso são os mesmos da esteira e estão relacionados aos seus requisitos.
* Organização da entrega: Os arquivos estão organizados na pasta Atividade-17, com os nomes pedidos na atividade.
