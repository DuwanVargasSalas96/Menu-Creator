# Menu Creator
Es una librería que permite realizar menús rápidos en consola.

## table()
La función **Table**, permite crear una tabla de una sola columna, con una cabezera y permite añadir filas de forma dinámica. Esta función requiere dos parametros:
1. **title**: Debe ser de tipo **String**. Permite modificar el titulo de la tabla.
2. **rows**: Debe ser de tipo **Array** y cada item del arreglo debe ser un **String**. Cada item del arreglo se convierte en una fila de la tabla.

## header()
La función **header** permite crear una cabecera y requiere un parametro:
1. **title**: Debe ser de tipo **String**. Permite modificar el titulo de la cabecera.

## row()
La función **row** crea las filas para la tabla. Requiere un solo parametro:
1. **txt**: Debe ser de tipo **String**. Es el texto que se procesa como fila en la tabla.