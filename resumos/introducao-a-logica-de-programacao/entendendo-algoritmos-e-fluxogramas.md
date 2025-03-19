# Entendendo Algoritmos e Fluxogramas

## A base de tudo

### Para que serve lógica

### Para quem é esse conteúdo

- A **lógica** é como você organiza seu pensamento computacional, enquanto que a linguagem é meramente uma sintaxe.
  - Posso pedir "água" em diferentes países — "water" no Estados Unidos, por exemplo — mas a estrutura sintática para isso é praticamente a mesma.

### A primeira coisa que você precisa aprender para se tornar dev

- Para passar **instruções** a uma máquina, você precisa primeiro conhecer essas instruções.
- A melhor maneira de estruturar seu pensamento lógico é através de **algoritmos**.

## Sobre algoritmos

### A base sobre algoritmos

- Lógica de programação nada mais é do que _estruturar_ seu **pensamento** de maneira lógica para _escrever_ **algoritmos**.
  - Algoritmos é o passo a passo lógico para resolver um **problema**.
    - 📍 Identificação do problema

### Algoritmos no seu dia a dia

- Há uma **ordem lógica** de ações a serem realizadas para resolver um problema.
  - Exemplo: assar um pão:
    ```mermaid
    flowchart TB
        Início
        --> B@{ shape: rect, label: "Abrir forno" }
        --> C@{ shape: diam, label: "Forno aceso" }
        C --> | Sim | D@{ shape: rect, label: "Botar lenha" }
        C --> | Não | E@{ shape: rect, label: "Acender fogo" }
        D --> F@{ shape: rect, label: "Assar pão" }
        E --> F
        --> Fim
    ```
