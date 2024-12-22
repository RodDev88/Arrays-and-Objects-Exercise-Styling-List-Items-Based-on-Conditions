## Instrucciones ejercicio ciclos y condicionales

1. Crea un archivo llamado misdatos.html.
   Este archivo será donde trabajaremos el código HTML y JavaScript.

2. Utiliza el mismo arreglo del código anterior:

```javascript
const datos = [1200, 350, 1500, 1400, 250, 5000, 1950, 1952];
```

3. Muestra los datos en una lista ordenada o desordenada ` (<ul> o <ol>)`:

4. Cada valor del arreglo debe mostrarse como un elemento de la lista ` (<li>)`.

5. Aplica colores según la condición:

Si el valor está entre 1000 y 2000 (inclusive), debe mostrarse en color verde.
Si el valor no cumple esta condición, debe mostrarse en color rojo.

6. Escribe el código JavaScript necesario para generar la lista:

7. Usa un bucle para recorrer el arreglo datos.

Evalúa cada valor del arreglo con la condición (valor >= 1000 && valor <= 2000).

Genera un elemento `<li>` con el texto del valor y aplica el color correspondiente usando estilos CSS (style).

8. Agrega los elementos generados al HTML:

9. Asegúrate de usar innerHTML solo una vez al final para optimizar el renderizado.

### Resultado esperado:

- Cuando abras el archivo misdatos.html en el navegador, verás una lista donde:
- Los números entre 1000 y 2000 están en color verde.
- Los números fuera de ese rango están en color rojo.
