# jogodavelhaC

# Relatório do Código - Jogo da Velha em C

## Visão Geral
O código fornecido implementa um jogo da velha em linguagem C. O jogo pode ser jogado por dois jogadores ou contra a máquina. O programa possui funções para inicializar o tabuleiro, exibir o tabuleiro, verificar o ganhador, realizar a jogada do jogador e da máquina, além de uma função para exibir os créditos.

## Estrutura do Código

### Constantes
- `JOGADOR_X`, `JOGADOR_O`, `EMPATE`: Representam os jogadores X e O, além do estado de empate.
- `CARACTERE_BRANCO`: Representa uma célula vazia no tabuleiro.
- `QTD_LINHAS`, `QTD_COLUNAS`: Definem as dimensões do tabuleiro.

### Funções
1. **`inicializarTabuleiro`**
   - Inicializa todas as células do tabuleiro com `CARACTERE_BRANCO`.

2. **`exibirTabuleiro`**
   - Exibe o tabuleiro na tela.

3. **`verificarGanhador`**
   - Verifica se algum jogador venceu ou se houve empate.

4. **`jogadaJogador`**
   - Permite que o jogador informe suas jogadas, tratando entradas inválidas.

5. **`jogadaMaquina`**
   - Implementa a lógica da jogada da máquina, escolhendo posições aleatórias.

6. **`creditos`**
   - Exibe uma mensagem de créditos.

7. **`iniciarJogo`**
   - Controla o fluxo do jogo, alternando entre jogadas de jogador e máquina. Atualiza o placar e oferece a opção de jogar novamente.

8. **`main`**
   - Solicita ao usuário que escolha o modo de jogo: dois jogadores, contra a máquina ou créditos. Chama a função correspondente ao modo escolhido.

## Funcionalidades
- **Dois Jogadores:**
  - Dois jogadores podem jogar no mesmo teclado.
- **Contra a Máquina:**
  - Um jogador pode jogar contra a máquina, que faz escolhas aleatórias.
- **Créditos:**
  - Exibe uma mensagem de créditos.

## Melhorias Sugeridas
- Adicionar uma opção para reiniciar o jogo sem reiniciar o programa.
- Implementar uma estratégia mais inteligente para a jogada da máquina.
- Refatorar e dividir o código em mais funções para melhor legibilidade.

## Conclusão
O código fornece uma implementação funcional do jogo da velha em C, permitindo diferentes modos de jogo. Ele utiliza funções para organizar o código e facilitar a manutenção. Entretanto, há oportunidades de melhoria em termos de estratégia da máquina e organização do código.
