<!DOCTYPE htmml>
<html lang="pt-br">


<head>

    <title> Média Bimestral </title>

</head>

<body>

    <h1> Média Bimestral </h1>

    <p> Aplicando conceitos de lógica de programação em um cálculo de média
    </p>


</body>

<script>

    var nome = prompt("Insira seu nome: ");

    alert("Bem vindo Sr. " + nome);

    var nota1 = prompt("Insira sua primeira nota ");
    var nota2 = prompt("Insira sua segunda nota ");                      
    var nota3 = prompt("Insira sua terceira nota ");

    var soma = (parseInt(nota1) + parseInt(nota2) + parseInt(nota3));
    var media = (soma / 3);

    document.write("A soma de suas notas é: " + soma + "<br>");
    document.write("A média de suas notas é: " + media + "<br>");

    if (media > 8) {
        document.write("Parabéns, você foi aprovado");

    } else {
        document.write("Reprovado, estude um pouco mais!");

    }

</script>

</html>



</doctype>