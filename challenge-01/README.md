# Desafio Semana #1

```js
// Declarar uma variável chamada `myvar`, sem valor.
var myvar;

// Após declarada, atribua o valor 10 à variável `myvar`.
var myvar = 10;

// Declare uma nova variável chamada `soma`, e adicione uma instrução somando os valores 15 e 8.
var soma = (15+8);

// Atribua à variável `soma` todo o valor dela, somando 1, usando o operador de soma abreviado.
var soma = (15+8) 
soma +=1;

// Atribua à variável `soma` todo o valor dela, multiplicando por 3, usando o operador de multiplicação abreviado.
var soma = (15+8)
 soma *=3;

// Qual é o valor da variável `soma` até aqui?
69

// Declare uma variável chamada `souninja`, atribuindo à ela o valor booleano que representa `verdadeiro`.
var souninja = true;

// Declare uma variável chamada `comida` que recebe um array com os valores 'numarroz', 'feijão' e 'ovo'.
var comida = ["arroz", "feijão", "ovo"];

// Digite a instrução que imprime o valor de 'feijao', que está na variável `comida`.
comida[1];

// Digite o código que verifica se a variável `soma' é igual a variável `myvar` (testando também o tipo).
soma == myvar; //testa se são iguais
soma ==== myvar; //testa se são iguais e o mesmo tipo 

// Digite o código que verifica se a variável `myvar` é menor ou igual à variável `soma`.
myvar <= soma;

// Crie uma função chamada `divisao` que receba como parâmetro dois números, e retorne o resultado da divisão entre eles.
//solução 1
function divisao(num1,num2){
    var num1 =4;
    var num2 =2;
    divisao = num1/num2;
    return divisao;

}

//segunda forma de fazer
function divisao(num1=4,num2=2){
    divisao = num1/num2;
    return divisao;
}


// Invoque a função criada acima, passando os parâmetros 10 e 2.
function divisao(num1=10,num2=2){
    divisao = num1/num2;
    return divisao;
}
