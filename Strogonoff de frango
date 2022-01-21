const prompt = require('prompt-sync')();

console.log("------------RESPONDA COM sim ou nao
console.log("--------------");
console.log("Sua esposa te manda ir ao mercado comprar ingredientes de um strogonoff, porem não te deu uma lista com os itens que falta, ela acha que voce sabe quais sao.");
console.log("--------------");
console.log("Logo quando você chega em casa, ela te pergunta sobre os itens que voce tinha que comprar");
console.log("--------------");

var sim = 0;
var nao = 0;

var frango = prompt("Voce comprou o peito de frango? ");
if ( frango == "sim") {
    sim = sim+1;
  }else if(frango == "nao") {
    nao = nao+1;
}

var batataPalha = prompt("Voce comprou a batata palha? ");
if ( batataPalha == "sim") {
    sim = sim+1;
  }else if(batataPalha == "nao") {
    nao = nao+1;
}

var ketchup = prompt("Voce comprou o ketchup? ");
if ( ketchup == "sim") {
    sim = sim+1;
  }else if (ketchup == "nao") {
    nao = nao+1;
}

var mostarda = prompt("Voce comprou a mostarda? ");
if ( mostarda == "sim") {
    sim = sim+1;
  }else if(mostarda == "nao") {
    nao = nao+1;
}

var creme = prompt("Voce comprou o creme de leite? ");
if ( creme == "sim") {
    sim = sim+1;
  }else if(creme == "nao") {
    nao = nao+1;
  }

console.log("sim - ", sim, " nao - ", nao);

if (sim == 0) {
    console.log("Voce nao comprou nada que precisava, voce tomou um tabefe da sua esposa.");
}else if(sim == 1 || sim == 2) {
    console.log("Voce comprou menos da metade dos ingredientes, CORRA! pois sua esposa esta furiosa.");
}else if (sim == 3){
    console.log("Voce comprou metade dos ingredientes, sua esposa te chamou de burro. Voce esta triste :(");
}else if (sim == 4) {
    console.log("voce comprou mais da metade dos ingredientes, sua esposa te mandou voltar e comprar o restante.")
}else{
    console.log("PARABENS!! voce comprou todos os ingredientes, sua esposa te deu um beijo de recompensa!")
}
