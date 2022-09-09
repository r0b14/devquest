## Tags HTML

#### 05 - Meta tags - configurando informações da sua página

Meta-tag ou meta-description é usada para poder descrever o conteúdo de uma página WEB. Isso permite os buscadores localizarem melhor o nosso site/conteúdo.
As descrições vão aparecer no mecanismo de busca (google, yahoo!)

_atalho_ -> ctrl + u permite que consiga exibir o código fonte da página.

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

primeiro ponto importante: - dentro das tags podemos repassar atributos -> `name` `property` `content`

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

Os comentários são trechos de códigos que não são executados e só serão exibidos para os desenvolvedores.

**atalhos** -> para comentar ou "descomenta" a linha inteira: `ctrl` + `;`

Comentários -> `<!-- -->`

Precisa-se ter cuidado para não fazer diversos comentários desnecessários.
Os códigos não são para fazer a documentação.

### 09 - Links Externos

são pontos, textos, imagens etc, clicáveis dentro do site que te levam para outros sites/lugares. Os links podem levar para seções externas e interna ao site.

- `<a>` -> tag usada para definir link.

Podemos difinir alguns parâmetros para a tag.

- `href` -> permite direcionarmos o link externo.
- `target` -> se a página vai ser sobrepor a mesma ou se vai abrir em uma nova página.
  - `_blank`: abrir em uma nova página

Exemplo: 
    Eu gostaria de saber como eu faço da forma contrária, quando eu clicar no link, ele abrir meu link em uma nova guia e na atual ele abrir uma página N. (vejo muito nos torrents da vida isso acontecer, a página abrir em uma aba nova e abrir uma propaganda no lugar.)
```html
<script>
    function abreLink() {
    window.open("http://www.google.com.br");
    }
</script>
    <a href="https://netflix.com" onclick="abreLink();">Abre Link</a>
```

*atalho* -> `ctrl` + `espace` => permite que vizualize os repostiórios existentes no projeto e possa selecionar o arquivo que você deseja referenciar.

### 10 - Imagens

Podemos usar livremente as imagens dentro do nosso site html.

- `<img src="local da imagem">` -> a tag permite inserir imagens ou link de imagens no nosso html.

Podemos inserir atributos/parâmetros para a tag.

- `src=""` -> é o local onde podemos encontrar a imagem, interna ou externa.
- `alt=""` -> texto alternativo caso a imagem não carregue 
- `title=""` -> permite que tenha um texto alternativo quando o cursor "descansar" sobre a imagem.

**Documentação**
https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/img 
https://placeholder.com/ -> imagens de marcação. só indicam o tamanho da imagem.


### 11 - Listas

Temos dois tipos de listas: as não ordenadas e as ordenadas.

**Não Ordenadas**
Uma lista que não tem ordem, geralmente compõe bolinhas, linhas.
O estilo da forma de ordenação pode ser editado pelo CSS.
Exemplo:
    Lista de supermercado.

- `<ul>` -> Inicializada a lista não ordenada
- `<li>` -> Usado para categorizar os itens.

*atalho* -> `ul>li*4` => criando um `ul` + 4`li`
*atalho* -> `ctrl` + `;` => no momento que está digitando, destrincha o que quer dizer a função.

**Ordenadas**
Uma lista que tem ordem, geralmente composta por números naturais, alfabetos ou algarismo romano.
O estilo da forma de ordenação pode ser editado pelo CSS.
Exemplo:
    Lista de prioridades, rank.

- `<ol>` -> Inicializada a lista ordenada
- `<li>` -> Usado para categorizar os itens.

**Documentação**
https://www.w3schools.com/html/html_lists.asp 
https://www.devmedia.com.br/listas-em-html/23853

### 12 - Tabelas

As tabelas são usadas de sua forma tradicional.

*atalho* -> `table>tr>td*3` => criará uma sequência de tabelas 

**Documentação**
https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/tfoot