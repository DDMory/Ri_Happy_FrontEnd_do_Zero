# ***Estrutura Básica do HTML***

## ***Introdução HTML***:

HTML não é uma lingugem de programação, mas sim de marcação para anotação de textos, imagens e outros recursos relacionados à exibição em um navergador web.

Consiste em 2 partes quando dentro de `<HTML></HTML>`:

- cabeça( `<head></head>` ): contém informações pre-carregadas antes da exibição do conteudo pro usuario.

- Corpo( `<body></body>` ): Informação que de fato é exibido ao usuario.

## ***Tags***:

Usadas como meio para estruturar a exibição de um navegador web, são delimitador por '<''>', normalmente, quando uma tag é aberta `<title>`, ela precisará ser fechada, `</title>`, mas há aquelas tags que não precisam ser fechadas

### ***Atributos***:

Configurações/propriedades para exibição de tags de maneira personaliada quando exibidas ao usuario, todas as tags podem ter certas propriedades alteradas, ex: `<strong id="titulo">`, o atributo id serve como identificador.

## ***Listas***:

### ***Lista ordenada*** 

```html
    ...
    <ol>
        <li> ITEM 1 </li>
        <li> ITEM 2 </li>
        <li> ITEM 3 </li>
            <OL>
                <li> ITEM 3.1 </li>
                <li> ITEM 3.2 </li>
                <li> ITEM 3.3 </li>
            </OL>
    </ol>
    ...

```

### ***Lista não ordenada***

```html
    ...
    <ul>
        <li> ITEM 1 </li>
        <li> ITEM 2 </li>
        <li> ITEM 3 </li>
    </ul>
    ...
```