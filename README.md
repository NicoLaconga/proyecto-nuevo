# PROYECTO PORTFOLIO 

Ejemplo básico de HTML, CSS y JAVASCRIPT, totalmente *vanilla*. Este texto acompaña a la didáctica impartida a la largo del proyecto.

## ASPECTOS BÁSICOS

## Asignación de clases selectoras en los TAGS.

De la siguiente forma podemos asignar una clase a un determinado TAG del arbol de NODOS HTML.

```html
<div class="box-title">
    <h1>This is a Title</h1>
</div>
```

En este caso, **box-title** es la clase asignada al TAG *div*, del cual, nos sirve como elemento padre de otro TAG, en este caso el *h1*. **Siempre se debe asignar la clase dentro del TAG de inicio (si el mismo tiene cierre "/"), y su aplicación de clave, que es el atributo (en este caso "class") y el valor, que corresponde al nombre que le damos a esa clase**. Ese nombre es a elección del desarrollador, pero siempre es buena práctica elegir un nombre descriptivo e intuitivo.
Seguido de eso, le damos paso a la asignación de estilos de esa determinada *class*, se puede hacer dentro del mismo HTML, hay ciertas formas (una de las cuales es con las TAG *styles*), pero lo ideal es un archivo separado del mismo, para así, mantener un orden en el desarrollo. Para este ejemplo, creamos el archivo *style.css*.

*style.css*

```css
.box-title{
    display: flex;
    flex-direction: row;
}
```


## Enlaces y redireccionamiento

Dentro de nuestro proyecto, podemos necesitar generar enlaces, de los cuales pueden ser utiles para navegar dentro del mismo sitio, o alguno externo. Para este propósito es necesario el elemento ANCLA o *anchor*, del cual es representado, dentro de la semantica del codigo HTML, como **a**.

```html
<a href="https://someotherwebsite.com" target="_blank">Some link</a>
```

Como se puede ver, cuenta con estos atributos (unos de los mas importantes). El primero, denominado ***"href"***, este mismo, adquiere un valor, puede tratarse como enlace. Como ya mencionamos, puede tratarse de una referencia a cierta sección del mismo sitio web, o mas bien un enlace externo, es decir, una URL que nos redirige a otro sitio web completamente distinto. El segundo atributo que podemos ver es el ***target***, el cual puede hacer referencia hacia *donde* se dirigirá el nuevo documento, si reemplazará al presente o generará uno nuevo en otro pestaña del navegador.
