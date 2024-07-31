| | | | |
|-|-|-|-|
|Lista de comprobación y resultados de la prueba para la aplicación móvil Urban.Lunch| | | |
| | | | |
|#|Descripción|Estado|Enlace al informe de errores|
|Pantalla Selección del punto de recogida | | | |
|1|El mapa muestra los puntos de recogida y la ubicación del usuario o usuaria|PASSED| |
|2|Ninguno de los puntos de recogida está seleccionado de forma predeterminada|PASSED| |
|3|Cuando tocas el punto de recogida, está en negro y se considera seleccionado.|PASSED| |
|4|Un toque repetido en el punto de recogida cancela la selección.|PASSED| |
|5|Tocar el punto de recogida cuando se selecciona otro punto de recogida cambia la selección al nuevo punto de recogida.|PASSED| |
|6|La lista desplegable cuenta con los nombres de los restaurantes|PASSED| |
|7|Al seleccionar un punto de recogida de la lista desplegable también se marca en el mapa|PASSED| |
|Pantalla de  Elección de platillos| | | |
|8|La lista de platillos es una lista donde cada elemento contiene una flecha|PASSED| |
|9|La lista de platillos es una lista donde cada elemento contiene el nombre del platillo|PASSED| |
|10|La lista de platillos es una lista donde cada elemento contiene el botón +|PASSED| |
|11|La lista de platillos es una lista donde cada elemento contiene un contador|PASSED| |
|12|La lista de platillos es una lista donde cada elemento contiene el botón -|PASSED| |
|13|Tocar en cualquier área de la lista, excepto +, te lleva a la pantalla de detalles del platillo.|PASSED| |
|14|Al hacer clic en +, el platillo se agrega a la lista de pedidos desde el restaurante más cercano hasta el punto de recogida.|PASSED| |
|15|Al hacer clic en - mientras esté habilitado, el platillo se resta a la lista de pedidos |PASSED| |
|16|El progreso del pedido se muestra en el pie de página|PASSED| |
|17|El primer paso se marca como completado (en color)|PASSED| |
|18|El segundo paso se marca como en curso.|PASSED| |
|19|El tercer paso se marca como el siguiente (sin realizar)|PASSED| |
|20|El boton flecha para continuar aparece en el pie de pagina|PASSED| |
|21|Al dar clic en el botón flecha sin haber agregado ningún platillo salta un mensaje de error "Elegir cualquier alimento"|PASSED| |
|Pantallla de descripción de platillo| | | |
|22|La descripción del platillo consta de una foto|PASSED| |
|23|La descripción del platillo cuenta con una descripción general|PASSED| |
|24|La descripción del platillo cuenta con la composición del platillo|PASSED| |
|25|La descripción del platillo cuenta con el nombre del restaurante donde está disponible|PASSED| |
|26|A la izquierda del nombre de un platillo hay una flecha para regresar a la lista de platillos.|PASSED| |
|27|Al tocar el +, el platillo se agrega a la lista de pedidos.|PASSED| |
|28|El botón "Siguiente" se encuentra inactivo si no hay platillos en la lista de pedidos.|PASSED| |
|29|Al dar cllic en la felcha de regreso se regresa a la lista de platillos|PASSED| |
|30|El nombre del restaurante que ofrece el platillo aparece del lado izquierdo en la ultima sección de la pantalla|PASSED| |
|31|Al dar clic en el nombre del restaurante se agrega +1 en el contador|PASSED| |
|Pantalla de confirmación de pedido| | | |
|32|La pantalla de Confirmación del pedido cuenta con el nombre del punto de recogida|PASSED| |
|33|La pantalla de Confirmación del pedido cuenta con el botón "Atrás"|PASSED| |
|34|La pantalla de Confirmación del pedido cuenta con la lista de platillos|PASSED| |
|35|La pantalla de Confirmación del pedido cuenta con el importe total|PASSED| |
|36|La pantalla de Confirmación del pedido cuenta con el tiempo estimado de entrega|FAILED|https://delr0810.atlassian.net/browse/ULS-1|
|37|Si en la pantalla de Confirmación la lista es demasiado larga, puedes desplazarte por ella.|PASSED| |
|38|El importe total contiene el precio de todos los platillos preparados y la entrega. |FAILED|https://delr0810.atlassian.net/browse/ULS-2|
|39|En la pantalla de confirmación de pedido el progreso del pedido se muestra en el pie de página|PASSED| |
|40|En la pantalla de confirmación de pedido el primer y segundo paso se marcan como completados (en color)|PASSED| |
|41|En la pantalla de confirmación de pedido el  tercer paso se marca como en curso.|PASSED| |
|42|En la pantalla de confirmación de pedido un toque en el botón "Pedir" lleva al usuario o usuaria a la pantalla de seguimiento de pedidos.|PASSED| |
|Pantalla de seguimiento de pedidos| | | |
|43|En la Pantalla de seguimiento de pedidos el mapa muestra el punto de recogida desde el que puedes recoger tu pedido.|PASSED| |
|44|En la Pantalla de seguimiento de pedidos el mapa muestra los restaurantes donde se preparan los platillos|PASSED| |
|45|En la Pantalla de seguimiento de pedidos el mapa muestra las rutas desde los restaurantes hasta el punto de recogida|PASSED| |
|46|En la Pantalla de seguimiento de pedidos se muestra el costo de todos los platillos pedidos en el restaurante|FAILED|https://delr0810.atlassian.net/browse/ULS-3|
|47|En la Pantalla de seguimiento de pedidos se muestra el tiempo de preparación restante|PASSED| |
|48|En la Pantalla de seguimiento de pedidos se muestra el tiempo de entrega desde el restaurante hasta el punto de recogida.|PASSED| |
|49|En la Pantalla de seguimiento de pedidos Si hay muchos elementos en la lista y no caben en la pantalla, puedes desplazarte por la lista.|PASSED| |
|50|En la Pantalla de seguimiento de pedidos El temporizador muestra el tiempo que queda hasta que se recoja el pedido.|PASSED| |
|51|En la Pantalla de seguimiento de pedidos Una vez entregados todos los platillos, el temporizador debe estar en cero, en ese momento se produce la transición a la pantalla "El pedido está listo".|PASSED| |
|Pantalla de el pedido ha sido entregado| | | |
|52|El cambio a la pantalla "El pedido ha sido entregado" se hace de manera automática cuando el temporizador expira.|PASSED| |
|53|El mapa muestra el punto en el mapa donde se encuentra el punto de recogida deseado.|PASSED| |
|54|Después de hacer clic en el botón "Recibí el pedido", el pedido se considera completado|PASSED| |
|55|Después de hacer clic en el botón "Recibí el pedido" se lleva al usuario a la página de feedback|PASSED| |
|56|Después de hacer clic en cualquier calificación de feedback se lleva al usuario a seleccionar un punto de recogida para crear un nuevo pedido|PASSED| |
|Notificaciones de error| | | |
|57|Si no permites que la aplicación acceda a la geolocalización, aparece un mensaje de error.|PASSED| |
|58|Si intentas hacer un pedido sin agregar ningún platillo, aparece un mensaje de error.|PASSED| |
