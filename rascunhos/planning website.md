## Components

### container

- display flex
- sombra;
- formatação;
- borda;
- raio;

- gap para caso tenha mais de 1 elemento no conteiner.

### container-card

- sistema de cards que podem se sobrepor de acordo com tamanho disponível;

### icons

- width e height fixas;

## Semantic construction

### page-start & header

```html
<div .class="page-start">
	<header class="container">
		<h2>Salem Nicholas</h2>
		<strong>Designer Gráfico</strong>
		<div>
			<img class="icons" src="/images/icons"></img>
			<img class="icons" src="/images/icons"></img>
			<img class="icons" src="/images/icons"></img>
		</div>
	</header>
</div>
```

- `page-start` será o local onde ficará o efeito de sombreamento na esquerda e a imagem de fundo que muda com o tempo;
- Para criar a linha que separa essa primeira parte do restante da página, usarei `gap` no body.


### main

```html
	<main>
		<section class="container-card">
			<h3>Tittle</h3>
			<div class="card"><img></img></div>
			<div class="card"><img></img></div>
			<div class="card"><img></img></div>
		</section>
	</main>
```


---

Ideias:

- Quando houverem números impares, a última carta deve cobrir 2 colunas.