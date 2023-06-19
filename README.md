# 7DaysOfCode.Day03
7DaysOfCode.Day03

const area = prompt("Você deseja seguir na área de 'Front-End' ou de 'Back-End'?");
let linguagem = "";
if (area === "Front-End"){
    linguagem = prompt("Você quer aprender React ou Vue?");
}
else if (area === "Back-End"){
    linguagem = prompt("Você quer aprender C# ou Java?");
}
else {
    alert("Você não inseriu uma área válida!");
}

const especialidadeOuFullstack = prompt("Digite 1 para seguir se especializando na área escolhida ou 2 para seguir se desenvolvendo para se tornar Fullstack");
if (especialidadeOuFullstack == 1){
    alert(`Continue se especializando em ${linguagem} para dominar a área de ${area}!`);
}
else if (especialidadeOuFullstack == 2){
    alert(`Chegou a hora de começar a aprender outras linguagens além de ${linguagem} se você quer se tornar Fullstack!`);
}
else {
    alert("Você não inseriu um valor válido!");
}

let msg = prompt("Tem mais alguma tecnologia que você gostaria de aprender? Digite 'sim' em caso positivo.");
while (msg === "sim"){
    let novaTecnologia = prompt("Qual a outra tecnologia gostaria de aprender?");
    alert(`${novaTecnologia} é realmente uma tecnologia muito interessante!`)
    msg = prompt("Tem mais alguma tecnologia que você gostaria de aprender? Digite 'sim' em caso positivo.");
}
if (msg != "sim")
    alert ("Bons estudos e sucesso na área escolhida!")
