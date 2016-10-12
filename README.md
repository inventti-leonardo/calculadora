# Calculadora 
# Com formatação
```
calcular('1000') // 1000.00
calcular('1000.00') // 1000.00
calcular('1000,00') // 1000.00
calcular('1.000.00') // 1000.00
calcular('1.000,00') // 1000.00
calcular('1,000.00') // 1000.00
calcular('1,000,00') // 1000.00
calcular('1 000.00') // 1000.00
calcular('1 000,00') // 1000.00
```
# Com semântica
```
calcular('R$1,00 + R$2,00') // 3.00
calcular('2UN * R$3,00') // 6.00
calcular('(2PC * R$3,00) / 2') // 3.00
```
# Com ponto flutuante
```
calcular('10.1 + 10.2') // 20.30
```
# Com parâmetros
```
calcular('{0}+({1}*{2})', '10,1', 10.2, 2) // 30.50
```
# Problemas
```
calcular('1.000') // 1.00, o número "1.000" deveria ser mil ou um?
```
