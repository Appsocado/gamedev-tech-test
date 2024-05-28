# Descripción de la prueba técnica
La prueba técnica consiste en el desarrollo de un minijuego: "Chain Chests". Para ello se empleará el motor gráfico Unity.

# Chain Chests
En este minijuego el jugador tiene a disposición un número X de cofres en cada ronda, de los cuales debe de seleccionar uno para revelar su contenido. Cada cofre contiene un valor variable de monedas. Si el jugador abre un cofre, el valor de monedas que estén asignadas el cofre deben acumularse en un premio acumulado. El listado de valores de monedas para los cofres, deben de poder ser cambiados antes de iniciar la ejecución y estos ser asignados a los cofres de manera aleatoria al inicio de cada ronda.

# Rondas
Para esta prueba el juego debe tener un número de rondas que puede ser configurado desde el inspector antes de iniciar el minijuego. En cada ronda aparecerán un número de cofres dados por un valor entero que debe ser dinámico, es decir, que este valor puede cambiar al inicio del minijuego o antes de iniciar la siguiente ronda y debe afectar el número de cofres visualizados para la siguiente ronda. Cada cofre debe de contener un premio de monedas asignado de manera aleatoria al inicio de cada ronda. 

# Cofres vacíos
En cada ronda, entre los cofres que deben ser instanciados, debe haber uno que esté vacío, exceptuando la primera ronda. Si el jugador abre un cofre vacío, el premio acumulado debe de posicionarse en 0 y el minijuego terminar, se le desplegará al jugador un mensaje informando que ha perdido. En este punto el juego habrá terminado y debe de desplegarse un menú o una opción para volver a intentarlo.

# Premio acumulado y finalización del juego
Por cada cofre que el jugador abra y no sea un cofre vacío, el premio en monedas que contiene el cofre debe ser acumulado en un premio acumulado. El objetivo del jugador será escoger un cofre al azar en cada ronda, esperando que ese cofre no este vacío, avanzando a la siguiente ronda. Si el jugador logra completar todas las rondas, se desplegará un mensaje informando cuál fue el premio total acumulado durante todas las rondas y un mensaje de felicitaciones. En este punto el juego habrá terminado y debe de desplegarse un menú o una opción para volver a intentarlo.

# Ítems que se evaluarán
* Orden y limpieza del código.
* Uso de patrones de diseño de código.
* Facilidad de configuración de los valores de rondas, número de cofres, valores de monedas y la estabilidad del minijuego ante estos cambios.
* Declaración de métodos y variables con sus respectivos modificadores de acceso.
* Despliegue de los elementos visuales en un Canvas y trabajo del minijuego en un entorno 2D.
* Métodos de instanciado y limpiado de elementos.

# Ítems que son un plus
* Lograr que el minijuego sea un módulo instanciable (.prefab). Es decir, podríamos tener un menú en la escena que permita abrir Chain Chests y este ser instanciado cuando el jugador deseé iniciar la partida (Para evitar que la escena tenga el game object contenedor del juego siempre presente).
* Eliminar la instancia de Chain Chests una vez el juego finalice y retornar al menú principal.
* Dar la opción al jugador de retirarse en cualquier momento y llevarse el premio acumulado.
* Usar una misma escena para desarrollar la prueba técnica.
* Atención al aspecto visual, uso de assets gráficos y la presentación de la prueba.

