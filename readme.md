# 🔢 Cálculo de π com Método de Monte Carlo

Este projeto foi desenvolvido em 2021 como trabalho final do Instituto Federal Catarinense – Campus Videira, com o objetivo de **aproximar o valor de π (Pi)** utilizando o **método de Monte Carlo** na linguagem **C**.

---

## 📌 Objetivo

Aplicar o método de Monte Carlo para estimar o valor de π por meio de experimentos estatísticos com geração 
 pontos aleatórios no plano cartesiano.

---

## 📘 Como funciona o método

1. Um círculo é inscrito dentro de um quadrado.
2. Pontos são gerados aleatoriamente no espaço do quadrado.
3. É verificado quantos pontos caem **dentro da circunferência**.
4. A razão entre os pontos dentro e o total de pontos é usada para estimar π com a fórmula:

   ```text
    π ≈ 4 * (pontos dentro do círculo / total de pontos)
   ```
