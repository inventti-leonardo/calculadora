# Calculadora 
# Exemplos
```
calcular('1 + 1,00 + 1.00') // 3
calcular('1000 + 1000,00 + 1000.00 + 1.000,00 + 1.000.00') // 5000
calcular('1000000 + 1000000,00 + 1000000.00 + 1.000.000,00 + 1.000.000.00') // 5000000
calcular('1aaa + bbb1 + c1c') // 3
calcular('R$1,00 + 1') // 2
calcular('2pc * R$3,00') // 6
calcular('(2pc * R$3,00) / 2') // 3
calcular('1,123456789 / 1.123456789') // 1
calcular('10.1 + 10.2') // 20, corrigindo problema de ponto flutuante do js
```
# Problemas
```
calcular('1.000 + 1') // 2, o número "1.000" deveria ser mil ou um?
```

