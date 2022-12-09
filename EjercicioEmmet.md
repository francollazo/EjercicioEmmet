# Ejercicio 1
## Cuál es el código emmet para generar la siguiente estructura?
~~~
<ul>
    <li></li>
    <li></li>
    <li></li>
</ul>
~~~
### ul < li * 3

# Ejercicio 2
## Cuál es el código emmet para generar una tabla con 10 filas y 2 columnas?

### table > tr10 > td2

# Ejercicio 3
## Cuál es el código emmet para generar la siguiente estructura?
~~~
<h1 class="text text-titulo">Ola mundo</h1>
~~~
### h1.class.text.text-titulo {Ola mundo}

# Ejercicio 4
## Cuál es el código emmet para generar la siguiente estructura?
~~~
<div>
    <p>datos</p>
    <p>datos</p>
</div>
~~~
### div >p * 2 {datos}

# Ejercicio 5
## Cuál es el código emmet para generar la siguiente estructura?
~~~
<div></div>
<p>
    <span></span>
</p>
<p>
    <span></span>
</p>
<p>
    <span></span>
</p>
<p>
    <span></span>
</p>
~~~
### div + p * 4 < span

# Ejercicio 6
## Cuál es el código emmet para generar la siguiente estructura?
~~~
<div id="hola" class="principal">
    <p>
       <section id="seccion" class="seccion">
          <h1>Ola mundo!</h1>
       </section>
    </p>
</div>
~~~
### div # hola.principal > p > section # sección.seccion > h1{Ola mundo!}

# Ejercicio 7
## Cuál es el código emmet para generar la siguiente estructura?
~~~
<ol>fora

    <li>dentro</li>

    <li>dentro</li>

    <li>dentro</li>

    <li>dentro</li>

</ol>
~~~
### ol{fora} > li * 4{dentro}

# Ejercicio 8
##Cuál es el código emmet para generar la siguiente estructura?
~~~
<p></p>
<div></div>
<p>
    <div>
    <div>
    </div>
    </div>
</p>
~~~
p + div + p > div * 2

# Ejercicio 9
## Cuál es el código emmet para generar la siguiente estructura?
~~~
<nav class="menu">

 <a href="">enlace1</a>

 <a href="">enlace2</a>

 <a href="">enlace3</a>

 <a href="">enlace4</a>

</nav>
~~~
### nav.menu > a * 4[href=”menú”]{enlace$}

# Ejercici 10
## Cuál es el código emmet para generar la siguiente estructura?
~~~
<ul class="lista">
    <li class="item-1">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ea, voluptatibus!</li>
    <li class="item-2">Eaque, impedit est tempora doloremque praesentium voluptatum quas nostrum consectetur.</li>
    <li class="item-3">Illum, reprehenderit minus ex soluta adipisci aperiam explicabo modi sapiente.</li>
    <li class="item-4">Nihil ratione voluptates iure cum eligendi dolores deleniti quos nostrum.</li>
</ul>
~~~
### ul.lista > li.item - $ * 4 > lorem10
