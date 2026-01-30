# Classificador de Nível de Herói 🏆

Este projeto em **JavaScript** calcula o nível de um herói com base em suas vitórias e derrotas.

## 📌 Descrição
A função `calcularNivel(vitorias, derrotas)`:
- Recebe o número de **vitórias** e **derrotas**.
- Calcula o **saldo de vitórias** (vitórias - derrotas).
- Classifica o herói em um nível de acordo com a quantidade de vitórias.

## 🚀 Como funciona
1. O saldo de vitórias é calculado subtraindo derrotas das vitórias.
2. O nível é determinado com base na quantidade de vitórias:
   - Menos de 10 → **Ferro**
   - Até 20 → **Bronze**
   - Até 50 → **Prata**
   - Até 80 → **Ouro**
   - Até 90 → **Diamante**
   - Até 100 → **Lendário**
   - Acima de 100 → **Imortal**
3. A função retorna uma mensagem com o saldo e o nível do herói.

## 🧩 Código de exemplo
