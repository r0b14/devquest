## Tags HTML

#### 05 - Meta tags - configurando informações da sua página

Meta-tag ou meta-description é usada para poder descrever o conteúdo de uma página WEB. Isso permite os buscadores localizarem melhor o nosso site/conteúdo.
As descrições vão aparecer no mecanismo de busca (google, yahoo!)

*atalho* -> ctrl + u permite que consiga exibir o código fonte da página.

<meta>tags sempre vão dentro do elemento <head> e normalmente são usadas para especificar o conjunto de caracteres, descrição da página, palavras-chave, autor do documento e configurações da janela de visualização.

Os metadados não serão exibidos na página, mas podem ser analisados ​​por máquina.

Os metadados são usados ​​por navegadores (como exibir conteúdo ou recarregar a página), mecanismos de pesquisa (palavras-chave) e outros serviços da web.

Nas tags `meta` não é preciso fechar, pois estamos definindo informações e não criando elementos.

Exemplo do que escrevemos no `html` e o que aparece no buscado.
```html
    <meta name="description" content="Blog pessoal do usuário Thiago." />
    <meta property="og:description" content="Blog pessoal do usuário Thiago." />
```

Essas informações são lidas(varridas) pelos robos do google e apresentam de uma melhor forma.

##### Descrevendo as tags

primeiro ponto importante:
    - dentro das tags podemos repassar atributos -> `name` `property` `content`

**Documentação**
https://www.w3schools.com/tags/tag_meta.asp

### 06 - Titulos e parágrafos

Os Titulos no html são representados pela tag header abreviada e um número. Representam também a relevância do conteúdo/texto. Quanto menor for o número, mais relevante ele é.
Exemplo: `h1`,`h2`,`h3`...`h6`.
Ela permitem criar hierarquia na página.

Os parágrafos são usados para poder descrever a seção que você deseja. A sua tag é representada pela inicial da sua palavra `<p></p>`

Exemplo: `<p> Texto que você deseja inserir </p>`

### 07 - Formatação de textos

Podemos aplicar estilos para textos usando tags, porém isso é mais comum usando o CSS.

- `<b>` -> é usado para deixar o texto em negrito(bold)
- `<strong>` -> é usado para deixar o texto em negrito, porém repassa um sensação de maior "peso" a fonte. isso é mais semântico para um leitor e ele entende que isso é mais importante.
- `<i>` -> é usado para deixar o texto em itálico(italic).
- `<u>` -> é usado para deixar o texto sublinhado(underline).
- `<s>` -> é usado para deixar o texto taxado(riscado ao meio).

Se o foco for deixar estilizado, não pense em usar HTML e sim usar CSS. Porém se o intuito for construir um código bem preciso e conciso, ai vale a pena aplicar essas tags no textos(deixar mais semântica).
As nossas tags precisam ter um significado.

**Documentação**
https://developer.mozilla.org/pt-BR/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting   

### 08 - Comentários 



**Documentação**
https://developer.mozilla.org/pt-BR/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting   