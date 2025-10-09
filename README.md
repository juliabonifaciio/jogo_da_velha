# 🎮 Jogo da Velha em Python

## 👩‍💻 Integrantes
- Alexandre Silva Alves – RM567415
- Gabriella Mostafa Garcia – RM568508  
- Mariana Pergentino Fonseca – RM568252  
- Julia Marcela de Faria Bonifacio – RM566673  

## ⚙️ Instalação

1. Clone este repositório ou baixe os arquivos para sua máquina:
   ```bash
   git clone https://github.com/juliabonifaciio/1TIAPR-CP2-Python-Gabriella_Mariana_Julia.git
    ```

2. Acesse a pasta do projeto:
    ```bash
    cd 1TIAPR-CP2-Python-Gabriella_Mariana_Julia
    ```

## ▶️ Execução

Para rodar o programa, basta executar o seguinte comando no terminal:
    ```bash
    python main.py
    ```

## 🎮 Como Jogar
- O jogo é para dois jogadores: Jogador 1 (X) e Jogador 2 (O).
- Os jogadores alternam suas jogadas.
- Para marcar no tabuleiro, digite os índices da linha e coluna (0, 1 ou 2).

📌 _Exemplo: se digitar 1 e depois 2, você marcará a posição linha 1, coluna 2._

O jogo termina quando:
- Um jogador completa uma linha, coluna ou diagonal com seu símbolo;
- Ou todas as casas forem preenchidas (empate).

## 🏆 Resultado
- Caso algum jogador consiga completar uma linha, coluna ou diagonal, o programa exibe a mensagem de vitória.
- Se todas as casas forem preenchidas sem vencedor, o jogo declara empate.

## 🖥️ Exemplo de Saída no Terminal
    === JOGO DA VELHA ===

    Jogador 1 = X
    Jogador 2 = O

    |   |  
    ---------
    |   |  
    ---------
    |   |  

    Vez do jogador: X
    Digite a linha (0, 1 ou 2): 0
    Digite a coluna (0, 1 ou 2): 1

    | X |  
    ---------
    |   |  
    ---------
    |   |  

    Vez do jogador: O
    Digite a linha (0, 1 ou 2): 1
    Digite a coluna (0, 1 ou 2): 1

    | X |  
    ---------
    | O |  
    ---------
    |   |  
