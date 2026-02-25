# 🟡 Pacman Clássico em Assembly (MARS MIPS)

## 📖 Descrição

Este projeto é uma recriação do clássico **Pacman** em um ambiente 2D,
desenvolvido utilizando linguagem de baixo nível Assembly através da
ferramenta **Java MARS MIPS**.

O objetivo principal do jogo é controlar o personagem pelo labirinto
coletando todas as bolinhas brancas enquanto evita os fantasmas. O jogo
foi construído com foco em lógica de movimentação, controle de estados e
manipulação direta de instruções em Assembly.

<br>

## 🎮 Mecânicas do Jogo

-   O jogo possui 2 fases de labirinto
-   Cada fase contém 3 fantasmas clássicos:
    -   Fantasma Rosa
    -   Fantasma Vermelho
    -   Fantasma Laranja
-   O jogador deve:
    -   Coletar todas as bolinhas brancas do mapa
    -   Evitar contato com qualquer fantasma
-   Controles de movimento:
    -   W → Cima
    -   A → Esquerda
    -   S → Baixo
    -   D → Direita
-   O jogo inicia quando o jogador começa a se mover

<br>

## 🧠 Regras de Progressão

-   Ao coletar todas as bolinhas da Fase 1, o jogador avança para a
    Fase 2
-   Se o jogador perder em qualquer fase:
    -   A tela Game Over é exibida
    -   O progresso é reiniciado desde a primeira fase
-   Se o jogador completar as duas fases:
    -   A tela You Win é exibida
    -   O jogo reinicia automaticamente

<br>

## 🖥️ Requisitos para Executar

Para jogar, você precisa:

-   Java instalado na máquina
-   Ferramenta MARS MIPS
-   Sistema operacional compatível com Java
-   Teclado para controle do personagem

<br>

## ▶️ Como Executar

Siga os passos abaixo para executar o jogo corretamente no MARS MIPS:

1. Instale o Java em seu computador  
2. Baixe e abra o MARS MIPS  
3. No MARS, carregue o arquivo `.asm` do projeto  
4. No menu superior, acesse:  
   **Tools → Bitmap Display**  
   → Esta será a tela onde o jogo será exibido  
5. Na janela aberta, configure:
   - **Unit Width in Pixels** = 4  
   - **Unit Height in Pixels** = 4  
6. Clique em **Connect to MIPS**  
7. No menu superior, acesse:  
   **Tools → Keyboard and Display MMIO Simulator**  
   → Esta será a janela de entrada de comandos do jogador  
8. Clique em **Connect to MIPS** nesta janela também  
9. Execute o programa clicando nos botões **Icone de Ferramentas** → **Run/Play** do MARS  
10. Clique na área **Keyboard** e utilize as teclas:

   - `W` → Cima  
   - `A` → Esquerda  
   - `S` → Baixo  
   - `D` → Direita  

O jogo inicia assim que o jogador começa a se mover.

<br>

## 🎯 Objetivo Acadêmico

Este projeto foi desenvolvido com fins educacionais para demonstrar:

-   Programação em Assembly MIPS
-   Lógica de jogos em baixo nível
-   Controle de fluxo e estados
-   Manipulação de entrada do usuário
-   Estruturação de um jogo completo em ambiente simulado
