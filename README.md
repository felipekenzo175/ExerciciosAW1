# ExerciciosAW1
1. 
a)
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobrescrito e Subscrito</title>
</head>
<body>
    <p>No 4<sup>th</sup> de setembro, você aprenderá sobre E = MC<sup>2</sup>.<br>
    A quantidade de CO<sub>2</sub> na atmosfera aumentou em 2ppm em 2009<sub>1</sub>.</p>
</body>
</html>
b)
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Strong</title>
</head>
<body>
    <p><strong>Cuidado:</strong> Os batedores de carteira roubam nesta área.<br>
    Este brinquedo tem muitos pedaços pequenos e <strong>não é adequado para crianças com menos de cinco anos.</strong></p>
</body>
</html>
c)
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emphasis</title>
</head>
<body>
    <p>Eu <em>acho</em> que Ivy foi o primeiro. <br>
    Eu acho que <em>Ivy</em> foi o primeiro.<br>
    Eu acho que Ivy foi o <em>primeiro</em>.</p>
</body>
</html>
d)
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Citações</title>
</head>
<body>
    <p><blockquote>For 50 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWT works in 100 cuntries and is supported by 1.2 milion members in the United States and close to 5 milion globally.</blockquote> <br>
    Como Alan Alexander Milne disse, <q>Some people talk to animals. Not many listen though. That's the problem.</q></p>
</body>
</html>
e)
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Definições</title>
</head>
<body>
    <p><dfn>Um buraco negro</dfn> é uma região no espaço da qual nada, nem mesmo a luz, pode escapar.</p>
</body>
</html>
f)
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Citações</title>
</head>
<body>
    <p>A <abbr title="World Health Organization">WHO</abbr> foi fundada em 1948.</p>
</body>
</html>
Exercícios DW1 Aula 5
1. <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabelas</title>
</head>
<body>
    <table>
        <tr>
            <th>Quantidade</th>
            <th>Salgado</th>
            <th>Preço: Reais</th>
        </tr>
        <tr>
            <th>100</th>
            <th>Coxinha</th>
            <td rowspan="4">50</td>
        </tr>
        <tr>
            <th>100</th>
            <th>Bolinho de Queijo</th>
        </tr>
        <tr>
            <th>100</th>
            <th>Risóles de Carne</th>
        </tr>
        <tr>
            <th>100</th>
            <th>Quibe</th>
        </tr>
    </table>
</body>
</html>
2.
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabelas</title>
</head>
<body>
    <form>
        <fieldset>
            <legend> Informações Pessoais </legend>
            <p>    
                <label for="nome_id">Nome: </label>
                <input type="text" name="nome" id="nome_id" 
                placeholder="Aline Paixão Bueno" 
                title="Digite conforme o exemplo">
            </p>
            <p>
                <label for="dataNascimento_id">Data Nascimento: </label>
                <input type="date" name="dataNascimento" id="dataNascimento_id"
                placeholder="05/07/2002"
                title="Digite conforme o exemplo">
            </p>
            <p>
                <label for="sexo_id">Sexo: </label>
                <input type="text" name="sexo" id="sexo_id"
                placeholder="">
            </p>
        </fieldset>
    </form>
</body>
</html>

EXERCÍCIOS 19/04
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS</title>
    <style type="text/css">
        .minha-classe{
            font-size: 200%;
        }
    </style>
</head>
<body>
    <p class="minha-classe">texto1</p>
    <p class="minha-classe">texto2</p>
</body>
</html>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS</title>
    <style type="text/css">
        #meu-id{
            font-size: 200%;
        }
    </style>
</head>
<body>
    <p id="meu-id">texto1</p>
    <p id="meu-id2">texto2</p>
</body>
</html>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS</title>
    <style type="text/css">
        body {
            font-family: arial;
            background-color: hsla(160, 68%, 50%, 0.623);}
        h1 {
            color: hsl(170, 90%, 67%);
        }
        p {
            color: hsl(128, 88%, 44%);
        }
    </style>
</head>
<body>
    <h1>Lorem ipsun</h1>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Unde aperiam quasi expedita in vero inventore minus odio, ea numquam explicabo ratione nulla soluta sunt aspernatur magnam dicta accusamus recusandae accusantium.</p>
</body>
</html>
