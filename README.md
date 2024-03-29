# Práctica 2.5 Generador de números aleatorios

## Parte 1

Crea un generador de números aleatorios gráfico. Utiliza el elemento *JSpinner* (contadores) que mostrará el número aleatorio generado entre esos dos números en un campo *JTextField* al pulsar el botón generar.

La ventana deberá tener además un **menú** con los elementos Fichero y Edición. El menú fichero deberá tener un elemento salir y el menú *Edición* un elemento que permita reiniciar el contenido de los campos de la ventana.

Ayúdate de la función `Math.random()` entre dos números o de la clase `radom` así como de una **clase auxiliar** para realizar dichos cálculos.

```java
Math.random() * (max - min + 1) + (min)
```

```java
Random rnd = new Random();
rnd.nextDouble() * max + min

```

> Nota: No olvides en tus proyectos agregar los ficheros **jar** precompilados.


![](media/ba18dcfdd7fd2df3ed8dfe1cefa04f24.png)


## Parte 2

Mejora el ejercicio anterior agregando un *checkbox* que en caso de estar marcado solo permita mostrar números **primos** entre los valores requeridos.

Agrega en el *menú edición* un elemento llamado **historial** que permita ver los últimos números generados en una ventana modal (*JDialog*) usando una lista (*JList*). 

Agrega en el *menú fichero* una opción para **guardar** el historial del listado generado en un fichero de texto mediante un *JFileChooser*. Se deberá verificar si ya existe un fichero con el mismo nombre antes de sobreescribirlo.
 
## Parte 3   

Agrega dos **pestañas** (*JTabbedPane*), una en la que se muestren los números primos anteriores y otra en la que se pueda cargar una imagen haciendo click sobre un JLabel.

Opcionalmente agregar una opción en el *menú edición* *llamada borrar todo* para eliminar el listado guardado del historial.



