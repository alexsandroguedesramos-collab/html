<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog</title>

    <style>
        header {
            background-color: #183C63;
            color: #FFFFFF;
            text-align: center;
            max-width: 800px;
            margin: 0 auto;
        }

        main {
            background-color: #FFFFFF;
            color: #183C63;
            text-align: center;
            max-width: 800px;
            margin: 0 auto;
        }
    </style>
</head>

<body>

    <header>
        <h1>Meu blog tech</h1>
        <p>Vou compartilhar conhecimentos sobre tecnologia e programação</p>
    </header>

    <main>

        <!-- Usei a tag article porque ela representa um conteúdo independente,
             como uma postagem de blog, tornando a estrutura mais semântica e organizada. -->
        <article>

            <h2>Meu primeiro post</h2>

            <p>Por: Marcelo Paludetto</p>

            <p>
                Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de
                programação e curiosidades da área de tecnologia.
            </p>

            <h3>Sobre a estrutura HTML</h3>

            <p>
                Quando falamos de uma página na internet, ela sempre possui uma
                estrutura. Essa estrutura começa com uma tag e termina com outra.
                Depois disso, o arquivo é enviado para o navegador, como o Google
                Chrome, que interpreta o conteúdo.
            </p>

            <p>
                Uma página pode ser acessada por computadores, celulares, tablets
                e outros dispositivos. Por isso, precisamos organizar o conteúdo
                corretamente para que todos consigam visualizar e interpretar a
                página da melhor forma possível.
            </p>

            <h3>Importância das configurações do documento</h3>

            <p>
                A configuração &lt;meta charset="UTF-8"&gt; permite que acentos,
                cedilhas e caracteres especiais do português sejam exibidos
                corretamente.
            </p>

            <p>
                Já a configuração
                &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
                ajuda a página a se adaptar a diferentes tamanhos de tela,
                melhorando a experiência em dispositivos móveis.
            </p>

            <h3>Credibilidade e autoria</h3>

            <p>
                Informar quem escreveu o conteúdo é uma forma de aumentar a
                credibilidade da informação publicada. Quando conhecemos a pessoa
                autora, podemos compreender melhor sua área de atuação e avaliar
                a confiabilidade do conteúdo apresentado.
            </p>

        </article>

    </main>

</body>

</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo Box Model</title>

    <style>
        header {
            background-color: #183C63;
            color: #FFFFFF;
            text-align: center;
            max-width: 800px;
            margin: 0 auto;          /* espaçamento externo e centralização */
            padding: 16px;           /* espaçamento interno */
            border: 5px solid #cf1010; /* borda */
        }

        main {
            max-width: 800px;
            margin: 20px auto;
            padding: 16px;
            border: 2px solid #333;
        }
    </style>
</head>
<body>

    <header>
        <h1>Meu Site</h1>
        <p>Exemplo de Header com Border, Padding e Margin</p>
    </header>

    <main>
        <h2>Conteúdo Principal</h2>
        <p>
            Este conteúdo está dentro da área principal da página.
            Observe o espaçamento interno (padding), a borda (border)
            e o espaçamento externo (margin).
        </p>
    </main>

</body>
</html>
