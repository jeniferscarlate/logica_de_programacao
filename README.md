# logica_de_programacao

# Operadores em JavaScript

Aprendendo a utilizar os operadores na linguagem JavaScript.

## operadores-aritmeticos.js

Inicialmente, declaramos as variáveis com a palavra `const`

~~~js
const num1 = 30;
const num2 = 20;
~~~

Depois, realizamos as operações utilizando os operadores aritméticos:

*`+`: soma dois números  
*`-`: subtrai dois números  
*`*`: multiplica dois números  
*`/`: divide dois números  
*`%`: obtém o resto da divisão dos dois números

~~~js
console.log(`Os números usados são ${num1} e ${num2}

soma: ${num1} + ${num2} = ${num1 + num2}

subtração: ${num1} - ${num2} = ${num1 - num2}

multiplicação: ${num1} * ${num2} = ${num1 * num2} 

divisão: ${num1} / ${num2} = ${num1 / num2}

resto: ${num1} % ${num2} = ${num1 % num2}

potência do ${num1} ** ${num2} = ${num1 ** num2}
`);

~~~

As operações são realizadas no momento da impressão do resultado e não necessitam ser armazenadas em variáveis.

## operadores-atribuicao.js

~~~js
let num = 10;
~~~

Declaramos a variável `num` usando a palavra reservada `let`, pois essa variável será reatribuída ao longo do nosso código.

Em seguida, fazemos uma série de reatribuições utilizando os operadores de atribuição.

~~~js
console.log(`
O número inicial é: ${num}

Somando 10: ${num += 10}
Subtraindo 10: ${num -= 10}
Multiplicando 10: ${num *= 10}
Dividindo 10: ${num /= 10}
Elevando à potência de 10: ${num **= 10}
Obtendo o resto da divisão por 10: ${num %= 10}
incrementando 1: ${++num}
Decrementando 1: ${--num}

O número final é ${num}
`);
~~~

### Operadores de atribuição:

*`=`   -> atribui um novo valor para a variável  
*`+=`  -> O próprio valor somado ao novo valor  
*`-=`  -> O próprio valor subtraindo-se o novo valor  
*`*=`  -> O próprio valor multiplicado pelo novo valor  
*`/=`  -> O próprio valor dividido pelo novo valor  
*`**=` -> O próprio valor elevado à potência do novo valor  
*`%=`  -> O resto da divisão do próprio valor pelo novo valor  
*`++`  -> O próprio valor **incrementado (somado) com 1** (pode ser um _pré-incremento_ ou _pós-incremento_).  
*`--` -> O próprio valor **decrementado (subtraído) com 1** (pode ser um _pré-decremento_ ou _pós-decremento_). 