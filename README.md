<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário</title>
</head>
<body>
    <h1>Formulário de Contato</h1>
    <form action="/submit_form" method="post">
        <label for="name">Nome:</label><br>
        <input type="text" id="name" name="name"><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br>
        <label for="message">Mensagem:</label><br>
        <textarea id="message" name="message" rows="4" cols="50"></textarea><br>
        <input type="submit" value="Enviar">
    </form>
</body>
</html>

