# Problema-2

Só precisamos somar os números paresTemos um número par a cada 3 números da sequência. Ao resultado de calcular todos os números da sequência e testar se o valor é par, podemos calcular de 3 em 3 e obter diretamente o resultado que queremos.
[code lang = "java" firstline = "1" toolbar = "true" collapse = "false" wraplines = "false"]
package com.loiane.projecteuler;public class Problem2 {public static void main (String [] args) {soma longa = 0;
prev longa = 1;
corrente longa = 2;
long n;enquanto (atual <4000000) {
soma = soma + corrente;
n = atual;
atual + = 2 * (atual + anterior);
prev + = 2 * n;
}System.out.println (soma);
}
}
[/ código]Para ver a solução, basta executar o código acima.
