# 🏆 Calculadora de Partidas Rankeadas

Projeto desenvolvido como parte de um **desafio de código da DIO (Digital Innovation One)**, realizado durante o curso de **Lógica de Programação**.

O desafio consiste em criar uma função capaz de receber a quantidade de **vitórias e derrotas** de um jogador, calcular o seu saldo de vitórias e determinar seu nível com base na quantidade de vitórias.

## 🎯 Objetivo

Criar uma função que receba como parâmetros:

- Quantidade de vitórias
- Quantidade de derrotas

O saldo de vitórias é calculado através da seguinte operação:

```text
saldo de vitórias = vitórias - derrotas
```

Depois, o jogador é classificado de acordo com sua quantidade de vitórias.

## 🏅 Classificação

| Vitórias | Nível |

| Menor que 10 | Ferro |
| 10 a 20 | Bronze |
| 21 a 50 | Prata |
| 51 a 80 | Ouro |
| 81 a 90 | Diamante |
| 91 a 100 | Lendário |
| Maior ou igual a 101 | Imortal |

## 💻 Tecnologias

- JavaScript
- Node.js

## 🧠 Conceitos praticados

Neste desafio foram trabalhados conceitos fundamentais de lógica de programação:

- Variáveis
- Operadores matemáticos
- Operadores de comparação
- Funções
- Parâmetros
- Retorno de valores
- Estruturas condicionais (`if`, `else if`, `else`)
- Template literals
- `console.log()`

## 🚀 Como executar

Clone o repositório:

```bash
git clone URL_DO_REPOSITORIO
```

Acesse a pasta do projeto:

```bash
cd calculadora-partidas-rankeadas
```

Execute o arquivo JavaScript:

```bash
node index.js
```

## 📤 Exemplo de saída

Considerando:

```javascript
let vitorias = 75;
let derrotas = 20;
```

O saldo será:

```text
75 - 20 = 55
```

E a saída:

```text
O Herói tem de saldo de 55 está no nível de Ouro
```

## 📚 Sobre o desafio

Este projeto faz parte dos desafios de código propostos pela **DIO** durante o curso de **Lógica de Programação**.

A atividade tem como objetivo colocar em prática conceitos básicos de programação através da criação de uma solução simples utilizando JavaScript.

---

Desenvolvido por _Eduardo Nobilioni_
