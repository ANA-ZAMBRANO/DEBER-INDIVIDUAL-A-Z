# DEBER-INDIVIDUAL-A-Z
DRIVERS
Este código en Java Swing crea una interfaz gráfica para mostrar datos relacionados con carreras de Fórmula 1 desde una base de datos PostgreSQL local. Aquí está el concepto de lo que hace el código al ejecutarse:

1. **Conexión a la base de datos**: Establece una conexión con una base de datos PostgreSQL llamada "Formula1" utilizando JDBC.

2. **Interfaz gráfica (GUI)**:
   - **Frame (ventana principal)**: Crea una ventana titulada "Tabla de Drivers por Año de Carrera" con dimensiones específicas.
   - **Combo box (comboBox)**: Permite seleccionar un año de carrera de una lista obtenida de la base de datos.
   - **Tabla (table)**: Muestra datos de corredores de Fórmula 1 para el año seleccionado, como nombre del corredor, victorias, puntos totales y posición.

3. **Funcionalidad**:
   - **Populación del combo box**: Consulta la base de datos para obtener los años disponibles de carreras y los añade al combo box.
   - **Actualización de la tabla**: Cuando se selecciona un año en el combo box, realiza consultas SQL para obtener datos específicos de los corredores para ese año y los muestra en la tabla.
   - **Renderización de la tabla**: Centra el contenido de las celdas de la tabla para una presentación más ordenada.

4. **Manejo de datos**: Utiliza consultas SQL parametrizadas para obtener nombres de corredores, victorias, puntos totales y posiciones desde las tablas "drivers", "driver_standings" y "races" en la base de datos.

En resumen, el código proporciona una interfaz gráfica interactiva para explorar estadísticas de corredores de Fórmula 1 por año de carrera, utilizando una base de datos PostgreSQL local como fuente de datos.
![image](https://github.com/ANA-ZAMBRANO/DEBER-INDIVIDUAL-A-Z/assets/169195758/bacaa14a-a725-4616-a989-863987b502d8)
![image](https://github.com/ANA-ZAMBRANO/DEBER-INDIVIDUAL-A-Z/assets/169195758/add862de-fc96-43b4-8a74-60ce17677894)
![image](https://github.com/ANA-ZAMBRANO/DEBER-INDIVIDUAL-A-Z/assets/169195758/9c4e2e1b-7f97-4082-97b8-83293982af11)



