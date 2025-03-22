# Estrutura de um Software e Seu Ambiente de Desenvolvimento

## Input - Process - Output

### Entendendo os conceitos de Input, process e output

São os pilares de qualquer aplicação.

#### Exemplo: Uso rotineiro de um aplicativo

- comandos de **entrada**
  - Procurar um pedido.
  - Solicitar um pedido.
- comandos de **processamento**
  - Verificar se o pagamento foi aprovado.
  - Verificar se o restaurante está aberto.
  - Começa a preparar o seu pedido.
- comandos de **saída**
  - "Seu pedido está a caminho!"

#### Comandos de entrada (input)

- Momentos de _interação_ com o usuário.

#### Comandos de processamento (process)

- Verificações e ações com base na entrada do usuário.

#### Comandos de saída (output)

- Retorno de algo para o usuário; um posicionamento ou uma mensagem, por exemplo.

### Conceito de features

#### Exemplo: App que solicita viagens de veículos online

|      Feature      |                                    Input                                     |                                                                Process                                                                 |                                              Output                                              |
| :---------------: | :--------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------: |
| Cadastrar usuário | Clicar no botão "Cadastrar"; digitar nome, CPF e dados do cartão de crédito. |                        Verificar se CPF possui irregularidades; verificar se cartão de crédito está disponível.                        |                       Mensagem de saída: "Usuário cadastrado com sucesso".                       |
| Solicitar veículo | Clicar no botão "Nova viagem"; colocar ponto de partida e ponto de destino.  | Verificar motoristas próximos ao ponto de partida; acionar o motorista mais próximo; coloca no gps do motorista o ponto do passageiro. | Mensagem de saída: "Motorista a caminho"; atualizar a tela com a estimativa de tempo de chegada; |

A ideia por trás deste exemplo é mostrar que:

- Para cada feature, há um **algoritmo**;
- Para cada algoritmo, há um fluxo input 🠲 process 🠲 output.

> _Independente da linguagem_, o fluxo é sempre o mesmo: feature 🠲 algoritmo (input 🠲 process 🠲 output). A linguagem de programação é só uma maneira de se comunicar com o computador para realizar ações de um algoritmo.

## Seu primeiro ambiente de código

### O que é uma IDE e o essencial que você precisa saber

- IDE — _Integrated Development Environment_
- [playcode.io](https://playcode.io/)
- IDEs têm o propósito de facilitar o desenvolvimento.

### Lidando com ambientes de código sem medo

### Como perder o medo de "quebrar" alguma coisa

Um desenvolvedor é um especialista em identificar problemas, então, "quebre" as coisas, propositalmente, para saber, depois, arrumá-las. Tudo é parte de entender o comportamento da coisa em questão.
