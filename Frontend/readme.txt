# AnzenApp

- Lenguaje de desarrollo : Java

### Demo

Usuario y contraseña pueden ser creados a través de la app.

### Ejecución básica

- Al iniciar la aplicación se debe crear un usuario diligenciando el formulario de registro a través de la opción "¿ No tienes cuenta ?"

- En la pantalla principal se muestra un mapa en la ubicación actual del dispositivo (Si se cuenta con el permiso para ello), dentro del mapa se muestran de diferentes colores los reportes que se han realizado en la zona con la posibilidad de ver el detalle del reporte tocando sobre el marcador.

- El la parte superior se encuentra una caja de texto en la cual se puede digitar una dirección y la app intentará ubicarla dentro del mapa, esto con el fin de ver los ultimos reportes en alguna zona de interes. (Cabe aclarar que se hace uso de el API de geocodificación de OpenStreetMaps que al ser gratuito tiene algunas limitaciones y margen de error mayor a la hora de realizar el proceso de geocodificación)

- En la parte inferior se encuentra el botón para agregar un nuevo reporte, se debe diligenciar el formulario ubicando fecha, hora, tipo de reporte (Hurtos de diferentes tipos, grupos sospechosos o expendio de sustancias) y la dirección utilizando el mapa dispuesto para tal fin. Al finalizar tocando el botón "Guardar" enviará el reporte a la base de datos para que otros usuarios puedan estar prevenidos antes tal suceso.