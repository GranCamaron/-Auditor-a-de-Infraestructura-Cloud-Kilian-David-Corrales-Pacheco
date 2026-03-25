# Auditoría de Infraestructura Cloud

## Descripción
En esta actividad se ha refactorizado el esquema XSD del catálogo de servidores de TechNova Cloud aplicando distintos indicadores de XSD para mejorar la organización, reutilización y validación del documento.

## Indicadores aplicados
- attributeGroup: Se han agrupado los atributos del servidor en un grupo reutilizable.
- group + sequence: Hemos creado un grupo para los componentes de hardware para orden.
- minOccurs y maxOccurs: Se ha limitado el número de discos 
- choice: Se ha añadido el elemento "red" obligando a elegir entre "ip" o "dhcp"
- unique: Aseguramos que el atributo "id"

## código ahorrado
Comparando el XSD original con el XSD refactorizado, se han ahorrado 24 líneas de código.
