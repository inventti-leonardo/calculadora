# Calculadora 

Documento utilizado como referência para formatação de números e moedas - https://docs.oracle.com/cd/E19455-01/806-0169/6j9hsml2h/index.html

### Calculando com diferentes separadores de milhar e decimal
```
calcular('1234.56') // 1234.56
calcular('1234,56') // 1234.56
calcular('1.234.56') // 1234.56
calcular('1.234,56') // 1234.56
calcular('1,234.56') // 1234.56
calcular('1,234,56') // 1234.56
calcular('1 234.56') // 1234.56
calcular('1 234,56') // 1234.56
```
### Calculando com letras
```
calcular('R$1,00 + R$2,00') // 3.00
calcular('2UN * R$3,00') // 6.00
calcular('(2PC * R$3,00) / 2') // 3.00
```
### Calculando com ponto flutuante
```
calcular('10.1 + 10.2') // 20.30
```
### Calculando com passagem de parâmetros
```
calcular('{0}+({1}*{2})', '10,1', 10.2, 2) // 30.50
calcular('{0}+{1}', '1+(2*2)', '3+(4*4)') // 24.00
```
### Problemas
```
calcular('1.000') // 1.00, o número "1.000" deveria ser mil ou um?
```
