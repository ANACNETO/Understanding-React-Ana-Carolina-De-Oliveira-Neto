# HTML e Suas Tags
<p>Os elementos HTML ou também chamados de tags HTML, são utilizados para informar ao navegador que tipo de estrutura é essa que está sendo construída, podendo ser títulos, parágrafos, imagens, links, entre outros. Dessa forma, para que um documento seja interpretado pelo navegador, é necessário que o arquivo tenha a extensão .html e a partir disso, poderá ser exibido por qualquer navegador web.</p>

<p>As tags podem ser categorizadas inicialmente em dois tipos, em “nível de bloco” (block-level) e “em linha” (inline). Um elemento em nível de bloco ocupa toda a largura de seu elemento pai, que também chamamos de elemento container, criando assim um “bloco”. Já os elementos inline, geralmente usamos para demarcação de conteúdos de texto.</p>

<p>Abaixo veremos exemplos de tags que compõe a estrutura básica de um HTML.</p>

### O que é DOCTYPE?
<p>O DOCTYPE não é uma tag HTML, mas uma instrução especial. Ela indica para o navegador qual versão do HTML deve ser utilizada para exibir a página. Quando não colocamos essa instrução a página é exibida numa espécie de "modo de compatibilidade" na qual algumas tags e estilizações não funcionam 100% corretamente. Principalmente as tags e estilizações mais atuais (lançadas na versão 5 do HTML).</p>
<p>O recomendado é sempre usar a última versão do HTML, usando a declaração de DOCTYPE simples:</p>

![Doctype](/HTML/assets/doctype.png)

### Tag HTML
<p>Esta tag representa a raiz do documento</p>

![Tag HTML](/HTML/assets/tag-html.png)

<p>Na estrutura do documento, antes de começar a colocar o conteúdo, inserimos esta tag. Dentro dela, é necessário declarar outras duas tags: head e body. Essas duas tags são "irmãs", pois estão no mesmo nível hierárquico em relação à sua tag "mãe", que é html.</p>

![Hierarquia das Tags](/HTML/assets/hierarquia-tags.png)


### Tag Head
<p>Contém informações sobre o documento HTML que são de interesse somente do navegador e para outros serviços da web, e não para as pessoas que vão acessar nosso site. São informações que não serão exibidas diretamente no navegador, também podemos considerar um local onde informamos os metadados sobre a página.</p>

<p>A especificação do HTML obriga a presença da tag de conteúdo title dentro da head, permitindo definir o título do documento, que poder ser visto na barra de título ou aba da janela do navegador. Caso contrário, a página não será um documento HTML válido.</p>

<p>Outra configuração muito importante, principalmente em documentos HTML cujo conteúdo é escrito em um idioma como o português, que contém caracteres "especiais" (acentos e cedilha), é a codificação/conjunto de caracteres, chamada de encoding ou charset.</p>

<p>Podemos configurar qual codificação queremos utilizar em nosso documento por meio da configuração de charset na tag meta. Um dos valores mais comuns usados hoje em dia é o UTF-8, também chamado de Unicode. Há outras possibilidades, como o latin1, muito usado antigamente.</p>

<p>O UTF-8 é a recomendação atual para encoding na Web por ser amplamente suportada em navegadores e editores de código, além de ser compatível com praticamente todos os idiomas do mundo. Abaixo é possível visualizar a estrutura completa:</p>

![HTML com a Tag Head](/HTML/assets/tag-head.png)

### Tag Body
<p>A tag body contém o corpo de um documento HTML, que é exibido pelo navegador em sua janela, ou seja, todo o conteúdo visível do site. É necessário que o body tenha ao menos um elemento "filho", ou seja, uma ou mais tags HTML dentro dele.</p>
<p>Abaixo um exemplo utilizando um a tag h1 (que indica o título principal de uma página) dentro do body:</p>

![HTML com a Tag Body Preenchida](/HTML/assets/tag-body.png)

### Tag Link
<p>É uma tag vazia, que contém apenas atributos e faz a relação do documento HTML com recursos externos, é usada para vincular uma folha de estilo externa, também é usada para definir o favicon da página (ícone da aba do navegador), como outros recursos.</p>

### Tag Style
<p>Essa tag é usada para declarar estilos (CSS) para um documento.</p>

### Tag Script
<p>Esse elemento contém instruções de script ou aponta para um arquivo de script externo por meio do atributo src.</p>

## Tags Semânticas:
<p>Tags semânticas são tags que possuem um significado, que dão sentido a informação de texto ao navegador e buscadores, como por exemplo, utilizar a tag header para cabeçalhos ou article para dar um significado de artigo para aquele bloco de texto, até mesmo a tag p para indicar que aquele texto é um parágrafo, é uma boa prática tentar sempre utilizar essas tags semânticas para ajudar no entendimento do código, além de ajudar muito no SEO do site (Otimização para motores de busca, é o que ajuda o seu site a se rankear melhor nos motores de buscas como o Google).</p>

#### Exemplos de tags semânticas

<ul>
<li>header</li>
<li>main</li>
<li>footer</li>
<li>section</li>
<li>article</li>
<li>aside</li>
<li>nav</li>
<li>ol</li>
<li>ul</li>
<li>li</li>
</ul>

![Exemplo de Estrutura com Tags Semânticas](/HTML/assets/estrutura-tags-sematicas.webp)

## Tags Sem Semântica
<p>As tags que não possuem semântica não definem um significado para aquele texto, normalmente são utilizadas apenas para fins de separação e estilização. Exemplos abaixo:</p>

<ul>
<li>div</li>
<li>span</li>
<li>b</li>
<li>i</li>
</ul>

## Comentários em HTML
<p>Comentários no HTML ou em qualquer outra linguagem são notas que podem ser incluídas no código fonte para descrever o que se quiser. Assim, não modificam o programa executado e servem somente para ajudar a pessoa que está desenvolvendo a melhor organizar os seus códigos.</p>

![Comentários](/HTML/assets/comentario-html.png)



<p>Mais informações disponíveis nos links abaixo:</p>

[https://www.alura.com.br/apostila-html-css-javascript/](https://www.alura.com.br/apostila-html-css-javascript/)

[https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/header](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/header)