Bem-vindo ao meu primeiro MarkDown !
===================

######Desconsiderar as mensagens de teste abaixo, a finalidade é aprender as principais funcionalidades do MarkDown.


Ola, estou estudando MarkDown para usar nas minhas atividades na Concrete, pretendo aprender o suficiente para atender as necessidades. **(Comentario em negrito)**.

---
Exemplos utilizando MarkDown
--- 

####Caixa de texto e marcadores
 
 Caixa de texto:
 
 ```
 >####**Nota>**
 > Somente texto.
 > - Texto e Marcador.
 ```
 
 Saída:
 
>#### **Nota:** 
> Para texto utilize '>'
> - Você pode colocar marcadores de texto com '> -'
> 

Marcadores:

```
- Texto 1
```

- Texto 1 (- use um traço no início de cada linha )
- Texto 2

----
####**Usando Ctrl + Tecla:**

Para bloquear a tela no Linux/Fedora:

```
><kdb>Ctrl + Alt + 1</kbd>
```
Saída:

><kbd>Ctrl + Alt + l</kbd> 

Ou (sem >):

<kbd>Ctrl + Alt + l</kbd>

___
####Algumas funções no MarkDown:

Separar textos com "traço", exemplo:

```
---
> Utilize três traços (---) acima e abaixo do texto.

---
```
---

####**Tamanho da fonte**

Utilize cerquilha 1 a 6 (###### Fonte menor), exemplo:
```
###### 6 Cerquilhas  
#### 4 Cerquilhas
```

Ou:
Três traços (---) abaixo do texto, exemplo:

```
Texto
---
```

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
####**Blocos de códigos/linguagens**

Utilize três crases no início e no final do texto (`), após as crases especifique o tipo de linguagem que irá usar, conforme exemplo abaixo ():
```
```c++
	Codigo;
	função;
	Condição;
 ``` 
```
**Saída:**

Linguagem C/C++:

```c
main(){
	char nome[10];
	strcpy(nome,"concrete");

	printf("Voce trabalha na: %s", nome);
}
```
Linguagem JavaScript:
```javascript
$(function(){
  $('div').html('I am a div.');
});
```

---
####**Imagens e links**

Adicionar imagens:
```
![](<url_da_imagem>)
```
Saída:
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTIuTMPLwJ-kbKX1DqaZuTgQI72NQzfjPTfU16S6XTuT_cCjrCn)

Adicionar links:
```
Especifique:
 [1]: http://www.concretesolutions.com.br/
 [Site Concrete Solutions][1]
```
Saída:
 [1]: http://www.concretesolutions.com.br/
 [Site Concrete Solutions][1]


###Dúvidas? 
reinaldo.pinto@concrete.com.br
