# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 

Certo

## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

aprendi sobre as variaveis: const, let, var, if, else, Switch, case, function, else if, Math.floor, Math.radom e array
e aprendemos várias outras coisas também.

## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 

Aqui está monstrando as somas, subtração, multiplicação e divisão dos numeros
Aqui também está mostrando a função do if, else if, function, return, Math.floor e Math.random.

## String

```JS
const nome = "Ana";
const sobrenome = "Olá, " + nome + "! Como vc está?";
console.log(sobrenome);Olá, Gustavo! Como você está?

```

## Number

```JS
let idade = 25;
console.log("Idade:");

// Operações com números
let soma = idade;
console.log("soma");
```

## Boolean

```JS
let estaChovendo = true;
let temCarro = false;

console.log("Está chovendo?", estaChovendo);  // true
console.log("Tem carro?", temCarro);  // false

// Exemplo de uso em uma condicional
if (estaChovendo) {
  console.log("Leve um guarda-chuva!");
} else {
  console.log("Aproveite o tempo ensolarado!");
}
```

## Array

```JS
let frutas = ["Maçã", "Banana", "Laranja"];
console.log("Frutas:", frutas);

// Acessando elementos do array
console.log("Primeira fruta:", frutas[0]);  // Maçã
console.log("Segunda fruta:", frutas[1]);  // Banana

// Adicionando um novo item ao array
frutas.push("Abacaxi");
console.log("Frutas atualizadas:", frutas);

// Exemplo de array com diferentes tipos de dados
let misturado = [10, "Texto", true, {chave: "valor"}, [1, 2, 3]];
console.log("Array misturado:", misturado);
```

## Condicionais

```JS
// Função simples que retorna a soma de dois números
function soma(num1, num2) {
  return num1 + num2;
}

// Usando a função com uma condicional
let x = 10;
let y = 5;

if (x > y) {
  console.log("A soma é:", soma(x, y));
} else if (x < y) {
  console.log("A subtração é:", x - y);
} else {
  console.log("Os números são iguais");
}

// Função para gerar número aleatório
function numeroAleatorio(min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}

console.log("Número aleatório entre 1 e 100:", numeroAleatorio(1, 100));
```
