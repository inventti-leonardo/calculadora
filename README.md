# Calculadora 
# Com formatação
```
calcular('1 + 1,00 + 1.00') // 3
calcular('1000 + 1000,00 + 1000.00 + 1.000,00 + 1.000.00') // 5000
calcular('1000000 + 1000000,00 + 1000000.00 + 1.000.000,00 + 1.000.000.00') // 5000000
```
# Com semântica
```
calcular('R$1,00 + 1') // 2
calcular('2pc * R$3,00') // 6
calcular('(2pc * R$3,00) / 2') // 3
```
# Com ponto flutuante
```
calcular('10.1 + 10.2') // 20
```
# Com parâmetros
```
calcular('{0}+({1}*{2})', '10,1', 10.2, 2) // 31
```
# Problemas
```
calcular('1.000 + 1') // 2, o número "1.000" deveria ser mil ou um?
```
