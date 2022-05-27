<!DOCTYPE html>
<html lang="pt-br">
<head>
    <title>DS Saúde</title>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./styler.css">

</head>

<body>

            <div class="box">
                <form action=
                    fieldset>
                        <legend><b>Cadastre suas informações</b></legend>
                        <br>
                        <div class="inputBox">
                            <input type="text" name="nome" id="nome" class="inputerUser" required>
                            <label for="nome">Nome Completo</label>
                        </div>
                        <br><br>
                        <div class="inputBox">
                            <input type="email" name="email" id="email" class="inputerUser" required>
                            <label for="email">Email</label>
                        </div>
                        <br><br>
                        <div class="inputBox">
                            <input type="tel" name="celular" id="Celular" class="inputerUser" required>
                            <label for="tel">Celular</label>
                        </div>
                        <br><br>
                        <div class="inputBox">
                            <input type="date" name="data-de-nascimento" id="data-de-nascimento" class="inputerUser" required>
                            <label for="data-de-nascimento" >Data de Nascimento:</label>
                        </div>
                        <br>
                        <input type="submit" name="submit" id="submit">
                    </fieldset>
                </form>
            </div>
    
        
</body>
</html>
