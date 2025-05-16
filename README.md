Método de Bisección para Encontrar Raíces

Este programa implementa el método de bisección para encontrar aproximaciones de raíces de una función predefinida f(x) = 0.

Descripción
El método de bisección es un algoritmo de búsqueda de raíces que divide repetidamente un intervalo a la mitad y selecciona el subintervalo que contiene la raíz, basándose en el teorema del valor intermedio.

Características
-Función predefinida: f(x) = x³ - 2x - 5 (modificable en el código)
-Entrada de parámetros con validación
-Cálculo automático con criterio de parada por tolerancia o máximo de iteraciones
-Visualización de resultados e historial de aproximaciones
-Manejo de errores con sugerencias para solucionarlos


Uso
1. Ejecute el programa: Evidencia 3.py
2. Ingrese los parámetros solicitados:
3. Intervalo inicial [a, b] donde la función cambia de signo
4. Tolerancia (precisión deseada)
5. Número máximo de iteraciones permitidas

El programa Contestará:

La raíz aproximada encontrada
El número de iteraciones realizadas
Opción para ver el historial completo de aproximaciones

Ejemplo de ejecución
_____________________________________

MÉTODO DE BISECCIÓN SIMPLIFICADO
Función actual: f(x) = x³ - 2x - 5


INGRESE LOS PARÁMETROS:
intervalo a: 2
intervalo b: 3
Tolerancia: 0.0001
Máximo de iteraciones: 100

CALCULANDO...

RESULTADOS:
Raíz aproximada: 2.09455156
Iteraciones realizadas: 17

¿Mostrar todas las iteraciones? (s/n): n
_______________________________________________
Personalización
Para cambiar la función a analizar:

Edite la función f(x) en el código fuente
Actualice el mensaje que muestra la función actual en main()

Limitaciones
Requiere que la función cambie de signo en el intervalo dado (f(a)*f(b) < 0)
La función debe ser continua en el intervalo [a, b]
La convergencia puede ser lenta para tolerancias muy pequeñas

Solución de problemas
Si el programa muestra un error:
Verifique que f(a) y f(b) tengan signos opuestos
Aumente el número máximo de iteraciones
Amplíe el intervalo de búsqueda

Autor
Este programa fue desarrollado por Jorge Luis Esparza Acosta para la materia de Métodos numéricos
