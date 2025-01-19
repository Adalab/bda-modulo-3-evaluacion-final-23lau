**Descripción del proyecto:**

Este proyecto tiene como objetivo realizar un análisis detallado de los datos relacionados con el comportamiento de los clientes dentro de un programa de fidelidad de una aerolínea. Para ello se trabaja con dos conjuntos de datos que contienen información sobre la actividad de vuelo de los clientes y su perfil demográfico. Se va a utilizar herramientas de exploración de datos, limpieza, visualización y pruebas estadísticas; con el objetivo de objetener información valiosa sobre cómo los clientes interactúan con el programa y poder sacar conclusiones de cara al analisis y su interpretación.


**Requisitos previos:**

Archivos de Datos con los que se va a trabajar:

Customer Flight Analysis.csv: contiene información sobre la actividad de vuelo de los clientes (vuelos reservados, distancia volada, puntos acumulados, costos asociados, etc).
Customer Loyalty History.csv: incluye detalles demográficos y de perfil de los clientes (género, educación, estado civil, tipo de tarjeta de lealtad, etc).


**Herramientas necesarias:**

Python
Pandas 
NumPy 
Matplotlib (para visualización)
Seaborn (para visualización)
Sklearn (para imputación de nulos)
Scipy (para pruebas estadísticas)


**Fases del proyecto:**

*FASE 1:* 
Exploración Inicial: Carga y exploración de los datos para identificar posibles problemas en los datos como valores nulos, atípicos o datos faltantes.
Limpieza de Datos: Tratamiento de los valores nulos y corrección de inconsistencias para asegurar que los datos estén listos para el análisis.

*FASE 2: Visualización de Datos*
En esta fase, se utilizan herramientas de visualización para responder a las sisguientes preguntas:
- ¿Cómo se distribuye la cantidad de vuelos reservados por mes durante el año?
- ¿Existe una relación entre la distancia volada y los puntos acumulados por los clientes?
-  ¿Cuál es la distribución de los clientes por provincia o estado?
- ¿Cómo se compara el salario promedio entre los diferentes niveles educativos de los clientes?
- ¿Cuál es la proporción de clientes con diferentes tipos de tarjetas de fidelidad?
- ¿Cómo se distribuyen los clientes según su estado civil y género?

*FASE 3 - Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo*
Preparación de Datos: Filtrar el conjunto de datos para trabajar solo con las columnas 'Flights Booked' y 'Education'.
Análisis Descriptivo: Agrupar los datos por nivel educativo y calcular estadísticas descriptivas.
Prueba Estadística: Realizar una prueba de hipótesis para determinar si existen diferencias significativas en el número de vuelos reservados entre los diferentes niveles educativos.


**Conclusiones:**
Los resultados obtenidos a través de las visualizaciones y los análisis estadísticos pueden ofrecer información valiosa sobre los comportamientos de los clientes y cómo estos se relacionan con variables como ingresos, educación y tipo de tarjeta de lealtad. Aunque es una primera aproximación, esta información podria ser analizada con más detalle de cara a la toma de deciciones y poder plantear nueva estrategias de marketing en la aerolinea.
