# Formulario-da-Disney
Esse é um formulario da disney!

HTML:
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="shortcut icon" href="../img/favicon.ico" type="image/x-icon">
        <link rel="stylesheet" href="../css/style.css">
        <title>Login to Disney</title>
    </head>
    <body>
        <header class="container">
            <div class="container-header">
                <img src="../img/logo.png" alt="" class="logo">
                <form action="" class="box-form">
                    <div class="box-div-form">
                        <p class="passo1">passo 1</p>
                        <h1 class="text-digite-email">Digite o seu e-mail para continuar</h1>
                        <p class="text-entre-na-conta">
                            Entre na sua conta. Se você não tiver conta, 
                            precisará criar uma.
                        </p>

                        <label for="email"></label>
                        <input type="email" placeholder="E-mail" required class="email-input"><br>
                        <button class="container-box-continuar">
                            <p class="box-Continuar">Continuar</p>
                        </button>
                    </div>
                </form>
            </div>
        </header>

        <footer class="container-cabeçalho">
            <div class="cabeçalho">
                <ul class="box1-ul">
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                </ul>
    
                <p class="text-footer1">
                    Disney+ é um serviço pago, baseado em assinatura e sujeito a termos e condições. O serviço Disney+ é comercializado por The Walt Disney Company (Brasil) Ltda., World Trade Center, Av. Das Nações Unidas, 12.551, 12.555, 12.559, Piso 10, São Paulo/SP - CEP 04578-903, Brasil e CNPJ/M
                    <br>73.042.962/0004-20
                </p>
    
                <p class="text-footer2">
                    © Disney. Todos os direitos reservados.
                </p>
            </div>
        </footer>
    </body>
</html>



CSS:
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html, body {
    height: auto;
}

.container {
    background: #0E1746;
}


.container-header {
    background-color: inherit;
    height: 800px;
    text-align: center;
}

.logo {
    width: 180px;
}

.box-form {
    background-color: white;
    width: 25%;
    margin: 0 auto;
    padding: 50px;
    border-radius: 25px;
    border: 1px solid white;
    height: 370px;
    width: 600px;
}

.box-div-form {
    text-align: left;
}

.passo1 {
    text-transform: uppercase;
    color: #252526;
    font-weight: bold;
    margin: 0px 10px 0px 0px;
}

.text-digite-email {
    color: #252526;
    font-weight: bold;
    margin: 10px 0;
}

.text-entre-na-conta {
    letter-spacing: 2px;
    margin: 10px 0;
}

.email-input {
    padding: 15px;
    width: 500px;
    background-color: #ebe1e1;
    border: none;
    border-radius: 3px;
    padding: 20px;
}

.email-input:focus {
    outline: 0;
    border-bottom: 3px solid black;
}

.email-input:focus::placeholder {
    position: relative;
    bottom: 15px;
    font-size: 12px;
}

.container-box-continuar  {
    color: white;
    padding: 10px;
    background-color: #0058E1;
    border: none;
    border-radius: 20px;
    width: 500px;
    padding: 20px;
    margin: 20px 0;
    font-size: 20px;
}

.container-box-continuar:hover {
    cursor: pointer;
    background-color: #3168c2;
    transition: 10ms;
}



