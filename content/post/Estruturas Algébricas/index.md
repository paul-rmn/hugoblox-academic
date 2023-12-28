---
title: Notas - Estruturas algébricas
date: '2023-12-27'
summary: "Notas de aula para o curso Estruturas algébricas do quinto semestre do curso de bacharelado em matemática da UFC."
author: 'Ramon Nunes'
featured: false
draft: false
math: mathjax
date:    2023-09-27T23:31:00-03:00
lastmod: 2023-09-12T23:31:00-03:00
---

<p>Desta vez, pela primeira vez eu espero conseguir finalmente escrever
notas de aula de uma disciplina. A vitima da vez será a disciplina de
Estruturas Algébricas.</p>
<h1 id="bibliografia">Bibliografia</h1>
<p>A referência principal será o livro do Lang <span class="citation"
data-cites="lang">(Lang, n.d.)</span>, principalmente por conta da ordem
mas o livro do Adilson Gonçalves <span class="citation"
data-cites="adilson">(Gonçalves, n.d.)</span> e de Garcia e Lequain
<span class="citation" data-cites="garcia-lequain">(Garcia and Lequain,
n.d.)</span> também serão referências úteis.</p>
<h1 id="revisão-de-tn">Revisão de TN</h1>
<h2 id="propriedades-básicas-dos-inteiros">Propriedades básicas dos
inteiros</h2>
<h3 class="unnumbered" id="princípio-da-boa-ordem-pbo">Princípio da boa
ordem (PBO)</h3>
<p>Todo subconjunto não vazio de <span
class="math inline">\(\mathbb{Z}_{&gt;0}\)</span> possui um elemento
mínimo.</p>
<h3 class="unnumbered" id="princípio-da-indução">Princípio da
indução</h3>
<p>Suponha que para todo inteiro <span class="math inline">\(n\ge
1\)</span>, <span class="math inline">\(P(n)\)</span> seja uma
proposição e que possamos provar</p>
<ol type="i">
<li><p><span class="math inline">\(P(1)\)</span> é verdadeira;</p></li>
<li><p>Se <span class="math inline">\(P(n)\)</span> é verdadeira, então
<span class="math inline">\(P(n+1)\)</span> é verdadeira.</p></li>
</ol>
<p>Então <span class="math inline">\(P(n)\)</span> é verdadeira para
todo <span class="math inline">\(n\ge 1\)</span>.</p>
<div class="pre-ex">
<p><strong>Exercício 1</strong>. <em><span
class="upright"></span></em></p>
<p><em>Mostre que para todo <span class="math inline">\(n\ge 1\)</span>
temos</em></p>
<ol type="a">
<li><p><em><span class="math inline">\(1+2+\cdots+n =
\frac{n(n+1)}{2}\)</span>;</em></p></li>
<li><p><em><span class="math inline">\(1^2+2^2+\cdots+n^2 =
\frac{n(n+1)(2n+1)}{6}\)</span>;</em></p></li>
<li><p><em><span class="math inline">\(1^3+2^3+\cdots+n^3 =
\left(\frac{n(n+1)}{2}\right)^2\)</span>.</em></p></li>
</ol>
</div>
<h3 class="unnumbered" id="algoritmo-de-euclides">Algoritmo de
Euclides</h3>
<div class="thm">
<p><strong>Teorema 1</strong>. <em>Sejam <span
class="math inline">\(a,b\in\mathbb{Z}\)</span> com <span
class="math inline">\(b\neq 0\)</span>. Então existem <span
class="math inline">\(q,r\in\mathbb{Z}\)</span> tais que <span
class="math inline">\(a=bq+r\)</span> e <span
class="math inline">\(0\leq r&lt;|b|\)</span>. Além disso, <span
class="math inline">\(q\)</span> e <span
class="math inline">\(r\)</span> são únicos.</em></p>
</div>
<div class="proof">
<p><em>Proof.</em> PBO aplicado ao conjunto <span
class="math inline">\(\{q\in \mathbb{Z}_{&gt;0};\;
|b|q&gt;a\}\)</span> ◻</p>
</div>
<h2 id="divisibilidade">Divisibilidade</h2>
<div class="dfn">
<p><strong>Definição 1</strong>. <em>Sejam <span
class="math inline">\(d,n\in\mathbb{Z}\)</span> com <span
class="math inline">\(d\neq 0\)</span>. Dizemos que <span
class="math inline">\(d\)</span> divide <span
class="math inline">\(n\)</span> se existir <span
class="math inline">\(q\in\mathbb{Z}\)</span> tal que <span
class="math inline">\(n=dq\)</span>. Neste caso escrevemos <span
class="math inline">\(d|n\)</span>. Sejam <span
class="math inline">\(m,n\)</span> inteiros, um divisor comum de <span
class="math inline">\(m\)</span> e <span
class="math inline">\(n\)</span> é um inteiro <span
class="math inline">\(d\)</span> tal que <span
class="math inline">\(d|m\)</span> e <span
class="math inline">\(d|n\)</span>. O máximo divisor comum de <span
class="math inline">\(m\)</span> e <span
class="math inline">\(n\)</span> é o maior divisor comum de <span
class="math inline">\(m\)</span> e <span
class="math inline">\(n\)</span> e é denotado por <span
class="math inline">\(\mathrm{mdc}(m,n)\)</span> ou simplesmente <span
class="math inline">\((m,n)\)</span>.</em></p>
</div>
<h2 id="fatoração-única">Fatoração única</h2>
<h1 id="grupos">Grupos</h1>
<h2 class="unnumbered" id="definição-e-exemplos">Definição e
exemplos</h2>
<div id="refs" class="references csl-bib-body hanging-indent"
data-entry-spacing="0" role="list">
<div id="ref-garcia-lequain" class="csl-entry" role="listitem">
Garcia, Arnaldo, and Yves Lequain. n.d. <em>Elementos de Álgebra</em>.
</div>
<div id="ref-adilson" class="csl-entry" role="listitem">
Gonçalves, Adilson. n.d. <em>Introdução à Álgebra</em>.
</div>
<div id="ref-lang" class="csl-entry" role="listitem">
Lang, Serge. n.d. <em>Undergraduate Algebra</em>.
</div>
</div>

