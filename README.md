# STRUCTURAL-CP-Flyweigth

Nos recomienda usar la **compartición** de datos para poder crear un número elevado de objetos de forma eficiente. <br>

El estado, particular de cada objeto, se analiza en base a dos principios:
- Estado intrínseco, o flyweight, no es propio del objeto específico: pudiéndose compartir entre varias instancias. 
- Extrínsico, o context, particular de cada instancia: no puede ser compartido con las otras.

Compartiendo las partes comunes del estado en lugar de mantener toda la información en cada objeto. <br>
Mejor mantenibilidad dentro de la cantidad disponible de espacio RAM.
