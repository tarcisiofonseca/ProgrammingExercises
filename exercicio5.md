# Exercício 5

## Questão 1

a) A linha __/* Programa exemplo01.cpp */__ se trata de um comentário nas linguagens C/C++. Assim sendo, comentários não fazem
alterações no programa.

b) Caso a linha 2 seja removida, o programa apresentará um erro na compilação, pois __using namespace std__ indica o escopo de nomes
que o compilador deve usar. Caso essa linha seja retirada, é necessário indicar esse escopo manualmente, adicionando _std::_ antes do cout
utilizado no programa de exemplo. Como isso não foi feito, o compilador não vai reconhecer o comandos usado, resultando em falha na
compilação

c) O nome da função _main_ não pode ser modificado, pois o compilador busca uma função com esse nome para saber por onde começar
a compilar. Sem essa função, o programa não será compilado. A única forma de permitir essa mudança é também modificando o código do 
compilador e inserindo nele o nome da nova função principal do programa.

## Questão 2

Comentários são partes do código que não alteram o programa final, funcionando como anotações. Em C/C++, podem ser representados por //
para comentários de apenas uma linha ou com \/*  \*/ para comentários de mais de uma linha.

## Questão 3

Linha 6: declara uma varíavel do tipo inteiro chamada i
Linha 7: mostra na tela "Digite um número: "
Linha 8: recebe um número inteiro do usuário e o armazena na variável i
Linha 9: escreve na tela "Número digitado foi " seguido do valor de i

## Questão 4

Variável é um endereço da memória onde é alocado um valor. Além disso, através desse endereço, esse valor pode ser encontrado
posteriormente e usado para fazer operações nos programas.

## Questão 5

Na primeira saída, as aspas em "i * j" representam uma string, então é exatamente isso que será a saída: "i * j".
Na segunda saída, como não há aspas, i * j representa uma multiplicação entre dois inteiros, então a saída será o produto deles: 20.
