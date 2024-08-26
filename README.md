# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.



## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 





//Array 
const time = ("Gustavo Henrique e Leandro Soares")
console.log(time)
const Fruta = prompt("Qual fruta você deseja comprar?")
const Hortfruiut = ["Uva", "maçã", "Melancia", "Banana", "Jaca"]

console.log(Hortfruiut.pop(3));
console.log(Hortfruiut.push("Manga", "Abacaxi", "Melão", "Cereja"));
console.log(Hortfruiut.sort());
console.log(Hortfruiut.length);
console.log(Hortfruiut)

switch(Fruta){
  case "Uva":
    console.log(`A Fruta ${Fruta} custa R$3;50`)
    break;
  case "maçã":
    console.log(`A Fruta ${Fruta}, custa R$4,50 por unidade`)
    break;
    case "Melancia":
    console.log(`A Fruta ${Fruta} custa R$12;50`)
    break;
    case "Banana":!
    console.log(`A Fruta ${Fruta} custa R$5;50`)
    break;
    default:
    console.log(`A Fruta ${Fruta} Está em falta no momento.`)
}
