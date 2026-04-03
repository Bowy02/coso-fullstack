# INFORMACION DEL CURSO

## Dimensiones de pantalla estandaren framework
**Telefono y tablets**
480 Para telefono
768 para tablet

**Para portatiles y ordenador de escritorio**
1140 para laptop o computadora de escritorio
1400 para pc estandar o grande

## CSS BOX MODEL
Hay que tener en cuenta varias cosas:
**El tamaño de lo que se muestra está delimitado por 4 cosas**
- Tamaño del contenido
- Tamaño de relleno (Padding)
- Tamaño del borde y margen
  
## CSS GRID
Permite definir el tamaño y las posicionesde los elementos

- En flexbox el contenido se ubica automaticamente de arriba hacia abajo o al reves, en grid se agrupa en un áreas definidas. Como una tabla de excel por poner un ejemplo.

## CUANDO USAR FLEXBOX Y GRID

### FLEXBOX
Lo usaremos para la alineación o distribución de los elementos que estarán dentro de contenedores como:
- Una barra de navegación
- Enlaces

### CSS GRID
Para definir el layout del sitio web como pueden ser las columnas o contenedores de elementos

## BEM
### ¿QUE ES BEM?
Es una metodología para crear código reutilizable y ordenado en tus proyectos con CSS.

#### REGLAS DE BEM
##### Bloques
Son un Contenedor, si una sección por si sola es significativa y no requiere de otras secciones para su apariencia (CSS) deberá deberá ir en un bloque
```
<div class="cliente">...</div>
```

##### Elementos
Parte de un bloque, depende del bloque y no es por si solo significativo; tienen la cracterística de que utilizan el nombre del bloque y después doble guion bajo__
```
<p class="cliente__nombre">...</p>
```

##### Modificadores
¿Un Bloque o Elemento tendrá una variante? Se utiliza un modificador que es una "bandera"que avisa que ese elemento tendráun diseño diferente.
```
<p class="cliente__nombre--ceo">...</p>
```