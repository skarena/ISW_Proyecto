
# CONTENIDO DEL TRABAJO

## INTRODUCCION

## INDICE

1. ASPECTOS DE LA ORGANIZACIÓN
    1. Mision
    2. Vision
    3. Objetivos
    4. Antecedentes
    5. Organigrama
    6. Ambito del Proyecto
        1. Area
        2. Recursos Humanos
        3. Software
        4. Hardware
        5. Cronograma de Actividades
2. ASPECTOS DEL NEGOCIO
    1. Problematica Actual o Analisis Situacional
3. METODOLOGIA
    1. Modelo de Requerimientos
        1. Cuadro de requerimientos funcionales, indicando: identificativo, nombre y descripcion.
        2. Cuadro de requerimientos no funcionales, indicando: identificativo, nombre y descripcion.
        3. Relacion de actores y su descripcion.
        4. Relacion de casos de uso.
        5. Modelo de caso de uso de requerimientos.
        6. Plantilla de especificacion de casos de uso.
        7. Matriz de trazabilidad de los requerimientos y casos de uso.
        8. Modelo Conceptual de clases
    2. Analisis Orientado a Objetos
        1. Modelo de Analisis
            1. Diagrama de analisis de clases.
            2. Diagramas de secuencia y colaboracion de analisis.
        2. Lista de Clases de Interfaz.
        3. Lista de Clases de Control.
        4. Lista de Clases de Entidades
        5. Modelo Logico de Clases.
    3. Diseño Orientado a Objetos.
        1. Modelo Fisico.
            1. Creacion de Esquema y Tablas.
        2. Estructura Modular del SWOO.
            1. Diseño de Ventanas.
            2. Diseño de Reportes.
        3. Diagrama de la Capa Presentación.
4. Diagramas de la Capa de Negocio.
        5. Diagrama de la Capa de Datos.
        6. Diagramas de Componentes.
        7. Diagramas de Distribución.

## CONCLUSIONES Y RECOMENDACIONES

## BIBLIOGRAFIA

1. ASPECTOS DE LA ORGANIZACIÓN
    1. Mision

        Prestamos servicios de transporte y logística como operadores integrales atendiendo el mercado nacional e internacional, a través del desarrollo de productos de calidad, proporcionando soluciones globales y a la medida de las necesidades de nuestros clientes.

    2. Vision
        Constituirnos en la empresa líder en el mercado de transporte y logística, desarrollando nuestros recursos humanos y técnicos para alcanzar un alto estándar de calidad y diferenciación en los servicios que brindamos a nuestros clientes.

    3. Objetivos

        "PENDIENTE"

    4. Antecedentes

    5. Organigrama
    ![Organigrama de la empresa](https://www.gestion.org/wp-content/uploads/2015/09/Organigrama-de-una-empresa-peque%C3%B1a-662x483.png)

3.1.3. Relacion de actores y su descripción

Actor|Asignado a|Responsabilidades
---|---|---
Cliente|Realizar Registro/Reservar Cita/Visualizar Productos|El cliente solicita el servicio mediante llamada telefónica, Whatsapp o pagina web brindando sus datos e informacion personal requerida.

3.1.4. Relación de casos de uso

 Nro. | Caso de Uso | Descripción
---|---|---
CUN01|Realizar registro|Para este caso de uso de negocio se necesita registra de manera óptima a un cliente para así poder brindar diversas funcionalidades al cliente en beneficio de ambos.
CUN02|Reservar Cita|En este caso de uso de negocio el cliente solicita al sistema la reserva de una cita, obteniendose como respuesta la seleccion de fecha y hora disponibles de acuerdo a conveniencia del cliente.
CUN03|Visualizar productos|El cliente interactua con el sistema, observandose diversos productos de interes, del cual el mismo podra obtener información de las diferentes caracteristicas de los productos mostrados.




3.1.7. Matriz de trazabilidad de los requerimientos y casos de uso


***Matriz de trazabilidad de los requerimientos de sistema***

|Requerimientos|Prioridad|Estado|Dificultad|Asignado a|
|:----|:----|:----|:----|:----|
|CUS1: Registrar logueo|Alta|Propuesto|Media|Administrador|
|CUS2: Registrar cliente|Alta|Propuesto|Media|Administrador|
|CUS3: Realizar catálogo|Media|Propuesto|Alta|Adminstrador|
|CUS4: Registrar empleado|Media|Propuesto|Media|Administrador|
|CUS5: Registrar diagnóstico|Media|Propuesto|Media|Optómetra|
|CUS6: Registrar citas|Media|Propuesto|Media|Recepcionista|
|CUS7: Generar ficha de atención|Media|Propuesto|Media|Recepcionista|
|CUS8: Registrar productos|Alta|Propuesto|Media|Administrador|
|CUS9: Registrar ventas|Alta|Propuesto|Media|Administrador|
|CUS10: Consultar catálogo|Media|Propuesto|Media|Cliente|
|CUS11: Realizar pedido|Media|Propuesto|Media|Cliente|
|CUS12: Generar reportes|Baja|Propuesto|Alta|Administrador|
|CUS13: Generar comprobantes de pago|Media|Propuesto|Media|Recepcionista|
|CUS14: imprimir documentos|Baja|Propuesto|Media|Recepcionista|
|CUS15: Generar ficha de atención|Media|Propuesto|Media|Recepcionista|
|CUS16: Realizar inventario|Alta|Propuesto|Alta|Administrador|



***Matiz de trazabilidad de casos de uso y actores***

|Relaciones |CUS1: Registrar logueo|CUS2: Registrar cliente|CUS3: Realizar catálogo|CUS4: Registrar empleado|CUS5: Registrar diagnóstico|CUS6: Registrar citas|CUS7: Generar ficha de atención|CUS8: Registrar productos|CUS9: Registrar ventas|CUS10: Consultar catálogo|CUS11: Realizar pedido|CUS12: Generar reportes|CUS13: Generar comprobantes de pago|CUS14: imprimir documentos|CUS15: Generar ficha de atención|CUS16: Realizar inventario|
|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|
|ACT1: Administrador|✔|✔|✔|✔| | | |✔|✔| | |✔| | | |✔|
|ACT2: Optómetra| | | | |✔| | | | | | | | | | | |
|ACT3: Recepcionista| | | | | |✔|✔| | | | | |✔|✔|✔| |
|ACT4: Cliente| | | | | | | | | |✔|✔| | | | | |



3.1.8. Modelo Conceptual de clases

[![modelo-conceotual.jpg](https://i.postimg.cc/prXGsGyg/modelo-conceotual.jpg)](https://postimg.cc/VrpW6FqR)
