## Historia de Usuario 3
Como estudiante, quiero personalizar la habitación de mi cuy compañero, para lograr obtener un entorno conforme a mis gustos sin tener que modificar la estructura de la aplicación.

- Módulo: Habitacion  
- Estado: Pendiente  
- Tamaño: L  
- Prioridad: 2  
- Complejidad: Intermedia  


## Escenario de Prueba

### Happy Paths (Escenarios exitosos)

1. agrega decoración correctamente
   - EL usuario decide agregar algún elemento a su habitación
   - El elemento se encuentra en su inventario y con cantidad de objetos suficientes para agregarse.
   - Resultado: la habitación del usuario ya se puede visualizar el elmento desplegado y reducido en su cantidad del inventario.

2. Cambio de color de la habitación
   - El usuario decide cambiar el color del fondo
   - La habitación tiene el tipo de fondo pensado disponible y habilitado
   - Resultado: La habitación cambia su color de fondo.


### Unhappy Paths (Escenarios fallidos o con errores)

1. Color u objeto no habilitado en el inventario
   - El usuario elige un elemento no desbloqueado
   - La aplicación muestra el mensaje: "No tienes el elemento en tu inventario disponible"
   - Resultado: No ocurre cambio alguno.
