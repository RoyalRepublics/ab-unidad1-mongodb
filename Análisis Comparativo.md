> **1.** **Análisis** **Comparativo** **(SQL** **vs** **NoSQL)**
>
> **Tabla** **Comparativa**

**Criterio**

**Flexibilidad**

**Modelo** **de** **Datos**

**Consulta** **de** **Datos**

**Escalabilidad**

**Evolución**

**del** **Schema**

**Relacional**

Rígido (requiere ALTER TABLE)

Tablas normalizadas

Requiere JOINs complejos para obtener detalles completos

Escalabilidad vertical

Migraciones complejas y

costosas

**NoSQL**

Flexible JSON/BSON

Colección de documentos anidados

Consulta simple a un único documento

Escalabilidad horizontal

Evolución gradual sin

downtime

**Justificación**

Es crucial porque maneja productos con atributos muy variables (laptops
con RAM/CPU vs. smartphones con cámaras), permitiendo adaptarse
rápidamente a nuevos tipos de productos sin modificar la estructura de
la base de datos.

Más eficiente ya que cada producto puede almacenarse como un documento
completo con todos sus atributos específicos, eliminando la necesidad de
múltiples JOINs para reconstruir la información completa del producto.

Mejor rendimiento porque las consultas frecuentes de catálogo y búsqueda
acceden a un solo documento, reduciendo la latencia y complejidad en
operaciones de lectura intensivas.

Ventaja estratégica para TechStore que puede experimentar crecimiento
exponencial, permitiendo distribuir la carga entre múltiples servidores
de manera más económica.

Adaptabilidad esencial en el comercio electrónico donde los requisitos
de productos cambian

constantemente, permitiendo iteraciones rápidas.
