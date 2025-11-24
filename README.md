# cineplus
Aplicación básica de cobro para un cine creada en python con wxglade. Consta de un archivo con de 4 clases (ventanas): inicio de sesión sin conexión a BD, taquilla, dulcería y ticket.
Creada por alumnos de Bachillerato. 

Ventana Inicio de Sesión (Login)
--El sistema debe tener una pantalla de inicio de sesión.
--Para este proyecto, el inicio de sesión se hará con datos preestablecidos (por ejemplo, usuario: cajero y contraseña: 12345). No es necesario implementar una base de datos.

Venta de Boletos (Taquilla)
--El sistema debe permitir al empleado seleccionar la película, el horario y la sala.
“IT”	14:00, 17:00, 20:00	Sala 1
“La hermanastra malvada”	13:30, 16:30, 19:30	Sala 2
“Superman”	15:00, 18:00, 21:00	Sala 3

--Se debe especificar la cantidad de boletos.
--Se debe indicar si los boletos son para adultos o para menores de edad, ya que el precio es diferente (adultos $90, menores de edad $80).
--Al finalizar la selección de boletos, el sistema debe mostrar un resumen de los boletos adquiridos y calcular el subtotal de la taquilla.

Venta de Productos (Dulcería)
--Después de la taquilla, el sistema debe preguntar si el cliente desea comprar productos de dulcería.
--Si la respuesta es afirmativa, el sistema debe llevar al empleado a una nueva pantalla. 
--En esta pantalla, se deben mostrar tres combos preestablecidos:

Combo	Precio	Contenido	Imagen sugerida
Básico	$75	Palomitas chicas + Refresco chico	
Cuates	$130	Palomitas medianas + 2 refrescos medianos	
Familiar	$200	Palomitas grandes + 3 refrescos grandes + dulces	

--Por cada combo, el sistema debe mostrar su precio, el contenido y una imagen alusiva.
--También se debe permitir la venta de productos individuales:
--Palomitas: Tamaños chico $30, mediano $50 y grande $70.
--Refrescos: Sabores Cola, Sprite, Manzana, en tamaños chico$25, mediano $40 y grande $60.
--El empleado debe poder indicar la cantidad de cada combo o producto individual.

Resumen de la Compra y Cobro (Pantalla Final)
--Al finalizar la selección de productos de dulcería, el sistema debe mostrar una ventana de resumen.
--Esta ventana debe incluir un desglose de la compra:
--Sección "Taquilla" con los boletos comprados y su subtotal.
--Sección "Dulcería" con los combos y productos individuales, y su subtotal.

--Finalmente, el sistema debe mostrar el costo total de toda la compra (taquilla + dulcería).

Para ejecutar el programa debes tener instalado Python 3.13, Visual Studio Code y wxGlade.
Abre el archivo en Visual Studio Code y Ejecuta el programa.
