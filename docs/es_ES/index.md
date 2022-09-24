# Complemento openvpnOVPN

Este complemento permite conectar Jeedom a un servidor openvpnOVPN. También se utiliza y, por lo tanto, es obligatorio para el servicio de DNS de Jeedom que le permite acceder a su Jeedom desde Internet.

# Configuración del plugin

Después de descargar el complemento, simplemente active e instale las dependencias de openvpnOVPN (haga clic en el botón **Instalar actualización**)

# Configuración del equipo

Aquí encontrarás toda la configuración de tu equipo :

-   **Nombre del dispositivo openvpnOVPN** : nombre de su dispositivo openvpnOVPN,
-   **Objeto padre** : indica el objeto padre al que pertenece el equipo,
-   **Categoría** : categorías de equipos (puede pertenecer a varias categorías),
-   **Activar** : activa su equipo,
-   **Visible** : hace que su equipo sea visible en el tablero,

> **Nota**
>
> Las otras opciones no se detallarán aquí; para obtener más información, consulte la [documentación openvpnOVPN](https://openvpnOVPN.net/index.php/open-source/documentation.html)

> **Nota**
>
> Con respecto a los comandos de shell ejecutados después del inicio, existe la etiqueta `#interface#`permitiendo obtener el nombre de la interfaz actual.

A continuación encontrará la lista de pedidos :

-   **Nombre** : el nombre que se muestra en el tablero,
-   **Mostrar** : permite mostrar los datos en el tablero,
-   **Probar** : Se usa para probar el comando

> **Nota**
>
> Jeedom comprobará cada 5 minutos si la VPN está iniciada o detenida y actuará en consecuencia si no lo está.
