# Arrays

- Un array es una zona de almacenamiento continuo, donde se pueden introducir varios valores, cada uno de ellos ubicado por la posición que se ocupa en el array.
- También son denominados arreglos o vectores, y cuando son de dos dimensiones son llamadas matrices.

- Los arrays nos brindan la capacidad de almacenar una colección de elementos y acceder a ellos de forma individual.
- Cada elemento se identifica mediante su posición en el array, denominada **indice**, y estos índices son siempre secuenciales.
- En Javascriot son altamente flexibles en términos de los diferentes tipos de datos que podemos almacenar en cada posición del array.

## Crear un array

1. Declarando un array con elementos en línea

```Javascript
// Declarando un array con elementos en línea
let miArray = [1, 2, 3];
console.log(miArray);
```

2. Declarando un array con la sintaxis **newArray**

```Javascript
// Declarando un array con la sintaxis new Array
let miArray = new Array(1, 2, 3);
console.log(miArray);
```

3. Declarando un array con un tamaño específico utilizando la sintaxis **new Array**

```Javascript
// Declarando un array con un tamaño específico utilizando la sintaxis new Array
let miArray = new Array(3);
miArray[0] = 1;
miArray[1] = 2;
miArray[2] = 3;
console.log(miArray);
```

4. Declarando un array con elementos de diferentes tipos de datos.

```Javascript
// Declarando un array con elementos de diferentes tipos de datos.
let miArray4 = [1, "dos", true, {nombre: "Juan", edad: 30}];
console.log(miArray4);
```

