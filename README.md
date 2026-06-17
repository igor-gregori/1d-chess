# Xadrez 1D

Variante de xadrez em uma dimensão, originalmente descrita por Martin Gardner na coluna *Mathematical Games* da Scientific American (julho 1980).

## Como jogar

Abra `index.html` no navegador. Você joga com as brancas contra a IA.

1. Clique em uma peça branca para selecioná-la
2. Os destinos válidos ficam verdes — clique em um para mover
3. A IA responde automaticamente

## Regras

**Tabuleiro:** 8 casas em linha.

**Posição inicial:** `♔ ♘ ♖ · · ♜ ♞ ♚`

**Peças:**

| Peça | Movimento |
|------|-----------|
| Rei (♔/♚) | 1 casa em qualquer direção |
| Cavalo (♘/♞) | 2 casas (pula peças) |
| Torre (♖/♜) | Qualquer distância (não pula) |

**Vitória:** xeque-mate no rei adversário.

**Empate:**
- Afogamento (stalemate) — sem movimentos legais e não está em xeque
- Repetição tripla de posição
- Material insuficiente (apenas reis)

## Solução

Com jogo ótimo, brancas têm vitória forçada: `N4 N5, N6 K7, R4 K6, R2 K7, R5++`

## Créditos

- Variante original: Martin Gardner, Scientific American, julho 1980
- Inspiração: [rowan441/1dchess](https://rowan441.github.io/1dchess/chess.html)
