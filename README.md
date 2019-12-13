


1
Creamos el repositorio git; despuÃ©s creamos el proyecto de eclipse en la misma ruta
que habiamos creado el repositorio git

Descargamos el archivo .zip y los descomprimimos en la carpeta src del proyecto.

Primer commit y push subi todos los ficheros del proyecto con la libreria JUnit3 ya importada.

2
Corremos el test de la aplocacion para ver si funcionan las pruebas Junit tras añadir la libreria y efectivamente son todas funcionales y las pasa con exito
Tambien hemos ejecutado el main para ver que ejecuta la aplicacion de forma correcta


1 refac


Refactorizamos la clase cell cambiando el owner 
Actualizamos el readme
hacemos el segundo commit and push

2


hacemos un push down  en available(cell.java) para crear  un errror en la super clase y despues lo 
arreglamos haciendo un pull up en el available(gocell.java) 
actualizamos el readme
tercer commit and push

3
creamos una nueva interfaz IOwnable de la clase cell.java e implementamos los getter y setters del Proprietary(player) y de isAvailable()
actualizamos readme
cuarto commit and push

4

Extraemos el bucle for del metodo getRent() y lo metemos en un nuevo metodo  calcMonopoliesRent() y pasamos las variables que nos interesan
Actualizamos el readme
quinto commit and push

5

Extraeremos la variable para ponerla de forma local  como un String
Actualizamos el readme 
sexto commit and push

6

cambiamos la estructura de los metodos getPropertyNumberForColor y  playAction() añadiendo lo pedido en la practica.
arreglamos los metodos que causan error
actualizamos el readme

ultimo commit and push