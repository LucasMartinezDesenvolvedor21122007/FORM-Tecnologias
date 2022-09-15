<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
</head>
<body>
   
<div>
    <h1 id="titulo">Cadastro De DEVs</h1>
    <p id="subtitulo">Complete suas informações</p>
    <br>
</div>

<form>
    <fieldset class="Grupo">
        <div>
            <label><strong>Nome</strong></label>
            <input type="text" name="nome" id="nome" required>
        </div class="campo">

<div class="campo">
    <label><strong><Strong>Sobrenome</Strong></strong></label>
    <input type="text" name="Sobrenome" id="Sobrenome" required>
</div class="campo">
</fieldset class="Grupo">

<div class="campo">
    <label for="email"><strong>email</strong></label required>
    <input type="email" name="email" id="email">
</div class="campo">
<br>
<div class="campo">
    <label for="Lado Da aplicação">De Qual Lado Da Aplicação Você Desenvolve</label>
    <label for="Desenvolvimento">
        <input type="radio" name="devweb" value="Front-End" checked>Front-end
        <input type="radio" name="devweb" value="Back-End">Back-end
        <input type="radio" name="devweb" value="Full-Stack">Full-stack
    </label>
</div class="campo">

<div class="campo">
    <label for="senioridade">Senioridade</label>
    <select id="Senioridade">
    <option selected disabled value="">Escolha</option>
     <option>Junior</option>
     <option>Pleno</option>
     <option>Sênior</option>   
    </select>
</div class="campo">

<fieldset class="Grupo">
    <div class="campo">
        <label>Selecione as tecnologias que utiliza:</label><br><br>
        <input type="checkbox" id="tecnologia1" name="tecnologia1" value="HTML">
        <label>HTML</label>
        <input type="checkbox" id="tecnologia2" name="tecnologia2" value="CSS">
        <label>CSS</label>
        <input type="checkbox" id="tecnologia3" name="tecnologia3" value="Javascript">
        <label>Javascript</label>
        <input type="checkbox" id="tecnologia4" name="tecnologia4" value="PHP">
        <label>PHP</label>
        <input type="checkbox" id="tecnologia5" name="tecnologia5" value="React Native">
        <label>React Native</label>
        <input type="checkbox" id="tecnologia6" name="tecnologia6" value="AngularJS">
        <label>AngularJS</label>
        <input type="checkbox" id="tecnologia7" name="tecnologia7" value="TypeScript">
        <label>TypeScript</label>
    </div class="campo">
</fieldset class="Grupo">

<div class="campo">
    <br>
    <label<strong>for="experiencia">Conte um pouco da sua experiência</strong></label>
    <textarea rows="6" style="width: 26em" id="experiencia" name="experiencia"></textarea>
    <button type="submit">Concluido</button>
</div class="campo">

</form>


</body>
</html>
