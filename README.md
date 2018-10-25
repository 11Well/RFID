# RFID
Sistema de segurança
<html>
    <head>
        <title></title>
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    </head>
    <body>
        <div>
            Login
        </div>
        <form action="controle.php" method="post">
            <input type="text" name="login" value="" />
            <input type="password" name="senha" value="" />
            <input type="submit" name="enviar" value="Login"/>
            <a href="cadastrar.php">Sem cadastro?</a>
        </form>
    </body>
</html>
Formulário de login
Figura 1: Formulário de login

Após a criação deste arquivo vamos criar o formulário de cadastro de usuário, assim, quem não possuir login e senha poderá realizar um cadastro rápido.

Listagem 2: Criando o arquivo cadastrar.php

<html>
    <head>
        <title></title>
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    </head>
    <body>
        <div>
            Cadastro de usuário
        </div>
        <form action="controle.php" method="post">
            <label>Login</label>
            <input type="text" name="login" value="" /><br />
            <label>Senha</label>
            <input type="password" name="senha" value="" /><br />
            <label>Tipo de usuário</label>
            <select name="tipo_usuario">
                <option value="">Selecione</option>
                <option value="1">Usuario Comum</option>
                <option value="2">Administrador</option>
            </select><br />
            <input type="submit" name="cadastrar" value="cadastrar"/>
        </form>
    </body>
</html>
