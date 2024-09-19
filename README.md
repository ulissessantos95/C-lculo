# Ca-lculo
Cálculo Simples

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Holerite</title>
</head>
<body>
    <h1>Exercício do beecrowd</h1>
    <h2>1008</h2>
    <button onclick="Executar1008()">Executar</button><br>
    
    <button onclick="Fulano()">Salario</button><br>

    <script src="script.js"></script>
    
</body>
</html>


*// estrutura funcão para Js

function Executar1008(){
    let Id, valorHora, salario;
    Id = Number(prompt("Digite seu id:"));
    horas = Number(prompt("Quantas horas trabalhou?"));
    valorHora = Number(prompt("Quanto você ganha por hora?"));

    salario = horas * valorHora

    alert("ID; "+Id+"\nSalario; R$" + salario.toFixed);

}

function Fulano(){
    let salarioFixo, comissão, vendedor, totaldeVendas, salariocombonus
    vendedor = (prompt("Digite o nome do vendedor"))
    salarioFixo = Number(prompt("Digite o salario Fixo"))
    totaldeVendas = Number(prompt("Digite o total de vendas"))
    comissão = totaldeVendas * 0.15
    salariocombonus = salarioFixo + comissão
    
    alert("vendedor" + vendedor+ "\n salario com bonus R$" + salariocombonus.toFixed(2))



}
