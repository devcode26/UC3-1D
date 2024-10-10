# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 

Certo

## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

aprendi sobre as variaveis: const, let, var, if, else, Switch, case, function, else if, Math.floor e Math.random
e aprendemos várias outras coisas também.

## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 

Aqui está monstrando as somas, subtração, multiplicação e divisão dos numeros
Aqui também está mostrando a função do if, else if, function, return, Math.floor e Math.random.
 
```js

const nome1 = "Gustavo"
const apelido = "Henrique"
const fullname = nome1 + " " + apelido

console.log("Meu nome é:" + fullname);

let a = 20
let b = 30 
let soma = a + b

console.log(soma)

let c =24
let d = 65
let subtrair = c - d

console.log(subtrair)

let e = 78
let f = 75
let multiplicar = e * f

console.log(multiplicar)


let g = 56
let h = 54
let dividir = g / h

console.log(dividir)

const pi = 23478

const be = 645
const circumference = 4 * pi * be;

console.log("a circunferencia é:" + circumference + " unidades ")
```
```JS
function soma(num1, num2) {
 return num1 + num2
};

if (num1 > num2) {
  console.log(soma(num1, num2))
} else if (num1 < num2) {
  console.log(sub(num1, num2))
} else {
  console.log("Dados inválidos")  
}

function aleatorio(min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}
