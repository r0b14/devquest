# CSS Básico

## CSS Inline

é quando usando o atributo style dentro da tag html.
Ex:

```HTML
    <!DOCTYPE html>
    <html>
        <body>
            
            <h1 style="color:blue;text-align:center;">This is a heading</h1>
        <p style="color:red;">This is a paragraph.</p>

    </body>
    </html>
```

## CSS Interno

O css vai ser interno ao html, porém estará entre as tags styles.

```html
    <!DOCTYPE html>
    <html>
    <head>
        <style>
        body {
        background-color: linen;
        }

        h1 {
        color: maroon;
        margin-left: 40px;
        }
        </style>
    </head>
        <body>

        <h1>This is a heading</h1>
        <p>This is a paragraph.</p>

        </body>
    </html>

```

*atalho*
`alt` + `l` depois `o` => permite inicializar o live server
`ctrl` + `p` => caixa de diálogo para poder escolher o que deseja abrir

## CSS Externo

O arquivo CSS externo vai ser referenciado internamente no html através da tag link.
Esse é o modo mais correto de se usar e o mais usual no mercado.

```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="mystyle.css">
</head>
<body>

    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>

</body>
</html>
```