# 5 Desafios de Sistema númericos

## Desafio 1: Decifrando um Código Secreto

> Cenário: Você encontrou um código em hexadecimal (base 16): 2F. Convertao para:

- Dica: Converta primeiro para base 10 e depois para as outras bases.

### **Base 10 (hexadecimal → decimal) - Desafio 2**

2F₁₆: 2x16¹ + 15x1=15 = 47₁₀

### **Base 2 (decimal → binário)**

47₁₀ →

47 ÷ 2 = 23 [47 - (2x23=46) = 1]

23 ÷ 2 = 11 [23 - (2x11=22) = 1]

11 ÷ 2 = 5 [11 - (2x 5=10) = 1]

5 ÷ 2 = 2 [ 5 - (2x 2= 4) = 1]

2 ÷ 2 = 1 [ 2 - (2x 1= 2) = 0]

1 ÷ 2 = 0 [ 1 - (2x 0= 0) = 1]

= 101111₂ binário

### **Base 8 (decimal → octal)**

47₁₀ →
47 ÷ 8 = 5 [47 - (8x5=40) = 7]
5 ÷ 8 = 0 [ 5 - (8x0= 0) = 5]
= 57₈ octal

## Desafio 2: Ajustando um Sistema de Computador Antigo

> Cenário: Um computador antigo usa octal (base 8) para armazenar dados. O valor 45 (em base 8) precisa ser convertido para:

- Dica: Lembre-se de que cada dígito octal equivale a 3 bits.

### **Base 10 (octal → decimal)**

45₈: (4x8¹=32) + (5x8⁰=8) = 37₁₀

### **Base 2 (octal → binário)**

45₈: 100101₂ comparando com a tabela

| Binário | Octal |
| :-----: | :---: |
|  0100   |   4   |
|  0101   |   5   |

ou

37₁₀ →

37 ÷ 2 = 23 [37 - (2x23=36) = 1]

23 ÷ 2 = 11 [23 - (2x11=22) = 1]

11 ÷ 2 = 5 [11 - (2x 5=10) = 1]

5 ÷ 2 = 2 [ 5 - (2x 2= 4) = 1]

2 ÷ 2 = 1 [ 2 - (2x 1= 2) = 0]

1 ÷ 2 = 0 [ 1 - (2x 0= 0) = 1]

= 100101₂ binário

### **Base 16 (octal → hexadecimal)**

45₈: Tabela de base [0010]=2 [1010]=5 igual á 25₁₆

## Desafio 3: Mensagem Binária em um Jogo de Quebra-Cabeça

> Cenário: Em um jogo de escape room, você encontra a mensagem binária 101101. Converta-a para:

Dica: Agrupe os bits em conjuntos de 3 (para octal) ou 4 (para hexadecimal).

### **Base 10 (binária → decimal)**

101101₂: (1x2⁵=32) + (0x2⁴=0) + (1x2³=8) + (1x2²=4) + (0x2¹=0) + (1x2⁰=1) = 45₁₀

### **Base 8 (binária → octal)**

45₁₀ 45 ÷ 8 = 5 [0.625 x 8 = 5]

5 ÷ 8 = 0 [5 - (0x8=0) = 5]

=55₈ octal

### **Base 16 (binária → Hexadecimal)**

101101₂
[0010]=2
[1101]=D 2D₁₆
