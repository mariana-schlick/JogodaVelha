# Jogo da Velha

## Descrição
Este é um projeto em Java que implementa o clássico **Jogo da Velha** (Tic-Tac-Toe) utilizando a biblioteca Swing para criar a interface gráfica. Dois jogadores se alternam no tabuleiro 3x3, com o objetivo de alinhar três símbolos iguais (X ou O) horizontalmente, verticalmente ou diagonalmente. O jogo também detecta empates e exibe mensagens de vitória ou empate.

---

## Funcionalidades
- Interface gráfica simples e intuitiva.
- Suporte para dois jogadores locais.
- Detecção automática de vitórias ou empate (deu velha).
- Destaque visual para o jogador vencedor.

---

## Tecnologias Utilizadas
- **Java**
- **Swing (Java AWT)**

---

## Como Executar

### Pré-requisitos
- Java JDK instalado (versão 8 ou superior).
- IDE ou editor de texto com suporte para Java (ex.: IntelliJ IDEA, Eclipse, VS Code).

## Parâmetros Utilizados no Projeto

Durante o desenvolvimento deste projeto, utilizei diversos conceitos e funcionalidades da linguagem Java. Abaixo, explico alguns dos principais parâmetros e elementos utilizados:

### 1. **Classes e Objetos**
- O projeto é baseado na criação de uma classe `TicTacToe` que representa todo o jogo. 
- **Objetos**, como `JFrame`, `JLabel` e `JButton`, foram utilizados para criar e manipular a interface gráfica.

### 2. **Eventos com ActionListener**
- A interface `ActionListener` foi utilizada para capturar e tratar os cliques nos botões do tabuleiro.
- Cada botão foi associado a um evento que atualiza seu texto com o símbolo do jogador atual (`X` ou `O`) e verifica as condições de vitória.

### 3. **Estruturas de Controle**
- **Condicionais (`if`, `else`)**: Usadas para verificar se um botão foi clicado e se o jogo já terminou.
- **Loops (`for`)**: Aplicados para iterar sobre as linhas e colunas do tabuleiro durante a verificação do vencedor.

### 4. **Manipulação de Strings**
- As condições de vitória utilizam comparações entre os textos (`getText()`) dos botões para determinar se os símbolos dos jogadores estão alinhados.

### 5. **Interface Gráfica com Swing**
- A biblioteca Swing foi usada para criar uma interface gráfica amigável:
  - **JFrame**: Janela principal do jogo.
  - **JPanel**: Organiza os elementos na interface.
  - **JLabel**: Exibe mensagens no topo da janela.
  - **JButton**: Representa as células do tabuleiro.

---

## O que aprendi com este projeto

### 1. **Criação de Interfaces Gráficas**
- Compreendi melhor como organizar componentes gráficos (botões, painéis, rótulos) utilizando layouts como `GridLayout` e `BorderLayout`.

### 2. **Manipulação de Eventos**
- Aprendi a implementar e associar **listeners** a botões, permitindo que o jogo reaja a interações do usuário.

### 3. **Lógica de Jogo**
- Desenvolvi uma lógica para verificar condições de vitória e empate, usando estruturas de repetição e controle.

### 4. **Fluxo do Programa**
- Ganhei experiência em gerenciar estados do jogo, como alternância de turnos, fim de jogo e contagem de rodadas.

---

## Conhecimentos que este projeto abrange

### 1. **Programação Orientada a Objetos (POO)**
- O projeto utiliza conceitos fundamentais de POO, como encapsulamento e manipulação de objetos.

### 2. **Estruturas de Dados**
- Trabalhei com matrizes bidimensionais para representar o tabuleiro do jogo.

### 3. **Lógica de Programação**
- A lógica do jogo envolve comparações, alternância de jogadores e controle de fluxo.

### 4. **Desenvolvimento de Jogos**
- Este projeto é um exemplo introdutório ao desenvolvimento de jogos simples com Java.

### 5. **Interface Gráfica**
- Garante uma experiência prática com bibliotecas de GUI, preparando para projetos mais complexos.

---

Este projeto foi uma excelente oportunidade para consolidar conceitos fundamentais de Java e para explorar o desenvolvimento de interfaces gráficas. Ele me permitiu criar uma aplicação funcional e interativa, ampliando minha compreensão e prática em programação orientada a objetos e lógica de programação.

