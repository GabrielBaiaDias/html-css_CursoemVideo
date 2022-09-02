# html-css
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<style>
    section#internalReadme {
        text-align: center;
    }

    .pastasMaisArquivos {
        width: 160px;
        background-color: rgba(176, 176, 176, 0.396);
        padding: 10px;
        padding-top: 0px;
        border-radius: 5px;
        border: 2px solid black;
    }

    .pastasMaisArquivos > h2 {
        margin-top: 5px;
        font-family: monospace;
    }
</style>

<body>
    <section id="internalReadme">
        <h1>Bem vindo ao meu readme</h1>
        <h2>Exercícios</h2>
    </section>
    <a href="https://gabrielbaiadias.github.io/html-css/Exercicios/ex-001/">1</a>
    <div id="exer">
    </div>
    <div>
        <h2>pasta do ex007</h2>
    </div>
</body>

</html>
<script>
    var ex = document.getElementById('exer');
    for (var cont = 2; cont < 5; cont++) {
        ex.innerHTML += `<a href="https://gabrielbaiadias.github.io/html-css/Exercicios/ex00${cont}">${cont}</a><br/>`;
        if (cont == 4) {
            ex.innerHTML += "<a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex005/'>5</a>- (pasta vazia)<br/>"
        }
    }
    for (var cont = 6; cont < 7; cont++) {
        ex.innerHTML += `<a href="https://gabrielbaiadias.github.io/html-css/Exercicios/ex00${cont}">${cont}</a><br/>`;
        if (cont == 6) {
            ex.innerHTML += "<div class='pastasMaisArquivos' id='a'><h2>pasta do ex007</h2><a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex007/html4.html'>7</a>- (html4.html)<br/><a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex007/html5.html'>7</a>- (html5.html)<br/></div>"
        }
    }
    for (var cont = 8; cont < 10; cont++) {
        ex.innerHTML += `<a href="https://gabrielbaiadias.github.io/html-css/Exercicios/ex00${cont}">${cont}</a><br/>`
    }
    for (var cont = 10; cont < 16; cont++) {
        ex.innerHTML += `<a href="https://gabrielbaiadias.github.io/html-css/Exercicios/ex0${cont}">${cont}</a><br/>`
        if (cont == 15) {
            ex.innerHTML += "<a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex016/cor01.html'>16</a>- (cor01.html)<br/><a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex016/cor02.html'>16</a>- (cor02.html)<br/><a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex016/cor03.html'>16</a>- (cor03.html)<br/>"
        }
    }
    ex.innerHTML += "<a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex017/font01.html'>17</a>- (font01.html)<br/>"
    ex.innerHTML += "<a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex017/font02.html'>17</a>- (font02.html)<br/>"
    ex.innerHTML += "<a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex018/fonte01.html'>18</a>- (fonte01.html)<br/>"
    ex.innerHTML += "<a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex018/fonte02.html'>18</a>- (fonte02.html)<br/>"
    ex.innerHTML += "<a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex019/seletor01.html'>19</a><br/>"
    ex.innerHTML += "<a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex020/hover.html'>20</a>- (hover.html)<br/>"
    ex.innerHTML += "<a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex020/links.html'>20</a>- (links.html)<br/>"
    ex.innerHTML += "<a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex020/pseudoclasse.html'>20</a>- (pseudoclasse.html)<br/>"
    for (var cont = 1; cont < 4; cont++) {
        ex.innerHTML += `<a href="https://gabrielbaiadias.github.io/html-css/Exercicios/ex021/caixa0${cont}.html">21</a>- (caixa0${cont}.html)<br/>`
    }
    for (var cont = 1; cont < 8; cont++) {
        ex.innerHTML += `<a href="https://gabrielbaiadias.github.io/html-css/Exercicios/ex022/fundo00${cont}.html">22</a>- (fundo00${cont}.html)<br/>`
    }
    ex.innerHTML += `<a href="https://gabrielbaiadias.github.io/html-css/Exercicios/ex023/Tabela001.html">23</a>- (tabela001.html)<br/>`
    for (var cont = 2; cont < 7; cont++) {
        ex.innerHTML += `<a href="https://gabrielbaiadias.github.io/html-css/Exercicios/ex023/tabela00${cont}.html">23</a>- (tabela00${cont}.html)<br/>`
    }
    for (var cont = 1; cont < 7; cont++) {
        ex.innerHTML += `<a href="https://gabrielbaiadias.github.io/html-css/Exercicios/ex024/iframe00${cont}.html">21</a>- (iframe00${cont}.html)<br/>`
    }
    for (var cont = 1; cont < 4; cont++) {
        ex.innerHTML += `<a href="https://gabrielbaiadias.github.io/html-css/Exercicios/ex025/form00${cont}.html">21</a>- (form00${cont}.html)<br/>`
    }
    // ex.innerHTML += "<a href='https://gabrielbaiadias.github.io/html-css/Exercicios/ex022/.html'>22</a>- (.html)<br/>"

</script>