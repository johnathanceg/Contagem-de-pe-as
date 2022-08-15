//Cadastro de Peças
const entrada = require("readline-sync");
let listaPecas = 11;
let peso = 80;
let nomePeca = "Pistão do Motor"; //string
let nome = entrada.question("Qual o nome da Peca?");

if(nome = "Pistao do Motor"); {
    console.log("Obrigado");

} 

if(peso >= 100 ){
    console.log("Peça tem peso permitido para cadastrar");
} else {
    console.log("Peça muito leve");
}

if(listaPecas >= 10){
    console.log("O numero de Usuarios ja esta no limite");
}

if(nomePeca.length < 3) {
    console.log("Nome muito Curto!!");
}

console.log("Fim do Programa");
