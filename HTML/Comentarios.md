# Conceitos básicos de HTML

* ## HTML não é uma linguagem de programação, ela é diferente de linguagens tipo c++, python, java;
* ## 100% de todos os websites usam HTML;

* ## tudo em HTML é contido em <>, tal é chamado de elemento, por exemplo, supondo que queremos mudar o titulo, devemos ter um elemente de $<head>$ e dentro deste teremos um elemento de $<title>$, que será modificado para ter o título desejado;

* ## A estrutura básica de todo elemento é composto por um início e um fim, o início: $<elemento>$, o fim: $</elemento>$.


* * ## Exemplo, o elemento do título seria: $<title>$meu Título $</title>$.

* ## Espaços em branco não importam em html, supondo que temos um paragrafo e queremos pular, ao invés de pular a linha, temos que criar um novo elemento de paragrafo, pois html ignora os espaços!!

* ## Para criar links é relativamente simples, basta usar o <a href = "http://google.com"> isto é um link </a>. o 'a' representa $\textit{ancor}$. Para abrir em outra aba usamos o target = "blank"

* ## você também pode referenciar arquivos dentro do seu servidor, <a href = "nome_arquivo.html"> isto é um link </a>.

* ## Adicionar imagens é relativamente simples <img src = 'nome.ext' width = x e height = y>

* ## Podemos utlizar imagens como links para outras páginas (ML,Amazon,etc)

* ## comentarios são simples, '''<!-- texto -->''', voce tambem pode fazer comentarios igual ao c/c++, /**/


* ## lista usasse <ul> para abrir e <li> para criar a lista;


* ## para alterar o simbolo na barra acima, basta ir em head e incluir "link:favicon"

* ## criar tabelas é relativamente simples

<table border = "1">

<tr>
<td>cell 1</td>
<td>cell 2</td>
</tr>

<tr>
<td>cell 3</td>
<td>cell 4</td>
</tr>

</table>

* ## em css temos as classes, que são pedaços de código que podem ser reutilizaveis para dar stylo a diversos objetos com stylos iguais.

* ## podemos colocar um label nos blocos com o comando id, &lt; p id = "nome"&gt;.

* ## o elemento form permite que o usuario interaja com o site. Ele gera botões, caixas de textos, etc.




# Conceitos Basicos de CSS

<h2>

* Como dito anteriormente, CSS é uma parte de de HTML, para implementar o mesmo, basta fazer: &lt; p style = "font-size: 10px"&gt;

* Ao adicionar o style, podemos alterar diversas coisas dentro do html: &lt; p style = "color: blue"&gt;

<p style = "color: blue;"> Texto em azul;
</p>

* Podemos também criar um bloco com diversos comandos e atribuir outro blocos com este comando;

<style>

bloco {color: red}

</style>


<bloco> texto em editado em vermelho</bloco>

* Podemos colocar mais de um bloco com isto. No caso, podemos colocar, div,p {atributos}

* Supondo que queremos focar em um div dentro de p, fazemos p div {atributos}. Note que anteriormente usamos virgula para que dois blocos possuissem os mesmo atributos, e agora estamos usando espaço para referenciar um bloco dentro de outro bloco 

* Podemos ainda generalizar isto para classes;

<style>

.blue {color: blue;
        text-transform: uppercase;}


#title {color:yellow;}
</style>

<p class = "blue"> texto com classe </p>

* Um bloco pode conter mais de uma classe;
* Podemos também usar um id no bloco, e referenciar tal no style para modificar apenas este. É ideal fazer apenas 1 id por bloco

<p id = "title"> texto com id modificado para amarelo <p>

* No final são diversas formas de fazer a mesma coisa;

* Até o momento colocamos todo o nosso style dentro do HTML, podemos também colocar em um arquivo .css externo e chamar este no codigo do html com o seguinte comando < link rel ="stylesheet" href = "arquivo.css" >



</h2>

# Javascript

<h2>
* Js é uma linguagem de programação;
* É usada no front end;
* Toda vez que algo acontece na tela, é um código js;
* podemos ter um arquivo .js ou escrever no proprio html o codigo em js.
*< script src = "script.js" > < / script>

* temos alguns tipos de variáveis em js, temos o const --> objeto constante, var --> variavel

* o comando let declara variaveis apenas dentro de blocos;

* para comentar basta //, ou /**/


</h2>