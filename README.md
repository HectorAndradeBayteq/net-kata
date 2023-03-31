# Gran Hotel Kata (net-kata)
Ejercicio de entrenamiento para la implementación de aplicaciones _frontend_ y _backend_.

## Contexto
Gran Hotel, reconocida cadena de hoteles nacional, requiere llevar un registro de todos los huespedes que ingresan por recepción. En este sentido, se require contar con una interfaz gráfica que permita registrar los datos del huesped, como son:

| Propiedad            | Tipo de dato | 
|----------------------|--------------|
| Nombre               | Texto        |
| Identificación       | Texto        |
| Habitación asignada  | Numérico     |
| Ingreso              | Fecha y hora |
| Salida               | Fecha y hora |

Por otro lado, cuando los huéspedes terminan su estancia se debe registrar su salida y por lo tanto liberar la habitación para que esta quede disponible.

## Consideraciones
- Tu solución debe considerar lo siguiente:
    - Un proyecto _frontend_ utilizando cualquiera de estos _frameworks_ o librerías: Angular, React o Vue.
    - Un proyecto _backend_ utilizando .Net Core 2.1 en adelante o .Net 5 en adelante. Alternativamente también puedes usar .Net Framework siempre y cuando sea en sus últimas versiones.
    - La información debe ser almacenada cualquiera de las siguientes bases de datos: MySQL, SQL Server, MongoDB o MariaDB.
- Las habitaciones son individuales, por lo tanto, un huesped puede estar asignado a una sola habitación y mientras esta habitación esté ocupada no puede ser asignada a otro huesped.
- *¡Extra!*: Dado que existe la posibilidad de que en determinados casos no existan habitaciones disponibles, ¿cuál es tu sugerencia para manejar este escenario? Recuerda que este punto no es necesario implementarlo pero si decides proponer una solución debes incluir tus comentarios en el README de tu repositorio.

## Recomendaciones
- La solución debe ser simple, pero recordando que es importante mantener buenas prácticas durante la implementación.
- Cualquier _plus_ que consideres importante para esta implementación es bienvenido. 
- Una vez finalizada tu implementación debe subirla a Github y compartir el enlace.
- No olvides incluir todas las instrucciones que consideres necesarias para facilitar la validación de tu solución.
