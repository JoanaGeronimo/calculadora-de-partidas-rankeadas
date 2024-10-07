# Calculadora de Partidas Rankeadas

Este projeto consiste em uma calculadora que determina o nível de um jogador com base em suas vitórias e derrotas em partidas ranqueadas.

## Como Usar

1. Defina a quantidade de vitórias e derrotas.
2. Chame a função `calcularNivel(vitorias, derrotas)` para obter o saldo e o nível.
3. A função retorna um objeto com o saldo e o nível.

## Exemplo

```javascript
const resultado = calcularNivel(45, 10);
console.log(`O Herói tem de saldo de ${resultado.saldoVitorias} está no nível de ${resultado.nivel}`);
