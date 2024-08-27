# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

```js
const nome = "Douglas"
console.log(nome)
```
# Switch
```js
switch(produto){
  case "Laranja":
    console.log("Laranja custa R$5,00")
    break;
  case "Morango":
    console.log("Morango custa R$10,00")
    break;
  default:
    console.log("Lamentamos, esta fruta não está disponível no momento.")
}
```
# If e Else
```js
const nome = prompt("Qual o seu nome?");
const lanche = prompt("Digite seu lanche");
const combo = prompt("Deseja comprar o nosso combo?");
if (combo == "sim") {
  console.log(`Parabéns, ${nome}, você ganhou um brinde, meu nobre`);
} else {
  console.log("Muito obrigado(a), volte sempre");


const idade = prompt("Qual a sua idade?");

if (idade >= 18) 
{
  console.log(`Pode entrar na festa!`);
}

else if (idade > 15 && idade < 18)
{
  console.log(`Pode entrar na festa, mas não pode tomar bebida alcoólica.`);
} 

else
{
  console.log(`Aqui não é Mirabilândia.`);
}
```
# média de notas
```js
const nome = prompt("Qual o seu nome?");
const nota1 = prompt("Insira a nota de Português.");
const nota2 = prompt("Insira a nota de História.");
const nota3 = prompt("Insira a nota de Química.");
const nota4 = prompt("Insira a nota de Geografia.");
const nota5 = prompt("Insira a nota de inglês.");

const media = (parseInt(nota1) + (parseInt(nota2) + (parseInt(nota3) + (parseInt(nota4) + (parseInt(nota5)) / 5;

if (media >= 7) {
    console.log(`Parabéns, ${nome}! Você está aprovado(a).`)
} else if (media >= 4) {
    console.log(`Você está de recuperação, ${nome}.`)
} else {
    console.log(`Infelizmente, ${nome}, você está reprovado(a).`)
}

## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 
