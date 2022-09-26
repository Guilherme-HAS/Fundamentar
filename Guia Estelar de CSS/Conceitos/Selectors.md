# Selectors

Conecta um elemento HTML com o CSS

## Tipos

* Global selector `*`
* Element/Type selector `h1, h2, p, div`
* ID Selector `#box, #container`
* Class Selector `.red, .m-4`
* Attribute selector, Pseudo-Class, Pseudo-Element, e outros


## HTML

<div id="container" class="m-40">
	<h1>Título</h1>
	<h2>Subtitulo</h2>
</div>

## CSS
```css

/* Seletor Global*/
* {
	width: 200px;
    font-size: 20px;
}

/* Seletor de ID*/
#container {
	width: 200px;
}

/* Seletor de Classes */
.m-40 {
	margin: 40px;
}

/* Seletor de Elementos / Tipos  +  Agrupamento de seletores */
h1, h2 {
	color: blue;
	font-size: 60px;
	background: gray;
}