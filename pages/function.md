# [Hello-World](https://github.com/sswellington/hello-world/tree/master/)

## Function

### Velocidade média
Cálculo de velocidade média (Vm) de um veiculo, o tempo que ele está na estrada (t) e o total a ser percorrido quando a viajem terminar (S ), a função deverá retornar quantos quilômetros faltam para terminara viajem.
Obs.1: O total já percorrido pode ser calculado como Vm * t 
#### Solução
* [Pascal](https://github.com/sswellington/hello-world/tree/master/src/function/pascal/velocidade-media.pas)

### Somatório
Faça um programa, com uma função que necessite de três argumentos, e que forneça a soma desses três argumentos.
#### Solução


### Imprimir matriz
Escreva uma função imprime_matriz(matriz), 
que recebe uma matriz como parâmetro e imprime a matriz, 
linha por linha. 
Note que NÃO se deve imprimir espaços após o último elemento de cada linha!

Exemplos:

minha_matriz = [[1], [2], [3]]

imprime_matriz(minha_matriz)
* 1
* 2
* 3

minha_matriz = [[1, 2, 3], [4, 5, 6]]
imprime_matriz(minha_matriz)
* 1 2 3
* 4 5 6

#### Solução
* [Python](https://github.com/sswellington/hello-world/tree/master/src/function/python/matriz-imprimir.py)


### Soma de matrizes
Escreva a função soma_matrizes(m1, m2) que recebe 2 matrizes e devolve uma matriz que represente sua soma caso as matrizes tenham dimensões iguais. 
Caso contrário, a função deve devolver False.

Exemplos:
* m1 = [[1, 2, 3], [4, 5, 6]]
* m2 = [[2, 3, 4], [5, 6, 7]]
* soma_matrizes(m1, m2) => [[3, 5, 7], [9, 11, 13]]
* m1 = [[1], [2], [3]]
* m2 = [[2, 3, 4], [5, 6, 7]]
* soma_matrizes(m1, m2) => False
#### Solução 
* [Python](https://github.com/sswellington/hello-world/tree/master/src/function/python/matriz-soma.py)

### Matrizes multiplicáveis
Duas matrizes são multiplicáveis  se o número de colunas da primeira é igual ao número de linhas da segunda. 

Escreva a função sao_multiplicaveis(m1, m2) que recebe duas matrizes como parâmetro 
e devolve True se as matrizes forem multiplicavéis (na ordem dada) e False caso contrário.

Exemplos:
* m1 = [[1, 2, 3], [4, 5, 6]]
* m2 = [[2, 3, 4], [5, 6, 7]]
* sao_multiplicaveis(m1, m2) => False
* m1 = [[1], [2], [3]]
* m2 = [[1, 2, 3]]
* sao_multiplicaveis(m1, m2) => True 
#### Solução 
* [Python](https://github.com/sswellington/hello-world/tree/master/src/function/python/matriz-multiplicacao.py)

### Verificador de CPF
Faça um programa que verifica um CPF
* Verificar se o CPF informado contém todos os dígidos nem são repetidos
* Confirmar se o primeiro dígito do verificador está correto
* Confirmar se o segundo dígito do verificador está correto
* Validar o CPF
* Informar o estado emissor do CPF
#### Solução