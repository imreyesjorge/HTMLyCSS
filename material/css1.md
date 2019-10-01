# CSS
Podemos ver a *CSS* como el 'maquillaje' que lleva puesto el documento *HTML*. Es el que define como se verá toda la página, de principio a fin. Puedes ver un [ejemplo](https://codepen.io/jorgert1205/pen/KKPEjXq).

El funcionamiento de **CSS** es simple, se usan *selectores* para determinar sobre que elemento del HTML se va trabajar y dentro de unas llaves `{}` van las propiedades que tendrá ese elemento seleccionado; por ejemplo, digamos que queremos que los elementos `<p>` sean de color verde; para eso nos tenemos que dirigir al archivo de CSS3 y poner lo siguiente:
```css
p {
    color: green;
}
```
###### Dónde `p` es el *selector*, `color` la *propiedad* y `green` el *valor* de esa propiedad.
&nbsp;
### Selectores
Para poder editar sólo los elementos que nosotros deseemos existen los *selectores*. Los básicos son por `elemento`, `clase` e `ID`. Todo esto se declara en el HTML.

- **Elemento:** modifica el elemento HTML en general, afectando a todos los elementos con ese nombre de etiqueta. `<p></p>`
- **Clase:** modifica los elementos que compartan el mismo nombre de clase. `<p class="btn"></p>`
- **ID:** modifica un único elemento, sin afectar a ningún otro. `<p id="btn1"></p>`

*Teniendo los elementos de HTML con sus debidas clases y/o ID's, ahora podemos proceder a seleccionarlos con CSS para poder modificarlos:*

**Elemento:** se usa unicamente el nombre de la etiqueta `p`
```css 
p {
    
}
```
**Clase:** se usa un "." seguido del nombre de la clase `.btn`
```css 
.btn {
    
}
```
**ID:** se usa un "#" seguido del nombre del ID `#btn1`
```css 
#btn1 {
    
}
```
##### Ejemplos de propiedades
Propiedad | Valor de ejemplo | Definición
:---: | :---: | :---
`color` | green | Cambia el texto de color a verde
`background-color` | black | Cambia el color de fondo del elemento a negro
`font-size` | 15px | Cambia el tamaño de la fuente a 15px

###### Así como HTML5, **CSS3** tiene muchísimas propiedades que pueden ser usadas, si quieres conocerlas puedes ver el [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference) de Mozilla.
***

#### [INICIO](../README.md)
