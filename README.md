# Representación de Módulos y Algoritmos de Consultas sobre Bases de Datos
Trabajo práctico sobre Consultas / Bases de Datos. Instancia: Diseño

Los algoritmos fueron pensados para ser implementados en C++.

El algoritmo Consultar funciona por recursión desglozando las consultas enlazadas que ingresan como argumento junto a una base de datos.

El caso base es From pues nos garantiza el acceso a la tabla.

Es posible acceder de manera recursiva sobre una consulta anidada pues cada una contiene un puntero a una consulta anterior.


