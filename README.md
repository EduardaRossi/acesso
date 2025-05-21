<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>Acesso negado ou liberado</title>
</head>
<body>
    <center>
        <h1>Login OU</h1>

        <script>
            var acesso = prompt("Digite o seu acesso")

            //Estrutura lógica - OU
            if(acesso == "SENAI" || acesso == "2025999") {
                document.write("Acesso liberado🤩")
            } else{
                alert("ACESSO NEGADO!😥")
            }
        </script>
    </center>
</body>
</html>
