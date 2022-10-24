# Código do Projeto

Mantenha neste diretório todo o código fonte do projeto. 

Se necessário, descreva neste arquivo aspectos relevantes da estrutura de diretórios criada para organização do código.

//Pagina de login //
html ==>
<!DOCTYPE html>

<html lang="pt-br">

    <head>

        <meta charset="UTF-8">

        <meta http-equiv="X-UA-Compatible" content="IE=edge">

        <meta name="viewport"content="width=device-width, initial-scale=1.0">

        <link rel="stylesheet" href="style.css">

        <title>Login</title>

    </head>

    <body>

        <div id="login">

            <form class="card">

                <div class="card-header">

                    <h2>Entrar</h2>

                </div>

                <div class="card-content">

                    <div class="card-content-area">

                        <label for="usuario">Usuário</label>

                        <input type="text" id="usuario" autocomplete="off">

                    </div>

                    <div class="card-content-area">

                        <label for="password">Senha</label>

                        <input type="password" id="password" autocomplete="off">

                    </div>

                </div>

                <div class="card-footer">

                    <input type="submit" value="login" class="submit">

                    <a href="#" class="recuperar_senha">Esqueceu a senha?</a>

                </div>

            </form>

        </div>

    </body>

</html>



 Css ==>
 
 
 body {

    padding: 0;

    margin: 0;

    background-color: #3c253d;

}

#login {

    display: flex;

    align-items: center;

    justify-content: center;

    height: 100vh;

    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;

}

.card {

    background-color:black;

    padding: 40px;

    border-radius: 2px;

    width:280px;

}

.card-header {

    padding-bottom: 50px;

    opacity: 0.8;

    color:white;

}

.card-header::after {

    content: "";

    width: 70px;

    height: 1px;

    background-color: white;

    display: block;

    margin-top: -17px;

    margin-left: -5px;

}

.card-content label {

    color: white;

    font-size: 20px;

    opacity: 0.8;

}

.card-content-area {

    display: flex;

    flex-direction: column;

    padding:10px 0;

}

.card-content-area input {

    margin-top: 10px;

    padding:0 5px;

    background-color: transparent;

    border:none;

    border-bottom: 1px solid #d3cccc;

    outline: none;

    color: white;

}

.card-footer {

    display: flex;

    flex-direction: column;

}

.card-footer .submit{

    width: 100%;

    height: 40px;

    background-color: #183b46;

    border:none;

    color:#c0b6b6;

    margin: 10px 0;

}

.card-footer a {

    text-align: center;

    font-size: 20px;

    opacity: 0.8;

    color: white;

    text-decoration: none;

}

//fim do codigo da pagina de login// 

