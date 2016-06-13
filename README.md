##### DevOps!!
###### Desconsiderar as mensagens abaixo, a finalidade é aprender as funcionalidades do MarkDown.

Bem-vindo ao meu primeiro MarkDown !
===================

Ola, estou estudando MarkDown para usar nas minhas atividades da concrete, pretendo aprender o suficiente para atender as necessidades nesse instante. **(Comentario em negrito)**.

---
Exemplos utilizando MarkDown
--- 

####Caixa de texto marcadores
 
 Caixa de texto:
 
>#### **Nota:** (Neste exemplo foi usado >###**Texto)
> - Para texto utilize '>' exemplo:
>  Teste!
> - Você pode colcoar marcadores de texto com '>-'
> 

Marcadores:

- Texto 1 (- use um traço no início de cada linha )
- Texto 2

----
####**Citar exemplos usando Ctrl + Tecla:**

Para bloquear a tela na distribuição Linux Fedora:

><kbd>Ctrl + Alt + l</kbd> 

Ou:

<kbd>Ctrl + Alt + l</kbd>

___
####Algumas funções no MarkDown:

Separar textos com "traço", exemplo:

---
> Utilize três traços (---) acima e abaixo do texto.

---

####**Tamanho da fonte**

Utilize cerquilha 1 a 6 (###### Fonte menor), exemplo:

> ###### 6 Cerquilhas  
> #### 4 Cerquilhas

Ou:
Três traços (---) abaixo do texto, exemplo:
Texto
---
---
###**Tabelas**

####**Tabelas**

Nome     |    Valor

.----------------

Celular | R 1500
Notebook | R 2000 

#####Obs: Desconsiderar o ponto "."
Saída:

Item     | Valor
-------- | ---
Celular | R$1600
Notebook | R$2000


---
M

```
// Foo
var bar = 0;
```

> **Tip:** To use **Prettify** instead of **Highlight.js**, just configure the **Markdown Extra** extension in the <i class="icon-cog"></i> **Settings** dialog.

> **Note:** You can find more information:

> - about **Prettify** syntax highlighting [here][3],
> - about **Highlight.js** syntax highlighting [here][4].


### Footnotes

You can create footnotes like this[^footnote].

  [^footnote]: Here is the *text* of the **footnote**.


### SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                  | ASCII                        | HTML              |
 ----------------- | ---------------------------- | ------------------
| Single backticks | `'Isn't this fun?'`            | 'Isn't this fun?' |
| Quotes           | `"Isn't this fun?"`            | "Isn't this fun?" |
| Dashes           | `-- is en-dash, --- is em-dash` | -- is en-dash, --- is em-dash |


### Table of contents

You can insert a table of contents using the marker `[TOC]`:

[TOC]


### MathJax

You can render *LaTeX* mathematical expressions using **MathJax**, as on [math.stackexchange.com][5]:

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> **Tip:** To make sure mathematical expressions are rendered properly on your website, include **MathJax** into your template:

```
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
```

> **Note:** You can find more information about **LaTeX** mathematical expressions [here][6].


### UML diagrams

You can also render sequence diagrams like this:

```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```

And flow charts like this:

```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```

> **Note:** You can find more information:

> - about **Sequence diagrams** syntax [here][7],
> - about **Flow charts** syntax [here][8].

### Support StackEdit

![](https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcQ9fuZ9QPQ_7LN9t9ZOSWx7yz2MAAIwlGQECJJzOs2qRIOOR797fw)  
ola

[![](https://cdn.monetizejs.com/resources/button-32.png)](https://monetizejs.com/authorize?client_id=ESTHdCYOi18iLhhO&summary=true)

  [^stackedit]: [StackEdit](https://stackedit.io/) is a full-featured, open-source Markdown editor based on PageDown, the Markdown library used by Stack Overflow and the other Stack Exchange sites.


  [1]: http://daringfireball.net/projects/markdown/syntax "Markdown"
  [2]: https://github.com/jmcmanus/pagedown-extra "Pagedown Extra"
  [3]: https://code.google.com/p/google-code-prettify/
  [4]: http://highlightjs.org/
  [5]: http://math.stackexchange.com/
  [6]: http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference
  [7]: http://bramp.github.io/js-sequence-diagrams/
  [8]: http://adrai.github.io/flowchart.js/
