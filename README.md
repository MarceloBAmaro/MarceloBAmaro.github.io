<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
<style>
    * {
        border: 0px solid black;
        font-family: Arial, Helvetica, sans-serif;
    }
    li {
        margin: 0.4em;
    }

    a {
        /*color: rgb(182, 35, 35);*/
        color: rgb(5, 5, 212);
        text-decoration: none;
        cursor: pointer;
    }

    .JavaScript {
        width: fit-content;
    }

    .blocoexJS {
        background: #00000020;
        margin: auto;
        min-height: 2em;
        width: 19em;
        padding: 0.5em;
        border-radius: 10px;
        transition-delay: 1s;
        text-align: center;
    }

    .blocoexJS > ol {
        text-align: left;
    }

    .meu-site {
        background: #00000020;
        width: 20em;
        padding: 0.6em;
        border-radius: 10px;
        display: flex;
        align-items: center;
        justify-content: center;
    }
</style>

</head>
<body>
    <h1><a href="https://github.com/MarceloBAmaro" target="_blank">repositório público de Marcelo</a></h1>
    <div class="JavaScript">

        <div class="blocoexJS">
            <h2 id="exJS">exercicios de JavaScript</h2>
            <ol class="JavaScriptOl">
                <li><a href="https://marcelobamaro.github.io/meus-sites/javascript/ex1/"  rel="external" target="_blank">abas window</a></li>
                <li><a href="https://marcelobamaro.github.io/meus-sites/javascript/ex2/"  rel="external" target="_blank">soma com abas window</a></li>
                <li><a href="https://marcelobamaro.github.io/meus-sites/javascript/ex3/"  rel="external" target="_blank">style com JS</a></li>
                <li><a href="https://marcelobamaro.github.io/meus-sites/javascript/ex4/"  rel="external" target="_blank">interação com JS</a></li>
                <li><a href="https://marcelobamaro.github.io/meus-sites/javascript/ex5/"  rel="external" target="_blank">calculadora com JS</a></li>
                <li><a href="https://marcelobamaro.github.io/meus-sites/javascript/ex6/"  rel="external" target="_blank">simulação de radar com JS</a></li>
                <li><a href="https://marcelobamaro.github.io/meus-sites/javascript/ex7/"  rel="external" target="_blank">cidadania com JS</a></li>
                <li><a href="https://marcelobamaro.github.io/meus-sites/javascript/ex8/"  rel="external" target="_blank">serviço eleitoral</a></li>
                <li><a href="https://marcelobamaro.github.io/meus-sites/javascript/ex9/"  rel="external" target="_blank">relogio digital com JS</a></li>
                <li><a href="https://marcelobamaro.github.io/meus-sites/javascript/ex10/" rel="external" target="_blank">dia da semana com JS</a></li>
            </ol>
        </div>
        <h2>desafios de JavaScript</h2>
        <ul>
            <li><a href="https://marcelobamaro.github.io/meus-sites/desafio%20ficha%20de%20cadastro/" rel="external" target="_blank">ficha de cadastro</a></li>
            <li><a href="https://marcelobamaro.github.io/meus-sites/desafio%20tela%20de%20login/" rel="external" target="_blank">tela de login</a></li>
        </ul>
    </div>
    <div class="meu-site">
        <h2>manual do codigo</h2>
    </div>
    <script>
        var exJS = document.querySelector('div.blocoexJS')
        exJS.addEventListener('mouseenter', openexJS)
        exJS.addEventListener('mouseleave', closeJS)
        var JavaScriptOL = document.querySelector('ol.JavaScriptOl')
        JavaScriptOL.style.display = 'none'
        function openexJS() {
            JavaScriptOL.style.display = 'block'
        }

        function closeJS() {
            JavaScriptOL.style.display = 'none'
        }
    </script>
</body>
</html>
 
