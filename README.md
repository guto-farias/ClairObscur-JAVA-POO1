# ClairObscur – Sistema de Batalha em Java (LPG1)

Projeto desenvolvido para a disciplina **Linguagem de Programação 1**, utilizando conceitos fundamentais de **Programação Orientada a Objetos (POO)** em Java.

O jogo implementa **batalhas 1 vs 1** entre personagens com mecânicas únicas.

---

## 📌 Índice
* [Descrição Geral](#descrição-geral)
* [Funcionalidades](#funcionalidades)
* [Como Executar](#como-executar)
* [Personagens](#personagens)
    * [Gustave](#gustave)
    * [Lune](#lune)
    * [Maelle](#maelle)
    * [Monoco](#monoco)
* [Arquitetura](#arquitetura)
* [Conceitos de POO Aplicados](#conceitos-de-poo-aplicados)
* [Observações Finais](#observações-finais)

---

## Descrição Geral

**ClairObscur** é um jogo de batalha em **linha de comando**, onde dois jogadores escolhem personagens e se enfrentam utilizando ataques básicos e habilidades especiais.

O projeto demonstra todos os **pilares da Programação Orientada a Objetos** de forma clara e prática.


[Image of an UML class diagram showing Inheritance, Abstraction, and Polymorphism in Object-Oriented Programming]


---

## Funcionalidades

* Seleção de personagens para dois jogadores.
* Sistema de **nível e XP persistente** enquanto o programa está rodando.
* **Mecânicas exclusivas** para cada personagem.
* Menu dinâmico baseado na classe selecionada.
* Alternância automática de turnos.
* Reset automático de estados ao fim da batalha.
* Múltiplas partidas no mesmo programa.

---

## Como Executar

No terminal, dentro da pasta do projeto:

```bash
javac *.java
java Main
